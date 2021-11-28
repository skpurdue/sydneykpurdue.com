---
date: "2017-06-01T00:00:00Z"
links:
- icon: link
  icon_pack: fas
  name: Launch Illinois Yield Trials Shiny App
  url: https://skpurdue.shinyapps.io/illinois_yield_trials/
image:
  caption: 
  focal_point: Smart
summary: .
tags:
- Data
title: Illinois Yield Trials
---

Over the summer of 2015, Anna Blinderman and I worked on the Illinois Yield Trials project at the Center for Robust Decision-Making on Climate and Energy Policy (RDCEP). We intended to explore and explain the notable increase in the yield of corn in Illinois, sourced from old agricultural journals covering the results and yield from different hybridizations of corn for regions across Illinois. Much of the data needed to be hand-entered at the time, due to the unique formatting of the journals making OCR difficult. Affectionately dubbing this the "corn project", we began introductory data analysis and visualization. We were given complete freedom over the tool we wanted to use, and we settled on R as the best for our purposes because we were intending to have a linear modeling portion of our project.

We got started with a handful of lines of code help from a coworker, teaching us the very basics of reading in a csv, and from there, we spent the summer digging into R and copious amounts of corn data. By coming through extensive amounts of documentation, I worked extensively with ggplot2, making visualizations of every aspect of our data to try to get a better handle on it. We pulled weather data from NOAA archives, and used that to explore outlier years and the possible impact of temperatures and rainfall on the hybrids' performances. Through the head of RDCEP, we got in contact with the agriculture librarians at the University of Illinois Urbana-Champaign (which originally spearheaded these trials and hosts one in their area), to fill in missing years of data. 

I was able to work on the corn project intermittently over the school year, and the following summer, I took over the project completely. In exploring the best way present our findings, I discovered Shiny and set out to make an interactive visualizer. It includes three different graphing types with your choice in variables, and allows you to adjust ranges with sliders, exclude points and reset those excluded points, create subgroups, add trendlines, color the whole plot by a variable, freeze the axes, and download the plot you've created. What you can access here is the final version as of approximately June 2017.

In the future, I would love to revamp this with my greatly expanded knowledge of R and data visualization techniques, providing more guidance to the user, more explanation of the context of the data, and more ways to view the data (such as descriptive statistics summaries or tables) as well as some purely aesthetic tweaks (like the overall design and theme of the graphs) and debugging, of course. 