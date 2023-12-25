# Chicago-Traffic-Crash-Analysis
This dataset contains information about traffic crashes in Chicago, including details about the incidents, vehicles involved, and people affected. The dataset is sourced from the Chicago Data Portal and is periodically updated. 

## Objectives
1. Identify High-Risk Areas: Locate specific regions in Chicago with the highest crash rates to prioritize safety measures.
2. Reveal Traffic Accident Trends: Analyze the dataset to uncover trends in traffic accidents over time, aiding in forecasting and planning.
3. Determine Accident Causes: Explore the primary factors contributing to accidents, facilitating preventive measures and awareness campaigns.
4. Impact of Climatic Conditions: Investigate the influence of weather conditions on accident frequency and severity.

## Dataset Overview
Dataset: https://www.kaggle.com/datasets/isadoraamorim/trafficcrasheschicago/data
Original Source: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data

## Dataset Description
The dataset comprises multiple attributes related to traffic crashes, providing extensive insights into various aspects of each incident. Some of the important features are: includes information on:
1. RD_no: Reference number or identifier for a specific traffic accident or incident.
2. Crash_Date: The date at which the crash happened includes time as well.
3. Posted_speed_limit: Speed limit at the area where the incident occurred.
4. Traffic_control_device: Tells us if there are any traffic signs present in the area.
5. Weather_condition: Condition of weather during the time of the incident.
6. Lightning_condition: provides information about whether the accident occurred in daylight or under specific lighting conditions.
7. Damage: This would provide a quantitative measure of the financial impact of the accident.
8. Latitude and Longitude: This gives the location points at which the accident occurred.

## Getting Started
### Prerequisites
AWS account with access to S3, AWS Glue, QuickSight, and other necessary services.

### Workflow Execution
1. Data Storage and Preparation:
   * Store the dataset in S3.
   * Clean and transform the data using AWS Glue.
2. Data Transfromation:
   * Utilize AWS Glue service to clean and transform the dataset. AWS Glue simplifies these tasks for analytics and reporting purposes, including data cleaning, standardization, and structuring.
3. Visualization Creation:
   * Utilize AWS QuickSight service to develop interactive visualizations using the transformed dataset.
4. Website Deployment:
   * Host a static website using Amazon S3 for hosting to present the interactive dashboard created with AWS QuickSight. 



