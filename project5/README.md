#GGPLOT2 GEOM

This project illustrates **how to create a new ggplot2 geom in R** that allows to visualize hurricane wind fields using the data from [The Tropical Cyclone Extended Best Track Dataset](http://rammb.cira.colostate.edu/research/tropical_cyclones/tc_extended_best_track_dataset/).  The motivation of this undertaking was to solve the peer-graded assignment of the [Building Data Visualization Tools](https://www.coursera.org/learn/r-data-visualization) course.

The purpose of this assignment is to draw on your knowledge of the grid and ggplot2 package to build a new geom. You will then need to load and tidy the provided dataset in order to plot the geom on a map.

Organization of the Files
The project has the following structure:

R scripts: Includes files in 2 directories:
[geom_hurricane.R](https://github.com/DYZI/Hurricane/blob/master/R/geom_hurricane.R) in R directory:It is the submitted code for the peer-graded assignment of the Coursera's course which creates two graphs of the Hurricane Ike
[roxygen2-style documentation](https://github.com/DYZI/Hurricane/tree/master/man) in MAN directory:
on how to integrate the new geom into a new R package.

[GRAPHS](https://github.com/DYZI/Hurricane/blob/master/graphs.png) Contains the plots created by geom_hurricane.R code in order to demonstrate how the new geom works

[DATA](https://github.com/DYZI/Hurricane/tree/master/data) contains clean and non clean datsets for the assignment

OTHER USEFUL RESOURCES: Includes all the resources notes that I considered relevant for this task

Review criterialess 
To submit this assignment you must submit

An R script containing the code implementing the geom

A plot file (in PNG or PDF format) containing a map that has the wind radii overlayed for Hurricane Ike

This assessment will ask reviewers the following questions:


1) Is a map included that shows the wind radii for a single observation time for Hurricane Ike?

2) Does the map show the correct hurricane?

3) Does the geom correctly map locations for the wind radii based on the center point, radii, and direction?

4) Is the proper notation used for calling functions in other packages?

5) Is there roxygen2-style documentation included in the R script?

6) Are all the parameters of the geom documented and described?

7) Does the geom include a scale_radii parameter that functions as described?
