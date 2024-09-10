
# PyCitySchools - School and Standardized Test Data Analysis

This project involves analyzing school and standardized test data using **Pandas DataFrames** to assist in making strategic decisions regarding school budgets and performance improvements for a local government area.

## Background
As part of the project, the data scientist was tasked with analyzing standardized test results from schools within a local government area. The goal was to provide insights to the school board and mayor for decision-making related to school budgets and priorities. The data included every student’s maths and reading scores, as well as information about the schools they attended. The analysis involved aggregating this data to identify trends and overall school performance.

## Project Structure

1. **Repository Creation**: A new repository named `pandas-pycityschools` was created to store the project files. The entire analysis was conducted within a folder named `PyCitySchools`.
2. **Main Script**: The main analysis script was developed and executed in a Jupyter Notebook, performing data manipulations using the Pandas library.

## Code Details
This code was written using Python with the **pandas** library. It merges two CSV files combining information from two separate datasets, joining them together to enable a comprehensive examination of various factors influencing school performance in reading and maths across 15 different schools categorized by:
- **School type** (government or independent)
- **School size**
- **School budget per student per year**

The code for this analysis can be found in the **PyCitySchools** subfolder, and the file is named `PyCitySchools_starter.ipynb`.

The written analysis is included at the bottom of the notebook and is also available as a separate Word document located in the main folder, named `Pandas_challenge`.

## Files Used
The project used datasets that contained detailed information about student reading and maths scores, as well as school-specific data such as school type and budget allocations.

## Analysis Overview
The project included the creation of a detailed report that provided insights into various aspects of school performance across the local government area. The report was broken down into several key components:

### Local Government Area (LGA) Summary
A high-level summary of key metrics for the local government area was generated, including:
- The total number of unique schools
- Total student enrollment
- Total school budget
- Average maths score
- Average reading score
- Percentage of students passing maths
- Percentage of students passing reading
- Overall percentage of students passing both subjects

### School Summary
A summary of key performance metrics was created for each school, detailing:
- School name
- School type (e.g., government or independent)
- Total students per school
- Total school budget
- Per student budget
- Average maths and reading scores
- Percentage of students passing maths and reading
- Overall percentage of students passing both subjects

### Highest- and Lowest-Performing Schools
The schools were ranked by their overall passing percentages, and both the top 5 highest-performing and lowest-performing schools were highlighted.

### Scores by Year and Category
The analysis also broke down:
- **Maths and Reading Scores by Year**: The average maths and reading scores for students in years 9 through 12 at each school.
- **Scores by School Spending**: An analysis of school performance based on average spending per student, categorizing schools into bins of different spending ranges.
- **Scores by School Size**: An examination of school performance based on school size, categorized as small, medium, or large.
- **Scores by School Type**: School performance was also analyzed based on school type, such as government or independent schools.

## Observations
Several key trends were identified from the analysis:
1. Schools with smaller student populations generally showed higher overall passing rates.
2. Higher spending per student did not always correlate with better performance, as schools with moderate spending ranges had better overall passing rates compared to schools with the highest spending per student.

