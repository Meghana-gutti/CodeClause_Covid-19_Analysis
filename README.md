# CodeClause_Covid-19_Analysis
A Data Analysis project on the spread of the Novel Coronavirus in India. This project uses raw data in the form of .csv files and transforms it into a Data Analysis. This project is an attempt of analysing the coronavirus (Covid – 19) spread in India using data science concepts and analytics with the help of Python in the Jupyter Notebook interface. This analysis will help us find the basis behind common notions about the virus spread purely from a data perspective. The data used in this project is spread across 2 files:

1. Covid_19_india.csv
2. Indian Coordinates.xls For the analysis we have used the common Python libraries, such as NumPy, Pandas, Seaborn, matplotlib, stdlib, folium and fbprophet.


# Results of Project Functions
1. In this project two files are imported.
   Covid_19_india.csv
   Indian Coordinates.xls

2. Data is prepared for analysis with the help of data cleaning by removing, modifying that is incorrect, incomplete, irrelevant, duplicated or improperly formatted.

3. Merging operation is done by joining two data frames. In this way information about a particular entity common to both the two datasets.

4. Pie charts are plotted for each state separately and for overall country data.
   • States like Maharashtra, Gujarat, MP, West Bengal have a death rate of nearly 5 percent
   • States like Tamil Nadu, MP, UP, Rajasthan, Andhra Pradesh, Telangana, Haryana, Kerala have more than 50% recovered cases
   • Punjab has almost 90% recovered cases
   • No deaths have been recorded in Tripura, Goa, Ladakh, Puducherry and Manipur
   • Andaman and Nicobar Islands have all the cases recovered
   • Dadar and Nagar Haveli, Sikkim, Nagaland has all active cases
   • Maharashtra has highest number of cases recorded
   • Overall in India, 53% are active, 3% have died and 44% have recovered

5. Merging of two datasets based on the state column was performed. Data repetition, Extra spacing, slight changes in name of the state was corrected and removing the not 
   common data for both the data sets.

6. Visualization was carried out using folium package. Maps were plotted indicating the Covid hotspots.

7. Prediction was carried out using timeseries fbprophet model and graphs were plotted indicating actual values and predicted values.
