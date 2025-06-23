# DA-IV-IOG-ASSIGNMENT
# About

This project is a data analysis exercise focused on identifying potential fraud, waste, or abuse in Medicaid claims. It involves exploratory data analysis (EDA), data cleansing, and transformation of multi-sheet healthcare data. The analysis includes provider-level payment and client metrics, outlier detection, and visual summaries. As request are the final results are compiled into a "Data product" named Medicaid_Fraud_Case_OIG_Investigated_Data.xlsx .

# Installation

The project has been tested in a clean environment and runs smoothly with all dependencies on both PyCharm Community and Professional Editions. Therefore, it should be relatively easy to execute.

However, if any issues are encountered, follow these steps to set up the environment with the required dependencies:

1. Install all dependent libraries from  'requirements.txt` --> python -m pip install -r requirements.txt
  
2. Install Jupyter Notebook to run the code--> python -m pip install notebook

# in-line comments

Clear, in-line comments were included before and after each major step to explain the thought process and ensure the flow of execution is easy to follow as requested.

#  Why IQR

I chose the IQR method for outlier detection mainly because it's simple and tends to work better with complex, real-world data like medical claims. 
The medical claim data is somewhat skewed—some patients have high-value claims like 'heart surgery' compared to lower-cost procedures like 'knee surgery.' This results in extreme values, making methods like Z-score less effective, since Z-score assumes the data is normally distributed, which isn’t the case here.

IQR, on the other hand, focuses on the middle 50% of the data and flags points that fall far outside that range. This made it easier to identify true outliers without being misled by the noise in the data.

# ZIP Archive & PPT
This repository includes a folder called PROJECT-SOURCE-CODE-ZIP, which contains a ZIP file with the full source code for the project and Power Point slides regarding quick visual representation of outlier analysis output

The project has been tested in a clean environment and runs smoothly with all dependencies using both PyCharm Community and Professional Edition.
