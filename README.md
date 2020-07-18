# COVID-19
This is a predictions of what would be the number of hospitalizations of cases if the number of confirmed cases are 42,000?

This is how I worked it step by step 

1. First, I did research on covid-19. I research what is it, who and how people get affected. I also search for the statistics on it like the confirmed, death, and recovery rate. 
2. Looking at all the information I decided that my question should be “What would be the amount of people who recovered from covid-19 by august 1st, 2020”
3. Shortly after coming up with my question I found the dataset I would be analyzing. 
4. After looking at the data, I decided to download it and use it for my project
5. I imported pandas and numpy because I need those 2 libraries to analyze on the data
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
16. I only did that on the x axis so but not the y so it raised an error because both x and y are suppose to the same amount of data points in order to graph
17. Next I changed the y axis and put it as the same amount as the as the x axis 
18. Finally, I graphed and plotted the points
19. But when I graphed it wasn’t as I expected so i decided to go back on few of my steps but it wasn’t the data that I was having trouble with but my question
20. The question that i asked wasn’t a question that I can use because the attributes of my question could lead me to making an analytic decision. 
21. I needed three key parts of my question to have an data analysis that i can work with two variables and an entity
22. I would first have to understand the three key parts because conducting a question about them
23. After some time i got my question: What would be the number of hospitalizations(variable) of cases (entity) if the number of confirmed cases(variable) are 42,000?
24. identifying my question once again i went to a dataset websites such as kraggle, data.org, and etc...
25. again i look for data sets from these websites and saw if they identity with my question
26. I found one that only pertained to connecticut but could work with the bigger picture
27. I fully downloaded the dataset, I imported the necessary libraries in order to do my analytics 
28. i located the path of the file I download and read it in pandas
29. What the data had was different counties in connecticut but the same day with these attributes: date updated, county code, county total cases, confirmed cases, probable cases total case rate, hospitalized cases, total deaths, confirmed deaths, and probable death
30. Wanting to see a certain day I took data points from hospitalized cases and confirmed cases 
31. I graph those various points to see the range the the data on that certain day
32. some thought I decided to sum up the days so when were exactly plotting point we wouldn’t have too much or unnecessary data points
33. summing up the various data points i decided to but various data point concerning hospitalized cases and the confirmed cases into variables so i can be able to graph them later
34. Then I put both variables into a scatter plot graph
35. I checked the shape because i wanted both variables to have the same dimensions 
36. sorting all of that out i decided to work on the linear regression
37. When putting in the x and y values of the graph that was to be plotted this error came up
38. It said i had to reshape the graph by making them into arrays and reshaping both of the variable because they needed to be in the same dimension in order to graph 
39. Once i did that i finished making the linear regression and my graph plotted
40. But what my graph showed was a lot of zeros so i needed to change that by clearing out all the ‘nan’ data because nan data isn’t really doing anything so why have it around
clearing all the nan data 
41. I once again ran the linear regression function and the graph that came out was better than the one before because it had a solid linear regression line going somewhere and it was displaying great predictions 
