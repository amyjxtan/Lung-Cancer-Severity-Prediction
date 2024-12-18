# Lung Cancer Severity Analysis
Amy Tan, Elizabeth Lee, Sandy Li, Jinyu Li

## Project Overview
This project focuses on analyzing factors influencing the severity of lung cancer using statistical and computational methods. The study aims to identify key predictors of severity and evaluate their impact through data-driven analysis, offering insights for improved understanding and management of lung cancer.

## Installation and Setup

### Codes and Resources Used
- **Editor Used:** RStudio
- **R Version:** R 4.x.x
- **R Packages Used:**
  - **Data Manipulation:** `dplyr`, `tidyr`
  - **Data Visualization:** `ggplot2`, `plotly`
  - **Statistical Analysis:** `survival`, `lme4`
  - **Others:** `knitr`, `rmarkdown`

### Prerequisites
- Install R and RStudio from [CRAN](https://cran.r-project.org/) or a similar repository.
- Install required packages by running the following in your R console:
  ```R
  install.packages(c("dplyr", "tidyr", "ggplot2", "plotly", "survival", "lme4", "knitr", "rmarkdown"))
  ```

### Running the Code
- Open the `.Rmd` file in RStudio.
- Execute the code chunks sequentially to reproduce the analysis and visualize results.

## Data
The dataset used in this project includes clinical and demographic information related to lung cancer patients. It contains details such as:
- Patient age, gender, and smoking history.
- Tumor characteristics and staging.
- Treatment history and outcomes.

Data preprocessing steps are included in the `.Rmd` file, ensuring readiness for analysis.

## Results and Evaluation
The analysis uncovers critical factors associated with the severity of lung cancer, including:
- Significant clinical predictors.
- Statistical models evaluating their contribution.
- Visualizations highlighting trends and relationships.

## Future Work
- Incorporate additional datasets to validate findings across broader populations.
- Apply machine learning techniques to improve predictive accuracy.
- Explore temporal patterns in severity using longitudinal data.

## References
- [Reference 1]: Cite relevant academic studies or articles.
- [Reference 2]: Include code inspirations or data sources.

## License
MIT License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
