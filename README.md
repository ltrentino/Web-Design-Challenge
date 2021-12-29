# UWA DATA ANALYSIS COURSE
# Web Design Homework - Web Visualisation Dashboard

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![Images/landingResize.png](Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualisation dashboard website using visualisations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualisations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

The website must consist of 7 pages total, including:

* A [landing page](#index.html) containing:
  * An explanation of the project.
  * Links to each visualisations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualisation.
* Four [visualisation pages](#WebVisualisations\vis01.html), each with:
  * A descriptive title and heading tag.
  * The plot/visualisation itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#WebVisualisations\comparison.html) that:
  * Contains all of the visualisations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualisations.
    * The grid must be two visualisations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#WebVisualisations\table.html) that:
  * Displays a responsive table containing the data used in the visualisations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method appropriately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)


### Copyright

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
