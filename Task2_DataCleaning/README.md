# 🧹 Task 2: Data Cleaning – AB_NYC_2019 Dataset

## 📌 Objective
Perform comprehensive data cleaning on the Airbnb NYC 2019 dataset to ensure it’s ready for further analysis or modeling.

---

## 📂 Dataset
- **File**: `AB_NYC_2019.csv`
- **Source**: Airbnb open data (2019)
- Contains listings for NYC including price, neighborhood, room type, availability, and more.

---

## 🔧 Cleaning Steps Performed

1. **Initial Data Inspection**
   - Used `.info()`, `.head()`, and `.describe()` to get an overview of the dataset
   - Checked for data types, missing values, and value distributions

2. **Handling Missing Values**
   - Dropped rows with critical missing data (e.g., `name`, `host_name`)
   - Imputed or filled values in non-critical columns when appropriate

3. **Duplicate Detection**
   - Checked for duplicate rows or duplicate listing IDs
   - Removed exact duplicates if found

4. **Outlier Detection & Removal**
   - Analyzed columns like `price`, `minimum_nights`, and `number_of_reviews`
   - Removed extreme outliers using thresholds (e.g., listings with `minimum_nights > 365`)

5. **Column Transformations**
   - Ensured proper data types (e.g., `last_review` to datetime)
   - Renamed columns for clarity (if applicable)

6. **Feature Engineerin**
