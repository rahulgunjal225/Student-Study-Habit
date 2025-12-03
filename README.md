🌟 STUDENT DATA ANALYSIS PROJECT

Using NumPy • Pandas • Seaborn • Matplotlib
A complete data-analysis pipeline that performs cleaning, exploration, statistical analysis, and visualization on student performance data.

📁 Project Structure
📦 Student-Analysis
 ┣ 📄 student_Data.csv
 ┣ 📄 student_1.py
 ┗ 📄 README.md

🚀 Key Features

🧼 1. Data Cleaning
      Removes unwanted spaces from column names
      Replaces missing numeric values using Mean
      Replaces missing categorical values using Mode

🧮 2. NumPy Operations
       Calculate Mean, Maximum, and Minimum of Marks
       Find average study hours using NumPy arrays

📊 3. Pandas Analysis
      Generate complete statistical summary with df.describe
      Display selected data → Name + Marks

📈 4. Visual Insights
   Visualizations Included:
      🔵 Scatter Plot — Study Hours vs Marks
      🟣 Histogram — Attendance Rate Distribution
      🟠 Bar Chart — Student Marks Comparison
All visuals are created using Seaborn + Matplotlib for a clean, modern look.

🛠️ Technologies Used
   Tool / Library                           Purpose
  🐍 Python 3.x                    	Base programming language
  🔢 NumPy	                        Numerical operations
  📊 Pandas                       	Data processing & analysis
  🎨 Seaborn                      	Advanced visualizations
  📈 Matplotlib                   	Graph plotting

▶️ How to Run the Project
   1️⃣ Clone the repository
       git clone https://github.com/your-username/student-analysis.git
      
   2️⃣ Install dependencies
       pip install numpy pandas matplotlib seaborn
   3️⃣ Execute the program
       python student_1.py

🗂️ Dataset Format
    Your student_Data.csv must include:
          Column Name	                                               Description
           Name	Student                                              full name
           Gender	                                                  Male/Female/Other
           StudyHours                                          PerWeek	Total weekly study hours
           AttendanceRate	                                       Attendance percentage
           Marks	                                                  Final exam score


📜 License — Apache 2.0
     Apache License  
  Version 2.0, January 2004  
  http://www.apache.org/licenses/

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.


