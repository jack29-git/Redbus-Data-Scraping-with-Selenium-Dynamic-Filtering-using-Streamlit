# Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit

## Table of Contents
1. Project Overview
2. Features
3. Technical Stack
4. Project Workflow
5. Business Use Cases
6. Future Enhancements
7. Deliverables
8. Repository Contents
9. Project Evaluation Metrics
10. Conclusion

---

## Project Overview
The **Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit** project revolutionizes the transportation industry by automating the extraction and visualization of bus travel data. It combines **Selenium** for web scraping, **SQL** for structured data storage, and **Streamlit** for interactive filtering and analysis, providing a comprehensive solution for real-time insights and decision-making.

### Key Highlights
- Automates data collection from Redbus, including routes, schedules, prices, and seat availability.
- Stores data in a structured SQL database for efficient querying.
- Provides an intuitive Streamlit dashboard for dynamic filtering and analysis.
- Supports business use cases like competitor analysis, customer insights, and market trends.

---
## Features
### **Data Scraping and Storage**
- **Web Scraping:** Extracts essential data fields like bus names, types, departure times, durations, star ratings, prices, and seat availability using Selenium.
- **Structured Storage:** Stores data in an SQL database with a well-designed schema for seamless data retrieval and management.

### **Streamlit Application**
- **Dynamic Filters:** Allows users to filter data by:
  - Bus Type (Sleeper, Seater, AC, Non-AC).
  - Price Range.
  - Star Ratings.
  - Seat Availability.
  - Routes.
- **Interactive Dashboard:** Visualizes insights such as price trends, route popularity, and seat availability.

### **Data Analysis**
- SQL-powered querying to generate actionable insights.
- Visual representation of travel trends and patterns.
- Competitive benchmarking and performance evaluation of service providers.

---

## Technical Stack
### **Languages & Frameworks**
- **Python**: Core programming for web scraping and data manipulation.
- **MYSQL**: Database creation and management.
- **Streamlit**: Interactive dashboard for user-friendly data exploration.
- **Selenium**: Web scraping automation.
### **Libraries**
- **Selenium**: Web scraping automation.
- **pandas**: Data processing and analysis.
- **Streamlit**: Application development.
- **datetime**: Time-based operations.

---

## Project Workflow
### 1. **Environment Setup**
- Install required libraries and configure Selenium drivers.
- Set up the SQL database schema for storing scraped data.

### 2. **Data Scraping**
- Automate Redbus data extraction using Selenium.
- Retrieve detailed bus information, including routes, schedules, prices, and availability.

### 3. **Data Storage**
- Store scraped data in an SQL database with the following schema:
  - **route_name**: Route information.
  - **route_link**: Link to detailed route info.
  - **busname**: Bus operator name.
  - **bustype**: Sleeper/Seater/AC/Non-AC.
  - **departing_time**: Scheduled departure.
  - **duration**: Journey time.
  - **reaching_time**: Scheduled arrival.
  - **star_rating**: Customer ratings.
  - **price**: Ticket cost.
  - **seats_available**: Current availability.

### 4. **Streamlit Application**
- Build an interactive app for filtering and visualizing data.
- Integrate real-time data visualization for user exploration.

### 5. **Data Analysis & Insights**
- Perform route efficiency analysis,
- price trend monitoring,
- competitor benchmarking.
- Generate actionable insights for improving customer satisfaction and service quality.

---

## Business Use Cases
1. **Travel Aggregators**
   - Real-time schedules and seat availability for enhanced booking experiences.
2. **Market Research**
   - Analyze customer preferences and travel trends.
3. **Service Optimization**
   - Improve bus operations and scheduling.
4. **Competitor Benchmarking**
   - Compare services and pricing strategies with competitors.

---

## Future Enhancements
- **Real-Time Updates:** Enable live data scraping for up-to-date insights.
- **Advanced Filtering:** Add complex filtering options for granular analysis.
- **Machine Learning Integration:** Predict travel trends and optimize pricing strategies.

---

## Deliverables
- **Source Code:** Python scripts for scraping, database interaction, and Streamlit application.
- **SQL Schema:** Scripts to create and populate the database.
- **Streamlit Application:** Interactive dashboard for filtering and visualization.

---

## Repository Contents
- **bus details extraction.ipynb**
  - Contains the Python script using Selenium to scrape bus details such as routes, timings, prices, and availability.

- **pymysqlconn.ipynb**
  - Demonstrates the connection to a SQL database for storing the scraped data.

- **red bus routes and links.ipynb**
  - Extracts bus routes and their respective URLs for data scraping.

- **redbus_all_data.csv**
  - A CSV file containing the scraped bus data for reference or analysis.

- **redbus_streamlit.py**
  - A Streamlit application script to dynamically filter and visualize the scraped data.

## Project Evaluation Metrics
- **Data Accuracy:** Completeness and correctness of scraped data.
- **Database Design:** Efficiency and scalability of the schema.
- **User Experience:** Intuitiveness and responsiveness of the Streamlit app.
- **Filter Functionality:** Precision and performance of dynamic filters.
- **Code Quality:** Adherence to Python best practices and modularity.

---

## Conclusion
The **Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit** project showcases the power of automation and interactive visualization in the transportation domain. By providing real-time insights and enabling data-driven decisions, this project empowers stakeholders to optimize operations, enhance customer satisfaction, and stay competitive in the market.


## streamlit application screenshot
- here's a screenshot Redbus Data Filtering in Streamlit Web Application
- This screenshot showcases the interactive Streamlit application built for dynamic filtering and visualization of bus travel data. Users can filter buses based on routes, timings, prices, ratings, and availability. The application provides an intuitive interface for analyzing transportation data in real time, helping in decision-making and market analysis.

![red bus data filter](https://github.com/user-attachments/assets/8ddcd3fa-4026-4341-9141-a0062693f0bd)
