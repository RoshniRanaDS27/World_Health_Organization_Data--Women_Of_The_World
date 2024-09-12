![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/c3624748-6ab9-425c-95c2-72cebc924e6e)
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/f7392ce8-e0a1-4bcc-9e41-bfd63148c791)
# Project - Women’s maternal and reproductive health 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/5ef7755e-4a38-4f3c-b12e-1fbb53e200ec)  
#  
# Data Collection topics: 
Data is collected on large set from different four topic source which are mentioned below. 
### Married-or-in-union-women-of-reproductive-age
1. who-have-their-need-for-family-planning-satisfied-with-modern-methods
2. Adolescent-birth-rate-(per-1000-women-aged-15-19-years)
3. Antenatal-care-coverage-at-least-four-visits 
4. Births-attended-by-skilled-health-personnel
# BackGround 
Women's health encompasses a diverse array of physical, mental, and social well-being concerns unique to females. This includes maternal and reproductive health, which focuses on aspects such as pregnancy, childbirth, and reproductive choices. Maternal health emphasizes prenatal care, safe delivery practices, and postpartum support, aiming to reduce maternal and infant mortality rates and promote healthy pregnancies. Reproductive health further encompasses family planning and access to reproductive healthcare services, crucial for empowering women to make informed decisions about their reproductive futures. Addressing these multifaceted issues requires comprehensive healthcare strategies that recognize the intersection of biological factors, societal norms, and healthcare access, thereby promoting the overall well-being of women throughout their lives. 
  

# Main question: How does access to and satisfaction with modern family planning methods 
How Among married or in-union women of reproductive age, impact reproductive 
health outcomes and maternal well-being rates are varied due to cultural barriers, lack of tech facilities. These disparities show the varying levels of support and challenges different regions face in collected Data sets.  
#

# Specific focus areas: 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/9f79dc2e-714a-4f93-a46c-fc1044f1dccb)
 
 - Mental health (psychological well-being such as depression, strees, anxiety)
 - Skilled birth attendance (count with doctors, nurses and midwives support) 
 - Postpartum support (health care for mothers within the first months)

# Sub-questions to guide the analysis: 
1. Access to Family Planning: How does access to modern family planning methods vary across different 
regions and socioeconomic groups? 

2. Reproductive Health Outcomes: What is the correlation between access to modern family planning methods and 
adolescent birth rates?

3. Maternal Well-being: Are there correlations between family planning access and maternal healthcare-
seeking behavior, such as antenatal care attendance and skilled birth attendance?
# Data Engineering 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/6e90d8a1-d78d-4ace-927c-aa971d447f24)
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/4d5c72aa-0630-4cf7-9d1a-ea088bb03750)

# Step 01 - Data Collection
- Sources: WHO datasets WHO Indicators.
- Size and Shape: Large datasets spanning various indicators of maternal and reproductive health.
* This Project journey involves data collection from The World Health Organization Relational Data Hub.   
* Had collected data set Related to Women’s maternal and reproductive health 
* Here Ensuring the reliability and relevance of  data was paramount for me as it formed the foundation for the depth and accuracy of our analysis.

### Data Collection Challenges:
- Data normalization across different countries.
- Varying data collection periods requiring assumptions for standardization.
# Step 02: Data cleaning ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/79ef9430-0100-4aac-ae03-91e58391ffcb)

* In this stage data cleaning was on focus. 
* Here, I prioritized data cleaning and quality by addressing issues like missing values, nulls, duplicates, outliers, changing data's physical type
* Ensuring standardization with Python. Hence, This meticulous preparation ensures that the data aligns seamlessly with analysis goals.
  
# Step 03: Data Transformation ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/cee5f36f-6618-4774-a7dd-993456b3f4a3)

* Step three involves data transformation, where I have shaped the data to fit the needs of analysis.   
* This includes normalization to ensure consistency and clarity in data representation, setting the stage for effective modeling.
  
## 1NF 
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/dfcc1e3e-77a7-4c13-8598-c7912394a235)
## 2NF 
- Family-planning Table
- Adolescent-birth-rate Table
- Antenatal-care-coverage Table
- Births-attended-by-skilled-health-personnel Table


#
# 3NF / Fact Table
- Normalization with location Table
- Normalizing Period Ranges
  

#


# Step 04: Data modeling  
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/e1a8c490-5f13-45fd-a6bd-7ebb529ac94a)

crafting entity-relationship diagrams (ERDs) and establishing connections between datasets by Postgre-SQL and assigning primary and foreign keys within each tables. 

 
# Step 05: Exploratory data analysis & Visualization ![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/c3f9eba7-c9eb-444a-a09b-339a4fc27456)

Delved into exploratory data analysis using Python libraries, and explored patterns with cleaned data sets.   
This phase unveils insights and prepares the data for meaningful visualizations.

### Sub-questions to guide the analysis: 
# 1. Access to Family Planning: How does access to modern family planning methods vary across different regions and socioeconomic groups?
## Geographical Analysis - Family Planning Data set 
# Continent Level Analysis
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/65e9fb6f-64a4-47a9-8dbd-72de6846cee0)

#
## Country Level Analysis
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/208bac75-c4a6-4e41-945c-628a02c19141)
# 
## Interactive Geographical Heat Map with tooltips Screenshot (HTML file is Saved)
# Geographical Analysis - Family Planning Data set (Visualization)
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/8ca51fc2-e792-480d-8a93-09a57b0af8ec)

## Top Three Countries within each Continent - Family Planning Data set
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/e199be97-52ae-49d8-b2c3-f12ac4bdf5f1)
# Top Three Countries within each Continent - Visualization
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/66ee770c-1307-47ca-a4cf-d3172c1fdb37)
# Time-Period Analysis
![image](https://github.com/RoshniRanaDS/Data_Engineering_Cleaning_Normalization_With_ERD/assets/161755928/ae34b079-c308-4eee-970d-a7174113f0a3)
#
#

# 2. Reproductive Health Outcomes: What is the correlation between access to modern family planning methods and adolescent birth rates? 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/ad0ccca0-d035-4c94-9d84-b94e0888e070)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/e12d18e4-61ff-4719-80be-c9414e2dfd5e)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/2fb61ddb-eb5b-4861-b93f-f583e2e15619)

# 3. Maternal Well-being: Are there correlations between family planning access and maternal healthcare-seeking behavior, such as antenatal care attendance and skilled birth attendance? 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/4bc84aa1-1ed3-405f-889f-9aaa924e65ff)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/70a513d6-9ca8-4493-a214-edc1e66484af)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/bf71c7a6-7f1f-4824-ba15-dc9543bcf41f)

# Conclusion 
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/2b9d1ec3-cdf7-45ee-90cd-92a5d4b9d819)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/2bfda1b5-70b9-44d8-91fb-13266ef00676)

![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/a8a44c19-04bf-4fce-8b8e-0caebf2099c4)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/3cad410e-7723-4467-8f19-396026f13657)
#
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/e69924f8-7141-4ff3-913f-709fcddc26cf)
#
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
#
> Ultimately, Data journey concludes with interpreting the results, weaving them into meaningful conclusions 
> Through this approach, I ensure that my analysis not only addresses initial problems but also adds unexpected value to business requirements through my technical expertise.
 #
<img src="https://media2.giphy.com/media/vMrUXf6Z8ltFG43H4R/giphy.webp?cid=ecf05e47zms89p82uk3aqi4z9h9haxheiu44s9rz2n4k2vge&ep=v1_stickers_search&rid=giphy.webp&ct=s" alt="Project GIF">
#

# Dependency 
- CSV
- OS
- matlotlib
- Pandas
- pyplot
- numpy
- seaborn
- geopandas
- folium
- time
- Selenium, webdriver
- Ipython.display, image
- plotly.express 
- scipy.stats, pearsonr, spearmanr
- statsmodels.api
#
<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYXE2MXcxOTJ4YWdyNGRqczBwMWRocmp4NDZsbm9pbmduZ3RsenRlciZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/W5XczpuPhqcrTxhdbo/giphy.webp" alt="Project GIF">
#
# Time Allocation:
* Problem Framing: 20%
* Data Exploration: 10%
* Data Cleaning: 40%
* Data Modeling: 20%
* Data Visualization: 10%

# Data Flow:  
- Data sourced from WHO -> Processed in Jupyter Notebook -> Stored and retrieved from a SQL database.
* Schema Diagram: Detailed in the Engineering_ERD folder.

# Tools Used:
Storage: SQL database for organized data storage and retrieval.
Processing: Jupyter Notebook (main_file.ipynb) for data manipulation and analysis.
Visualization: Matplotlib, Seaborn, Geopanda, webdriver for plotting graphs and charts.

# Additional Tools:
* NumPy: For numerical operations.
* Pathlib: For file path manipulations.
* CSV and OS Libraries: For handling data files.

# Analytical Use Cases
* Access Disparities: Analyzing regional and socioeconomic variations in access to family planning.
* Adolescent Birth Rates: Correlation between family planning access and adolescent birth rates.
* Maternal Healthcare Behavior: Link between family planning access and antenatal care or skilled birth attendance.

# Demonstration
* Jupyter Notebook: Demonstrates data retrieval and visualization.
* Visuals: Includes Geograhical Interactive Maps(.HTML), bar charts, line graphs, and heatmaps to depict key findings. Visuals are included in the project report and presentation.

# Assumptions:
* When the period of study was done between 2 years (i.e. 2022-2023), it is assumed that the results of that particular study corresponds to 12 months and it is a reflection of the latest year (2023).__
* The datasets were broken down in intervals of 3 years each starting in 2003 to 2023 to allow consistent analysis of data over time.
* The study was done in married and in-union women of reproductive age, which is assumed to be between 15-49 years.
* Assumed the same collecting data method accross countries.

# Limitations:
![image](https://github.com/RoshniRanaDS/World_Health_Organization-Women-s_Maternal_and_Reproductive_health/assets/161755928/e3eed74b-37f0-4be6-8c1b-e01be53e6c2d)
#
* There are more indicators that could have been analyzed to contribute to the overall hypothesis. We focused on 4 key indicators due to time constrainsts.
* Period data was not standardized accross datasets. Some assumptions needed to be made to standardize it and make them fully comparable.

# Ethical Considerations:
* Ensuring the confidentiality and ethical use of data.
* Addressing biases inherent in data collection methods.

# Future Work Scope:
* Extended Analysis: Incorporate more indicators for a comprehensive view.
* Data Integration: Enhance the database with additional sources and real-time data.
* Interactive Dashboards: Develop more interactive visualization tools for dynamic data exploration.
* Please, refer to the word file to get the summary of the findings

# Folder Structure:
* Output: Contains all exported datasets and analysis results and visual Files.
* Engineering_ERD: ERD for schema and SQL database export.
* Project_Analysis: Findings and summary documents.

# How to Run:
Environment Setup: Ensure you have Python and Jupyter Notebook installed.
Dependencies: Install required libraries via pip: numpy, pandas, matplotlib, seaborn.
Run Notebook: Open main.ipynb in Jupyter Notebook and run the cells sequentially.

### Presentation link : https://docs.google.com/presentation/d/1x9B9XUovqEVoICqrudJISOiVQhtrC1XmSFutZ8thbOo/edit#slide=id.gc6f919934_0_0

# Sources:
* https://www.who.int/data/gho/data/indicators/indicator-details/GHO/married-or-in-union-women-of-reproductive-age-who-have-their-need-for-family-planning-satisfied-with-modern-methods-(-) 
* https://www.who.int/data/gho/data/indicators/indicator-details/GHO/adolescent-birth-rate-(per-1000-women-aged-15-19-years)
* https://www.who.int/data/gho/data/indicators/indicator-details/GHO/antenatal-care-coverage-at-least-four-visits
* https://www.who.int/data/gho/data/indicators/indicator-details/GHO/births-attended-by-skilled-health-personnel-(-)
#
<img src="https://media3.giphy.com/media/T8yn6Fv6ZiYXZEvZFy/giphy.webp?cid=ecf05e47zms89p82uk3aqi4z9h9haxheiu44s9rz2n4k2vge&ep=v1_stickers_search&rid=giphy.webp&ct=s" alt="Project GIF">

