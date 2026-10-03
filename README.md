# mtcars Shiny Dashboard

A simple R Shiny web application built to analyze the standard `mtcars` dataset. I created this dashboard to practice building interactive R apps, handling user inputs, and deploying Shiny projects online.

## Live Demo

You can try the live app hosted on shinyapps.io here:  
https://70b283-mostafa-ezzeldin.shinyapps.io/mtcars_project/

## What the Dashboard Does

The app divides the exploratory data analysis into three main sections:

1. **Numerical Variables**: Generates histograms and boxplots for continuous variables (like `mpg`, `hp`, `wt`). Includes options to adjust histogram bin counts and switch color fills.
2. **Categorical Variables**: Shows simple bar charts for discrete metrics such as number of cylinders (`cyl`), transmission type (`am`), and gear count (`gear`).
3. **Correlation Plots**: Displays scatter plots showing relationships between continuous variables and vehicle weight (`wt`), grouped by categorical variables.

## Tech Stack & Packages

- **R** & **Shiny** for the backend and dashboard interface.
- **ggplot2** and **tidyverse** for plotting and data formatting.
- **rsconnect** for publishing to shinyapps.io.

## Running the App Locally

If you want to run this project on your machine:

1. Clone the repo:
   ```bash
   git clone [https://github.com/Mostafaezzeldin2025/mtcars-shiny-dashboard.git](https://github.com/Mostafaezzeldin2025/mtcars-shiny-dashboard.git) 

Open ui.R or server.R in RStudio.
Make sure the required packages are installed:
install.packages(c("shiny", "tidyverse", "ggplot2", "rlang"))
Click Run App in RStudio.
