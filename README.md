# Prediction of Credit Card Default Rate

### Summary

Lending companies would benefit greatly by knowing how current economic conditions predict future loan default rates. This project uses publically-available macroeconomic data to use machine learning to evaluate the aggregate national credit card default rate, attempting to predict its value 6 months in advance.

### Contents

The project is broken up into sections on data wrangling, data exploration, and machine learning as follows:

<ol>
    <li><b>macro_capstone_data_wrangling.ipynb</b> - The data required to predict the credit card default rate is all sourced, wrangled, and exported into a .pkl for future use in this notebook.</li>
    <li><b>macro_capstone_data_exploration.ipynb</b> - The data is explored to demonstrate that there are macroeconomic variables that are leading predictors of the credit card default rate, and to explore the path of these variables over time.</li>
    <li><b>macro_capstone_xgboost</b> - Using the XGBoost machine learning package, predictions are made on the path of the credit card default rate and tested against historic values.</li>
    <li><b>macro_capstone_presentation_pdf.pdf</b> - A brief summary of each of the stages is presented in this document.</li>
    <li><b>Data</b> - This folder contains the independent and dependent variables in .pkl form, although it is recommended to use the data wrangling notebook referenced in (1) to re-create this data and ensure that the most recent available data is used.</li>
</ol>
