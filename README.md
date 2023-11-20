# matplotlib-challenge

- In this analysis, the following was observed for mice used in a drugs vs tumor size study
    - for the mice used in this study, the following was noted:
        - ID assigned to the mouse 
        - weight 
        - sex 
        - age 
        - the drug mouse was treated with 
    - results were obtained and the following was noted:
        - mouse ID
        - timepoint
        - tumor volume
        - metastic sites
- The mouse details and the results were combined into one Data Frame by merging the mouse details data with the results based on the Mouse ID, then duplicated mouse data was dropped in order to clean the data

### Summary Statistics

- The following was calculated for all the drug regimens used in the study:
    - mean tumor volume
    - median tumor volume
    - tumor volume variance
    - tumor volume standard deviation
    - tumor volume standard error

### Bar and Pie Charts

- Created a bar graph showing the total number of Timepoints for each drug regimen used in the study (# of Timepoints vs Drug Regimen)
- Created a pie chart showing the percentage of male and female mice used in the study

### Quartiles, Outliers and Boxplots
- Filtered the dataframe containing cleaned data with merged mouse details and results based on Mouse ID to show only the data for the greatest Timepoint for each mice to obtain the final tumor volume for each mouse
- Following drugs were selected:
    - Capomulin
    - Ramicane
    - Infubinol
    - Ceftamin
- The following was calculated with the tumor volume for the greatest timepoints (final tumor volume) of mice for each drug regimen listed above
    - quartiles
    - iqr
    - upper bound
    - lower bound
    - all of the above were used to determine outliers for each drug regimen listed above
- A box plot was created giving a visual of the calculated data above with the final tumor volumes for each of the drug regimens listed above

### Line and Scatter Plots
- A single mouse treated with Capomulin was selected and a line plot was created showing the tumor volume with respect to timepoint (tumor volume vs timepoint)
- Average tumor volume was obtained for each mouse who underwent the Capomulin drug regimen and it was plotted with respect to its weight (created a scatter plot, average tumor volume vs weight)

### Correlation and Regression
- Calculated the correlation coefficient for on the scatter plot average observed tumor volume vs mouse weight for the entire Capomulin regimen
- Performed a linear regression and displayed the regression line on the scatter plot average observed tumor volume vs mouse weight for the entire Capomulin regimen
<br><br>
