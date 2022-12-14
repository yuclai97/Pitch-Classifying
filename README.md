# Classifying Pitches using Machine Learning
## Background
###  Trying to identify different pitches thrown by the pitchers has been one of the most popular topics not only between amatuers baseball fans but also baseball savants. The goal of this project is try to build up pitch classifying model and review the performance of different machine learning algorithm including "Random Forest", "Decison Tree", and "SVC".
## Data
### To gather the pitching data, I used the pybaseball, a python package for scraping baseball data. The pitching data I selected is all the pitches of Cleveland Guardians' pitcher, Shane Bieber from 2022-04-01 till 2022-10-01, basically all his pitches of 2022 MLB regular season.
## Machine Learning
### The variables I picked for the model building are the pitch name (as the label and dependent variable), the release speed, release spin rate, velocity in x,y and z planes, and acceleration in x,y and z planes. To be noticed, sometimes different kinds of fastballs, including but not limited four-seam, two-seam, and cutter are more difficult to be identified from each other, so I built a fastball group filter to further compare the performance of different algorithm with or without all fastballs being labeled as only one kind of pitch.
