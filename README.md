
## Proposed Project Title: 
Integrating Google Trends data and socioeconomic indicators to accurately forecast State-Level Mental Health Service Utilization for the upcoming year.

## Brief background:

Access to mental health services remains a significant public health concern in the United States. Despite the increasing demand for mental health care in recent years, disparities in access and utilization persist due to economic, geographic, and structural barriers. To better understand these trends, data from SAMHSA and the last 20 years of Google Trends API data will be analyzed to identify correlations between mental health awareness and search trends. By aggregating these trends, the goal is to improve state-level mental health forecasting and provide insights into the key factors influencing mental health service utilization.

## Hypothesis:

States with higher Google Trends search interest for mental health-related terms and poorer socioeconomic indicators (e.g., low income, high unemployment) will show higher utilization rates for mental health services in the following year.

## Prediction:

A machine learning model trained on past trends and demographic indicators will predict 2024 utilization rates with an RMSE under 5 points and an R-squared above 0.75 for at least 70% of states. This project builds upon an existing study conducted by a student's research team, which explores predictive modeling of mental health service utilization using Google Trends data. Their preliminary findings demonstrated promising results but require methodological enhancements to improve model robustness, predictive accuracy, and interpretability. This project aims to develop a more robust and accurate predictive model by refining feature engineering, optimizing machine learning methodologies, and enhancing hyperparameter tuning techniques. The insights gained from this project could contribute to an original research paper, positioning the work for academic publication.

## Data Sources:  
- **NSUMHSS** (2013–2023): Facility-level mental health service availability.
- **Google Trends**: Aggregated state-level search interest for mental health topics.
- **COVID Flag**: 2020–2022 period indicator to control for pandemic-related disruptions.

## Environment Setup:
Prerequisites:
Python 3.7 or above
Required libraries: pandas, numpy, jupyter, google-colab

### Installation:
Clone the repository:
git clone https://github.com/AlourdesJ/DSE6311OM_SP2025R2_Data-Science-Capstone.git
cd DSE6311OM_SP2025R2_Data-Science-Capstone
Install required libraries:
bash
pip install -r requirements.txt
If requirements.txt is unavailable, manually install the required packages:
bash
pip install pandas numpy jupyter google-colab

### Google Colab Setup:
Mount your Google Drive:
Python
from google.colab import drive
drive.mount('/content/drive')
Ensure all data files are placed in the correct directories as referenced in the code.

### How to Run the Code:
Launch Jupyter Notebook:
bash
jupyter notebook
Open the Codebook.ipynb file in the Jupyter interface and execute each cell sequentially (Shift + Enter).
Alternatively, upload the .ipynb file to Google Colab and follow the instructions.

## Outputs and Interpretation:
### Key Outputs:
#### Codebook CSV: 
The notebook generates a codebook (codebook_mental_health_utilization.csv) summarizing the dataset variables.
#### Model Predictions: 
Outputs include predicted utilization rates for 2024.

## Interpreting Results:
Open the generated CSV file in a spreadsheet tool to review variable descriptions and structure.
Analyze the predictive model's performance metrics (RMSE and R-squared values) for insights.
## Troubleshooting:
Ensure input data paths are correct.
Review error messages in the notebook output for debugging.
## Team Alpha:
Alourdes Joseph,
Devin McGovern,
Wilson Mazile 


