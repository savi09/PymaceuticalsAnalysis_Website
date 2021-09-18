# PymaceuticalsAnalysis_Website
Using HTML and CSS to create a dashboard showing the Pymaceuticals analysis.

To view the original analysis go to [PymaceuticalsAnalysis](https://github.com/savi09/PymaceuticalsAnalysis) github repository.

## Sumamry Table
Created a summary table of mean, median, variance, standard deviation, and standard error of mean of the tumor volume for each drug regimen. Drugs for treatment: Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Placebo, Propiva, Ramicane, Stelasyn, and Zoniferol

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/7f709c5792479447344288ec903d68c3eba29179/Charts/Drug%20Regimen_Summary%20Table%20(Screenshot).png)

## Bar Chart
Created a bar chart to display the number of mice in each drug regimen.

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/df85942d227223dcda5ae03e84edc258d81953c8/Charts/Number%20of%20Mice%20Tested.png)

## Box Plot
Of all the drug regimens only one drug had a potential outlier. Infubinol's has 1 potential outlier. Created a box and whisker plot of the final tumor volume for Campomulin, Zoniferol, Ketapril, and Propriva. For this I used the following sources:
  
    * To loop through two lists (used to print potential outliers): https://stackoverflow.com/questions/1663807/how-to-iterate-through-two-lists-in-parallel
    * To convert from list to array for plotting: https://www.educative.io/edpresso/how-to-convert-a-list-to-an-array-in-python

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/df85942d227223dcda5ae03e84edc258d81953c8/Charts/Final%20Tumor%20Volume.png)

## Line 
Created a line chart to display tumor volume vs. time point for a specific mouse treated with Capomulin. A list of mouse IDs are displayed, so that you can choose a mouse you want to look at. The following chart displays mouse ID: s710.

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/df85942d227223dcda5ae03e84edc258d81953c8/Charts/Tumor%20Volume%20over%20time%20for%20mouse%20of%20choice.png)

## Scatter Plot
Created a scatter plot to display the average tumor volume versus mouse weight for the Capomulin regimen.

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/df85942d227223dcda5ae03e84edc258d81953c8/Charts/Scatter%20Plot_Avg%20Tumor%20Volume%20vs.%20Mouse%20Weight.png)

## Correlation and Regression
This is the scatter plot displayed above but includes linear regression. In the Jupyter Notebook, it will also display the correlation coefficient.

![alt text](https://github.com/savi09/PymaceuticalsAnalysis/blob/df85942d227223dcda5ae03e84edc258d81953c8/Charts/Correlation%20Linear%20Reg.png)

