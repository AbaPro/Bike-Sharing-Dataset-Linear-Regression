# Bike-Sharing-Dataset-Linear-Regression

## AIMS OF THE PROJECT

From this project I want to learn how to work with big data and to prove a specific point using an appropriate statical methods, to achieve this aims I will go deeper in python’s library pandas and matplot.

## Research Questions

1-	Do people rent bikes in weekend more than the beginning of the week ?

2-	Do people rent bikes in working days more than normal days ?

3-	Does wind speed affect renting bikes ?

4-	Does weather condition affect renting bikes ?

5-	Is there is a relation between weather situation and humidity ?

## ANALYSIS AND FINDINGS

" You can find more details in the main notebook "

By ranking the weather situations as follow 

1-	Clear, Few clouds, Partly cloudy, Partly cloudy

2-	Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

3-	Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

And Using the aggregation function “mean” we can see that humidity increases with weather situation. the cloudier the weather is the more humidity there are 


![image](https://user-images.githubusercontent.com/102380881/209818298-6266fe69-cf4d-4fdd-979f-c97a1a0e4c73.png)

By using python’s crosstab we can see an interesting summaries of the weather situation and humidity over the whole dataset
Note that the hum columns have been rounded to get this 10 columns crosstab
 
![image](https://user-images.githubusercontent.com/102380881/209818345-b7719958-b277-46b6-96f1-55b8f76d7ae5.png)

Average number of rented bikes in each day, visualized using bar plot

![image](https://user-images.githubusercontent.com/102380881/209818455-a02b0ca5-8467-40ca-9ba5-3e32b1f8ec85.png)

By scatter plotting windspeed and number of rented bikes
We can see that there is a lot of dots centered in a specific spot

![image](https://user-images.githubusercontent.com/102380881/209818490-5336c703-793c-49f2-ad09-933055abe5d0.png)

By using seaborn’s heat map to visualize the correlation between every two variables using spearman method

![image](https://user-images.githubusercontent.com/102380881/209818522-c9fafb8a-c7bc-414f-9c3d-98b63eeb3323.png)

![image](https://user-images.githubusercontent.com/102380881/209818534-c5e4664e-b3a3-4ca0-bbb3-ef11d289cbda.png)

![image](https://user-images.githubusercontent.com/102380881/209818547-4b2d5ac9-010d-48f9-acaa-023dda56b910.png)

# REFERENCES

Frost, J., 2020. Spearman’s Correlation Explained. [Online] 
----------------
Available at: https://statisticsbyjim.com/

Accessed 5 October 2022.

Kumar, P., 2021. SciPy in Python. [Online] 
----------------
Available at: https://www.h2kinfosys.com/

Accessed 6 October 2022.

pands, 2020. Pandas Library. [Online] 
----------------
Available at: https://pandas.pydata.org/

Accessed 5 October 2020.

Simplilearn, 2022. What is Statistical Analysis?. [Online] 
----------------
Available at: https://www.simplilearn.com/

Accessed 8 October 2022.

Solomon, B., 2020. Python Plotting With Matplotlib. [Online] 
----------------
Available at: https://realpython.com/

Accessed 4 October 2022.


