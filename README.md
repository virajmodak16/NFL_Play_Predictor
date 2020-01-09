# NFL_Play_Predictor - PLEASE READ BEFORE PROCEEDING #

All the the relevant coding files and reports are in this particular repositoru. Please read this file before proceeding to understand the project flow and the aspects discussed in each relevant file.

### Objective ###
In this project I have developed an NFL play (Run/Pass) predictor based on the game situation. The game situation can be quantified using factors such as play down, quarter, clock, timeouts remaining, yardage, etc. The full project proposal and problem solving approach is described in the file "NFL Play Predictor_Proposal.docx"

### Data clean-up ###
The raw data can be found in the zip file "Data.zip" and the code for data clean up can be found in "Python_code.zip". The raw data consists of the following
(1) csv files for each year for both regular season and post-season
(2) csv files for player roster for each season
To clean up the data, please run the file "main.py". All supporting packages need to be in the same folder as this particular file. The final output of this file will also be dumped in the same folder: "FINAL_PBP_DATA.csv"
The data clean-up procedure is describe in detail in the file "Viraj Modak Capstone Project 1 Data Wrangling Report.pdf"

---
The code used in data clean-up will is the only code in a ".py" format. Subsequent code is in the form of a Jupyter IPython notebook ".ipynb"
---

### Exploratory Data Analysis ###
EDA was performed to explore preliminary trends seen in the data. The detailed report along with the code is presented in the Jupyter Notebook "VirajModak_Capstone1_DataStorytelling.ipynb"

### Statistical Analysis ###
The trends observed in EDA were subjected to statistical tests and methods, and the code for the same is presented in the Jupyter Notebook "VirajModak_StatisticalAnalysis_20191128.ipynb". The actual thought process and conclusions drawn are presented in "Viraj Modak Capstone Project 1 Statistical Analysis Report.pdf"

### Milestone Report ###
A summary of everything done so far is presented as a milestone report as a document and a deck of slides:
"VirajModak_Milestone_Report_20191208.pdf"
"VirajModak_Milestone_Report_20191208.pptx"

### Machine Learning ###
Multiple ML techniques were tried on the final data set including K-Nearest Neighbors, Logistic Regression, Decision Trees and Random Forests. RF resulted in the best performance. Basic Feature Engineering was also attempted using the RF model and some key insights were drawn to explain the significance of the results. Details of ML model training and the performance metrics are presented in the following files:
"PredictiveModeling.ipynb"
"PredictiveModeling_FeatureEngineering.ipynb"
"PredictiveModeling_FeatureEngineering_withAnalysis.ipynb"
"VirajModak Capstone Project 1 In-depth Analysis.pdf"

### Final Report ###
The final report is presented as a document as well as a slide deck:
"VirajModak_Final_Report_20191225.docx"
"VirajModak_Final_Report_20191225.pptx"
