# EDA-on-Google-Playstore-Apps-data

### Business Objective:
The Play Store apps data has enormous potential to drive app-making businesses to success. However, many apps are being developed every single day and only a few of them become profitable. It is important for developers to be able to predict the success of their app and incorporate features which makes an app successful. Before any such predictive-study can be done, it is necessary to do EDA and data-preprocessing on the apps data available for google app store applications. From the collected apps data and user ratings from the app stores, let's try to extract insightful information.

### Approach:
The required libraries were imported and the data was read from the dataset file. The data presented was not clean to carry any analysis.
1. To understand the data checked the datatypes of each field, the summary statics was checked. Then the presence of any duplicate records were checked and removed if any.
2. The column "Rating" which contained the ratings of the apps was checked for any missing values and then converted that column into a categorical column and values High(Greater than 3.5 out of 5) and low(less than 3.5 based on the rating the app has scored.
3. The column "reviews" which contaoned the number of people wbo reviewed the app has checkedd for any non numerical data and covverted the column to a numeric field. The presence of outliers was also checked and treated.
4. The columns "Price", "Size" and "Installs" also had some cahracter along with numbers in the entries they were removed and those fields were converted into numerical datatypes.
5. Finally the Target and Feature columns were seperated and the data were split into train and test sets and then standardized so that it can be used for further analysis.

### Tools used: Python(pandas, NumPy, Plotly,matplotlib, seaborn, Sklearn)
