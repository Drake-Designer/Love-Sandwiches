![image](https://github.com/user-attachments/assets/d8079e03-6759-4763-9bd3-c9d214928582)

<br>

# 🥪 Love Sandwiches

Love Sandwiches is a Python-based automation project that helps a fictional sandwich business manage stock more efficiently.  
The program collects sales data, calculates surplus, and generates recommended stock levels for the next market day. All integrated with **Google Sheets** for real-time updates.

---

## 📌 Project Overview

The program includes:

- **Sales Data Input**  
  Collects 6 numbers (one per sandwich type) entered by the user and validates the input.

- **Automated Worksheet Updates**  
  New rows are automatically added to the **Sales**, **Surplus**, and **Stock** worksheets.

- **Surplus Calculation**  
  Compares sales with available stock to identify waste (positive values) or shortages (negative values).

- **Smart Stock Prediction**  
  Analyzes the last 5 entries of sales for each sandwich, calculates the average, adds 10%, and suggests how many sandwiches to prepare.

- **Clear Output**  
  Displays a summary in the terminal showing the recommended stock levels for each sandwich type.

---

## 🛠️ Technologies Used

- **Python 3** for logic and automation
- **gspread** to interact with Google Sheets
- **google-auth** for secure API authentication
- **Google Sheets API** as the backend database

---

## 📚 What I Learned

- How to connect Python with Google Sheets using APIs
- Validating and processing user input effectively
- **Creating and implementing functions** to structure and organize code
- Working with lists, loops, and dictionaries in a real-world context
- Automating repetitive business processes
- Presenting clear output for end users

---

## 📊 Example Output

Welcome to Love Sandwiches Data Automation

Please enter sales data from the last market. <br>
Data should be six numbers, separated by commas. <br>
Example: 10,20,30,40,50,60

Enter your data here: 20,30,25,22,18,27 <br>
Data is valid!

Updating sales worksheet...

Sales worksheet updated successfully. The new sales data are: [20, 30, 25, 22, 18, 27]

Calculating surplus data..

Updating surplus worksheet...

Surplus worksheet updated successfully. The new surplus data are: [3, -5, 1, 0, 6, -2]

Calculating stock data...

Updating stock worksheet...

Stock worksheet updated successfully. The new stock data are: [22, 25, 24, 22, 21, 24]

--- Make the following numbers of sandwiches for next market: ---

cheese ham: 22 <br>
tom moz: 25 <br>
chicken salad: 24 <br>
egg salad: 22 <br>
hummus veg: 21 <br>
ham egg: 24
