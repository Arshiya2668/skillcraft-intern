# skillcraft-intern
this is my 3rd internship journey
 🛳 Titanic Data Cleaning & Exploration

📌 Project Overview
This project cleans and explores the **Titanic Dataset**.  
The goal is to handle missing values, remove duplicates, and prepare data for further analysis or machine learning models.

🧹 Data Cleaning Steps
1. **Create a Copy of Original Dataset**
   - `data = df.copy()`

2. **Handle Missing Values**
   - **Age:** Replaced missing values with median age.
   - **Embarked:** Replaced missing values with most common value (mode).
   - **Fare:** Replaced missing values with median fare.
   - **Cabin:** Too many missing values → filled with `"Unknown"`.

3. **Remove Duplicates**
   - Dropped duplicate rows if any existed.

4. **Final Dataset**
   - Saved cleaned dataset as `titanic_cleaned.csv`

📊 Exploratory Data Analysis (EDA)
- Plotted bar chart of survivors vs non-survivors.
- Plotted survival rate by gender.
- Plotted survival rate by passenger class.
- Visualized distribution of age using histogram.
- Visualized distribution of fare using histogram.

 📁 Files in This Project
- `titanic_cleaned.csv` → Cleaned dataset
- `titanic_cleaning.ipynb` → Jupyter/Colab notebook with code & outputs
- (Optional) `plots/` → Contains saved plots as `.png` images

 🚀 How to Run
1. Open the notebook in Google Colab or Jupyter.
2. Upload the Titanic dataset CSV (if not included).
3. Run all cells step by step.
4. Check outputs & download `titanic_cleaned.csv`.

 🏁 Results
- Dataset is fully cleaned and ready for ML models.
- Missing values handled carefully.
- Visualizations provide quick insights into survival patterns.

👩‍💻 Author
**Arshiya Samreen**  
CSBS Student | Data Science Enthusiast

