# DA-IV-IOG-ASSIGNMENT

# Installation

Before running the Jupyter Notebooks, make sure to install all required dependencies by executing the following commands: 

1 - to install all dependencies from requirements.txt --> 
python -m pip install -r requirements.txt

2 - to install jupyternotebook to execute code  -->
python -m pip install notebook

# ZIP Archive & PPT
This repository includes a folder called PROJECT-SOURCE-CODE-ZIP, which contains a ZIP file with the full source code for the project and Power Point slides regarding quick visual representation of outlier analysis output

The project has been tested in a clean environment and runs smoothly with all dependencies using both PyCharm Community and Professional Edition.


#  Why IQR

I went with the IQR method for outlier detection mainly cause it's simple and works better with messy, real-world data like medical claims. 

The medical claim data is kind of skewed, because some patients have high-value claims like “heart surgery” vs “knee surgery” resulting in extreme values, so methods like Z-score didn’t really help much, as Z-scores method assumes data is always normally distributed, which isn’t the case here. 

IQR just looks at the middle chunk of the data and flags data points that’s way off, which made it easier to spot actual outliers without getting distracted by the noisy data.

**
