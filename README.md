# COVID-19
This is a predictions of the people who have recovered from COVID-19 by August 1, 2020

This is how I worked it step by step 

1. First, I did research on covid-19. I research what is it, who and how people get affected. I also search for the statistics on it like the confirmed, death, and recovery rate. 
2. Looking at all the information I decided that my question should be “What would be the amount of people who recovered from covid-19 by august 1st, 2020”
3. Shortly after coming up with my question I found the dataset I would be analysing. 
4. After looking at the data, I decided to download it and use it for my project
5. I imported pandas and numpy because I need those 2 libraries to analyze the data
6. Then I took the data I got off online and imported it in the Jupyter Notebook with the pandas library
7. Next I started to clear the data because some of the data was unnecessary to answer my question
8. At the first I didn’t know where to start because they summarized the data by give the first 5 rows and the last five rows
9. Then I used a built-in function ‘iloc’ this help sort through the data and see where the data started exactly 
10. After figuring it out I started to delete the columns
11. Next I used the histogram function to describe each column and what they were doing
12. Then I found the mean of each day and put it in a dataframe variable 
13. After, I put the colunms of each day in a seperate dataframe variable. 
14. When I plot it the first time there were too many data points to see what was going on 
15. So i used the 'iloc' function so I could skip some data points to get the full picture
16. I only did that on the x axis so but not the y so it raised an error because both x and y are suppose to thace the same amount of data points in order to graph
17. Next I changed the y axis and put it as the same amount as the as the x axis 
18. Finally but graph plotted it points
19. After some time i got my question: What would be the number of hospitalizations(variable) of cases (entity) if the number of confirmed cases(variable) are 42,000?
20. identifying my question once again i went to a dataset websites such as kraggle, data.org, and etc...
21. again i look for data sets from these websites and saw if they identity with my question
22. I found one that only pertained to connecticut but could work with the bigger picture
23. I fully downloaded the dataset, I imported the necessary libraries in order to do my analytics 
24. i located the path of the file I download and read it in pandas
25. What the data had was different counties in connecticut but the same day with these attributes: date updated, county code, county total cases, confirmed cases, probable cases total case rate, hospitalized cases, total deaths, confirmed deaths, and probable death
26. Wanting to see a certain day I took data points from hospitalized cases and confirmed cases 
27. I graph those various points to see the range the the data on that certain day
28. some thought I decided to sum up the days so when were exactly plotting point we wouldn’t have too much or unnecessary data points
29. summing up the various data points i decided to but various data point concerning hospitalized cases and the confirmed cases into variables so i can be able to graph them later
30. Then I put both variables into a scatter plot graph
31. I checked the shape because i wanted both variables to have the same dimensions 
32. sorting all of that out i decided to work on the linear regression
33. When putting in the x and y values of the graph that was to be plotted this error came up
34. It said i had to reshape the graph by making them into arrays and reshaping both of the variable because they needed to be in the same dimension in order to graph 
35. Once i did that i finished making the linear regression and my graph plotted
37. But what my graph showed was a lot of zeros so i needed to change that by clearing out all the ‘nan’ data because nan data isn’t really doing anything so why have it around
clearing all the nan data I once again ran the linear regression function and the graph that came out was better than the one before because it had a solid linear regression line going somewhere and it was displaying great predictions 
