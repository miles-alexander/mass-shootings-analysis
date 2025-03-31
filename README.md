# Mass Shootings in the United States: A Data-Driven Investigation  


## Overview

This project explores mass shootings in the United States through a data science lens, aiming to uncover patterns and trends that may inform future prevention efforts and policy decisions. The analysis focuses on variables such as weapon type, location, gender, race, and signs of mental illness in an attempt to identify consistent patterns among perpetrators.

**This project is not intended to provide definitive solutions but rather to initiate data-driven conversations around prevention, safety, and mental health.**

---
## Authors

- [@miles-alexander](https://www.github.com/miles-alexander)

## Research Questions

    1. What types of weapons are most commonly used?
    2. Do the attackers have prior criminal histories?
    3. Which gender is most commonly involved?
    4. Where do most mass shootings occur?
    5. Does race play a role in the data?
    6. Is there a correlation between mass shootings and mental illness?

---

## Approach

- **Data Cleaning:** Handled missing values using `na.omit()` and normalized inconsistent formats (e.g., dates).
- **Exploratory Data Analysis (EDA):** Used R packages to create tables and visualizations highlighting variable trends.
- **Visualization Tools:** `ggplot2`, bar plots, histograms, maps, and correlation charts.
- **Statistical Analysis:** Grouped, filtered, and summarized data using functions from `dplyr` and other R libraries.

---

## Data Sources

    1. [US Mass Shootings (Kaggle)](https://www.kaggle.com/datasets/zusmani/us-mass-shootings-last-50-years)
    2. [Stanford Mass Shootings Dataset](https://www.kaggle.com/datasets/carlosparadis/stanford-msa)
    3. [Mental Health and Suicide Rates](https://www.kaggle.com/datasets/twinkle0705/mental-health-and-suicide-rates)

---

## Tools & Libraries

- `R`
- `dplyr`
- `ggplot2`
- `tidyr`
- `lattice`
- `reshape2`
- `ggthemes`
- `knitr`

---
## Run Locally

To run this project on your own machine:

- **Clone the Repository**:
   ```bash
   git clone https://github.com/miles-alexander/mass-shootings-analysis.git
   ```

- **Go to the Project Directory:**
    ```bash
    cd mass-shootings-analysis
    ```

- **Open the R project or R script in RStudio.**

- **Install the required packages:**
   ```R
   install.packages(c("dplyr", "ggplot2", "tidyr", "lattice", "reshape2", "ggthemes", "knitr"))
   ```

- **Run `.Rmd` file**:
   - Click `Knit` in RStudio to generate the HTML report.

## Key Findings

- **Weapon Type:** Semiautomatic handguns and rifles are frequently used, though inconsistencies in weapon descriptions posed analysis challenges.
- **Gender:** The vast majority of attackers were male, with only a small number of female or mixed-gender offenders.
- **Location:** Schools and workplaces are the most frequent locations for mass shootings, outside of generic “other” categories.
- **Race:** White individuals were involved in the highest number of incidents.
- **Mental Health:** Most attackers showed prior signs of mental health issues, although some records were incomplete or unclear.

---

## Limitations

- **Inconsistent Labeling:** Many data entries (e.g., weapon types) lacked standard formatting.
- **Missing Data:** No conclusive information on prior criminal history or full mental health diagnoses in many cases.
- **Ethical Boundaries:** The analysis avoids making deterministic assumptions but focuses on identifying patterns.

---

## Conclusion

This project serves as an early step in using data science to understand the complex and tragic issue of mass shootings. While not comprehensive, the findings point to patterns worth deeper investigation and provide a potential foundation for future research, prevention strategies, and mental health advocacy.

---

## Future Work

- Apply natural language processing (NLP) to attacker summaries or news articles.
- Incorporate machine learning for predictive modeling or anomaly detection.
- Expand visualizations to interactive dashboards for policy advocacy and awareness campaigns.


