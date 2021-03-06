## Python-for-Data-Analysis
The project focuses on Exploratory Data Analysis to discover hidden patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations by using fundamental Python syntax and libraries (NumPy, Pandas, Matplotlib, Seaborn, Plotly, and Cufflinks).


## [Project 1: Emergency 911 Calls -- Exploratory Data Analysis](https://github.com/Ivan-Meng0115/Python-for-Exploratory-Data-Analysis/blob/main/Emergency%20911%20Calls%20--%20Exploratory%20Data%20Analysis%20Project%20.ipynb)

#### 911 is an emergency telephone number for the North American Numbering Plan (NANP). Analysing emergency calls dataset and discovering hidden trends and patterns will help in ensuring that the emergency response team is better equipped to deal with emergencies. Considering road accidents, fire accidents etc, high numbers in specific areas indicate that there is a high demand for ambulance services in those areas. Road accidents in some areas might be due to road conditions which need to be improved. High frequency of emergencies due to respiratory problems might be due to harmful pollutants in the air in that specific area. Association rule mining will thus help in discovering such patterns. The dataset contains Emergency 911 calls in Montgomery County located in the Commonwealth of Pennsylvania. The attributes chosen include: type of emergency, time stamp, township where the emergency has occurred.

* Analyzed emergency 911 calls dataset to help the emergency team is better equipped to deal with emergencies.
* Reprocessed the dataset (class th elables, clean unrelated data, deal with the missing data)
* Used data to create reports and dashboards ti find the hidden trends and patterns

## Features of Data
* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)


## Reprocessing Data
* class the category of data
* drop the unuseful data
* split the data to create new features dataset


## Exploratory Data Analysis (EDA)


#### Overall 911 calls
![](/output_58_0.png)

#### Most common reason for 911 emergency call
![](/output_45_0.png)

#### 911 calls in each month
![](/output_50_0.png)


#### Top 10 reasons for emergency calls
![](/output_55_0.png)



