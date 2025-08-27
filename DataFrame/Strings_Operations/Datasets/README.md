# Dataset Descriptions

## Expense Data (`expense_data.csv`)

This dataset contains **personal expense and income records**.  
It is useful for analyzing **spending patterns, income-expense balance, and transaction categorization**.

### **Columns**
- **Date** – Date and time of the transaction  
- **Account** – Source or account used for the transaction  
- **Category** – Broad classification of the expense or income (e.g., Food, Transportation)  
- **Subcategory** – Detailed subcategory (mostly empty in this dataset)  
- **Note** – Additional details or descriptions of the transaction  
- **INR** – Amount in INR currency  
- **Income/Expense** – Specifies whether it is an income or an expense entry  
- **Note.1** – Empty column (not relevant for analysis)  
- **Amount** – Amount of the transaction  
- **Currency** – Currency type (mostly INR)  
- **Account.1** – Duplicate numeric value of amount, likely for balance calculations  

---

## Titanic Dataset (`titanic.csv`)

The classic Titanic dataset used for **machine learning and data analysis**, focusing on **survival prediction**.  
It provides demographic and ticket-related details of passengers.

### **Columns**
- **PassengerId** – Unique ID for each passenger  
- **Survived** – Survival status (`0 = Did not survive`, `1 = Survived`)  
- **Pclass** – Ticket class (`1 = 1st`, `2 = 2nd`, `3 = 3rd`)  
- **Name** – Full name of the passenger  
- **Sex** – Gender of the passenger  
- **Age** – Age of the passenger (some missing values)  
- **SibSp** – Number of siblings or spouses aboard  
- **Parch** – Number of parents or children aboard  
- **Ticket** – Ticket number  
- **Fare** – Ticket fare price  
- **Cabin** – Cabin number (many missing values)  
- **Embarked** – Port of embarkation (`C = Cherbourg`, `Q = Queenstown`, `S = Southampton`)  

---

## Use Cases
- **Expense Data** – Budget tracking, trend analysis, and personal finance visualization.  
- **Titanic Data** – Exploratory data analysis (EDA), feature engineering, and classification model training.

