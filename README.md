# Portfolio
---

## Education & Work Experience
<ul>
<li>B.S. in Data Science, Mathematics -  Merrimack College</li>
</ul>

<ul>
<li>Machine Learning Intern - Roi Solutions</li>
<li>Research Assisstant - Merrimack College</li>
<li>Teaching Assistant - Merrimack College</li>
</ul>

- [Education and Experience in depth - Resume](https://patrick-norcross-resume.tiiny.site/ "Resume")
  
---

## Projects

### My Work for Amnesty International
Unfortunately, I was not able to hold on to the work I produced for ROI Solutions. However, I still wanted to take
the oppurtunity to highlight the project in more detail that what is seen on my resume. As the Machine Learning 
Intern, I was tasked with improving upon the reinstatement model for ROI Solutions' client Amnesty International.
The reinstatement model pulls data from Amnesty's constituent database regarding last donation date, demographic data,
donation amounts, total donations, and much more using a SQL script. The goal was to identify constiuents who had
not donated in 24 months or longer and determine through machine learning models which constiuents were most likely
to respond to Amnesty's upcoming mail campaign. Some of the major changes to this rebuild was updating the date range
from 2018-2019 and bringing it up to date by including 2018-2022. I also added new features into the SQL script to 
add more information of each constiuent.
ROI Solutions utilizes DataRobot, a third-party service used for building a large variety of machine learning models
based on the file that is given. They rank the models based on a very large set of possible scoring techniques which
is then intepretted by the user to make a final call on which model will perform best. To make sure this resulting
model was able to perform better I ran a test campaign which was withheld in the original training set. I ran these
scores through the current model in place as well as the rebuilt model. Looking at results yielded about a 10%
increase in the selection of constiuents who did respond to the mail campaign with a gift. Real World results of
this rebuild have not been determined yet as it will be used for Amnesty's November Campaign with results of the
campaign coming in around Febuary of 2024.

I also spent time working with python, creating a script that the team could use on a monthly basis when producing
scores for models of various clients and model type. It was able to pull the data that needed scoring from an SFTP
server, score the data in the script by using DataRobot's API, and then return the results back to the server,
as well as downloading the files needed locally for further analysis of the scores produced.

### Supervised Learning on Sleep Data
The american time use survey measures the use of time spent doing various activites throughout a 24 hour period.
My goal in this project was to create categories of sleep levels "Low, average, high" to then see if I can use 
the rest of the time use data to correctly categories these groups. I used 2018 data as a training set and used
the newest 2021 data as the test set going into the project in hopes of being able to use these models for future
years. Throughout the project I used various ensemble methods, tested with many different parameters to get optimal
scores. I also worked with Voting Classifiers which took into account Tree, kNN, SVM, and Naive Bayes models with 
optimized parameters using Grid Search.

![Confusion matrix of the 2021 data as well as an accuracy score.](/assets/ATUS_1)

Used accuracy score to refrence results as well as looking at confusion matrices to understand the results
visually and more in-depth.

[Link to the Code and Project](https://www.google.com)

### Classifying Written Digits using Nueral Networks
Using a large database of hand written digits, I performed data manipulation to get these images into a dataframe
that identified each pixel on a scale of 0-255 based on its place in a scale from white to black. From there, I used
linear regression, multi-layer perceptrons, and nueral networks to build models to predict these digits correctly. 

[Link to the Code and Project](https://www.google.com)

### Visualizations for Merrimack College's Swim Team
One of the research projects I had the oppurtunity to be a part of was working with the Swim and Diving team here 
at Merrimack College. This was something that was worked on slowly throughout the year. The swimmers were tasked 
with filling out a survey weekly. I took this data and had to perform heavy data cleaning and wrangling to be able
to perform any type of analysis. A large portion of the time has been devouted to creating visualizations for the 
swimmers to view after recieving data. This has been made easy by using R Shiny to be able to select the respective 
ID and their respective charts will then be brought up to view. There has been a dive into model building but hopes 
of more objective data in the future has largely held us off on that for now. Current work involves constant updates
to visuals, new visual ideas, and automating the process from data recieved to visuals produced.

[Link to the Code and Project](https://www.google.com)

---

## Connect with Me!
<a href="https://www.linkedin.com/in/patricknorcross"/><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>

<a href="mailto:patrick.norcross@comcast.net?"><img src="https://img.shields.io/badge/gmail-%23DD0031.svg?&style=for-the-badge&logo=gmail&logoColor=white"/></a>
