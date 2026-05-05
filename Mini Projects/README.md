# Customer Ticket Support Analyser

## 📌 Overview

This mini-project is a Python-based system developed to analyze customer support tickets. It processes ticket data, performs text cleaning, analyzes issue patterns, and generates insights to understand common customer problems and support efficiency.

## 🎯 Objective

To build a structured ticket analysis workflow using core Python fundamentals and extract meaningful insights from customer support data.

---

## 🛠 Implementation

### 🔹 Data Initialization

* Created a structured dataset using a dictionary of lists
* Stored ticket details such as Ticket Number, Customer Name, Issue Description, and Priority
* Displayed the dataset in a readable format

---

### 🔹 Dynamic Ticket Addition

* Allowed user input to add new tickets
* Collected:

  * Customer Name
  * Issue Description
  * Priority (High / Medium / Low)
* Implemented:

  * Auto-incrementing Ticket IDs
  * Validation for priority values
* Appended new records to the dataset

---

### 🔹 Text Preprocessing

* Cleaned issue descriptions by:

  * Removing punctuation
  * Converting text to lowercase
  * Removing extra spaces
  * Standardizing text for consistency

---

### 🔹 Keyword-Based Analysis

* Built a function to count occurrences of specific words
* Performed case-insensitive keyword search
* Analyzed frequency of words like:

  * "poor"
  * "good"
  * "slow"
  * "excellent"

---

### 🔹 Data Analysis & Insights

#### 📊 Ticket Summary

* Calculated total number of tickets
* Analyzed distribution of tickets based on priority levels:

  * High
  * Medium
  * Low

#### 🧾 Longest Issue Identification

* Identified the ticket with the longest issue description
* Displayed:

  * Ticket number
  * Customer name
  * Issue description
  * Word count

#### 🔤 Unique Word Extraction

* Extracted unique words from all ticket descriptions
* Calculated total count of unique words
* Displayed sorted list of words

---

## 📊 Key Insights

* High number of tickets indicates frequent customer interaction with support systems
* Common issues include system delays, login problems, and payment failures
* Repeated complaints suggest unresolved root causes
* Response delays indicate inefficiencies in ticket handling

---

## 💡 Recommendations

* Improve system performance and backend efficiency
* Enhance reliability of login and payment systems
* Optimize ticket handling and prioritization
* Address root causes to reduce recurring issues

---

## 📈 Conclusion

The analysis shows that while support services are functioning, technical issues and delays impact customer satisfaction. Improving system performance and resolution efficiency can significantly enhance overall support quality.

---

## 📂 File

* `Customer Support Ticket Analyzer.ipynb` → Complete implementation and analysis

---

## ▶️ How to Run

* Open the notebook in Jupyter Notebook or Google Colab
* Run all cells sequentially to view outputs

---

## 🧰 Skills Demonstrated

* Python fundamentals (loops, conditionals, functions)
* Data handling using lists and dictionaries
* Text preprocessing and cleaning
* Keyword-based analysis
* Logical problem-solving and insight generation

---

## 🚀 Future Enhancements

* Use Pandas for efficient data analysis
* Add visualizations using Matplotlib and Seaborn
* Work with larger and real-world datasets
