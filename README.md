# Hotel-Bookings-Analysis-Project
Business Context
•	Booking.com operates at the forefront of global hospitality, managing a diverse range of hotel bookings across various locations, customer profiles, and booking channels. This dataset provides an extensive look into their booking operations, capturing key details such as booking lead times, arrival dates, meal plans, room types, and customer preferences. It also includes information on booking channels, special requests, and reservation statuses.
•	In the competitive landscape of travel and accommodation, companies like booking.com must continuously refine their booking processes to enhance customer satisfaction and optimize revenue. The dataset offers valuable insights into how different factors—such as the booking window, guest demographics, and reservation types—affect hotel performance and customer experience. By analysing this data, booking.com aims to improve booking efficiency, predict guest needs, and tailor their offerings to better meet market demands. This strategic approach helps streamline operations, maximize occupancy rates, and deliver exceptional service, ensuring a competitive edge in the dynamic hospitality industry.
Objective
•	This EDA capstone project aims to extract meaningful insights from hotel booking data to improve decision-making in the hospitality industry. We will analyse booking trends, cancellations, pricing strategies, and customer preferences to provide actionable recommendations for optimizing occupancy rates, revenue, and customer satisfaction. 
Project Summary
•	For this hotel booking analysis, purpose of this exploratory data analysis (EDA) was to explore the hotel booking data set and identify potential relationships between key variables. As part of the analysis, descriptive statistics were calculated for each variable, and visualizations were created. To get insight from the dataset, we built a variety of charts, including a count plot, bar plot and boxplot. Dataset variables are in int64, float64, and object datatypes. We performed some feature engineering for more convenience and created new variables: total_stays, total_people, total_bookings. From these insights, we can suggest some business objectives to clients.
Dataset
This dataset contains information on records for client stays at hotels. More specifically, it contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the guest are coming for first time, number of days in waiting list, among other things. For the purpose of this post, we only focused on some of these variables to examine.
Variables Description
________________________________________
•	Hotel: Type of hotel (City or Resort)
•	is_cancelled: If the booking was cancelled (1) or not (0)
•	lead_time: Number of days before the actual arrival of the guests
•	arrival_date_year: Year of arrival date
•	arrival_date_month: Month of arrival date
•	arrival_date_week_number: Week number of year for arrival date
•	arrival_date_day_of_month: Day of arrival date
•	stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) spent at the hotel by the guests.
•	stays_in_weel_nights: Number of weeknights (Monday to Friday) spent at the hotel by the guests.
•	adults: Number of adults among the guests
•	children: Number of children
•	babies: Number of babies
•	meal: Type of meal booked
•	country: country of the guests
•	market_segment: Designation of market segment
•	distribution_channel: Name of booking distribution channel
•	is_repeated_guest: If the booking was from a repeated guest (1) or not (0)
•	previous_cancellation: Number of previous bookings that were cancelled by the customer prior to the current booking
•	previous_bookings_not_cancelled: Number of previous bookings not cancelled by the customer prior to the current booking
•	reserved_room_type: Code from room type reserved
•	assigned_room_type: Code of room type assigned
•	booking_changes: Number of changes made to the booking
•	deposit_type: Type of deposit made by the guest
•	agent: ID of travel agent who made the booking
•	comapny: ID of the company that made the booking
•	days_in_waiting_list: Number of the days the booking was in the waiting list
•	customer_type: Type of customer, assuming one of four categories
•	adr: Average daily rate
•	required_car_parking_spaces: Number of car parking spaces required by the customer
•	total_of_special_requesrs: Number of special requests made by the customer
•	reservation_statuse: Reservation status (Cancelled, check-out or no-show)
•	reservation_status_date: Date at which the last reservation status was updated
