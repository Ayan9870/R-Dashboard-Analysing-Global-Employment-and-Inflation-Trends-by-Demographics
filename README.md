# R Dashboard Analysing Global Employment and Inflation Trends by Demographics

---

### Project Preview

An interactive R Shiny dashboard to analyze and visualize inflation and unemployment trends in Australia in comparison to global data. The dashboard enables users to explore unemployment rates across countries and demographics with dynamic filtering by gender, age group, and region. It also presents inflation trends using a combination of line plots and bar charts, offering both global comparisons and a detailed breakdown of Australian goods and services categories. With an intuitive layout and responsive controls, the tool supports insightful economic analysis for both academic and practical use cases.

---

## Access to Code 🔒

The source code for this project is **private** and available upon request. 

If you're an **employer** or **recruiter** and would like to review the code, please **request access via email** at **ayanhashmi205@yahoo.com**.

---

## Installation 📦

#### Prerequisites
Ensure you have R and RStudio installed on your system.

#### Clone this repo

```bash
git clone https://github.com/ayanhashmi/r-dashboard-analysing-global-employment-and-inflation-trends-by-demographics.git
```

#### Install required R packages

```r
install.packages(c("shiny", "tidyr", "plotly", "shinyalert", 
                   "shinyBS", "shinydashboard", "dplyr"))
```

#### Run the application

```r
# In RStudio or R console
shiny::runApp("app.R")
```

Navigate to the local server address displayed in your R console (typically `http://127.0.0.1:XXXX`)

Or Visit: https://ayan99.shinyapps.io/assignment3_s4020459/

---

## Features 📋

* **Interactive Employment Analysis** - Compare unemployment rates across countries with demographic filtering
* **Global Inflation Trends** - Multi-country inflation rate comparison over time
* **Australian Economic Focus** - Detailed analysis of Australian goods & services inflation
* **Educational Qualification Insights** - Bachelor's degree completion rates by gender and age
* **Dynamic Data Visualization** - Interactive plotly charts with hover details and filtering
* **Responsive Dashboard Design** - Clean, professional interface with tabbed navigation
* **Real-time Data Updates** - Reactive filtering and chart updates based on user selections
* **Comprehensive References** - Academic and data source citations

---

## Technology Stack 🔧

### Backend
* **R** - Statistical computing environment
* **Shiny** - Web application framework for R
* **dplyr** - Data manipulation and transformation
* **tidyr** - Data tidying and reshaping

### Frontend & Visualization
* **shinydashboard** - Dashboard framework with sidebar navigation
* **plotly** - Interactive plotting library
* **shinyalert** - User notification system
* **shinyBS** - Bootstrap components for enhanced UI

### Data Sources
* **Global Inflation Dataset** - Kaggle economic indicators
* **Global Unemployment Data** - International labor statistics
* **Australian Bureau of Statistics** - Official Australian economic data

---

## Dashboard Structure 📄

### Employment Tab
* **Country Selection** - Choose up to 5 countries for comparison
* **Demographic Filters** - Filter by sex and age group
* **Trend Visualization** - Line charts showing unemployment rates over time
* **Education Analysis** - Australian bachelor's qualification rates by demographics

### Inflation Tab
* **Global Comparison** - Multi-country inflation rate trends
* **Australian Focus** - Quarterly goods & services inflation breakdown
* **Interactive Controls** - Year slider and country selection
* **Contextual Information** - Economic insights and explanations

### References Tab
* **Academic Sources** - Course materials and documentation
* **Data Sources** - Official statistics and datasets
* **Technical References** - R package documentation and tutorials

---

## Interactive Features 🎯

### Data Filtering
* **Multi-country selection** with maximum limits for performance
* **Demographic filtering** by sex and age groups
* **Temporal filtering** with year sliders and range selection
* **Real-time updates** as filters change

### Visualization Controls
* **Hover details** showing exact values and context
* **Color-coded legends** for easy differentiation
* **Responsive scaling** based on data ranges
* **Export capabilities** for further analysis

---

## Author ✨

| <a href="https://github.com/ayan9870" target="_blank">**Muhammad Ayan Hashmi**</a> |
|:--:|
| ![Ayan Hashmi](https://github.com/ayan9870.png?size=100) |
| [`github.com/ayan9870`](https://github.com/ayan9870) |

---

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
