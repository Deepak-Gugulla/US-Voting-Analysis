# Republican Voting Percentages Analysis 

**Authors:**  
- Deepak Gugulla  
-gugulladeepak@gmail.com
---

## 📖 Project Overview

This project analyzes Republican voting percentages by state across US presidential elections from **1856 to 1976**.  
We explored regional differences, trends over time, and identified key patterns of political alignment and realignment.

The analysis uses the historical `votes.repub` dataset and interactive visualization libraries in R to produce insightful maps, charts, and trends.

---

## 🛠 Tools & Libraries

Developed in **RStudio** with:
- `tidyverse`
- `cluster`
- `ggplot2`
- `plotly`
- `lubridate`
- `leaflet`
- `sf`
- `statebins`
- `viridis`
- `tibble`

---

## 📂 Repository Structure

- `us-voting-analysis.Rproj` – RStudio project file  
- `project.qmd` – Quarto source document with all analysis and visualizations  
- `project.html` – Rendered report for easy viewing in any web browser  
- `.gitignore` – Ignore unnecessary files (`.Rhistory`, `.Rproj.user/`, etc.)  
- `README.md` – Project documentation (this file)

---

## 🔗 Rendered Report

👉 **[Click here to view the report](./project.html)** (open locally in browser)  
(Optional: publish via GitHub Pages for an online view)

---

## 🔬 Key Insights

- **Regional trends:** Western states leaned more Republican than Eastern states during this period  
- **Political realignment:** The Southern states were undergoing a transition from Democrat to Republican dominance in the 1970s  
- **Top Republican states:** Maine, Kansas, South Dakota, Vermont, Nebraska (above 50% average vote share)  
- **Lowest Republican support:** Georgia, South Carolina, Louisiana, Texas (below 35% average vote share)  
- **Historical voting trends:** Mean and median Republican percentages varied sharply across decades with recoveries post-1920 and post-1940

---

## 📄 Dataset Reference

The `votes.repub` dataset was sourced from the R `cluster` package:

> Peterson, S. (1973). *A Statistical History of the American Presidential Elections*. New York: Frederick Ungar Publishing Co.

Additional data from 1964–1976 was sourced from:

> R. M. Scammon, *American Votes 12*, Congressional Quarterly.

---

## 📝 License

This project is released under the **MIT License** — free to use and modify with attribution.

---

## 👥 Questions?

Feel free to open an issue or contact any of the project authors.
