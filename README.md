# matplotlib-challenge

![Laboratory](https://github.com/s0uravk/matplotlib-challenge/assets/144293972/5ba959b0-75e8-4c09-9c08-c755954e918a)

In this algorithm, it's analyzing the data regarding 249 mice being tested on with various Drug regimens to find a cure for Skin cancer and using Matplotlib to visualize the data to enchance the decision making process. First, it's extracting the data from two CSV files and  merging them on a common column i.e. MOUSE ID in this case and then checking the data for any duplicates and getting rid of it to analyse the data with accuracy. And then, Statistically summarize the data and visualize the data in bar graphs, pie charts using pyplot and pandas, where bar graphs show the number of timepoints observed for each Drug regimen and pie charts show the percentage of obeservations based on the Gender.

Furthermore, this script create a dataframe where timepoint for each mouse is maximum, hence shows the observations at the final stage of the testing. Then, it calculates necessary values such as lower quatile, upper quatile, interquartile range, lower boundry and upper boundry, to locate potential outliers for a list of specific drugs that is also confirmed later when we visualize the data using boxplot.

Moreover, it visualize the changes occured in tumour volume over timepoints(in days) for a specific Drug Regimen and Mouse ID. And the, data for weight of the mice and tumour volume is visualized using scatter plot as these two are correlated. And to show this correlation a line is also plotted on to the scatter plot using linregress function to obtain slope and intercept of the scatter plot as well as rvalue is calculated i.e. 0.84 which is a great correlation. 
