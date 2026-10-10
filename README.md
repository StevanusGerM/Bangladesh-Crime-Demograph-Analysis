# Bangladesh Crime Dataset - Exploratory Data Analysis (EDA)

This project contains an Exploratory Data Analysis (EDA) using Python to analyze crime patterns in Bangladesh based on the `Bangladesh_Crime_Dataset_B.csv` dataset[cite: 4].

## 🛠️ Libraries Used
This notebook utilizes several core libraries for data manipulation and visualization:
- **Pandas** & **NumPy**: For data processing and manipulation[cite: 4].
- **Matplotlib** & **Seaborn**: For data visualization[cite: 4].
- **Scikit-Learn**: For clustering preparation (such as `KMeans`, `RobustScaler`, `PCA`, and evaluation metrics like the *Silhouette Score*)[cite: 4].

## 📊 Analysis Steps Summary
1. **Load Dataset**: Loading the crime dataset into a Pandas dataframe[cite: 4].
2. **Data Overview**: 
   - Checking data dimensions (total rows and columns)[cite: 4].
   - Reviewing data types and non-null counts[cite: 4].
   - Checking for missing values and duplicate rows[cite: 4].
   - Displaying descriptive statistics for numerical variables[cite: 4].
3. **Categorical Variable Analysis**:
   - Examining unique values in regional columns (`incident_district` and `incident_division`)[cite: 4].
   - Analyzing the distribution of crime types (e.g., *murder*, *rape*, *assault*, *robbery*, etc.)[cite: 4].
   - Reviewing seasonal conditions during incidents (*season*)[cite: 4].

## 🚀 How to Run
1. Ensure you have installed the required Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`)[cite: 4].
2. Place the dataset file `Bangladesh_Crime_Dataset_B.csv` in the same directory as the notebook[cite: 4].
3. Run the code cells in the notebook sequentially.
