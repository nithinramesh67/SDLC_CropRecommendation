# Requirements

## Introduction
Features of soil like pH, N, P, K are important values which determine Which
crop is suitable for growing in that particular land, But At present Farmer is not
Selecting according to above values this will create a issue it will makes the farmer
to be in loss, will not get proper yield of profit in the end. To overcome problem
we have applying Machine Learning technique history of Crop yield Information
of the region
## Objectives
* Recommend a Suitable Crop to farmer based on his region soil features surface temperature, rainfall from dataset which is gathered from Open Government Data (data.gov.in)
* Study various Classification Algorithms in machine learning and analyze
which classifier is suitable for Crop Recommendation
* Predict the Crop price monthly changes by analyzing dataset of Wholesale
price index, Rainfall and Base price of market

## Research
* Earlier there was Manual identification of soil in lab.
* The measurement of moisture content is not precise.
* Crops for a certain soil cannot be specified for a particular area.
* Time-consuming.
* Crop yield reduction.
* No forecasting and the traditional technique are used.


## Cost and Features
### *Cost*
Since the system uses only open source software, it is free of cost..!!



### *Features*
The various features of the system are:
* Recommending the crop helps the agriculture and cropping seasonal will
help the farmer
* Proposing the elective turn will help in supporting the Soil ripeness
* Using the classifiers which helps us determine the better crop to when compared single classifier
* Accuracy is improved.
* Crops suitable for the soil type are identified.
*  Manuals is reduced and Time consumption is minimized.
* Concentrated on crop growth depending on regional factors and Forecasting to get a good yield

## Defining the System
![System-Diagram](https://github.com/nithinramesh67/SDLC_CropRecommendation/blob/main/1_Requirements/architecture.PNG)
    
## SWOT ANALYSIS
![SWOT-Analysis](https://github.com/Sanchana-2k/LTTS_C_MiniProject/blob/6f6972167470b4b186e9995b7a6647f3f8c7cbd5/1_Requirements/swot%20analysis.jpg)

# 4W&#39;s and 1&#39;H

## Who:

The tool is a helping hand for farmers who have confusion in selecting the Godd crop for better yield and profit at market.

## What:

Analysing the history of regions dataset and recommending the suitable crop to farmer for better yield.

## When:

When farmers are struggling for good yield and profit for their yield outcome. 

## Where:

Can be analyzed based  history of soil data of region and recommending the suitable crop to farmer for better yield.

## How:

The system opens up to the standard dataset consists of Features of soil like pH, Nitrogen
(N),Phosphorus (P), Potassium (K) are important values which determine which
crop is suitable for growing in that particular land. This project using the above
values classify the crop which is suitable for the farmer to grow on his land also
classified it using various Machine learning algorithms

# Detail requirements
## High Level Requirements:

|      ID          |Description                          |Status                         |
|----------------|-------------------------------|-----------------------------|
|HR_01|Crop dataset / Soil charactersitics|Implemented|
|HR_02|Training requirements |Implemented|
|HR_03|Data security|Implemented|
|HR_04|Data PreProcessing|Implemented|
|HR_05|classification algorithm |Implemented|
|HR_06|Rainfall condition|Implemented|
|HR_07|Temperature|Implemented|



##  Low level Requirements:
|      ID          |Description                          |  HLR_ID  |Status               |
|----------------|-------------------------------|----------|-----------------------------|
|LR_01|Data validation |HR_01|Implemented|
|LR_02|Precesion|HR_01|Implemented|
|LR_03|conversion of nominal to Numeric|HR_04|Implemented|
|LR_04|outliers|HR_01|Implemented|
|LR_05|data splitting|HR_04|Implemented|
|LR_06|handling missing values|HR_04|Implemented|


