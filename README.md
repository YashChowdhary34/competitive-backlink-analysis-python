# Competitive Backlink Analysis with Python

## Overview
This project provides a Python-based solution to conduct competitive backlink analysis, which is critical for understanding the backlink profile of your domain and comparing it with competitors. By analyzing backlinks, you can gain valuable insights into SEO strategies, identify link-building opportunities, and improve your digital marketing efforts.

The project is implemented as a Jupyter Notebook, where you can:
- Import backlink data for multiple domains.
- Clean and preprocess the data for analysis.
- Assess the quality of backlinks using Domain Rating (DR).
- Analyze the growth and distribution of referring domains over time.
- Visualize key metrics to understand backlink trends and performance.

## Repository Structure
- **`Competitive-Backlink-Analysis-Python.ipynb`**: The main Jupyter Notebook containing the complete script for analysis.
- **Sample Data**:
  - `comp-1.csv`, `comp-2.csv`, `comp-3.csv`, `my-domain.csv`: Example CSV files representing backlink data for multiple domains. These are used to demonstrate the analysis workflow.

## Key Features
### 1. Data Import & Cleaning
- Automates the import of CSV files containing backlink data for different domains.
- Cleans the data to ensure consistency and accuracy in analysis.
- Supports preprocessing steps such as handling missing values and standardizing formats.

### 2. Link Quality Assessment
- Evaluates backlink quality using Domain Rating (DR), a metric that quantifies the authority of referring domains.
- Creates visualizations, such as box plots, to compare the DR distributions across different domains.

### 3. Link Volume Analysis
- Analyzes the volume of referring domains over time.
- Computes cumulative growth trends to identify the effectiveness of link-building campaigns.
- Generates line plots to visualize the trajectory of backlink acquisition.

### 4. Data Visualization
- Provides clear and insightful visualizations for:
  - Distribution of Domain Ratings.
  - Cumulative growth of referring domains.
- Helps stakeholders quickly interpret the results and make data-driven decisions.

## Getting Started
Follow these steps to run the project:

### Prerequisites
Ensure that Python and the required libraries are installed:
```bash
pip install pandas numpy matplotlib plotnine
```

### Clone the Repository
```bash
git clone https://github.com/YashChowdhary34/competitive-backlink-analysis-python.git
cd competitive-backlink-analysis-python
```

### Prepare Your Data
- Export backlink data from an SEO tool (e.g., Ahrefs, SEMrush) in CSV format.
- Replace or add your CSV files in the repository.
- Update file paths in the `Competitive-Backlink-Analysis-Python.ipynb` notebook to match your data files.

### Run the Notebook
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Competitive-Backlink-Analysis-Python.ipynb
   ```
2. Execute the cells sequentially to perform the analysis.

## Detailed Workflow
1. **Data Loading**:
   - Load CSV files for your domain and competitors.
   - Combine and structure data into a format suitable for analysis.

2. **Preprocessing**:
   - Clean the data to remove duplicates and handle missing values.
   - Standardize date formats and ensure numeric consistency in DR values.

3. **Analysis**:
   - Calculate descriptive statistics for each domain’s backlink profile.
   - Compare Domain Rating (DR) distributions using visualizations.
   - Compute cumulative referring domain counts to analyze growth over time.

4. **Visualization**:
   - Generate box plots to highlight DR distribution across domains.
   - Plot cumulative growth curves to visualize backlink acquisition trends.

## Example Visualizations
### Domain Rating Distribution
Visualize the quality of backlinks across different domains:

![Domain Rating Distribution](images/4_comp_dr_dist_box_plt.png)

### Cumulative Growth of Referring Domains
Track backlink acquisition over time:

![Cumulative Growth](images/5_count_cumsum_smooth_plt.png)

## Why Use This Project?
- **Comprehensive Analysis**: Provides an end-to-end workflow for understanding backlink profiles.
- **Actionable Insights**: Helps you identify strengths and weaknesses in your backlink strategy.
- **Scalability**: Easily adapt the notebook to analyze additional domains or new data.

By using this project, you can gain a competitive edge in the SEO landscape, refine your link-building strategies, and improve your website’s search engine rankings.
