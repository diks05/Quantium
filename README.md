

# **Retail Store Trial Analysis**  

### 📌 **Project Overview**  
This project evaluates the effectiveness of a store trial conducted in three test stores (77, 86, and 88) to measure the impact of marketing strategies on sales performance. Using **R**, we identified suitable control stores, analyzed key sales metrics, and performed statistical testing to validate the results.  

### 📊 **Key Analysis Steps**  
✔ **Control Store Selection:** Used Pearson correlation and magnitude distance metrics to find stores with similar pre-trial sales patterns.  
✔ **Trend Visualization:** Compared sales trends of trial and control stores using **ggplot2** to check pre-trial similarity.  
✔ **Scaling for Comparison:** Adjusted control store sales using a scaling factor to match pre-trial conditions for a fair comparison.  
✔ **Statistical Testing:** Applied **t-tests** to determine if sales during the trial period were significantly different from pre-trial trends.  

### 📈 **Findings**  
- Store 86’s performance was **not significantly different** from its control store, as sales remained within the **5-95% confidence interval** for most trial months.  
- Other trial stores showed **observable increases in total sales**, suggesting a potential positive impact of the trial.  

### 🔧 **Technologies Used**  
- **R (dplyr, ggplot2, data.table, ggpubr)** for data manipulation & visualization  
- **Statistical hypothesis testing (t-tests, confidence intervals)**  
- **Control store selection using correlation & magnitude distance metrics**  

### 🚀 **Next Steps**  
🔹 Extend analysis to other product categories.  
🔹 Perform **A/B testing** with different promotional strategies.  
🔹 Automate reporting with **Shiny dashboards**.  

