# Bayesian SEM Analysis Project

This project demonstrates how to perform Bayesian Structural Equation Modeling (SEM) using R. Bayesian SEM is a flexible approach that incorporates prior knowledge and allows for uncertainty quantification in structural models. The project includes a fabricated dataset and a step-by-step R Markdown file to guide the analysis.

---

## Files Included

1. **`bayesian_sem_data.csv`**  
   - A fabricated dataset with 200 samples and 9 observed indicators across three latent variables.

2. **`bayesian_sem_analysis.Rmd`**  
   - An R Markdown file that demonstrates:
     - Loading and exploring the dataset.
     - Defining the Bayesian SEM model.
     - Fitting the model using the `blavaan` package.
     - Checking model diagnostics and interpreting the results.

---

## Steps to Run the Analysis

1. **Download the Files**:  
   Clone this repository or manually download the files.

2. **Install Required R Packages**:  
   Install the following R libraries:
   ```R
   install.packages(c("tidyverse", "blavaan"))
   ```

3. **Open and Run the R Markdown File**:  
   Open `bayesian_sem_analysis.Rmd` in RStudio and knit it to an HTML file. Follow the steps in the document to perform Bayesian SEM.

---

## Key Features of Bayesian SEM

- **Latent Variable Modeling**: Estimate relationships between latent variables and their observed indicators.
- **Structural Relationships**: Model regression paths between latent variables.
- **Bayesian Approach**: Incorporate prior information and evaluate uncertainty with posterior distributions.

---

## Applications

Bayesian SEM is particularly useful in Human Factors (HF) and User Experience (UX) research for:
- Modeling complex relationships between variables.
- Quantifying uncertainty in parameter estimates.
- Incorporating prior knowledge to improve model fit.

---

## Contribution

Feel free to explore, modify, and share these resources. If you have suggestions or improvements, open an issue or submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, adapt, and share it with proper attribution.
