📊 **Student Job Application System — Power BI Dashboard**

**Project Overview**

The Student Job Application System is a comprehensive Power BI dashboard designed to analyse the full lifecycle of student job applications
— from submission to interviews and outcomes. It integrates multiple datasets into a clean star schema model and provides insights for students, 
universities, and employers.

This project demonstrates strong skills in data modelling, ETL, DAX, and interactive dashboard design.

**Data Model (Star Schema)**

Fact Tables:

Applications - All job applications submitted by students
Interviews - Interview schedules and outcomes

Dimensions Tables:

Students - Student demographics, academics, and experience
Jobs - Job postings created by employers
Employers - Employer/company details	

🗂️ **Table Structures**

**Students (Dimension)**
•	Student_ID
•	First_Name
•	Last_Name
•	Gender
•	University
•	Degree
•	Graduation_Year
•	Date_Joined
•	Work_Experience
•	Certifications

**Employers (Dimension)**
•	Employer_ID
•	Company_Name
•	Industry
•	Company_Size
•	Location

**Jobs (Dimension)**
•	Job_ID
•	Employer_ID
•	Job_Title
•	Job_Type
•	Department
•	Location
•	Salary
•	Start_Date
•	End_Date

**Applications (Fact)**
•	Application_ID
•	Student_ID
•	Job_ID
•	Application_Date
•	Application_Status (Pending Review, Shortlisted, Interview Scheduled, Rejected)

**Interviews (Fact)**
•	Interview_ID
•	Application_ID
•	Interview_Date
•	Interview_Type
•	Interview_Result (Pass, Fail, Pending)

📈 **Dashboard Pages & Insights**

1️⃣ **Applications Overview**
This page provides a high level view of the entire application pipeline.
•	Top Employers by Application Volume
•	Applications Over Time
•	Application Funnel
•	Interview Results Breakdown (Pass / Fail / Pending)
This page helps identify trends, bottlenecks, and overall hiring performance.

2️⃣ **Student Analytics**
This page analyses student performance, engagement, and success factors.
•	University wise Performance
•	Work Experience vs Applications & Pass Rate
•	Degree wise Application Trends
•	Certifications vs Pass Rate
•	Applications by Gender
This page highlights how student background, experience, and education influence outcomes.

3️⃣ **Employer Analytics**
This page focuses on employer engagement and hiring effectiveness.
•	Top Employer by Applications (SkyWave Media)
•	Employer wise performance table
•	Shortlist Rate by Employer
•	Interview Pass Rate by Employer
•	Employer Engagement Score
This page helps identify which employers are most active and effective in the hiring process.

🛠️ **Tools & Technologies**
•	Power BI Desktop
•	Power Query (ETL)
•	DAX for KPI calculations
•	CSV datasets
•	GitHub for version control

🎯 **Key Skills Demonstrated**
•	Data modelling (fact/dimension schema)
•	DAX measures for pipeline and performance metrics
•	Interactive visual design
•	Data cleaning and transformation
•	Analytical storytelling
•	Insight generation for stakeholders

**How to Use**
1.	Download the .pbix file
2.	Open in Power BI Desktop
3.	Explore the dashboard pages
4.	Review the data model and DAX logic

**Contact**

Dhanashree Shripatwar

www.linkedin.com/in/dhanashree-shripatwar-484416209
