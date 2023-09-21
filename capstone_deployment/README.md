# Team-Catboost-Capstone-Project

# Remittance Patterns And Economic Development

## Definition
In an era characterized by global mobility and interconnected economies, the phenomenon of remittances has emerged as a significant force shaping economic landscapes across the world. Remittances, defined as the funds transferred by migrants working abroad to their families and communities in their home countries, have profound implications for economic development, social dynamics, and livelihoods. 

## Objective
- This project delves into the intricate relationship between remittance patterns and various economic indicators, with a focus on understanding their influence on Gross Domestic Product (GDP) and unemployment rates.
- And also, to deploy a model that will predict the GDP and unemployment-rate of a country based on its remittance flow pattern.

## Team Members
- Confidence Chinelo Ojiako (Project Lead)
- Deya Chatterjee (Assistant project lead)
- Miracle Uche (Query Analyst)
- Arundarasi Rajendran
- Anih Nathan Chizoba 
- Adeniyi Olaolu Peter
- Akinade Phillip Akintoye
- Olalekan Okewale
- Ibrahim Abdulsalam Abdullahi
- INCREASE CHRISTIAN
- Etietop Udofia
- Carla Bailón
- Akanbi Abiodun
- Kawonise Abdullateef
- Joseph Ngota Chilo
- Abdulkareem Sikirulahi Opeyemi
- Bamiteko Ibiduni Adekemi
- Sunday Kingsley
- Benjamin Lawani


## Flow of Project:
Data Sourcing --> Data Gathering And Understanding --> Data Preparation --> Data Preprocessing --> Model Training --> Model Evaluation --> Model Deployment

## Source of Data:
### GDP
https://data.worldbank.org/indicator/NY.GDP.MKTP.CN?intcid=ecr_hp_BeltC_en_ext

### Remittance Paid
https://data.worldbank.org/indicator/BM.TRF.PWKR.CD.DT

### Remittance Received
https://data.worldbank.org/indicator/BX.TRF.PWKR.CD.DT

### Unemployment Rate
https://data.worldbank.org/indicator/SL.UEM.TOTL.FE.ZS

### Migration
https://data.worldbank.org/indicator/SM.POP.NETM

### Population
https://data.worldbank.org/indicator/SP.POP.TOTL

## Feature Description
- Population: This refers to the total number of people living in a specific region, country, or area. It's a fundamental demographic measure that can impact various economic and social aspects.

- Remittance Growth Rate: This represents the percentage change in the amount of remittances received over a specific period of time. Remittances are money transfers sent by individuals working in one country to their families or friends in another country.

- Remittance Paid: This likely refers to the total amount of money sent by individuals as remittances to recipients in another country. It reflects the financial support provided by migrants to their families.

- Remittance Per Capita: This is the average amount of remittances received per person in the receiving country. It gives an idea of how much financial support each individual receives on average.

- Remittance Received: This is the total amount of money received by a country from individuals working abroad and sending money back to their home country.

- Remittance Volatility: This could represent the degree of fluctuation or instability in the amount of remittances received over time. High volatility might indicate economic uncertainty for families relying on remittances.

- Unemployment Rate Change: This likely refers to the change in the unemployment rate, which is the percentage of the labor force that is currently unemployed and seeking employment.

- Net Migration: Net migration represents the difference between the number of people entering a country (immigrants) and the number of people leaving the country (emigrants). Positive net migration indicates more people entering the country.

- Remittance-to-GDP Ratio: This is the ratio of remittances received to the Gross Domestic Product (GDP) of the receiving country. It provides insights into the significance of remittances in relation to the country's overall economic output.

- Country Name: This represents the name of a specific country. It's an identifier that uniquely identifies each country in your dataset. For example, "United States," "India," "Nigeria," etc.

- Income Group: This likely categorizes countries based on their income levels or economic development. Income groups can include classifications like "Low-Income," "Lower Middle-Income," "Upper Middle-Income," and "High-Income," as defined by organizations like the World Bank.

- Region: This refers to the geographic region to which a country belongs. Countries are often grouped into regions based on their geographical proximity and similar characteristics. Examples of regions could be "North America," "Asia," "Sub-Saharan Africa," and so on.

- GDP (Gross Domestic Product): GDP is a fundamental measure of a country's economic performance. It represents the total value of all goods and services produced within a country's borders over a specific period, typically a year or a quarter.

- Unemployment Rate: The unemployment rate is the percentage of the labor force that is currently unemployed and actively seeking employment. It's an important indicator of labor market conditions and can reflect the health of an economy.
## Data Preprocessing:


## Modelling
We built different algorithms, such as

- Linear Regression
- XGBoost and
- Support Vector Machines,
- And compared their metrics.

## Model selected for the project:
XGBoost

## Model Deployment:
Streamlit was used to deploy the model

## Dashboard Link (POWER BI)
https://app.powerbi.com/view?r=eyJrIjoiYzMwYmRmY2QtZjJhZi00ZDRlLTk4MmYtMDk5MGViMTAzZGNlIiwidCI6IjU0NjJmMDc4LWFiYTgtNDE1OS05MWYwLWVhODg1MmJjOTU4NCJ9

## Colab link (Preprocessing and Modelling)


## Link to the slides
https://docs.google.com/presentation/d/14djmqNU36mC2RXSl-C-B7rOsaddkawvN/edit?usp=sharing&ouid=101028808435953258774&rtpof=true&sd=true

## Link to the documentation

https://docs.google.com/document/d/1wf9p4NuqtEVIMXHbjOJKFH2DEnwu3b3A/edit?usp=drivesdk&ouid=113551083294748919720&rtpof=true&sd=true

## Folders present in the project:

Also, the dataset we have downloaded has following directory structure.

<pre style="font-size: 10.0pt; font-family: Arial; line-height: 2; letter-spacing: 1.0pt;" >
<b>CatBoost-Team-Project</b>
|__ <b>Cleaned Data</b>
|__ <b>Code</b>
|__ <b>EDA</b>
|__ <b>Feature Engineering</b>
|__ <b>New Dataset</b>
|__ <b>Data</b>
</pre>
