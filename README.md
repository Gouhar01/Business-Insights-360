# Business-Insights-360

## Project Overview
AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

I worked on this project by following the Codebasics PowerBi Course, Link to the course is here

Live Report Link

## Tools Used
- SQL
- PowerBI Dasktop
- DAX Language
- Excel
- DAX Studio (For optimizing the report)
- Project charter file

## PowerBI technical terms
- Creating Calculated Columns
- Creating calculated measures using DAX Functions
- Data Modeling
- using Bookmarks to switch betfween two visuals
- Page navigation with buttons
- Using divide funtion to prevent zero divition error
- creating date table using M Language
- Using KPI indicator
- Data validation
- Conditional formatting
- PowerBI service
- Publishing report to PowerBi service
- Setting Up personal Gateway to set up the auto refresh of data

 ## Business related terms
 - Gross Price
 - Pre-invoice Deductions
 - Post-invoice Deductions
 - Net invoice sales
 - Net sales
 - Gross Margin
 - Gross Margin %
 - COGS- Cost of goods sold
 - Net Profit
 - Net Profit %
 - YTG - Year to Go
 - YTD - Year to Date

   ## Company's Back ground
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors
  
Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

## Data Understanding
understanding what  types of data is available will be more helpful while doing analysis. Before jumping on to the analysis get good understaing  what type of data are available

Dimension Tables: It will have static data like details of customer and products

Fact Tables:  It will have data about the transaction

- gdb041:
   - dim-customer
        - 27 distinct markets (ex India, USA, spain)
        - 75 distinct customers thorough out the market
        - Two types of plateforms
            - Bricks & Mortal- Physical/ offline stores
            - E- commerce- Online(Amazone, flipkard)
        - Three types of channels
           - Retailer
           - Distributor
           - Direct
        - dim-market
           - 27 distinct markets (ex India, USA, spain)
           - 7 sub-zones
           - 4 regions
                - APAC
                - EU
                - NA
                - LATAM
        - Divisions
                - P & A
                   - Peripherals
                   - accessories
                - PC
                   - Notebook
                   - Desktop
                - N & S
                   - networking
                   - storage
        - There are 14 differnt categories like, keyboareds, Internal HDD
        - there are the differnt varients avialable for the same product
   - fact-forecast-monthly
        - This table is used to forecast the customer’s need in advance, which can help in
        - The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
        - All the date of the month will be replaced by the start date of the month
        - It will have all the column names and in the end it will have the forecast quantity need of the customer
   - fact_sales_monthly
        - This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value
 - gbd0456:
     - freight_cost
        - This table has details of travel cost and other cost for each market with fiscal year
     - gross_price
        - Has the details of gross prices with product code
     - manufacturing_cost
        - Has the details of manufacturing cost with product code with year
     - Pre_invoice_dedutions
        - Has the details of pre invoice deductions percentage for each cutomer with year
     - Post_invoice_deductions
        - Post invoice deductions and other deductions details

## Importing data into PowerBI
   As the dabase is MySQL in this project. We need to importe the dataset from MySQL to PowerBi by providing the databae access credential

## Data Model
   - data modeling plays a vital role and consier as the basement of report. All the visuals will be build upon the data modeling.
   - Poor data modeling affects the performance of the report.
   - In this project we have followed the Snowflakes data model.

 ![21](https://github.com/Gouhar01/Business-Insights-360/assets/141431067/c96318af-8b4c-4dac-b0c2-1089292f38d3)

## Dashboard Designing 
Besed on the mock ups requrement, team starded building measures as and when required.

## Home view
In Home view, all the views button will be available. User will land on specific view page by clicking the button
 - Info
 - Financial View
 - Sales View
 - Marketing View
 - Supply Chain View
 - Executive View
 - Support

## Home 

          
        
          

          
     
     
    
        
                   
        
        
        
     

                        
      
  
  
