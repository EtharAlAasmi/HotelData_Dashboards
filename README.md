# Hotel Booking Analysis Power BI Project

### Introduction

This Power BI project focuses on analyzing hotel booking data to provide comprehensive insights into booking trends, guest behavior, and cancellations. The project aims to help hotel management make data-driven decisions to optimize operations, enhance guest experiences, and maximize revenue.

### Objectives

#### Hotel Analysis Dashboard
![image](https://github.com/EtharAlAasmi/HotelData_Dashboards/assets/172024720/ee4aa722-525e-4aba-bcbf-82308a131182)

- **Daily Booking Dynamics:** Explore daily booking trends, distinguishing between weekdays and providing insights into the total number of non-canceled and canceled bookings.
- **Monthly Guest Insights:** Illustrate the monthly guest count for both hotels, offering a comprehensive overview of visitor patterns.
- **Special Requests Over Time:** Examine the monthly variations in special requests for both hotels, shedding light on guest preferences and needs.
- **Comparative Cost Analysis:** Present the average daily rates for both hotels on a monthly basis, facilitating a clear understanding of cost disparities over time.
- **Repeated Guest Analysis:** Delve into the distribution channels associated with repeated guests, providing valuable insights into customer loyalty and acquisition channels.

#### Reservations Analysis Dashboard
![image](https://github.com/EtharAlAasmi/HotelData_Dashboards/assets/172024720/31af93e6-f64f-403c-9f7e-5e7254eeb2a6)

- **Room and Meal Preference Overview:** Uncover the top 3 room types and meal preferences.
- **Average Stay Duration per Room Type:** Understand guest behavior trends, identifying longer stays for specific room types.
- **Yearly/Monthly Stay Duration & Meal Count Dynamics:** Examine meal count analysis alongside stay duration trends. Identify any correlation between the count of meals served and the duration of stay.
- **Stay Duration Distribution:** Illustrate the distribution of stay duration between weeknights and weekend nights.

#### Cancellations Analysis Dashboard
![image](https://github.com/EtharAlAasmi/HotelData_Dashboards/assets/172024720/5b59fa1e-91a0-4191-8eb9-754116d3f4d7)

- **Cancellation Rate Trends by Month:** Monitor and analyze the cancellation rates on a monthly basis to identify trends and potential influencing factors.
- **Booking Status by Distribution Channel:** Explore the distribution of bookings, differentiating between non-canceled and canceled, across various channels to understand the impact of each channel on cancellations.
- **Average Daily Rate and Monthly Cancellation Percentage:** Examine the relationship between the average daily rate and the percentage of cancellations each month, providing insights into pricing dynamics and their effect on cancellations.
- **Cancellation Status by Customer Type:** Investigate the cancellation status based on different customer types, allowing for a targeted analysis of cancellation behavior among distinct customer segments.
- **Guest Demographics Overview:** Understand the demographics of guests associated with cancellations, exploring potential patterns or correlations that may influence booking cancellations.

### Insights and Recommendations

#### Hotel Analysis Dashboard Insights
- **Daily Bookings:** Peak days for total non-canceled bookings are Monday, Thursday, Friday, and Saturday. Thursday, Friday, and Saturday also witness the highest occurrence of canceled bookings.
- **Total Guests Per Month:** Guest count rises gradually from July to August, with August being the peak month for hotel occupancy.
- **Monthly Special Requests:** August records the highest volume of special requests, correlating with the influx of guests during this peak period.
- **Monthly Average Daily Rate (ADR):** ADR peaks in July and August, reflecting heightened demand and increased bookings during these months.
- **Repeated Guests by Distribution Channel:** Corporate and TA/TO channels attract the majority of repeated guests, with direct bookings following closely.

#### Recommendations
- **Optimize Staffing on Peak Days:** Focus on adequate staffing during peak days to ensure a seamless experience for guests.
- **Strategic Marketing in August:** Implement targeted marketing campaigns to attract more guests during the peak occupancy period in August.
- **Enhance Special Request Services:** Prioritize and enhance services to meet guest expectations during high special request periods.
- **Dynamic Pricing Strategy:** Implement a dynamic pricing strategy, especially in July and August, to optimize revenue during peak demand.
- **Customer Engagement through Direct Bookings:** Strengthen customer engagement strategies for direct bookings through loyalty programs and exclusive offers.
- **Diversify Repeated Guest Channels:** Explore opportunities to diversify repeated guest channels by targeting audiences beyond Corporate and TA/TO.

#### Reservations Analysis Dashboard Insights
- **Room Type and Meal Preference:** Room Type A leads in reservations, with BB meal type being the most preferred.
- **Average Stay Duration per Room Type:** Room E and C have the highest average length of stay, while Room A has the lowest.
- **Stay Duration & Meal Count Trends:** Both stay duration and meal counts peak during summer months.
- **Stay Duration Distribution:** Weeknights account for 72% of stay duration, while weekends contribute 27%.

#### Recommendations
- **Optimize Room Allocation:** Ensure efficient utilization of popular room types and enhance the appeal of less popular ones.
- **Meal Package Promotions:** Create promotions for the most preferred BB meal type and tailor promotions for other meal types.
- **Enhance Guest Experience for Popular Room Types:** Focus on personalized services and amenities for rooms with longer stays.
- **Weekend Stay Packages:** Create special weekend stay packages to attract more guests during weekends.
- **Feedback Mechanism:** Implement a feedback mechanism to gather real-time insights from guests.
- **Social Media Engagement:** Use social media platforms to promote unique room types and meal offerings.

#### Cancellations Analysis Dashboard Insights
- **Cancellation Rate by Month:** The cancellation rate is highest in June, April, May, September, and October.
- **Booking Status by Distribution Channel:** The TA/TO channel is the major contributor to both canceled and non-canceled bookings.
- **Average Daily Rate and Percentage Cancellations by Month:** Higher average daily rates align with lower cancellation rates during July and August.
- **Cancellation Status by Customer Type:** Transient customer type has the highest counts for both non-canceled and canceled bookings.
- **Guest Demographics:** The majority of guests are adults, constituting 94% of the total.

#### Recommendations
- **Cancellation Rate Trends by Month:** Implement targeted promotions during peak cancellation months.
- **Booking Status by Distribution Channel:** Diversify distribution channels to reduce dependency on the TA/TO channel.
- **Dynamic Pricing Strategy:** Offer competitive rates during high cancellation periods to attract more committed bookings.
- **Cancellation Status by Customer Type:** Tailor marketing campaigns to address the specific needs of transient and transient-party customer types.
- **Guest Demographics Overview:** Develop packages and amenities that appeal to adult guests and those with children.

### Data Preparation and Modeling
- **SQL Integration:** Imported the original dataset into SQL to create an additional column consolidating information from the DATE column.
- **Power BI Data Model:** Designed a data model that includes a FACT table with all booking details, a lookup table for hotel information, and a calendar table for date information.
- **Calendar Table Creation:** Used a DAX formula to create the Calendar table in Power BI.

### Additional Notes
- All files related to project can be found above
- Measures are organized in a dedicated table for clarity.

For further inquiries, comments, or concerns, please do not hesitate to get in touch.
