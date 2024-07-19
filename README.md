# CareerSuccessPredictor

**CareerSuccessPredictor** is a machine learning project designed to predict students' likelihood of securing a job after graduation based on academic and personal data. The project aims to help educational institutions and students understand the factors influencing career success.

## Objective
Build a predictive model to forecast job placement success for students using historical data. Identify key factors that impact career outcomes to improve career planning and support.

## Data
The project uses the `collegePlace.csv` dataset, which includes:
- **Stream**: Academic major of the student.
- **Age**: Student's age.
- **Internships**: Number of internships completed.
- **CGPA**: Cumulative Grade Point Average.
- **Hostel**: Hostel residency (1 for Yes, 0 for No).
- **Gender**: Gender of the student.
- **HistoryOfBacklogs**: Academic backlog history.
- **PlacedOrNot**: Job placement status (1 for Yes, 0 for No).

## Methodology
1. **Data Preprocessing**: Convert categorical variables, handle missing values.
2. **Exploratory Data Analysis (EDA)**: Visualize data to understand patterns.
3. **Model Building**: Train and evaluate models including SVC, Decision Tree, Logistic Regression, Random Forest, and KNN.
4. **Evaluation**: Use cross-validation and confusion matrix to assess model performance.

## Results
- Random Forest Classifier achieved the highest accuracy.
- Key features influencing placement include CGPA, internships, and academic stream.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/MasoomehAzimi/CareerSuccessPredictor.git
