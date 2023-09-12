# Hotel-Booking-Analysis
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
![Hotel-Booking](https://user-images.githubusercontent.com/89864373/132099143-4d15689a-568b-4cb9-adad-cdf9a9ef9ff7.jpg)


# Dataset Specs
* Count of rows= 119390
* Count of columns= 32

# Programming Language
* Python 

# IDE
* Google Colaboratory

# Nomenclature
Naming our dataframe is very crutial for any data analysis project as you have to call the dataframe time and again for every set of operation which are to be performed for the in-depth analysis.

In this case, our copy of the dataframe will be called 'df' , simple and easy to recall.

# Data Variables Glossary

* **hotel**
Two hotels are given:
Resort Hotel
City Hotel
* **is_canceled**
1: Canceled
0: Not canceled
* **cancelation**
0 as not_canceled
1 as canceled
* **df_not_canceled_guests**
dataframe with just not_canceled bookings
* **lead_time**
gap between booking and arrival
* **arrival_date_year**
arrival year
* **arrival_date_month**
arrival month
* **arrival_date_week_number**
arrival week
* **arrival_date_day_of_month**
arrival date
* **stays_in_weekend_nights**
count of nights the guests booked the hotel during Sat-Sun
* **stays_in_week_nights**
count of nights the guests booked the hotel during Mon-Fri
* **total_stay_nights**
duration of stay including weekend nights and week nights stay
* **adults**
count of adults
* **children**
count of children
* **babies**
count of babies
* **meal**
meal type (no meal package; BB; HB; FB)
* **country**
country of guests
* **df_country_guests_top10**
top10 countries with most visitors
* **market_segment**
TA: Travel agents
TO: Tour operators
* **distribution_channel**
* **is_repeated_guest**
1: Yes
0: No
* **previous_cancellations**
count of previous bookings that were cancelled by the customer before final booking
* **previous_bookings_not_canceled**
count of no canceled bookings
* **reserved_room_type**
booked room category
* **assigned_room_type**
assigned room category
* **booking_changes**
count of changes made by the customer before final booking
* **deposit_type**
type of deposit made by the customer
* **agent**
travel agent id
* **company**
booking company id
* **days_in_waiting_list**
count of days the booking was in the waiting list before it was confirmed
* **customer_type**
Transient
Contract
Group
Transient-party
* **adr**
average daily rate for the booking
* **price**
total price spent by a guest entity
* **required_car_parking_spaces**
count of car parking spaces alloted by the customer
* **total_of_special_requests**
count of special requests made by the customer
* **reservation_status**
status of reservation
* **reservation_status_date**
date corresponding to status of reservation

# INTRODUCTION & OBJECTIVE OF THE CHASE
Our main objective is to perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

Let's begin the chase!

# SUMMARY OF CONCLUSIONS
* City Hotel has a higher number of bookings compared to Resort Hotel.
* City Hotel generated more revenue
* ADR[Average Daily Rate] is increasing year by year.
* We can see that city hotel has more booking but we can also see it has maximum number of cancellation also.
* It's clear that contract basis customer stays more than other type of customer.
* It's clearly visible customers from portugal are more likely to book in our hotels
* We can see booking are mostly done through TA/TO channel than Direct or Corporate channels.
* We can see bookings are higher from month July to September.
* We can clearly sense BB food is mostly in demand.
* Maximum booking done on Friday,Thursday,Monday and Saturday respectively.
* We can see that how some columns correlate and create hues of red and darker blue like revenue and total_room_sold,total_stay  and revenue and etc.
* We can see what factors are dependent and independent to each other like days_in_waiting_list and lead_time have a correlation.
