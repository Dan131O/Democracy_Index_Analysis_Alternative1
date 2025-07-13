# Democracy Index Analysis – Alternative 1

**A data-driven exploration of global Democracy Index trends and their correlations with key socio-economic indicators, implemented entirely in Python and Jupyter.**

This is the **first alternative** of the Democracy Index project. For the second version that integrates **Python, SQL, and Tableau**, see:  
📎 [Alternative 2 – Python + SQL + Tableau version](https://github.com/Dan131O/Democracy_Index_Analysis_Alternative2)

---

## How to View This Project

You can explore the project results at three levels of detail:

1. **Full notebook (source code, visualizations, written analysis):**

   - Open `main_notebook.ipynb`  


2. **Summary Report (visualizations, written analysis):**

   - Open `Project_Report.pdf`  


3. **Visualizations only:**

   - Browse the `Output_Visualizations/` folder  


---

## Project Overview

This project evaluates the relationship between the **Economist’s Democracy Index** and several key indicators:

- **Press Freedom Score**
- **Life Expectancy**
- **Education Spending (% of GDP)**
- **Population**

The main goal is to test the hypothesis:

> *Countries with higher democracy scores exhibit better press freedom, longer life expectancy, and higher educational investments.*

---

## Core Analytical Steps in `main_notebook.ipynb`

1. Libraries imported:  
`pandas`  
`numpy`  
`seaborn`  
`matplotlib`  
`scipy`  
`scikit-learn`  
`jupyter`  
2. Load & clean datasets (Democracy Index, Press Freedom, Life Expectancy, etc.)
3. Exploratory Data Analysis:
   - Plot democracy vs. each indicator
   - Visual examination of correlations
4. Quantitative analysis:
   - Pearson correlation coefficients
   - Linear regression models
   - Metrics: R² score, regression coefficients for each indicator
5. Results exported as plots in `Output_Visualizations/`
6. Findings summarized in `Project_Report.pdf`

---

## Example Insights

- **Democracy vs. Press Freedom:** Positive correlation with Pearson *r* ≈ 0.8
- **Democracy vs. Life Expectancy:** Moderate correlation with *r* ≈ 0.6
- **Democracy vs. Education Spending:** Weaker correlation, *r* ≈ 0.4
- Regression summary table included in PDF report

---

## Tested Environment

- **Last updated:** Jul 12, 2025
- **Tested with Python versions:** 3.10 – 3.13
- **OS compatibility:** Developed and tested on Windows; should work on Unix/macOS systems as well

---

## Repository Structure

```
.
├── main_notebook.ipynb                # Main analysis: code, report text, graphs (full version)
├── Project_Report.pdf                 # Executive summary & key findings (light version)
├── Output_Visualizations/             # Automatically generated plots from the notebook ("visualization only" overview)
├── Input_Datasets/                    # Raw CSVs needed for the analysis:
│   ├── Democracy_Index_2006_2023.csv
│   ├── Population.csv
│   ├── Press_Freedom.csv
│   ├── Life_expectancy.csv
│   └── Education.csv
├── requirements.txt                   # Required packages (pandas, seaborn, sklearn, scipy, jupyter, etc.)
└── README.md                          # You are here
```

---

## How to Reproduce

### **A) Recommended: Command-Line Method**

1. **Clone the repository**

   ```bash
   git clone https://github.com/Dan131O/Democracy_Index_Analysis_Alternative1.git
   cd Democracy_Index_Analysis_Alternative1
   ```

2. **Create and activate a virtual environment**\
   *(You can name the environment folder as you wish; here we use **`venv`** as an example)*

   ```bash
   python -m venv venv
   # Windows:
   .\venv\Scripts\activate
   # Linux/macOS:
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   python -m pip install -r requirements.txt
   ```

4. **Run the analysis notebook**

   ```bash
   jupyter notebook main_notebook.ipynb
   ```


### **B) Alternative: Run in Visual Studio Code (VS Code)**

1. **Open the project folder in VS Code**
2. **Open the integrated terminal** (\`Ctrl + \`\`)
3. **Create and activate a virtual environment** as above, if not already done
4. **Install dependencies** as above, if not already done
5. **Open **``** directly in VS Code**\
   • The [Jupyter extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) lets you view and run cells interactively.
6. **Select the correct Python interpreter** (the venv you just created) from the kernel picker at the top right of the notebook.


**You can also run the notebook in Jupyter Lab, Google Colab, or any compatible environment as desired.**

---

## Data Sources

Full dataset references (including links and notes) are included in:

- The Jupyter notebook: `main_notebook.ipynb`
- The written report: `Project_Report.pdf`

---

## Contact

Questions, feedback or collaboration ideas are welcome via email (daniel.ourinson@web.de) or [*LinkedIn*](https://www.linkedin.com/in/daniel-ourinson-phd-200755143/).\
Feel free to reach out directly if you'd like to discuss the project or suggest improvements.

---

*This repository is part of my personal portfolio. For more projects, please visit* [*Dan131O/portfolio*](https://github.com/Dan131O/portfolio)*.*

