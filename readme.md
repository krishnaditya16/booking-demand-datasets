### Quantitative Methodology Assignment 2

---

## Overview
This project contains the code and analysis for **Task 1** and **Task 2** of the Quantitative Methodology (QM) Assignment. The primary objective is to analyze datasets related to the hospitality industry and derive meaningful insights regarding statistical correlations and regression analyses.

---

## Author
**I Gusti Ngurah Agung Krishna Aditya**  
Management & Science University (MSU)

---

## Tasks and Datasets

### **Task 1**
**Objective:** Analyze the relationship between price and variables such as offers and room scarcity.  
**Dataset:** [OSF Dataset](https://osf.io/r6uqb/)

### **Task 2**
**Objective:** Investigate the correlation between lead time and previous cancellations.  
**Dataset:** [Data in Brief Dataset](https://www.data-in-brief.com/article/S2352-3409(18)31519-1/fulltext)

---

## Methodology
1. **Data Cleaning and Preprocessing:** Ensured the datasets were prepared for analysis, including handling missing values and standardizing variables.  
2. **Statistical Analyses:** 
   - Performed correlation analysis to measure the strength and direction of relationships between variables.
   - Conducted regression analysis to evaluate predictive relationships.  
3. **Interpretation of Results:** Emphasis on distinguishing statistical significance from practical relevance.

---

## Key Findings

### **Task 1**
- Variables such as **offers** and **room scarcity** showed **very weak correlations** with price.  
- Despite statistically significant p-values, the correlations were close to zero, indicating minimal practical relevance.  
- This underscores that statistically significant results do not always imply meaningful insights or causation.

### **Task 2**
- Analyzed the relationship between **lead time** and **previous cancellations**:
  - Found a **very weak correlation** with a negligible regression slope.  
  - The low R² value suggested that **lead time** is a poor predictor of cancellations.
  - Highlighted the importance of considering additional variables for more robust predictive models.

---

## Conclusion
The analyses revealed that:
- Weak correlations, even when statistically significant, often lack practical relevance.  
- Statistical outputs should be interpreted in context to avoid conflating correlation with causation.  
- Effective models require the inclusion of multiple relevant variables to enhance predictive power and decision-making in real-world applications.

---

## Requirements
The project uses the following Python libraries:
- pandas
- seaborn
- matplotlib
- scipy
- statsmodels

A `requirements.txt` file has been provided to simplify the setup.

---

## How to Set Up and Run the Project
1. Clone the repository to your local machine.  
2. Set up a Python virtual environment (optional but recommended):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
5. Open the respective notebooks for Task 1 and Task 2:
   - **Task 1:** `model-task1.ipynb`
   - **Task 2:** `model-task2.ipynb`

6. Execute the cells sequentially to view the analysis and results.

---

## Acknowledgments
Gratitude to the dataset providers for their contributions to open data, enabling this analysis.  

For any questions or clarifications, feel free to reach out.  

**I Gusti Ngurah Agung Krishna Aditya**  
Management & Science University (MSU)  