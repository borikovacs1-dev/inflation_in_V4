# Review For inflation_in_V4 project by Abdullah Abdulrahim

##  Reproducibility Report

 - **Could I run the analysis?**
Partially. I was eventually able to run the notebook and reproduce the main results (data loading, dataset merging, and plot generation). However, the process required several path corrections and environment adjustments before the code could run successfully from start to finish. There were also minor setup issues, such as missing kernel registration and required packages (ipykernel, jupyter). 


 - **Can I do so by changing only 1 line of code?**
  Not exactly. While each individual issue was simple to fix, several lines had to be changed or adjusted:

    - The file paths for reading the CSVs (../data/raw/...)

    - The path for saving combined data (../data/combined_inflation_data.csv)

    - The path for saving figures (../output/...)



 - **Can I do so without changing a single line of code?**
  
   No. Running the notebook in its original state produced multiple FileNotFoundError exceptions, which prevented the analysis from completing.



## Overall opinion

 - **How do you rate the mini project (reproducibility, clean documentation and analysis, coding style, use of git, etc.)?**
  Overall, I would rate the mini project as good, but with room for improvement in reproducibility.



## Suggested improvements

 - **At least 2–3 concrete ideas for what could be improved (structure, clarity, analysis steps, commit messages, etc.).**

    The project is well-structured and clearly shows the workflow from data collection to visualization. The analysis is logical and the results are easy to interpret. To make it even stronger, some reproducibility issues can be addressed to achieve that end.







