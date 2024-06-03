Masters of Applied Data Science - Capstone Project
# BEV Adoption Forecasting Model for Local Government Areas in Australia
### Introduction
---
 This project aims to develop an accurate and explainable forecasting model for Battery Electric Vehicle (BEV) uptake at the local government area (LGA) level in Australia. By leveraging machine learning techniques, the model will integrate diverse data sources to better understand and predict BEV adoption, providing more precise and actionable insights for policymakers and stakeholders. This will facilitate the transition towards a net-zero emission economy, addressing the critical need for localized BEV adoption research and strategic planning.
---
2. Introduction
3. Background
4. Objectives
5. Data Sources
6. Methodology
7. Installation
8. Usage
9. Results
10. Contributing
11. License
12. References
---
### Background
Addressing climate change necessitates a rapid reduction in greenhouse gas (GHG) emissions, especially by curbing fossil fuel use. The transport sector, responsible for about a quarter of global GHG emissions, is a key focus. Countries like Australia, with transport emissions per capita 45% above the OECD average, face significant challenges in transitioning to low and zero-emission technologies such as electric vehicles (EVs). Despite growing consumer interest, Australia lacks accurate modelling of BEV adoption at the LGA level, hindering informed decision-making and strategic planning.

### Objectives
Develop a Forecasting Model: Create an accurate and explainable model to predict BEV uptake at the LGA level in Australia.
Integrate Diverse Data Sources: Utilize socio-demographic, attitudinal, behavioural, household, regional, and spatial variables.
Leverage Machine Learning Techniques: Apply advanced machine learning algorithms to capture complex, non-linear relationships.
Provide Actionable Insights: Offer precise and actionable insights for policymakers and stakeholders to facilitate BEV adoption.

### Data Sources
The model will integrate data from various sources, including but not limited to:

Socio-demographic data from Australian Bureau of Statistics
Vehicle registration data from local transport authorities
Charging infrastructure data from government and third-party providers
Environmental awareness proxies such as voting patterns
Economic indicators and household characteristics

### Methodology
Data Collection: Gather data from relevant sources using defined keywords and search strategies.
Data Preprocessing: Clean and preprocess data for analysis, ensuring compatibility and completeness.
Feature Engineering: Identify and create relevant features influencing BEV adoption.
Model Development: Develop and train machine learning models, including tree-based algorithms like XGBoost.
Model Evaluation: Evaluate model performance using metrics such as Mean Absolute Percentage Error (MAPE).
Explainability: Ensure the model's predictions are explainable to support decision-making.

### Installation
To set up the project environment, follow these steps:

### Clone the repository:

sh
Copy code
git clone https://github.com/your-username/bev-adoption-forecast.git
cd bev-adoption-forecast
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Usage
To run the forecasting model, use the following command:

sh
Copy code
python run_model.py
This script will preprocess the data, train the machine learning model, and output the BEV adoption forecasts for each LGA.

### Results
The results of the model, including detailed forecasts and insights, will be available in the results directory. Visualizations and analysis reports will also be provided to facilitate interpretation and decision-making.

### Contributing
We welcome contributions to improve the model and expand its capabilities. Please follow these steps to contribute:

### Fork the repository
Create a new branch:
sh
Copy code
git checkout -b feature/your-feature-name
Make your changes and commit them:
sh
Copy code
git commit -m "Add your commit message"
Push to the branch:
sh
Copy code
git push origin feature/your-feature-name
Create a pull request

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### References
Berkeley et al., 2018
Brückmann, Willibald & Blanco, 2021
Broadbent et al., 2022
Broadbent, Metternicht & Drozdzewski, 2019
Chakraborty et al., 2023
Christidis & Focas, 2019
Dixit & Singh, 2022
Egnér & Trosvik, 2018
Foley, Degirmenci & Yiğitcanlar, 2020
Graham, 2022
Higgins et al., 2012
International Energy Agency, 2017
Jia et al., 2020
Kahn, 2007
Kumar, Guha & Chakraborty, 2022
Li, Chen & Wang, 2017
Liu et al., 2017
Mitchell & Monterosso, 2021
Morton et al., 2018
Neves et al., 2019
Palmer et al., 2018
Plötz et al., 2014
Sheetal, Jiang & Di Milia, 2022
Sierzchula et al., 2014
Smith et al., 2017
Sovacool et al., 2018
United Nations, 2021
Wang et al., 2011
Wicki, Brückmann & Bernauer, 2022
Wicki et al., 2022
Wood, Reeve & Ha, 2021
Wu, 2019
Zhuge & Shao, 2019
For more details and the complete list of references, please refer to the References file.
