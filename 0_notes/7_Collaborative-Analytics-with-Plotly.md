# Collaborative Analytics with Plotly 

# Plotly for Web-Based Data Visualizations

## Plotly works with: 

* Python: NumPy, pandas, matplotlib, Jupyter
* R
* Excel 
*SQL 

The Plotly library is very useful becasue it allows you to use Python to quickly create beautiful and web-friendly interactive charts, dashboards, and reports that you can easily share across the internet. 

## Cufflinks for pandas in Plotly

* The cufflinks library is useful for binding Plotly to pandas objects within the Jupyter notebook. 

## Plotly Attibutes 

To generate Plotly plots from NumPy objects, you use the following Plorly attributes:

* Traces: These are objects taht describe a single variable of data in a graph; for example, a scatter plot or heatmap.

* Layouts: You use these attributes to set layout elements for your plot: for example, the title, x-axis, or annotations.

## Standard Plots in Plotly

* Line charts
* Bar charts 
* Pie charts

# Plotting Histograms from pandas Objects

1. Simple histogram chart - a Series object plotted as a simple interactive histogram

2. Multiple histogram charts - a DataFrame object plotted out in overlapping, transparent, interactive histograms

3. Subplot histograms - a DataFrame object plotted out in seperate, clear, interactive subplots

## Generativng Scatterplots

**Always set the 'mode' parameter to 'markers'**

* By default, Plotly will draw lines between data points, so if you want the points with no lines you need to designate the plot mode as markers
