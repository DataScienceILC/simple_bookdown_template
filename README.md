# Simple Bookdown template

This repository contains a simple **template for creating course materials using the bookdown package**. In this file, the different parts of the template are explained. But first, we will explain how you can get started with this template. 

## How to use this template?
In order to use this template, you need to have **git** and **RStudio** installed on your computer (if you have no admin rights, you can install these programs on your Desktop). Then you can clone this repository (containing the template) to your computer. After cloning, you should copy the files of the template to a new folder on your computer. You can couple this new location to a GitHub repository. Finally, you can open the *simple_bookdown_template.Rproj* file using RStudio and start creating your own course materials using bookdown. 

## What are the files in this template?

### index.Rmd
The *index.Rmd* is the most important file of the template, as it contains some code that determines the appearance of the resulting website. When using this template to create course materials, we advice you to change the following elements of the index file:

* If you are planning to use the same URLs in multiple lessons of your course, you can create a file called *course_urls.RData* using the R code chunk in the index file. This RData file will then contain all the important URLs and can be loaded in every lesson Rmd file. 
* Change the header **'CURSUS TITEL'** to the title of your course. 
* Indicate the learning objectives of the course under the header **'Leerdoelen cursus'**. 

### les1.Rmd
In this file, you can include the content for the first lesson of the course. If you are planning to use the URLs in the course_urls.RData file, you can use them by including the R code chuncks as indicated in this template file.

### les2.Rmd
Similar as for *les1.Rmd*, but this file is intended for the content of lesson 2. 

### course_urls.RData
This file contains the URLs that are used in the course. The content in the file is defined using the R code chunck in the index file (see the section index.Rmd).

### Other files in this repository
The other files in this repository are standard files related to a git repository. These files include *.gitignore* (which indicates which files should be ignored by git when committing changes), *README.md* (the file you are currently reading) and *simple_bookdown_template.Rproj* (the file that is required to load the template files in RStudio).  


