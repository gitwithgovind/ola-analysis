# ola-analysis
# 🚖OLA: Analysis of the Reasons and Trends for Ride Cancellations
_An interactive Power BI dashboard built to identify key reasons and trends behind ride cancellations on the Cab Industry —designed to drive strategic decisions that reduce losses and improve operational efficiency._

## 🧠 Purpose </br>
The OLA Analysis Dashboard is a visually engaging Power BI solution that uncovers cancellation patterns across time, location, and stakeholder behavior (riders and drivers). This tool is developed to help business stakeholders understand critical pain points in the
booking lifecycle and design solutions that reduce cancellations and revenue loss. This tool is intended for use by Risk Assessment Consultants in the cab industry or any cab/mobility startup enthusiast.

## 🛠 Tech Stack </br>
The dashboard was built using the following tools and technologies: <br>
•📊 **Power BI Desktop** – Used for creating the interactive dashboard and visual analysis. <br>
•📂 **Power Query** – Applied for cleaning, reshaping, and transforming the data from various sources. <br>
•🧠 **SQL** – Used for querying, joining, and aggregating data to prepare key indicators. <br>
•📁 **File Format** – .pbix for development; .png files used for screenshot previews. <br>
•📈 **Data Modeling** – Relationships were built across key tables like ride history, user behavior, and cancellation logs to enable effective cross-filtering. <br>

## 🔍 Data Source <br>
This project combines simulated OLA ride data across real locations in Kolkata, West Bengal, enriched with custom attributes to reflect real-world cancellation behavior.
Source: Realtime dataset generated via ChatGPT.

The dataset includes fields such as: <br> <pre>
•Booking ID,                                                   •Booking Status,                                 •Vehicle Type,                  •Time, <br>
•Pickup Location,                                              •Drop Location,                                  •Ride Distance,                 •Booking Value(Fare), <br>
•Cancellation Reason (both from Driver and Customer) ,         •Rating (both from Driver and Customer),         •Completion Status, etc. </pre>

## 🌟 Features <br>
_**• Business Problem**_
Whether it's OLA, Uber or any other cab provider in the industry, they all face high volumes of ride cancellations across metros and tier-2 cities —directly impacting their customer satisfaction and profitability. Without clear insights into what drives these
cancellations, solving this problem becomes a guesswork.
Key questions such as:
_-What are the most common reasons for ride cancellations?  <br>
-Are cancellations more frequent at specific times of the day or week?  <br>
-Do riders or drivers cancel more frequently—and in which scenarios?  <br>
-What is the revenue impact of these cancellations on OLA's operations?_  <br>
....are difficult to answer quickly with raw data.  <br>

_**• Goal of the Dashboard**_ <br>
To deliver an interactive visual tool to OLA’s Strategy and Operations teams that: <br>

-Reveals the most common reasons behind ride cancellations.
-Shows cancellation trends across time, vehicle type, and ratings.
-Showcasing Ride Volume over Time.

_**• Walkthrough of Key Visuals**_ <br>
The dashboard is classified into the following 5 pages: <br>
_Page 1:_ Overall <br>
➡Date (_Slicer_) - An interactive filter allowing users to select a custom date range, dynamically updating all visuals on the page for flexible temporal analysis. <br> 
➡Total Bookings (_KPI Card_): 1000 <br>
➡Total Booking Value (_KPI Card_): 3.10M <br>
➡Booking Status Breakdown (_Pie Chart_) - Visualizes the distribution of rides by status: Success, Cancelled by Rider, Cancelled by Driver, Incomplete. <br>
➡Ride Volume Over Time (_Line Chart_) - Plots ride volumes across time. Highlighting fluctuations, seasonality, and patterns in user behavior that may relate to cancellations or booking spikes. <br>

_Page 2:_ Vehicle Type <br>
A structured table for visualizing vehicle-wise performance, with vehicle types (e.g., Prime Sedan, Mini, Prime Plus, SUV, Auto, Bike, etc.) as columns and the following key performance metrics as row: <br> <pre>
➡Total Booking Value,         ➡Successful Booking Value,         ➡Average Distance Travelled,         ➡Total Distance Travelled. </pre>

_Page 3:_ Revenue <br>
➡Revenue by Payment Method (Stacked Column Chart) <br>
➡Date (Slicer) <br>
➡Top 5 Customers by Revenue (Table) <br>
➡Total Ride Distance Over Time (Stacked Column Chart) <br>

_Page 4:_ Cancellation <br>
➡Date Slicer <br>
➡List of KPIs- <br> <pre>
✔Total Bookings: 10000            ✔Successful Bookings: 6815 
✔Cancelled Bookings: 2662         ✔Cancellation Rate: 74.042% <br> <pre>
➡Cancelled Rides by Customer (Pie Chart) <br>
➡Cancelled Rides by Driver (Pie Chart) <br>

_Page 5:_ Ratings <br>
Custom Tables: Driver Ratings by Vehicle Type & Customer Ratings by Vehicle Type <br>

_**•Business Impact & Insights**_ <br>
**Root Cause Discovery:** Two primary reasons behind cancellations were identified—driver unavailability and high wait time—which can now be targeted with operational fixes. <br>
**Revenue Recovery:** Strategic changes based on these insights could lead to a projected increase in monthly profitability. <br>
**Policy Optimization:** Enables product teams to modify app logic (e.g., match-making timing, incentives) to reduce high-risk cancellation scenarios. <br>
**Location Intelligence:** Zone-specific cancellations guide demand-balancing and driver allocation improvements. <br>
