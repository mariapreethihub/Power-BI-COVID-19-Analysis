# COVID-19-Global Analysis

 **Table of Contents:**
 
     1.Project Overview
     2.Data Source 
     3.Tools
     4.Basic Data Cleaning
     5.Dax Calculation
     6.Data Visualization
     7.Key findings and insight
     8.Recommendation
    

**Project  Overview :**

      This repository provides an interactive analysis of COVID-19 statistics globally and within the United States,
      visualized using a dashboard. The data highlights key trends, insights, and critical statistics about confirmed 
      cases, deaths, recoveries, and mortality rates.

**Datasource :** 

   https://www.kaggle.com/datasets/imdevskp/corona-virus-report

**Tools :**

    Microsoft Power BI

**Basic Data Cleaning :**

     To ensure data accuracy and consistency, the following data cleaning tasks were performed in the given dataset using 
     Power Query Editor in Power BI:

        1.Identifed and removed unncessary columns that did not contribute to the analysis.
        2.Ensured that each column has the correct datatype.
        3.Handled missing values/blanks by imputing or excluding incomplete record.
        4.Checked for duplicate values to ensure integrity.


**DAX Operation:**

       While creating reports in Power BI,to visualize the data in the most effective way sometimes we 
       have to infere data from existing fields to form new column or tables.Here, we discuss such cases.

        1.We have created a new table Calendar using function calendar() by taking the start and end dates
          from the existing table full_grouped-date and country.

        2.New measures total active cases,total confirmed cases, total death cases and total recovered 
          cases are created in the table full_grouped-date and country using aggregate function sum().
          Measure mortality rate is also added in table full_grouped-date and country and usa_country_wise.

**Data Visualization:**
        
        A simple interactive dashboard report is created in Power BI.The report is structured using visualization charts,tables,
        slicers and map.
        The final outlook of the dashboard is as under:
        
<img width="596" alt="coro" src="https://github.com/user-attachments/assets/3182bbb3-aebd-4d43-979b-c897843e9a0b">

<img width="604" alt="coroo" src="https://github.com/user-attachments/assets/f9264513-ed6d-4d32-ba74-dbff06de58da">


**Key findings and insight:**

  **Global Analysis:**
  
     1.Total Cases Overview:

          * 829M total confirmed cases worldwide.
          * 397M active cases and 388M recoveries.
          * 43M total deaths, with the US having the highest fatalities (11M).
     
     2.Top Affected Countries:

          * US leads in active cases (156.9M) and total deaths.
          * Other affected countries include Brazil, UK, and India.
          
      3.Monthly Trends:

          * Confirmed cases have shown exponential growth, with a rapid rise between March and July.
          
      4.Mortality Rate:

         * Global mortality rate was at peak at the begining but began to stabilize in subsequent months.
         
      5.Filters and Bookmarks

         * Filters are added to analyze trends over specific date range.
         * Bookmarks are included for US,China and India for easy access.


**US Analysis:**

    1.State-wise Data:

         * New York leads in confirmed cases (39M) and deaths (3.17M), followed by California and New Jersey.
         * States like Texas, Florida, and Illinois are also on higher side.
         
    2. National Averages:

        * Mortality Rate: 2.44%
        * Confirmed Cases (per region): 357.84M on average.
        
   3.Geographical Spread:

        * The heatmap indicates the concentration of cases across the United States, with heavier clusters in major
           metropolitan regions.

         
  **Recommendation:**
  
        * Focus on countries with high active cases and mortality rates, such as the US and Brazil, to boost healthcare 
          infrastructure and vaccination efforts.
        * Monitor recovery rates to assess healthcare effectiveness.
       

     

