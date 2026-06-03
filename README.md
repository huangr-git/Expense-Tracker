[Expense Tracker.pptx](https://github.com/user-attachments/files/28567086/Expense.Tracker.pptx)
# Expense & Savings Tracker

A local Command Line Interface (CLI) application built in Python to track daily expenses and monitor personal savings goals. The application automates data storage using local CSV files and provides dynamic data visualizations to help users analyze their financial habits.

## 🚀 Features

### Expense Management
* [cite_start]**Add Expense:** Log an expense by selecting a predefined category and entering the amount spent. [cite_start]Automatically timestamps the entry with the current date.
* [cite_start]**View Expense Table:** Display all logged data in a structured tabular format using Pandas.
* **Expense Graphs:** Generate dynamic visualizations, including:
  * [cite_start]A **Bar Chart** showing total spending broken down by category.
  * [cite_start]A **Line Chart** displaying the daily spending trend over time.

### Savings Goals Tracking
* [cite_start]**Create Savings Goals:** Set up new financial goals with a target amount and a target completion date.
* [cite_start]**Contribute to Goals:** Allocate funds toward specific goals and instantly view your updated progress percentage.
* [cite_start]**Visual Progress Charts:** Render data visualizations to track how close you are to reaching your financial milestones.

---

## 🛠️ Tech Stack

* **Language:** Python 3
* [cite_start]**Data Libraries:** Pandas (for structured data manipulation and CSV handling) [cite: 1, 2]
* [cite_start]**Visualization Libraries:** Matplotlib (for rendering customized analytical charts) [cite: 1, 2]
* [cite_start]**Environment:** IPython Display (for enhanced tabular formatting in supported environments) [cite: 1, 2]

---

## 📋 File Structure & Automation

The application is fully self-sustaining. [cite_start]On its first run, it checks for existing storage files and automatically generates them if they do not exist[cite: 1]:
* [cite_start]`Expense Sheet.csv`: Stores columns for `Date`, `Category`, and `Amount`[cite: 1].
* [cite_start]`Savings Goals.csv`: Tracks `Goal Name`, `Target Amount`, `Current Amount`, and `Target Date`[cite: 1].

---

## ⚡ Getting Started

### Prerequisites
Ensure you have Python 3 installed on your machine. You will also need to install the required external libraries.

### Installation
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/expense-tracker.git](https://github.com/YOUR-USERNAME/expense-tracker.git)
   cd expense-tracker
