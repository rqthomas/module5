![](www/project-eddie-banner-2020_green.png)<!-- -->
# Module 5: Introduction to Ecological Forecasting
## [Macrosystems EDDIE](https://serc.carleton.edu/eddie/macrosystems/index.html)
### Summary
Here is the code for running the Macrosystems EDDIE Module 5: _Introduction to Ecological Forecasting_. There is a detailed guide below for launching the R Shiny App locally on your own machine. For more details about teaching this module please visit our [website](http://module5.macrosystemseddie.org/).

##  Setting up the Shiny App
### Pre-requisites
1. Latest version of [R](https://cran.r-project.org/) installed (currently R 4.0.3 as of 2021-01-22).  
2. [RStudio](https://rstudio.com/products/rstudio/download/) installed (preferably >1.3).  

### Step 1: Download this repository
There are two options:  
1. Download the repository as a .zip file. (Easiest option).  
    a.  Click the green "Code" button on this page and select "Download ZIP".  
    b.  Unzip this file on your computer.  
2. Clone this repository into RStudio.  
		a.  Open RStudio.  
		b.  Click "File > New Project...".  
		c.  In the "Create Project dialog select "Version Control: Checkout a project from a version control repository".  
		d. Select "Git: Clone a project from a Git repository.  
		e. In the "Repository URL:" option input the URL to this repository, select where to save the project directory.  
		f. Click "Create Project".  
		g. You will then have a project with all the files from this repository.  
		
### Step 2: Install required R packages
1. The list of required of packages is detailed in the `install.R` script in this repository. Open and run this script to install the necessary packages.  
  Watch out for errors in package installation. Most can be avoided using the most up-to-date version of R (4.0.3 as of 2021-01-22).  
  Updating of current R packages on your system is recommended.

### Step 3: Launch Shiny App
1. Open the script `app.R` in your console.  It is found in the `app` directory
2. Click the "Run App" button in the Script (indicated below).  
3. This will launch the Shiny App in your default web browser or in a new RStudio window. The Shiny App is run from RStudio so you will need to keep RStudio running in the background.  
![](www/launch_app.png)<!-- -->	

## Quickstart option 1

Here is an alternative way to quickly launch the Shiny app in less than a minute, but can be prone to package installation errors if your packages have not been updated recently.
```
# Step 1. Install required R packages
source("https://raw.githubusercontent.com/MacrosystemsEDDIE/module5/main/install.R")

# Step 2. Launch Shiny app
shiny::runGitHub("module5", "MacrosystemsEDDIE", ref = "main", subdir = "app")
```

## Quickstart option 2

You can click on the link below to launch the Shiny app.  It may take a while to launch because it is being created on a remote server (i.e., not on your computer). This option prevents issues with installing R and packages. It only requires an internet browser and a connection to the internet.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rqthomas/module5/main?urlpath=shiny/app/)


## Questions & Feedback
If you have any questions, comments or feedback related to these materials you can send an email to [macrosystemseddie@gmail.com]().
 
