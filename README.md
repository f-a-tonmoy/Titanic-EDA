# Titanic Exploratory Data Analysis (EDA)

## 📋 Project Overview
This project explores the **Titanic Dataset** to uncover insights into the survival of passengers. Using Python and various data visualization libraries, the notebook performs detailed exploratory data analysis (EDA), cleanses missing values, and examines patterns that could explain the survival rates.

---

## 📂 Project Structure

```plaintext
├── Titanic EDA.ipynb         # Main analysis notebook
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
```

---

## 📂 Dataset Details

The dataset used for this project is the **Titanic - Machine Learning from Disaster** dataset, available on [Kaggle](https://www.kaggle.com/c/titanic/data).

### Files:
1. **train.csv**:
   - Contains 891 entries with labeled survival outcomes.
   - Includes features such as:
     - `PassengerId`: Unique ID for each passenger.
     - `Pclass`: Passenger class (1st, 2nd, or 3rd).
     - `Name`: Passenger's name.
     - `Sex`: Gender.
     - `Age`: Age of the passenger.
     - `SibSp`: Number of siblings or spouses aboard.
     - `Parch`: Number of parents or children aboard.
     - `Ticket`: Ticket number.
     - `Fare`: Ticket fare.
     - `Cabin`: Cabin number (mostly missing).
     - `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

2. **test.csv**:
   - Contains 418 entries without survival labels.
   - Used for prediction and evaluation.

3. **gender_submission.csv**:
   - Sample submission file provided by Kaggle for formatting predictions.

### Dataset Link:
Access the dataset at [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data).

---

## ✨ Features
- **Data Preprocessing**:
  - Handled missing values using statistical imputation (median for `Age`, mode for `Embarked`, and mean for `Fare`).
  - Dropped the `Cabin` column due to excessive missing data.
- **Visualization**:
  - Correlation heatmaps to analyze relationships between variables.
  - Bar plots, pie charts, and box plots to study survival patterns across age, gender, class, and family relationships.
- **Key Analyses**:
  - Survival rate by gender, ticket class, port of embarkation, and family size.
  - Examined the influence of age and fare on survival rates.
- **Comparison of Survival**:
  - Analyzed survival rates between males and females, passengers in different classes, and families with varying numbers of dependents.

---

## 📊 Key Findings
1. **Gender and Survival**:
   - 82.62% of female passengers survived, compared to only 12.93% of male passengers.
2. **Class and Survival**:
   - First-class passengers had the highest survival rate, followed by second and third class.
3. **Port of Embarkation**:
   - Passengers from Cherbourg had a higher survival rate compared to Southampton and Queenstown.
4. **Family Size**:
   - Passengers with smaller families (1-2 dependents) had higher survival rates.
5. **Age**:
   - Younger passengers were more likely to survive than older passengers.

---

## 📈 Visualization Highlights
- **Correlation Matrix**: Highlighted a strong positive correlation between `Survived` and `Sex`.
- **Bar Plots**: Compared survival rates across classes, genders, and family sizes.
- **Box Plots**: Illustrated the age distribution of survivors and non-survivors.

---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `Pandas` for data manipulation
  - `Seaborn` and `Matplotlib` for visualization
  - `Missingno` for missing value analysis
  - `Scikit-learn` for machine learning

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Titanic\ EDA.ipynb
   ```

---

## 📄 License
This project is licensed under the MIT License.

---

## 📬 Contact
For questions or feedback, please reach out via:
- **Email**: [f.a.tonmoy00@gmail.com](mailto:f.a.tonmoy00@gmail.com)
