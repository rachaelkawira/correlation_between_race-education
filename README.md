# correlation_between_race-education
This is a story of how not every data day is a good day. I saw a video of someone saying that the lack race doesn't have the luxury of not choosing education because in terms of income we are the most disadvantaged without education and I decided to put that to a test.
I checked on Bigquery census data and decided to create a new table with the data I had picked out to be essential for my study.
![Code to extract data on Bigquery](https://github.com/user-attachments/assets/005ddbfe-517d-4810-bfc3-1e40a7b95d58)
At this point, I thought I would easily be able to find a correlation between the number of people per race and the number of people having degrees. So I thought I should either do a scatter plot or just directly write the code to find the correlation on R.
![The dataset on google sheets](https://github.com/user-attachments/assets/71105ec0-6c15-4d16-9ba9-7c8c58651437)
I opened the dataset on google sheets to do an exploration. After a few outcomes that weren't loking like what I envisioned, I decided to move the data to excel to give me better options playing with the graph. Only then did I realize that the data wasnt quite friendly in terms of plotting a scatter plot because the races were separate and the level of degrees were also separate. Plotting a scatter graph with multiple variables on the x and the y is nasty business.
![Screenshot 2024-11-12 141807](https://github.com/user-attachments/assets/6f371e56-4b57-492d-8fba-cd8ccccbfc30)
I decided to try and find the correlation matrix directly on R but that didnt work out. So after thinking and thinking I decided to just compare the races separately and the degrees separately so that I feel better about myself 
![Screenshot 2024-11-12 141807](https://github.com/user-attachments/assets/20e8a183-1f64-49b6-9405-7d4d0c7ccb81)
But it doesn't really make me feel better about myself
