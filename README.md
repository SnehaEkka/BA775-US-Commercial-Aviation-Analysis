# BA775-US-Commercial-Aviation-Analysis

A comprehensive team analytics project investigating delays, cancellations, and route patterns in U.S. commercial aviation, with a deep dive into Boston Logan (BOS). This project combines robust data engineering, visual analytics, and practical business insights to illuminate factors shaping airline reliability and passenger experience.

## Project Overview

**Context:**  
The commercial aviation industry moves millions, yet travelers routinely face flight delays, cancellations, and disruptions. Understanding the causes and patterns behind these challenges is vital for airlines, airports, and travelers alike.

**Objective:**  
- Evaluate US commercial flight delays and cancellations for 2015 by airline, airport, and route  
- Identify the most and least reliable airlines, busiest routes, and key temporal patterns  
- Drill down into Boston’s airport (BOS), benchmark against national trends, and spotlight performance drivers

**Course Context:** Developed for Boston University, MSBA BA775: Business Analytics Toolbox Class (Fall 2024)

**Team:** Santiago Mazzei, Setu Shah, Sneha Ekka, Tiancheng Yang, Varun Kaza, Victor Floriano

## Skills & Tools Demonstrated

- Data engineering, cleaning, and integration from multi-table aviation datasets
- Descriptive and comparative analytics using Python (pandas, seaborn, matplotlib)
- Advanced visualization and dynamic dashboards in Tableau
- Segmentation, benchmarking, and actionable insights by location, carrier, route, and time
- Translating technical analysis into clear business recommendations

## Dataset

- **Source:** U.S. Department Of Transportation Air Travel Consumer Report (2015)  
- **Prepared through:** [Kaggle (Maven Analytics)](https://www.kaggle.com)  
- **Rows:** ~5.8 million records across four tables (flights, airlines, airports, cancellations), ~40 columns  
- **Key Dimensions:** Carrier, origin/destination airport, route, time (month/week/day/hour), delay & cancellation metrics

## Case Summary

Our analysis addressed:

- **National Patterns:** Quantifying on-time performance, delays, and cancellations—by carrier, airport, and time.
- **Deep Dive: Boston (BOS):** Examining major routes, delay/cancellation risks, airline-specific performance, and seasonal challenges.
- **Practical Application:** Insights for passenger trip planning, airline/airport operations, and decision-making by industry stakeholders.

_For detailed steps, code, and methods, see our [Jupyter notebook](./BA775%20B05%20Commercial%20Aviation%20Analysis.ipynb)._  

## Dashboard Sneak Peek

Here’s a look at our main Tableau dashboards used for analysis and communication:

**National & Citywide Delay/Cancellation Patterns:**  
![Dashboard Sheet 1](Dashboard%20Sheet%201.png) 

**Airline Performance Breakdown:**  
![Dashboard Sheet 2](Dashboard%20Sheet%202.png) 

**Live Tableau Dashboard**
> **Interact with the full analysis:**
>   
> [Tableau Public - Sheet 1](https://public.tableau.com/app/profile/sneha.ekka/viz/ProjectDashboard_17021561609430/DashboardSheet1)
> 
> [Tableau Public - Sheet 2](https://public.tableau.com/app/profile/sneha.ekka/viz/ProjectDashboard_17021561609430/DashboardSheet2)

## Analytics Journey: Approach & Key Analyses

1. **Data Wrangling & Integration**
   - Joined multiple tables, harmonized IATA codes, resolved inconsistencies in airport/carrier names.
   - Used SQL views to protect raw data and enable scalable, flexible exploration.

2. **Descriptive & Comparative Analysis**
   - Quantified national and city-specific rates of delays & cancellations, segmented by airline, airport, and time period.
   - Leveraged Tableau and Python (pandas, seaborn) for dynamic, stakeholder-focused dashboards.

3. **Key Visual Insights**
   - Created bubble maps, stacked trends, pie charts, and alert tables for rapid pattern recognition.
   - Segmented delay/cancellation causes for actionable benchmarking.

4. **Boston Logan Deep-Dive**
   - Evaluated busiest destinations and riskiest routes for BOS flyers.
   - Compared BOS trends to national figures and identified weather/airline-specific drivers.

## Key Findings

- **National:**
  - Only 61% of flights were truly “on time”—severe delays affected nearly 11% of flights.
  - Spirit Airlines led delays (48.1%), while Alaska Airlines had the best on-time and lowest delay averages.
  - Weather caused the majority of cancellations, particularly in winter and summer.
- **Airports & Routes:**
  - Persistent delay challenges for the Caribbean and Midwest; BOS’s busiest routes targeted East Coast hubs.
  - Delays to the Caribbean, Ohio, and NY regional airports were most common.
- **Boston:**
  - February saw Boston’s worst delays, driven by harsh winter weather; Spirit was the least punctual at BOS.
  - Most BOS flights remain focused within the Eastern Seaboard; cancellation and severe delay risk peaked on certain carriers.
- **Temporal Patterns:**
  - Nationally, Thursday was the worst for severe delays; for Boston, Tuesdays and February were riskiest.
- **Business Implications:**
  - Proactive planning (e.g., early flight bookings, selecting more reliable airlines, mitigation plans for seasonal/weather spikes) can reduce disruption risk for both travelers and operators.

## Reflections & Recommendations

- **For Airlines:** Invest in winter ops (esp. BOS), and prioritize comms for high-risk routes/months.
- **For Travelers:** Book earlier flights on consistently reliable carriers; watch for peak month/weekday risks.
- **For Planners:** Data consistency (e.g., code harmonization) is crucial; robust, interactive dashboards drive real-world value and stakeholder engagement.

Explore the analyses, dashboards, and presentation materials throughout this repo!  
For questions or collaboration, connect via Issues or contributor profiles.
