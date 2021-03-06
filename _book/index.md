--- 
title:    "Data Science Boot Camp"
subtitle: "Weldon Cooper Center for Public Service, University of Virginia"
author:   "Arthur Small, Principal Scientist"
date:     "June 8-10, 2021"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "Course materials for the Data Science Boot Camp, Weldon Cooper Center for Public Service, University of Virginia June 8-10, 2021"
---

# Overview

This boot camp is designed to help research assistants rapidly to become productive doing data science as a member of the Cooper Center team. The mini-course offers introductory training in how to do data science as a member of a team. It also provides an orientation to the projects, resources, and house styles that are specific to the Cooper Center.


## Core texts and resources

R4DS: [R for Data Science](https://r4ds.had.co.nz/) by Hadley Wickham and Garrett Grolemund. An excellent introduction, available for free online.

DSBC: [Data Science Boot Camp](https://bookdown.org/arthursmalliii/boot-camp/) by Arthur Small. These notes.

[DataCamp](https://www.datacamp.com/groups/shared_links/204e9d252e533227deb1caf2ce99e30b6df1f98c45a978824364bda2a6bc00ef). Online interactive courseware for data science, including many modules on R.



## Schedule of topics


| **June 8:** *Welcome; orientation to data science at the Cooper Center; doing data science as part of a team; concepts of* **reproducible research** *and* **literate programming**; *working in R Studio; importing data; tidy data*


| Time         | Topic                         |  Resources       | Example code    | 
|:------------:|:-----------------------------:|:---------------- |:----------------------|
|  9:00--9:45  | Welcome                       | [Cooper](https://coopercenter.org/) [Center](https://ceps.coopercenter.org/) [websites](https://energytransition.coopercenter.org/)
|  9:45--10:30 | Data science at CCPS  | [DSBC Ch. 2](https://bookdown.org/arthursmalliii/boot-camp/intro.html)
| 10:30--11:00 | -- *break* --     
| 11:00--12:00 | A simple session in R Studio | [R4DS Ch. 1, 2, 4, 6, 8](https://r4ds.had.co.nz/introduction.html) | [cte-trailblazers.Rmd](https://github.com/coopercenter/cte-trailblazers/blob/main/cte-trailblazers.Rmd) |
| 12:00--1:00  | -- *lunch break* --    
|  1:00--1:45  |  Importing data from flat files 
|  1:45--2:30  |  Data types in R    | 
|  2:30--3:00  |  -- *break* --     | 
|  3:00--4:00  |  Data wrangling I; tidy data     | 


**June 9:** *Wrangling data with dplyr; visualizing data with ggplot2; importing data from databases, APIs; working with databases; good data management practices*


| Time         | Topic                         |  Resources       | Example code    | 
|:------------:|:-----------------------------:|:---------------- |:----------------------|
|  9:00--10:15 | Visualizing data with ggplot2      | 
| 10:15--10:45 | -- *break* --     
| 10:45--12:00 |  Wrangling data with dplyr, Datatable   | 
| 12:00--1:00  | -- *lunch break* --    
|  1:00--2:30  | Databases: overview; read/write; connections; credentials    | 
|  2:30--3:00  |  -- *break* --     | 
|  3:00--3:30  |  Data management: good practices       | 
|  3:30--4:00  |  Importing data from APIs, web resources    | 


**June 10:** *Version control and file management with git and Github; working with larger files; using R Markdown to create documents and publications; creating dashboards with Shiny; cloud hosting*

 
| Time         | Topic                         |  Resources       | Example code    | 
|:------------:|:-----------------------------:|:---------------- |:----------------------|
|  9:00--10:00  | Version control with git and Github    |  
| 10:00--10:30 |  Creating dashboards with Shiny           | 
| 10:30--11:00 | -- *break* --     
| 11:00--12:00 | Cloud hosting        | 
| 12:00--1:00  | -- *lunch break* --    
|  1:00--2:00  | File management: good practices            |
|  2:00--2:30  | Using R Markdown to create documents and publications    | 
|  2:30--3:00  |  -- *break* --     | 
|  3:00--3:30  |  Working with larger files      | 
|  3:30--4:00  |  Wrap up      | 




## Credits

These course materials were generated using the **bookdown** package [@R-bookdown], which was built on top of R Markdown and **knitr** [@xie2015].
