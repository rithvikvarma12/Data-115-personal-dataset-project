# English Premier league 2019-20 data 

# Motivation
I decided to make this project based on soccer. So, While browsing the internet for some datsets, I found a few datasets that seemed to have pretty good data for entire seasons of the english Premier league which is the highest division of english soccer.Being pretty intrigued, I went through the data. Naturally, this led to some questions. This led to me comparing between different data columns. The Main question Im trying to answer is what is the relationship between the number of shots taken and the number of goals scored by the teams and how this differs with home and away teams.

# Data Sources
I obtained this data from the datahub.io website. I extracted the dataset of the 2018-2019 english Premier League season from the football dataset section of the datahub.io website. The website sourced this data from the website www.football-data.co.uk

# Processing steps 
The datset that I had procured needed to be processed. The main issue with the dataset was that it was faily large. This meant that some columns did not show up on jupyter notebook as the dataset was being compressed. This means that a new dataset from the existing dataset had to be made. The Processing 2018-2019 ibynb file extracts columns from the existing dataset and combines them to create a new dataset that shows all the columns that are required.

The new processed dataset looks like this :

![Snippet of new processed dataset](https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/processing%20data.PNG)

# Visualizations
Once I finished processing the data, I started to wonder about the relationships between the different columns of the dataset. I wanted to find out if there was a strong or weak correlation of the number of shots taken with the number of goals scored by the teams. Further, I wanted to find out how this correlation differs with home and away teams.
I first made scatter plots for the columns before trying find the relationships between the shots taken and goals scored

<table>
  <tr><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/FTHG.PNG"></td><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/FTAG.PNG"></td><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/HS.PNG"></td><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/AS.PNG"></td></tr>
   <tr><td>Home Team Goals</td><td>Away team Goals</td><td>Home Team shots</td><td>Away Team shots</td></tr>
  </table>
  
   We can see that the scatter plots for the home teams shots taken and goals scored are different from the scatter plots of the away teams shits taken and goals scored.
   
# Analysis
In order to find out the relationship between the shots taken and goals, I first combined the home and away team stats for shots taken and goals scored 

<table>
  <tr><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/FTHG%20VS%20FTAG.PNG"></td><td><img src="https://github.com/rithvikvarma12/Data-115-personal-dataset-project/blob/main/HS%20VS%20AS.PNG"></td></tr>
   <tr><td>Home Team vs Away Team Goals</td><td>Home Team vs Away Team shots</td></tr>
  </table>

From these two figures, we can see a picture forming. On average Home Teams take more shots and they also score more goals than away teams. This means that home teams performed better than away teams.

This is backed up by analysis. There is a moderately strong positive correlation between home team shots and home team goals scored. Away team shots taken and away team goals also have a moderately strong correlation. Although, home teams have a slighty stronger correlation between their shots taken and goals scored. This means that home teams score more goals from their shots when compared to away teams.

<table>
  <tr><td><img src="https://raw.githubusercontent.com/rithvikvarma12/Data-115-personal-dataset-project/main/FTHG%20VS%20HS.PNG"></td><td><img src=""></td></tr>
   <tr><td>Home Team Shots taken Vs Home team Goals</td><td> Away Team shots taken vs Away team goals scored</td></tr>
  </table>




# Descriptions of Code and Materials
