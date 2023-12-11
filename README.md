# DAL_Project_Team6
# Comprehensive Environmental Insight Project: Unveiling India's Ecological Footprint

## Programmed by
1. Homita Ganguly (Reg no. 22112314) 
2. Lakshmi Madhu Warrier (Reg no. 22112320)
3. Siddhi Jhanwar (Reg no. 22112334)
4. Simran Adwani (Reg no. 22112335) 

## Description
The Environmental Impact Data Analytics Project delves into the intricate analysis of air quality, land quality and environmental factors across various states and union territories (UTs) in India. This data-driven exploration aims to uncover insights that contribute to a deeper understanding of environmental challenges. The comprehensive project involves data cleaning, descriptive statistics, exploratory data analysis (EDA), and predictive modeling, providing valuable tools for addressing environmental concerns.

## Dataset Description
The dataset encompasses a comprehensive array of parameters, integrating air quality indicators (SO2, NO2, PM10, PM2.5), pesticides consumption, population, state area, and diverse environmental features such as land use, forest cover, wetlands, and water bodies. The main Django project utilizes the cleaned_data.csv file, featuring an extensive set of headers like State/UT, SO2, NO2, PM10, PM2.5, Pesticides Consumption, Population, State Area, and various environmental characteristics. This dataset's diversity facilitates a holistic examination of environmental conditions.
For the land erosion prediction component, the project folder incorporates .ipynb files utilizing the cleaneddata.csv dataset. This dataset includes headers such as S. No., State/UT, State Area km², Water Erosion, Wind Erosion, Water Logging, Salinisation/Alkalisation, Acidification, Anthropogenic, Others, Total, SO2, NO2, PM10, PM2.5, Year, Annual temperature (min), Annual temperature (max), and Annual rainfall. These parameters contribute to a nuanced analysis, providing insights into various erosion factors and climatic conditions over different time periods.

## Project Structure

 **Data Cleaning and Exploration:**

  - Data Tab View:
   - Provides an overview of the dataset.
   - Showcases the first and last ten rows.
   - Detailed column information included.

 **Data Profile:**

  - Profile View:
   - Generates a Pandas profiling report.
   - Offers insights into data types, missing values, correlations, and variable distributions.

 **Descriptive Statistics:**

  - Descriptive Statistics Tab View:
   - Presents summary metrics like mean, standard deviation, and quartiles.
   - Focuses on numerical columns.

 **Exploratory Data Analysis (EDA):**

  - Exploratory Data Analysis Tab View:
   - Utilizes interactive visualizations:
     - Histograms
     - Scatter plots
     - Pie charts
   - Explores data distribution patterns and relationships.

 **Data Profiling:**

  - Integral for Comprehensive Analysis:
   - Unveils crucial insights into:
     - Data types
     - Missing values
     - Correlations
     - Distributions

 **Predictive Modeling:**

  - Predict Air Quality View:
   - Implements a RandomForestRegressor.
   - Allows users to input values for various features.
   - Obtains predictions, and the trained model is saved for future use.

  **Additional**
   - Land Erosion Prediction (Jupyter Notebook):
      - land_prediction folder:
        - Contains .ipynb files providing codes and analysis for predicting land erosion.
        - Includes data preprocessing, feature engineering, and model training using machine learning techniques.


## Functionality

- *Data Profiling:*
  - Access the data profiling report.

- *Data Cleaning and Exploration:*
  - Use the data_tab view to explore the first and last ten rows of the dataset.

- *Descriptive Statistics:*
  - Utilize the descriptive_statistics_tab view to get summary statistics.

- *Exploratory Data Analysis (EDA):*
  - Navigate to the exploratory_data_analysis_tab view to explore interactive visualizations.

- *Predictive Modeling:*
  - Use the predict_air_quality view to input values for various features and get predictions.

- *Data Export:*
  - Export cleaned data to CSV or Excel using the export_to_csv and export_to_excel views.

## Usage

1. Clone this repository to your local machine.
2. Ensure the cleaneddata.csv and cleaned_data.csv files are in the data_analysis_project folder.
3. Install the required packages: pandas, ydataprocessing.
4. Run the Django project.
5. Access various functionalities through the provided views.

## Project Layout
![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/273bcd94-2137-4835-ac23-45549c41372b)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/adf90ae5-9a1e-43e2-9f00-3ca604219869)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/9c7271d9-22ed-46cd-bd9e-acf38bb58691)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/59d2e1a6-b31b-4c34-aa7c-3b1c838badb5)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/bc63f8a0-df96-4f32-876f-1e1f59460cf7)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/9de70f69-8cb7-48f5-993c-c57457038dde)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/47e1e78c-0ed5-41e1-9c95-fa50d3fa31a4)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/d9ad34a5-b766-41f7-8191-710be4441821)

![image](https://github.com/simranadwani/Environmental-Insight-Project/assets/118894785/1a74a26d-7fd0-4626-9e60-c66f6a30ac67)





