## DS4200 Information Visualization Assignment 5

Assignment 5: Altair Basic Plots
For this assignment, 3 basic visualizations for information related to Netflix movies and TV shows was created using the Altair library for python on Jupyter Notebook.

### Submission 1: Simple Visulization

This is a simple viz created with Altair. It shows the number of Movies vs the
number of TV Shows on Netflix as of Jan 2020.

![simpleViz](/images/simpleViz.png)


### Submission 2: Histogram

This visualization shows that The distribution of movie lengths appears gaussian. We can see the signature bell-shaped curve for the histrogram dispite some outliers. I chose the histogram for this visualization because it is commonly used to demonstrate the distribution of data.

X axis is the duration of the movie, while the Y axis is the number of movies with that specific duration. Netflix's red is used for the bar for thematic purposes.

![viz1](/images/viz1.png)


### Submission 3: Line Chart

This visualization shows that the rate at which netflix adds titles to its platform stayed relativly flat from 2008 to 2013, saw significant increase from 2014 to 2017, and is graduly slowing down since.

The data was cleaned and the rate of increase was calculated from calculating the derivatives. Originally, I plotted the graph using the number of titles added at each year. This was alter changed because it did not generate a intuitive visulization, leading to increased processing time, and possible false conclusions. The data from 2020 was removed because the year has not passed in full. 

I chose a line chart for this visualization because it is commonly used to showcase trend. X axis is the year, while the Y axis is rate of increase of title adds. Netflix's red is again used for the line.

![viz2](/images/viz2.png)
