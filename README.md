## Weather Analysis Dashboard (https://jorgearv.github.io/HTML_CSS_Weather_Data_Dashboard/)

I have created a visualization dashboard website that contrasts weather data accross various latitudes and longitudes.

In building this dashboard, I have created individual pages for each plot and a means by which the user can navigate between them. These pages contain the visualizations and their corresponding explanations. I have also included a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.

* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  
* A comparisons page that:
  * Contains all of the visualizations on the same page so the user can easily visually compare them.

* A data page that:

  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting the `.csv` file in Resources as HTML. To achieve this, I have used the `to_html` method in Pandas that allowed me to generate a HTML table from a pandas dataframe.

The website has, at the top of every page, a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.


The website has been deployed to GitHub pages (https://jorgearv.github.io/HTML_CSS_Weather_Data_Dashboard/)

---------

Contact information: jorge.arriola.villafuerte@gmail.com
