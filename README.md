# CSCI2000U_Final_Project_Group_9

# ReadMe File

# IMPORTANT: csv file too large, not uploading to GitHub
# URL to download HERE: https://www.kaggle.com/sobhanmoosavi/us-accidents?select=US_Accidents_Dec20_updated.csv
## HTML file shows report running

## ****************
## * Final Project
## * Scientific Data Analysis
## * December 6th 2021
## * Noah Briffa, Seodong (Andrew) Lim, Nathaniel Tai
## ****************
## PREDICTING THE NEXT TRAFFIC ACCIDENT WITH THE USE OF CODING  
### CONTENTS OF THIS FILE  
### About Us  
### Introduction  
### Requirements  
### Installation  
### Discussion  
### Conclusion  
### Maintainers  
### Acknowledgement  
### ABOUT US  
This report was done by Noah, Seodong (Andrew), and Nathaniel. Three students that are currently attending Ontario Tech University.  This report was done as the final project for the course of “Scientific Data Analysis”. More information about the authors that have worked on this project can be found in the “Maintainers” portion of this readme file. Information includes things such as GitHub users and contact information.  
### INTRODUCTION  
This is the README file for the US traffic accident dataset. Here one will find out how to access the information needed to run the code or find the origin of the database used. As shown in the table of contents, this readme file can be as well used to access the contact information about the author, if one may run into problems in the future when using the code and need assistance with the code.  
In this report, the information that one will find is based on all traffic accidents that have happened in the United States. By using the information based on the traffic acciden### ts that happened across the country, one can make predictions and through scientific based analysis, can look at these trends and work around the future regarding the traffic. This will be shown more in depth in the coding portion of the project. For example, by using the data given, it is possible to piece the information together and allow one to possibly know where the next traffic accident might most likely be. With the help of this information, it can lead to a safer driving experience for everyone on the road and assist the government in incorporating safer road protocols in hot zones where it is common for vehicles to cause accidents.  
The acquired data is all the recorded traffic accidents that have happened in the country during February 2016 to December 2020. Note that these accidents were all recorded by traffic and government officials (ex. Police). There can be other accidents that happened in the country that might have not been recorded. In total there are 1.5 million total recorded accidents found in the dataset.    
The dataset that was used when working on the project was found on the Kaggle website. The link to the website will be found below. Kaggle is an online platform with many other data scientists who put up their repositories for others to use. Through Kaggle, one can access other people’s projects and the Jupyter Notebook environment. The US traffic accidents was one of the many open datasets that can be found on this website. More information and sources can be found in the original Kaggle webpage and as well this can be found under the “Acknowledgement” section of the readme file.  
The information that was used for the traffic accidents can be found here: https://www.kaggle.com/sobhanmoosavi/us-accidents  
### REQUIREMENTS  
To run the code, it is necessary to use Jupyter Notebook.  
### INSTALLATION  
To install Jupyter Notebook, there are several different methods which are listed in this link:  
https://jupyter.readthedocs.io/en/latest/install.html  
The code that was used in this project can be found in the GitHub repository.  Downloading the original dataset is also needed as it holds the information for all of the recorded traffic accidents in the US.  
### DISCUSSION  
There is much interesting information that can be absorbed using this dataset. With the help of Python, and the libraries that were imported (ex. NumPy and Pandas), it allowed for easy analysis of the 1.5 million total accidents. The help of these tools can be shown in our code and helped visualize each representation with the graphs.  
Looking at each year separately, it was possible to separate the dataset by the total number of traffic accidents per year. The total number of accidents per year were found to be in 2016: 129325 (Note: the information recorded for the year of 2016 was accounted later in the year) accidents, in 2017: 170099 accidents, in 2018: 166936 accidents, in 2019: 261772 accidents, and in 2020: 787932 accidents. The general pattern that is shown per year is the increase of accidents that are happening. It is interesting to point out that in the 2020 year, does not follow the trend of the small increase of accidents per year. But instead, there is a huge spike in the number of total accidents. During this period, it was the start of the Covid 19 pandemic. Due to this, governments worldwide and in the United States called for a lockdown. Although this was in place, by using the dataset. It was found that during the pandemic, it was the year with the most volume. There are many reasons and factors on why this could have been happening. With people being locked in their homes for most the year, it was likely that people wanted to go out and get time out of their homes.  
Now by looking at the time of when the traffic accidents happen. One can see what time is the most dangerous to be on the road as specific time of the day will have more vehicle accidents than others. By arranging it by each hour interval, the times were listed with the volume of traffic accidents. There were two main time intervals that were found to have the most amount of traffic accidents. It was found to be between 07:00-08:00 and 13:00-18:00. During this time, it is usually when most people will start heading to their workplace or homes. Therefore, it is not much of a surprise to see that these time intervals have the highest volume of accidents. However, from 15:00 – 18:00, is the peak of when the accidents happen the most. Using this information, one can know when it is the safest time to usually drive and if one must drive in the hours where there are a lot of accidents. To drive safer than usual and take more precautionary measures as it is more likely to be in a traffic accident.  
Another piece of information that was looked at was the relationship between the severity of the accident (the amount of impact the accident had on the traffic from a scale 1 to 4) and the length of the road affected. Here is the calculation listed for all 4-severity amount; severity 1 had affected 0.201586 miles, severity 2 had affected 0.504544 miles, severity 3 0.606261 miles, and severity 4 had affected 1.351702 miles (Note: these values are taken as average amount of road it has affected, therefore there are times where it could be much more significant/less than the listed amounts depending on the severity). As foreseeable as the information could have been for few, it is very interesting to see the gap and the impact it has on the road from severity 3 to severity 4. From the first 3 severities, there are small jumps in the length of the road affected, but from 3 to 4. It almost tripled the length, showing the huge difference between the two severities. Another thing that was looked at was the wind speeds and its correlation with the severity. By looking at this information, the wind speed had no effect on the severity levels. As wind speeds will most likely never cause a vehicle to move. The wind speed was also found to be in similar ranges for each of the severities which further proves that it had no impact on the traffic accident.  
### CONCLUSION  
In summary, using any datasets, one can show many different patterns and relationships between things to prove points. In this case, with the help of traffic accidents in the US dataset, one can see different ways to analyze the traffic situations to avoid accidents to stay safe or even ways to avoid the areas that have a high volume of traffic.     
### MAINTAINERS  
Noah Briffa - noah.briffa@ontariotechu.net - https://github.com/Noah-Briffa  
Seodong (Andrew) Lim - seodong.lim@ontariotechu.net - https://github.com/seodong-lim  
Nathaniel Tai - nathaniel.tai@ontariotechu.net - https://github.com/NathanTai  
Other contact info (Professor of the course):  
Mariana Shimabukuro – mariana.shimabukuro@ontariotechu.net  
### ACKNOWLEDGEMENT  
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.  
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019."  
