# Team_5_Statistics
Repo to work on Mental Health Dataset Together

To-Do List for EDA Report:

### Complete this weekend (1-5):

1. **Data Overview**
   - [ ] Merge Datasets to create one dataset to work on.
   - [ ] Clean (we need to create categorical variable for life ladder).
   - [ ] Provide sample size, number of variables, and data source.
   - [ ] Include a brief description of how the data was collected.
   - [ ] Clearly state the research questions.
        + To what extent do happiness metrics (predictor variables: log GDP per capita, social support, life expectancy, freedom, perception of corrpution, generosity) predict mental health disorders, specifically, depression (outcome variable: continuous) in countries?
        + To what extent do mental health disorders and happiness
metrics (predictor variables: schizophrenia, bipolar disorder, eating disorders, anxiety disorders, depression, log GDP per capita, social support, freedom, perception of corrpution, generosity) predict life ladder (outcome variable: categorical)?

2. **Outcome Variables**
   - [ ] Generate a plot for each outcome variable.
   - [ ] Ensure the plots are well-labeled and described.
   - [ ] Use variable descriptions in labels (e.g., "Salary ($)" instead of "salary_in_usd").

3. **Primary Relationships of Interest**
   - [ ] For the dependent variable and primary independent variable (if applicable):
     + [ ] Present descriptive statistics (mean, median, mode, CIs, etc. _PLS ADD HERE BASED ON WHAT YOU THINK IS NECESSARY_)
     + [ ] Create exploratory plots (tables or figures).
     + [ ] Provide clear descriptions of findings.

4. **Other Characteristics**
   - [ ] Briefly describe the types of variables present in the data (e.g., demographic information).
   - [ ] Avoid listing all variables if there are many.

5. **Potential Challenges**
   - [ ] Identify potential challenges in the data that may affect modeling. (AARYA)
   - [ ] Consider categorical variables that might need collapsing. (_Included in Data Cleaning_)
   - [ ] Address missingness, especially in key variables.
   - [ ] Discuss any issues related to dataset size and its impact on model selection. (AARYA)

6. **No Data Cleaning (Except if Necessary)**
   - [ ] Perform data cleaning only if needed, such as combining datasets or creating an outcome variable. (_Mentioned above for categorical variable. I dont think we need anything else._)

### For Later:

7. **Use Quarto for Report**
   - [ ] Ensure the report is generated using Quarto.
   + - [ ] Code to use later:
title : ""
documentclass: report
output:
  pdf_document:
    latex_engine: xelatex
  top-margin: 1in
geometry: margin = 3.175cm
   - [ ] Render the report directly to PDF.

8. **Formatting and Labels**
   - [ ] Double-check the formatting of tables and figures.
   - [ ] Verify that all labels and descriptions are clear and informative.

9. **Collaboration and Code Sharing**
   - [ ] Utilize GitHub to share code among group members.
   - [ ] Plan tables and figures allocation among group members and consolidate the code for the report.

10. **Submission**
   - [ ] One person should submit the report on Gradescope.
   - [ ] Ensure all group members are correctly assigned in the submission.

Remember to allocate tasks efficiently among group members and communicate effectively to ensure a comprehensive and well-organized EDA report.
