# 📊 Bike Sales Dashboard Project
This project involved building an interactive Bike Sales Dashboard in Excel to analyze customer purchasing behavior based on gender, age group, and income. The goal was to transform raw sales data into clear, visual insights using pivot tables, slicers, and formulas.

# 🔧 Key Features & Tools Learned
Insert Slicer: Implemented dynamic filtering options, allowing users to easily explore data by gender, product category, and region.

Remove duplicates: This is applied to clean the dataset before analysis, ensuring accurate customer and sales figures.

Logical Formulas (IFS & AND): Used to group customers into meaningful age categories for better segmentation.

#💡 Formula Improvement
One key learning milestone was improving a flawed age categorization formula. Initially, the logic was written as: =IFS(L2 >54, "Old (Grater than 54)", L2 >=31 AND L2 < 55 , "Middle age(31-54)" , L2 <31, "Adolescent()Less than 31 "). This version caused issues due to incorrect use of the AND operator inside IFS. After troubleshooting and learning about correct syntax, it was improved to: =IFS(L2 > 54, "Old (Greater than 54)", AND(L2 >= 31, L2 <= 54), "Middle age (31–54)", L2 < 31, "Adolescent (Less than 31)").
This change significantly improved formula accuracy and readability, enhancing the quality of the dashboard.

# 📈 Outcome
The final dashboard allows users to:

1) Filter sales data interactively

2) Understand customer distribution by age and gender

3) Analyze the average income required per gender for purchase

4) Identify sales trends by product category

## 📚 What I Learned
Through this project, I gained hands-on experience with:

1) Excel dashboard design

2) Data cleaning techniques

3) Structured logical expressions

4) Visual storytelling using data



