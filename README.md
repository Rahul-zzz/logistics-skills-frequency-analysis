Logistics Skills Frequency Analysis

Project Overview
This project analyzes logistics and supply chain job postings collected from Naukri.com to identify the most in-demand skills in the industry. Using Python, Pandas, and Matplotlib, the project performs skill frequency analysis, categorizes skills into meaningful groups, identifies must-have skills, and visualizes the results.

Objectives
Extract and analyze required skills from job postings.
Identify the most frequently requested skills by employers.
Calculate skill occurrence percentages across job postings.
Categorize skills into predefined skill groups.
Highlight must-have skills based on frequency thresholds.
Visualize skill demand using a bar chart.

Dataset
Source: Naukri.com job postings
Domain: Logistics and Supply Chain

Cities Covered:
Mumbai
Delhi
Chennai
Bengaluru
Pune
Ahmedabad
Total Job Postings Analyzed: 200
Technologies Used
Python
Pandas
Matplotlib
OpenPyXL
Project Workflow
Load the cleaned job postings dataset.
Extract and split skills from the Required Skills column.
Count the frequency of each skill.
Calculate percentage occurrence across all postings.
Identify the Top 30 most requested skills.
Categorize skills into:
Technical Skills
Soft Skills
Software/Tools
Language Requirements
Flag skills appearing above the defined threshold as "Must Have".
Create a bar chart for the Top 15 skills.
Outputs
Skills Frequency Table

Contains:
Skill Name
Frequency Count
Percentage of Job Postings
Skill Category
Must Have Indicator

Output File:

skills_frequency_table.xlsx
Skills Frequency Visualization

Top 15 skills are visualized using a bar chart.

Output File:

top15_skills.png
Sample Insights
Logistics was the most frequently requested skill.
Dispatch and Operations were among the top employer requirements.
Technical skills dominated logistics job postings.
No individual skill exceeded the 30% threshold for "Must Have" classification, indicating a diverse skill demand across employers.

Project Structure
Logistics-Skills-Frequency-Analysis/
│
├── clean_jobs_200.csv
├── skills_analysis.py
├── skills_frequency_table.xlsx
├── top15_skills.png
└── README.md

How to Run

Install required packages:
pip install pandas matplotlib openpyxl
Run the analysis:
python skills_analysis.py

Learning Outcomes
Data cleaning and preprocessing using Pandas
Frequency analysis of textual data
Skill categorization and classification
Percentage-based job market analysis
Data visualization using Matplotlib
Extracting business insights from recruitment data

Author
Raghul Baskaran

Logistics & Supply Chain Job Market Analysis using Python, Pandas, and Matplotlib.
