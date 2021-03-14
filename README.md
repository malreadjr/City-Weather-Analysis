# City-Weather-Analysis
Multiple cities were analyzed in this dataset and used to compare different weather aspects.  Temperature, Humidity, Cloudiness, and Wind Speed were the four relational data points.

Background
Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![image](https://user-images.githubusercontent.com/69222103/111078686-1dea7980-84cd-11eb-8cee-91e0e8705a07.png)

Before You Begin


Create a new repository for this project called Web-Design-Challenge. Do not add this homework to an existing repository.


Clone the new repository to your computer.


Inside your local git repository, create a directory for the web challenge. Use a folder name to correspond to the challenge: WebVisualizations.


Add your html files to this folder as well as your assets, Resources and visualizations folders.


Push the above changes to GitHub or GitLab.


Deploy to GitHub pages.



Latitude - Latitude Analysis Dashboard with Attitude
For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting weather data.
In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

Website Requirements
For reference, see the "Screenshots" section below.
The website must consist of 7 pages total, including:

A landing page containing:

An explanation of the project.
Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.


Four visualization pages, each with:

A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.


A "Comparisons" page that:

Contains all of the visualizations on the same page so we can easily visually compare them.
Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.




A "Data" page that:

Displays a responsive table containing the data used in the visualizations.

The table must be a bootstrap table component. Hint

The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here






The website must, at the top of every page, have a navigation menu that:

Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change

![image](https://user-images.githubusercontent.com/69222103/111078719-4e321800-84cd-11eb-89d1-073e11e81389.png)
