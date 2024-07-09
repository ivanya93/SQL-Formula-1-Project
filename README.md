# SQL-Formula-1-Project

MOOC Spring Last Year Project - Code First Girls Course on Data and SQL

Project Overview

This project was undertaken as the final challenge for the Code First Girls course on Data and SQL. Our team chose to analyze the Formula 1 World Championship dataset, sourced from Kaggle, covering the years 1950 to 2020. The objective was to apply the concepts learned during the course, such as Data Definition Language (DDL) and Data Manipulation Language (DML), and to present our findings through analytical insights and visualizations.

Judging Criteria

Teams were judged based on four key criteria, each carrying equal weight (25%):

	1.	Innovation: Did the response take a fresh approach to the challenge?
	2.	Analytical Skills: Demonstration of understanding of DDL, DML, and aggregate functions.
	3.	Presentation: Quality of code files, database design, and overall presentation.
	4.	Adherence to Challenge Theme: Did the team adhere to the theme of the challenge?

Dataset

Source: Formula 1 World Championship 1950-2020

Project Summary

1. DDL / Data Definition Language

1.1. Preparation and Processing of Data

	•	Normalized tables to eliminate redundancy and ensure data integrity.
	•	Adjusted data types to match the requirements of SQL queries.

1.2. Primary Key and Foreign Key

	•	Defined primary keys for unique identification of records.
	•	Established foreign keys to maintain referential integrity between tables.

2. Defining the Problem We Are Trying to Solve

General Info about F1

	•	What countries compete in F1?
	•	Which country has hosted the most F1 races?
	•	Which circuit has hosted the most F1 races?

About the Racer

	•	Average, maximum, and minimum time differences between the 1st, 2nd, and 3rd place finishers.
	•	Constructor with the most race wins.
	•	Driver with the most race wins.
	•	Fastest pit stop in history.

Investigating the Relationships

	•	Comparison of the nationality of champions and the hosting countries.
	•	Top speed record in F1, correlated circuits, and constructors.
	•	Aggregate analysis (average, sum, count) of pole positions and race winners.
	•	Correlation between pit stop durations and race outcomes.
	•	Average pit stop duration by constructor and by circuit.
	•	Analysis of the so-called “Curse of Number 13” (Did car number 13 lose more races or have more disqualifications/accidents?)

3. DML / Data Manipulation Language / Aggregate Functions / Analyzing the Data

	•	Used SQL to manipulate and query the data.
	•	Employed aggregate functions (COUNT, SUM, AVG, MAX, MIN) to derive insights.

4. Sharing the Insights

	•	Created dashboards and graphs using tools like Tableau to visualize findings.
	•	Presented the insights in a clear and compelling manner.

Detailed Analysis and Findings

General Info about F1

	•	Countries Competing in F1: Analyzed the dataset to list all countries that have participated.
	•	Most Hosting Country: Identified the country with the most F1 races hosted.
	•	Most Hosting Circuit: Determined the circuit that has hosted the most F1 races.

About the Racer

	•	Time Differences: Calculated the average, maximum, and minimum time differences between the top three finishers.
	•	Top Constructor: Identified the constructor with the highest number of race wins.
	•	Top Driver: Found the driver with the most race wins.
	•	Fastest Pit Stop: Tracked the record for the fastest pit stop in history.

Investigating the Relationships

	•	Champion Nationality vs. Hosting Country: Compared the nationality of race winners with the countries where races were hosted.
	•	Top Speed Record: Correlated the top speed records with specific circuits and constructors.
	•	Pole Positions and Winners: Aggregated data on pole positions (q1, q2, q3) and race winners.
	•	Pit Stop Analysis: Analyzed the correlation between pit stop durations and race outcomes, and calculated average pit stop durations by constructor and circuit.
	•	Curse of Number 13: Investigated if car number 13 had a higher incidence of losses, accidents, or disqualifications:
       -- Formula 1 has banned the number 13. There is also no garage with the number 13 and, previously, when numbers were assigned based on constructors' position in          the standings, teams avoided that number.
         Why? Because historically, whoever has used 13 in F1 has finished badly. This number records two deaths in a row in 1925 (Paul Torchy) and 1926 (Giulio                 Masetti). In recent history, four riders have tried this number and it hasn't gone well: fires, dropouts, failures to qualify for races...
         The closest case is that of Pastor Maldonado. The Venezuelan used the 13 in his Lotus during the 2014 and 2015 seasons, and retired from F1 with almost more            DNFs/dropouts than points in those two seasons.

-- Conclusion

-- This project provided a comprehensive analysis of the Formula 1 World Championship dataset, demonstrating our team’s proficiency in SQL and data analysis. The innovative approach, thorough analytical skills, clear presentation, and adherence to the challenge theme were all focal points of our project.

Team

	•	Ivana Lovera
	•	Vaibhavi C Mayya
 	•	Jasmine Lam.

Tools and Technologies

	•	SQL
	•	Python
	•	Tableau
 	•	Kaggle

Acknowledgments

We would like to thank Code First Girls for providing this learning opportunity and Kaggle for the dataset. Special thanks to our course instructors and mentors for their guidance and support.

This README should provide a clear and detailed overview of your project, covering all essential aspects and highlighting your team’s efforts and achievements.
