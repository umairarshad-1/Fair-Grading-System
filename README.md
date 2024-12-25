# Fair-Grading-System
User Information:
username: admin
password: abc

Fair Grading System using Python

1. Introduction
Grading systems at universities often rely on either absolute or relative grading schemes to determine final grades. The objective of this project is to design and implement a Relative Grading System that takes student scores, analyzes their distribution, and adjusts the grades to conform to a predefined distribution while maintaining fairness and statistical validity. This system allows instructors to input grades, select grading schemes, and visualize adjustments with statistical justifications. The report documents the methodology, statistical analysis, and results achieved during the project implementation.
________________________________________
2. Methodology
The system was implemented following the outlined requirements:
1.	Input Module:
o	Allowed instructors to upload student grades via a CSV or Excel file.
o	Provided an option to select either absolute grading (fixed thresholds) or relative grading (adjustments to fit a predefined grade distribution).
2.	Statistical Analysis:
o	Computed descriptive statistics, including mean, variance, standard deviation, and skewness, for both original and adjusted grades.
o	Generated histograms and density plots to illustrate grade distributions before and after adjustments.
3.	Grade Adjustment:
o	Relative Grading: Applied curve fitting to normalize the distribution, scaling grades to match a desired normal curve.
o	Absolute Grading: Applied fixed thresholds as per instructor-defined grade boundaries (e.g., >=90% = A, >=80% = B).
4.	Reporting and Visualization:
o	Created comparative visualizations, including histograms, bar charts, and box plots.
o	Provided a detailed summary of grade adjustments and the impact on grade categories.
5.	Error Handling:
o	Ensured invalid or missing inputs were flagged with appropriate error messages.
4. Results and Visualizations
The following visualizations were generated to illustrate the results of the grading adjustments:
1.	Histogram of Original Grades:
o	Displays the distribution of raw scores before adjustments, showing variability in student performance.
2.	Histogram of Relative Grades:
o	Demonstrates the impact of applying relative grading, aligning grades to a normal distribution.
3.	Box Plot of Grades:
o	A comparative box plot highlights the spread, median, and outliers for both original and adjusted grades.
4.	Bar Plot of Absolute Grades:
o	Illustrates the count of students in each grade category (A, B, C, D, F) under absolute grading.
5. Insights and Conclusions
•	Relative Grading:
o	Ensures fairness by adjusting grades to a predefined statistical distribution.
o	Helps in situations where raw scores are unevenly distributed.
•	Absolute Grading:
o	Provides clear, fixed benchmarks for performance evaluation.
o	May not reflect relative performance in competitive scenarios.
•	Grade Distribution:
o	Relative grading increased the proportion of students in higher grade categories.
o	Absolute grading categorized students strictly based on predefined thresholds.
________________________________________
6. Challenges and Future Work
•	Challenges:
o	Handling missing or inconsistent data in real-world datasets.
o	Balancing fairness in relative adjustments while maintaining transparency.
•	Future Work:
o	Implement a GUI for user-friendly interaction.
o	Extend the system to support additional statistical and machine learning-based grading models.
________________________________________
7. Appendix
•	Dataset: A sample dataset of student grades is provided in the accompanying CSV file.
•	Code Implementation: The Python code used to generate the results and visualizations is available upon request.
________________________________________
8. References
•	Statistical methodologies for grade normalization and distribution.

