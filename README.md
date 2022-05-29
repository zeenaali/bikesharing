# NYC CitiBike
Data Visualization with Tableau

## Project Overview

### Purpose

For this project I am creating data visualization with Tableau for bike sharing program in New York City. The idea is to analyze the data, see the mechanics of the business and figure out how the bike share business actually works in NYC. This is the first step of expanding the idea to other cities. With a strong and clear story, backed-up by data we can create a proposal on how the business could work in other cities as well.

The Tableau story of the NYC CitiBike can be found in the following link: https://public.tableau.com/app/profile/zeena.ali/viz/citi_bike_challenge_16536201170730/NYCCitiBike

### Background

Tableau is one of the most popular tools for data visualization in today’s professional world. It allows data visualization professionals to create data stories that are visually appealing and easy to understand for a non-technical audience. Moreover, Tableau provides the tool to create powerful analytic dashboards and tell a clear story that can be easily shared with others. Tableau can be simple, requiring little-to-no-coding, or quite complex, requiring some experience to write custom code in so-called calculated field. For this project I am using:

- Tableau to create visualizations, dashboard and story.
- Pandas to convert integer to a datetime datatype.

### Resources

- Data Source:
      - CitiBike Trip History Data from August 2019 in NYC
- Software:
      - Tableau Public 
- Languages & Environment:
      - Pandas, Python 3.7

### Results

#### Basic Information

On first page of the story is the dashboard that contains basic information about the data set. The purpose of this page is to familiarize with the data and to introduce to the audience what kind of data we will be dealing with in the further analysis.

![image](https://user-images.githubusercontent.com/99419112/170888769-bc630b97-adaa-4c8a-9ac9-520ee9915759.png)


The page contains the following information:

- Type of business, time frame and location of the data: CitiBike, New York City, August 2019.
- Number of the total rides: 2,344,224.
- Customer type: subscribers and customers.
- Peak hours, divided by gender, with at-a-glance information about user behavior.

1.Checkout Times for Users Most active time - within the first hour

![image](https://user-images.githubusercontent.com/99419112/170888944-911b5aca-e071-4b80-a403-9694bb72f27a.png)


2.Checkout Times by Gender The majority of users are males and tend to have longer trip durations.

![image](https://user-images.githubusercontent.com/99419112/170888954-9c399bcf-c114-471d-8f40-d0dc08088ce3.png)

3. Trips by Weekday per Hour

![image](https://user-images.githubusercontent.com/99419112/170889063-f2ace3bd-2a50-465a-80f4-a581f06b5073.png)

The graph shows number of trips per hour and per weekday. The graph has hours on the y-axis and weekdays on the x-axis. The color indicates the number of trips. Darker color indicates more trips, while lighter color indicates less trips. Form the graph we can see that the busiest times are in the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm. On weekends (Saturday and Sunday) the busiest times are in the middle of the day approximately between 10 am and 6 pm.

4. Trips by Gender (Weekday per Hour)

![image](https://user-images.githubusercontent.com/99419112/170889091-b00276ba-cf7c-41ee-987c-6ff579cc288d.png)

The graph shows number of trips per hour and per weekday. The graph has hours on the y-axis and weekdays on the x axis. The color indicates the number of the trips. Darker color indicates more trips, while lighter color indicates less trips. Additionally, the graph is divided by gender (male, female and unknown). From the graph we can see that distribution of the checkout times for all genders is similar - the busiest times are in the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm. On weekends (Saturday and Sunday) the busiest times are in the middle of the day approximately between 10 am and 6 pm. However, males have significant higher number of trips than female or unknown gender.

5. User Trips by Gender by Weekday

![image](https://user-images.githubusercontent.com/99419112/170889131-91efe503-0e72-41b7-a456-08d81d2b4eb9.png)

The graph shows number of trips by weekday, by user type (subscribers and customers) and by gender. The graph has weekdays and user type on y-axis and gender on x-axis. Amongst subscribers, male has the highest number of the trips especially on Thursdays and Fridays, followed by trips on Monday and Tuesdays. Female has similar distribution of trips, with significant lower number of trips than male. Unknown gender has uniform distribution of the trips throughout the week. Looking at the customers’ data we can see significant less trips throughout all genders with slight increase amongst unknown gender on Saturdays and Sundays.

### Summary

The story of the NYC CitiBike starts off with the basic information about the users and the trips. From the first page we can learn a lot about users for bike share company and helps us understand data in further analysis. This data analysis contains data from August 2019, a busy time for bike share business in NYC. We have two user types subscribers and customers, three genders - male, female and unknown and two important aspects of the business - time and bike maintenance.

**Bike maintenance**

Bike maintenance plays a big role in bike share business. Heat maps are great visualization for large amount of data and give us clear story about the data. From the graphs Peak Hours per Gender, Trips by Weekday per Hour and Trips by Gender (Weekday per Hour) we can see that the least busy time is between 11pm and 5am. That suggests a good time for bike maintenance. 

**Customers and Subscribers**

Customers are the most important part in the business. Our business is doing well because of them. In bike share business we have two types of users with a slightly different habit of using the service. It is important to be aware of those differences to ensure a good customer experience. In popular times for tourism we can expect that more customers (non-subscribers) will use the service. In order to be prepared for this surge, business should plan ahead for bike and station maintenance, rotation of the bikes and keep popular stations stocked.

**Gender**

From most graphs we can see that usage of the bikes is disproportional amongst genders. With careful and mindful marketing approach, we could target underrepresented groups and increase business.

**Trip-duration**

The most popular trip duration checkout time is between 3-8 hours. From this we can learn more about users' behavior. One way to see this side of the story is that users checkout bike for a single trip and return bike to the station (3 hour) or may rent the bike and keep it until their return trip (8+ hours). We could address a few things here. From revenue perspective, it is good that customer is willing to pay for the whole time, yet the utilization of bikes may not be the most efficient. Business could set up more stations for users to return the bikes to the station for the time that they are not using the bikes.

Additionally, I would suggest a few things for further analysis with the given data set:

- Trip duration of checkout times per user types. With this analysis we could see the trend of trip durations amongst user types.
- Weekday and the trip duration. With this analysis we could see if the trend of the trip duration is similar on particular day (i.e. weekends and weekdays).
- Additional color filter in Top Ending and Top Starting location to see which stations are more popular amongst subscribers and customers.






