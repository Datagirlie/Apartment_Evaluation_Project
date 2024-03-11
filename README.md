##  Apartment Building Evaluation in Toronto.

_This is an Excel Analysis on the apartment building evaluation scores from the year 2017 to 2021 that are registered in Toronto with RentSafeTO. The data was visualized with **Tableau**._

![](Apartment.jpg)

## Introduction
**RentSafeTO** aims to ensure that building owners and operators comply with building maintenance standards through initiatives like evaluations and that tenants understand their rights and responsibilities. Apartment Building Standards is a bylaw enforcement program established in 2017 to ensure that owners and operators of apartment buildings with three or more storeys or 10 or more units comply with building maintenance standards. 


##  Skills Concepts demonstrated:
The following analysis skills were incorporated:

Data Cleaning, Data Management, KPI Metrics, Data visualization.

##  Problem Statement
During evaluations, Bylaw Enforcement Officers inspect common areas, mechanical and security systems, parking and exterior grounds. Each item is inspected and assigned a score from one to five, with one being the lowest and five being the highest. If an item is not applicable to the building at the time of evaluation, the score will show as blank in the dataset.
The dataset was downloaded from RentSafeTO website.

However, based on the given dataset the following questions are to be answered:

1. What were the common errors / issues you encountered with the data?
2. What is the evaluation scores based on property type?
3. What is the evaluation scores based on year registered on property?
4. What is the building scores based on ward areas?
5. What is the apartment building scores distribution by geography?
6. What is the apartment building scores based on year of building?

## Data Cleaning/Transformation
The common error associated with this dataset include:

-	Blank Spaces
-	Null figures
-	Incomplete Rows and Columns
-	Inconsistency with Data about information given

## Methodology
  To clean the dataset given using Microsoft Excel, i took the following steps:
  
1.	I created  a consistency with all the Headings in the column. Selected the heading row and made them bold using _Ctrl + B_.
2.	I removed all blank Spaces. Clicked on _Ctrl + A_, then _Ctrl + B_. Go to _Special_, click on _Blanks_, all blank Spaces were highlighted. Right click on any of the blank spaces, then click on _Shift cells up_.
3.	I replaced all **N/A**  values with **0**. I clicked on the columns that contain value, then i clicked on _Ctrl + H > Find and Replace_. Then i replaced all values with 0.
4.	I arranged all the dataset alphabetically by the Ward names.I clicked on the column containing the ward names, then  on the _Home tab_ in the editing space, click on _Sort and Filter_ > A-Z.
5.	I formatted the table structure.

![](https://github.com/Datagirlie/Apartment_Evaluation_Project/blob/main/Excel%20Apartment%20Evaluation.PNG)

# Analysis
In other to be able to analyse my cleaned data and get meaningful insights from it, i decided to use the _Key Performers Indicators_ by creating a new rule in the _conditional formatting_ tab based on the appartment scores given in different ward areas by the year of registration. Also, i used the _Pivot Table_ to be able to summarize the average scores gotten during evaluation by different ward areas based on the years. Based on the average scores gotten per each year from the evaluation scores of the different ward areas, the years with high evaluation was able to known.
The year with highest scores indicates a **green** dot while the year with the average scores indicates **yellow**  and finally the year with the lowest scores indicates **red**. All of this are based on the ward areas, therefore all the different ward areas have there different values and average scores. I also inserted **slicers** to be able to shuffle through the different ward areas,to understand the average distribution of scores per year.


## Visualization
After cleaning and analysing the data using pivot tables and KPIs, i went over to Tableau to create a visual report of this dataset.

![](https://github.com/Datagirlie/Apartment_Evaluation_Project/blob/main/Dashboard%201%20(19).png)



## Insights.





