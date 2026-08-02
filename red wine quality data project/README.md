WINE QUALITY 🍷
Exploratory data analysis work
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="2048" height="1152" alt="image" src="https://github.com/user-attachments/assets/03aeb37c-dc85-469b-a3c4-b0537e3d7d45" />

# Wine Quality Exploratory Data Analysis (EDA) 🍷

In this repository, I have successfully completed an Exploratory Data Analysis (EDA) on the **Wine Quality** dataset. The primary motive of this project is to thoroughly analyse the physicochemical properties of the wine variants and comprehend how they influence the final quality rating.

## 📂 About the Dataset
The data is sourced directly from the enclosed `WineQT.csv` file [cite: 1]. It comprises a total of **1143 rows** and **13 columns** [cite: 1]. 
The physicochemical features provided in the dataset are as follows:
`fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `chlorides`, `free sulfur dioxide`, `total sulfur dioxide`, `density`, `pH`, `sulphates`, `alcohol`, `quality`, and `Id` [cite: 1].

As it is generally observed that a higher quality of wine commands a greater price, we can safely deduce that `quality` is our dependent variable, whilst the remaining attributes serve as independent variables [cite: 1].


## The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/).

- **Source:** UCI Machine Learning Repository
- **Instances:** [e.g., 4,898]
- **Features:** [e.g., 11 numerical attributes, 1 target label]


## 🛠️ Tools & Libraries Utilised
To perform the needful data wrangling and visualisation, I have imported the following Python libraries [cite: 1]:
* **NumPy** & **Pandas**: For seamless data manipulation and array operations [cite: 1].
* **Matplotlib** & **Seaborn**: For plotting elegant and insightful visualisations, such as heatmaps and boxplots [cite: 1].

## 🔍 Step-by-Step Execution
1. **Data Inspection**: We commenced the programme by loading the dataset and examining its shape and columns [cite: 1].
2. **Data Cleaning**: 
   * Checked for missing values. Fortunately, **no null values** were present in this dataset [cite: 1].
   * Ascertained and dropped duplicated records to ensure our dataset is absolutely pristine and ready for further analysis [cite: 1].
3. **Univariate Analysis**: 
   * Visualised the value counts of the wine quality using a bar chart [cite: 1]. 
   * Analysed the alcohol content distribution using histograms fitted with a KDE (Kernel Density Estimate) [cite: 1].
4. **Bivariate & Multivariate Analysis**: 
   * Generated a comprehensive correlation heatmap to visualise the relationship metrics between all numeric variables [cite: 1].
   * Plotted boxplots to meticulously understand the behaviour of alcohol concentration across the different tiers of wine quality [cite: 1].

## 💡 Key Insights Drawn
* **Quality Distribution**: The quality rating of the wine is mostly clustered between 5 and 6 [cite: 1]. From this, we can conclude that the vast majority of the wines evaluated are of medium quality [cite: 1].
* **Data Purity**: The dataset is exceptionally clean with absolutely zero null values [cite: 1]. Post the removal of duplicate rows, the integrity of the data was perfectly maintained [cite: 1].
* **Presence of Outliers**: A visual inspection of the distribution plots revealed that the dataset possesses quite a few outliers across various features, which is evident from the charts plotting values extending up to the 1600 mark [cite: 1].
* **Alcohol-Quality Relationship**: The boxplots clearly illustrate a notable variation in alcohol content across different quality levels, indicating it is a significant factor in determining a wine's overall grade [cite: 1]. 

## 🚀 Instructions to Run the Project
To view and execute this analysis on your local machine, kindly do the needful:
1. Clone this GitHub repository to your local system.
2. Ensure you have Python installed along with the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).
3. Keep the `WineQT.csv` file in the same directory as the Jupyter Notebook [cite: 1].
4. Run all the cells in the notebook sequentially to reproduce the visualisations and analysis.

-------
