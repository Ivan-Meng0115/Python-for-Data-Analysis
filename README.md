## Python-for-Data-Analysis
Fundamental Python syntax and libraries (NumPy, Pandas, Matplotlib, Seaborn, Plotly, and Cufflinks) to make data cleaning, data analysis, and data visualization.



## [Project 1: Emergency 911 Calls -- Exploratory Data Analysis](http://localhost:8888/nbconvert/html/GitHub/Python%20Data%20Analysis/911%20Emergency%20Calls/Emergency%20911%20Calls%20--%20Exploratory%20Data%20Analysis%20Project%20.ipynb?download=false)
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


## Reprocessing data
* class the category of data
* drop the unuseful data
* split the data to create new features dataset


## Exploratory Data Analysis (EDA)


* Overall 911 calls
![](https://github.com/Ivan-Meng0115/Python-for-Data-Analysis/blob/main/output_58_0.png)

* Most common reason for 911 emergency call
![](https://github.com/Ivan-Meng0115/Python-for-Data-Analysis/blob/main/output_45_0.png)

* 911 calls in each month
![](https://github.com/Ivan-Meng0115/Python-for-Data-Analysis/blob/main/output_50_0.png)


* Top 10 reasons for emergency calls
![](https://github.com/Ivan-Meng0115/Python-for-Data-Analysis/blob/main/output_55_0.png)



