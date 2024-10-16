# LITA_Class_Documentation
---
## Data Analysis
---
## Outline
---
[Overview](#overview)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-analysis)

#### Overview
---
Here I have a documentation of all that I learnt while learning Data Analysis with the Incubator Hub.

### Tools Used
---
Tools used includes:
- Microsoft Excel [Download here](https://www.microsoft.com)
  1. for Data Cleaning
  2. For DataAnalysis
  3. For Data Visualization
- Structured-Query-Language (SQL) for Data Query
- GitHub for Portfolio Building 

### Data Cleaning and Preparation
---
Before any analysis can be done, data must first be Extracted, Transformed and then load (ETL)
- Extraction involves pulling data from a database
- Transforming a data set is making a data set suitable for analysis and this can be by removal of excesses, trimming and addition.
- LOading is to upload the transformed data set to where its going to be analysed i.e to the system used for analysis.
  
### Exploratory Data Analysis
---
This inolves exploring amd manipulation of data to answer some questions. Such as;
 1. What Region has the lowest sales recorded?
 2. Which Line of business is more profitable?
 3. What are the Model of goods sold within a period of time, e.t.c

### Data Analysis
---
This has to do with the several functions or line of codes (queries) used during the Analysis;

```SQL
SELECT * FROM [dbo].[SALARY]
where STAFF_ID = 'AB503'

select * from payment
where Payment_Method = 'cash'
```

### Data Visualization
This is where we have a visual display of all results generated after the analysis.
![Chat1](https://github.com/user-attachments/assets/fb280209-379b-4929-9b21-5fff829c4155)
![Chat2](https://github.com/user-attachments/assets/a411c655-1647-47bf-ba26-f3deaf8090f8)
