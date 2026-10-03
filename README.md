# 🏎️ Interactive mtcars Shiny Dashboard

An interactive R Shiny web application for exploratory data analysis (EDA) on the classic `mtcars` dataset. This dashboard allows users to dynamically analyze distributions, categorical frequencies, and variable correlations.

## 🚀 Live Demo
Experience the live interactive application hosted on shinyapps.io:  
👉 **[Interactive mtcars Dashboard](https://70b283-mostafa-ezzeldin.shinyapps.io/mtcars_project/)**

---

## 📊 Features & Functional Modules

### 1. Distribution of Numerical Variables
- **Histogram Viewer**: Select any continuous variable (e.g., `mpg`, `hp`, `wt`) with customizable bin counts and color themes.
- **Boxplot Visualization**: Examine data spread, medians, and potential outliers.

### 2. Distribution of Categorical Variables
- **Bar Charts**: Analyze categorical distributions for variables like cylinders (`cyl`), transmission type (`am`), and gears (`gear`).

### 3. Data Correlation Analysis
- **Scatter Plots**: Explore relationships between continuous metrics and vehicle weight (`wt`), color-coded by categorical dimensions.

---

## 🛠️ Built With

- **[R Language](https://www.r-project.org/)**: Core programming language.
- **[Shiny](https://shiny.posit.co/)**: Web application framework for R.
- **[ggplot2 & tidyverse](https://www.tidyverse.org/)**: Data transformation and visualization.
- **[rsconnect](https://cran.r-project.org/package=rsconnect)**: Deployment interface for shinyapps.io.

---

## 💻 How to Run Locally
Open ui.R or server.R in RStudio.

Install required libraries if needed:
install.packages(c("shiny", "tidyverse", "ggplot2", "rlang"))
Click Run App in the top right corner of the RStudio editor.

To run this application on your local machine using RStudio:

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/mtcars-shiny-dashboard.git](https://github.com/YOUR-USERNAME/mtcars-shiny-dashboard.git)
