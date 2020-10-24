# John Grando
## Data Science Portfolio

### About Me
I'm a lifelong student who is passionate about data science. I have over 6 years of experience performing data analyses, applying transformations, and building machine learning models to provide business intelligence solutions. Additionally, I have been working in the commercial building energy and sustainability sector.

---  
#### EIA Data Analysis and Prediction
---  
I am currently developing tools to extract information from the U.S. Energy Information Administration (EIA) [bulk download feature](https://www.eia.gov/opendata/bulkfiles.php), and make some initial predictions to gain insight.  

[ETL Details - PySpark](https://github.com/john-grando/eia-data-analysis/tree/master/app/PreProcess)  
[ETL Output Analysis](https://github.com/john-grando/eia-data-analysis/blob/master/app/Notebooks/total_energy.ipynb)  
[Net Generation Analysis](https://john-grando.github.io/EIADataPages/total_energy_prediction.html)

---
#### Modification of the Time Series Cross Validation function (tscv) in the forecast R package
---
I, like many others, have found much value in the book [Forecasting: Principles and Practice](https://otexts.com/fpp2/).  The code that comes with that text provides a very sophisticated cross-validation technique that is packaged as the tsCV() function.  However, when used with external predictors (`xreg`), the function does not always return results.  The detailed breakdown of the bugs, and proposed fix, are provided in this summary report.  Additionally, a vectorized version of this function is provided which may work on larger data sets but is untested.

[Report](https://john-grando.github.io/EIADataPages/tsCV_analysis.html)  
[Source File](https://github.com/john-grando/eia-data-analysis/tree/master/app/RFiles/Source)

---  
#### Building Energy Consumption Prediction - Capstone project
---  
This is a comprehensive report that explores and transforms a set of survey questions about commercial building characteristics, extracts the most impactful features pertaining to electrical and natural gas consumption, and uses those features to create a deep feed-forward neural network prediction algorithm for each fuel source.  

[Full Report](https://github.com/john-grando/john-grando-portfolio/blob/master/CapstoneDocuments/CapstoneFullReport.pdf)  
[Summary](https://github.com/john-grando/john-grando-portfolio/blob/master/CapstoneDocuments/CapstoneSummary.pdf)  

---  
#### New York City Energy Consumption Visualized  

---  
This project was created in an effort to showcase some programming and visualization skills I acquired.  It is built using HTML, CSS, Javascript (d3.js), and the Plotly graphing package.  It is a little slow, as it is hosted on a free platform, but it serves the purpose of showing what can be visualized from such data.

[HTML Page](https://john-grando.github.io/EnergyPages/ll84.html)
