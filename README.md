# Fair-Grading-System
Fair Grading System using Python
Relative Grading System Project Report
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

