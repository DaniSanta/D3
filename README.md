# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)


The data set included with the analysis is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml). The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Core Assignment: D3 Dabbler (Required Assignment)

![4-scatter](Images/4-scatter.jpg)

I created a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques, I created a scatter plot that represents each state with circle elements. I coded this graphic in the `app.js` file directory— I pulled the data from `data.csv` by using the `d3.csv` function. My scatter plot ultimately appear like the image at the top of this section.

* Included state abbreviations in the circles.

* Created and situated axes and labels to the left and bottom of the chart.

* Note: I used `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in my web browser.

- - -

### Bonus: Impress the Boss 

Why make a static graphic when D3 lets you interact with your data?

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

I included more demographics and more risk factors. Placed additional labels in my scatter plot and give them click events so that my users can decide which data to display. Animated the transitions for my circles' locations as well as the range of my axes. Did this for two risk factors for each axis. Or, for an extreme challenge, created three for each axis.

* Hint:I binded all of the CSV data to your circles. This allowed me to easily determine their x or y values when you click the labels.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Added tooltips to my circles and displayed each tooltip with the data that the user has selected. Used the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)— I have already included this plugin in my analysis directory.

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how I implemented tooltips with d3-tip.

- - -
