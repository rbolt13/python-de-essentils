# Practical Data Visualization 

# Creating standard data graphics

## Charts 

### Line Chart

* Show the change in value of an attribute with respect to a x-variable (which is often "time")
* Can be used to visually compare the values of several related attributes

### Bar Chart

* Represents data attribute values within a particular data category by using bars of differing heights 
* Bar charts represent observation counts within categories

### Pie Chart

* Represents data attribute values using a circle and slices that comprise it
* A whole and entire set of categorical data is represented by the complete circle, and the proportions of observations that fall into the different categories are represented by proportionate pie slices. 

## Two Methods for Plot Building 

* Functional method: build plot by calling the plotting function on a variable or set of variables. 
* Object-oriented method: build plot by generating a blank figure object and then populating that object with a plot and plot elements. 

## Popular Data Visualizations Libraries in Python

* Matplotlib
* Seaborn 

# Defining Elements of a Plot

* Plot elements add context to your plot, so the plot effectively conveys meaning to its views

## Steps in Object-Oriented Plotting 

1. Create a blank figure object.
2. Add axes to the figure.
3. Generate plot(s) within figure object.
4. Specify plotting and layout parameters for the plots within your figure. 

## Subplots 

* A subplot is a plotting figure that contains more than one plot - or subplots

# Plot Formatting

* Defining plot color
* Customizing line styles
* Setting marker styles

## Matplotlib Color Options

* Set the color parameter equal to the name of the color that you want.
* Or, set the color parameter equal to RGB or RGBA color codes for even more customization. 

![image](https://user-images.githubusercontent.com/76530973/191789151-8c61f497-d852-43be-a622-dd97d3cc87de.png)

[Matplotlib Color Examples](https://matplotlib.org/2.0.2/examples/color/named_colors.html)

## Matplotlib Line Styles

* Line style argument: ls='...'
* Line width argument: lw='...'

![image](https://user-images.githubusercontent.com/76530973/191789452-60342131-689e-4f2f-a86d-1a4376486ea6.png)

[matplotlib.lines](https://matplotlib.org/2.0.1/api/lines_api.html)

## Matplotlib Marker Styles

* Marker style argument: marker='...'
* Marker size argumnet: s='...'
* Marker edge Width argument: mew='...'

![image](https://user-images.githubusercontent.com/76530973/191790700-569a9d02-f2ba-48a2-a671-e66e9bcabb75.png)

[matplotlib.markers](https://matplotlib.org/stable/api/markers_api.html)

# Labels and Annotations Overview

* Labeling plot features
* Adding a legend to your plot
* Annotating your plot

## Labeling  Plot Features Overview

* Functional method
* Object-oriented method

## Adding a Legend

Placing a legend on plot axes: .legend(label, loc)

* label = A string, list of strings, or anything printable with '%s' conversion; to be used as variable or category labels
* loc = int, string, or pair of floats, default: 'upper right'; the location of the legend

![image](https://user-images.githubusercontent.com/76530973/191797569-197f9c17-c520-46dd-b0f9-0f5b81dc7621.png)

## Annotating YOur Plot 

**.annotate(xy, xytext, arrowprop)**

To annotate some features of the plot:

* xy = The location being annotated
* xytext = The location of the text
* arrowprop = Draws an arrow from the text to the annotated point by giving a dictionary of arrow properties

# Visualizing time series

## Time Series

A time series is a measure of unit change over time for any variable under observation.

The built-in Python datatime module supplies classes for manipulating dates and times in both simple and complex ways. 

Source: [Python Documentation](https://docs.python.org/3/library/time.html)

## Spotting Trend and Seasonality

![image](https://user-images.githubusercontent.com/76530973/191805225-e278d2d2-3a8d-462f-a17f-1f4128e12dba.png)

# Creating Statistical Data Graphics

* Identify outliers
* Visualize distributions
* Deduce variable types
* Discover relationships and core relations between variables in a dataset

## Histograms 

* A histogram shows a variable's distribution as a set of adjacent rectangles on a data chart. Histograms represent counts of data within a numerical range of values. 

## Scatterplots

* Scatterplots are useful when you want to explore interrelations or dependencies between two different variables. These data graphics are ideal for visually spotting outliers and trends in data. 

## Scatterplot Matrices 

* Scatterplot matrices use a matrix of scatterplots to visually display correlations between two or more variables. 

## Boxplots 

* Boxplots are useful for seeing a variables's spread and for detecting outliers. 



