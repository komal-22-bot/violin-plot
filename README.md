## App Ratings Violin Plot Dashboard

This project visualizes the distribution of app ratings by category using a violin plot. It is built with Plotly and filters data based on specific business logic and time constraints.

##  Features

- Filters apps that:
  - Have names containing the letter **"C"**
  - Have more than **10 reviews**
  - Have a **rating less than 4.0**
- Only includes **categories with more than 50 apps** meeting the above criteria.
- The graph is displayed **only between 4 PM and 6 PM IST**.

##  Time Restriction Logic

To manage visibility based on time:
- The code checks the current time in **India Standard Time (IST)**.
- If the time is **not between 16:00 and 18:00**, the graph is **not shown**.

##  Requirements

Install the necessary Python packages:
*Ensure your CSV file apps.csv includes at least the following columns:

-App

-Category

-Rating

-Reviews
