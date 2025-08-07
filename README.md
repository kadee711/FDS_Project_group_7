🌍 Global Student Migration - Data Preprocessing and Visualization
This repository contains a complete pipeline for preprocessing and visualizing data related to global student migration and placement outcomes. The dataset includes academic, demographic, language, visa, and placement information for international students.

📌 Features
Data Upload and Exploration
Uploads a CSV file (global_student_migration.csv), displays initial rows, and summarizes data info and missing values.

Missing Data Handling

Fills missing values in placement_country, placement_company

Replaces 0.0 in test_score with mean value

Encoding Categorical Variables

Binary encoding for scholarship_received, placement_status

Label Encoding for columns like origin_country, field_of_study, etc.

Feature Engineering

Adds a new feature: duration = graduation_year - year_of_enrollment

Feature Scaling

Scales numerical columns such as GPA, test score, salary, and duration using StandardScaler

Train-Test Split

Splits the dataset into training and test sets for modeling

Exporting Processed Data

Saves the cleaned and processed dataset as Preprocessed_Global_Student_Data.csv

Data Visualizations

📊 Histogram: Distribution of GPA (scaled)

📊 Count Plot: Field of Study distribution

🔥 Correlation Heatmap: Relationships among numerical features

📊 Visa Status distribution

🛠️ Libraries Used
pandas, numpy

matplotlib, seaborn

sklearn (LabelEncoder, StandardScaler, train_test_split)
