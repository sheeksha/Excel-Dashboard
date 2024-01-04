# Creating a Dashboard in Microsoft Excel

## Table of Content
1. Remove duplicates
2. Data cleaning / manipulation / recording
3. Create pivot tables
4. Create Charts
5. Create Dashboard and Insert Slicer

For this portfolio project I used the data from Kaggle from https://www.kaggle.com/datasets/unica02/data-on-bike-buyers-by-using-ms-excel.

![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/78471309-67eb-44e6-bb12-a2a50e4f81c2)


### 1. Remove duplicates
To remove duplicates in MS Excel, do Ctrl+A to select the whole dataset > Go to Data > Click on "Remove duplicates" button in the Data Tools.

### 2. Data cleaning / manipulation / recording
Before creating pivot tables and dashboards, we need to perform few data manipulations and/or cleaning. 

1. Change Marital Status column from M or S to Married and Single respectively.
    - Select the whole Column
    - Do Ctrl+H to open Find & Replace
    - Fill in the fields as shown in the image below. Ensure that you select <Search: By columns>
         ![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/94c6cd71-b2f0-42cb-a4d1-1b89777c6818)
    
    - Click on "Replace All" then "Close"

2. Change the Gender column from F or M to Female and Male respectively.
    - Repeat the same procedure as for the Marital Status column

3. Convert the Age column into Age Brackets for meaningful visualisation
    - Insert a new column
    - Perform the operation as follows :
      If the age is between 0 - 30 : Youngster, between 31 - 54 : Middle Age, as from 55 and above : Old
  ![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/77aa2b66-1ada-4324-8a4e-700c65b4d9fe)
  ![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/5b17fc24-f044-4e5e-95bd-f962e93972d6)

### 3. Create pivot tables
  - To create pivot tables, Go to Insert > Pivot Table.
  - Select the range by doing Ctrl+A. Then click OK
  
  - To create , for example, a pivot table that shows the Average Income by Gender who brought a bike, Drag the fields between the areas as shown in the image :
 
  ![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/08c2f9d2-ede1-49ed-b437-0dfd2f8d26c3)

### 4. Create Charts
  - Click on any cell within the pivot table, then Go to Insert > Recommended Charts. Choose the chart that you like.
  ![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/eab00c7a-846e-431f-8487-4667ab4a66fc)

### 5. Create Dashboard and Insert Slicer
  - Copy-Paste your chart(s) into a new blank sheet.
  - Click on one of the charts, Go to PivotChart Analyze > Insert Slicer
  - Click on the slicer then Go to Slicer > Report Connections > Select all Pivot Table to which you want the slicer to be functional. Then click OK.

## Your final dashboard will look something like :
![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/3cb13e24-6ebb-473c-bf17-ea60df1c86d7)

## If you select the slicers, the charts adjusts automatically :
![image](https://github.com/sheeksha/Excel-Dashboard/assets/69764380/e3eda0dc-60e1-4577-b204-08882fdd919a)




   




  

