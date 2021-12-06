# Call Analysis Project_Project Group 16
<h4>Description<br>
<h5>Question 1: Top10 
In this project, we firstly analyzed the top 10 incident types in our zip code area (10025) by using pandas.DataFrame. Firstly, we indicated our_zipcode variable to be 10025. Then we created new_df using our_zipcode as a filter of df['Incident Zip']. Then we used value_counts().sort_values(ascending = False).head(10) methon on new_df['Complaint Type'], to find the top 10 causes of calls to 311 and calculate the number of total incidents of each of these 10 types in our zip code area in the year 2020.
Question 2: Parking
The creation process of df and new_df is the same with Question 1.To get the illrgal parking rates, we basically use [new_df['Complaint Type'] == 'Illegal Parking'] as the mask of new_df['Complaint Type'], and use count() function to count the illegal parking rows. And we calculated the rates based on the number of rows of illegal parking and total rows. The methods to get our_illegalparking_rate and global_illegalparking_rate are similar. Then, we compared the proportion of illegal parking incidents in our zip code area with that in all zip code areas. Since our_illegalparking_rate < global_illegalparking_rate, the higher_parking_proportion was assigned to be False.

<h4>IEOR_4501_sec_002<br>
Project Group 16

<h4>Group member list<br>
sb4557<br>
lp2932<br>