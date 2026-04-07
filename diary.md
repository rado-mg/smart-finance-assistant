### AI Collaboration #[1]
**Context**: [we were trying to load data in the code and explore them.]
**Prompt**: "[I'm building a Smart Finance Assistant for my programming assignment. I need to load a CSV file with transaction data (columns: Date, Amount, Category, Description). The Amount column has dollar signs that need cleaning. Please write professional Python code with detailed comments that:
-Loads the CSV data
-Cleans and validates the data
-Shows basic information about the dataset
-Handles any common data issues"* :::]"
**Result**: [The AI gave me python code that shows how to open the csv file, then clean the amount column by removing dollar sign and commas, and make sure the numbers are usable for calculations.It also checks for missing values, convert the date column into proper date format, and drops rows that do not have critical information.Finally, it prints out useful details about the dataset such as summary statistics and the list of categories, and fills in missing descriptions with "No description"]
**Reflection**: "[I was trying to upload the transactions file because it was unfound, apart from that , everything was correct.I learned how to open and read a CSV file in python, and I saw that it's important to check if the file exists before using it.Also, I found out that numbers in finance data often come with symbols like $ and these need to be cleaned before doing calculations.Then,I understood that date should be converted into proper date format for easy sorting and analyzing transaction over time.Moreover, I noticed that missing values can cause problems , so the row with missing data is removed  or fill with default text.]"
### AI Collaboration #[2]
**Context**: [I was trying to create the core analysis functions for my smart finance assistant so that I could understand the spending patterns.]
**Prompt**: "[For my Smart Finance Assistant, I need functions to analyze spending data. Please create well-documented functions that:
-Calculate total spending by category
-Find the top 5 spending categories
-Calculate average spending per transaction
-Identify any unusual transactions (very high or negative amounts) Each function should have clear business explanations and error handling.]"
**Result**: [The AI gave me simple python functions that help analyze my spending data.One function adds up all the money spent in each category, another shows the top 5 categories where I spend the most,another calculates the average amount I spend per transaction, and the last one finds unusual transactions such as very high amounts or negative values.]
**Reflection**: "[when I run it , nothing bad happened. I learned that breaking my project into small, and clear functions makes it much easier to understand and test.I could see thanks to Ai how each function can focus on one task such as finding totals, averages or unsual transactions.Also , I realized that adding simple checks for errors keeps the code from failing when data is not perfect. ]"
### AI Collaboration #[3]
**Context**: [I was trying to generate business insights from my spending data by turning the analysis functions into a financial report]
**Prompt**: "[Using the transaction analysis functions, help me create a comprehensive spending report that would be useful for personal financial planning. Include recommendations for potential savings and spending pattern observations. Format it like a professional financial summary]"
**Result**: [The AI gave me a report about spending which is written like financial summary.Within it , I can see how much I spent in each category.Also, it listed the top 5 spending areas, and calculated the average amount per transaction.There are flagged transactions which are unusual , short notes about my spending habits and  simple tips for saving money.]
**Reflection**: [the spending report was clear and easy to follow.But some of the values were placeholders such as $X, $Y, $M, so I had to replace them with my actual data.What I learned is how to turn raw transaction data into a report that looks professional and easy to understand.]

