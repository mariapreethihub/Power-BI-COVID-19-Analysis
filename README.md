# COVID-19-Analysis

 **Table of Contents:**
 
     1.Project Overview
     2.Data Source 
     3.Tools
     4.Basic Data Cleaning
     5.Dax Calculation
     6.Data Visualization
     7.Key findings and insight
    

**Project  Overview :**

    In this POWER BI project, i have analysed the paramters to arrive at various metrics of the dataset.This project 
    involves several stages, including ETL (Extract, Transform, Load) using Power Query, data modelling, DAX calculations,
    and data visualization.  

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

   COVID 19 Analysis:

       1.Total Summary:
       
          *	Total Confirmed Cases: 829 Million cases were reported.
          * Total Active Cases:397 Million.
          * Total Recovered Cases:388 Million were recovered.
          * Total Death Cases :43 Million.
          
       2. Slicers:
         *	We have slicers for WHO Region and Country to get more tailored insights from the data.

       3. World wide confirmed cases:
       
          * Map 

     
   
      
         
  **Recommendation:**
  
  


