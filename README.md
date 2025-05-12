# OIBSIP-NUTRITION-DATASET-
This dataset provides a nutrition analysis of every menu item on a Restaurant menu, including breakfast, beef burgers, chicken and fish sandwiches, fries, salads, soda, coffee and tea, milkshakes, and desserts.

## Project Objective
This project aims to perform an exploratory data analysis (EDA) on the nutritional dataset of McDonald's US menu. The dataset contains detailed nutritional information on all menu items, including breakfast items, beef burgers, chicken and fish sandwiches, fries, salads, beverages, milkshakes, and desserts. The objective is to uncover patterns, compare item categories, and provide insights that can help guide healthier food choices or marketing strategies.

## Key Concepts and Challenges:
-  *Data Loading and Cleaning: Load the retail sales dataset.

-  *Descriptive Statistics: Calculate basic statistics (mean, median, mode, standard deviation).

-  *Visualization: Present insights through bar charts, line plots, and heatmaps.

-  *Recommendations: Provide actionable recommendations based on the EDA.

## Data Cleaning Process
**Data Loading**
   - The dataset was loaded using pandas and inspected for structure and completeness.
**Missing Values**
   - No missing values were found in the dataset; all 260 rows and 24 columns were complete.
**Data Types**
   - All numerical columns such as Calories, Fat, Sugars, Sodium, etc., were already in correct numeric formats.
   - Non-numeric columns like `Category`, `Item`, and `Serving Size` were recognized as object types.
**Duplicates**
   - Checked for duplicate rows and confirmed that none existed.

## Key Insights

- **High Calorie Items**: Items such as large burgers and full-sized milkshakes were among the highest in calories, with some exceeding 1,000 calories per serving.
- **Sugars**: Desserts and beverages like shakes and sodas contribute significantly to daily sugar intake.
- **Sodium Levels**: Some salads and breakfast sandwiches contain sodium levels comparable to burgers, making them less healthy than assumed.
- **Portion Size Impact**: Larger portions or combo-style items drastically increase intake of calories, fats, and sugars.
- **Healthy Options**: While some items (like Egg White Delight) offer relatively lower calories and fat, others in the same category do not—indicating that assumptions based on category may be misleading.
- **Micronutrients**: A few items contribute significantly to daily Vitamin A, Calcium, or Iron requirements, but overall, most items are not strong sources of micronutrients.


