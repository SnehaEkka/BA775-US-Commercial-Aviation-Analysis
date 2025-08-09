# BA775 – US Commercial Aviation Analysis  
#### *"End-to-end analysis of 2015 U.S. flight delays, cancellations, and route reliability, blending Python and Tableau to uncover actionable patterns for airlines, airports, and travelers"*

## About  
A comprehensive analytics project investigating delays, cancellations, and route patterns in U.S. commercial aviation with a focused deep dive into Boston Logan (BOS). This project combines robust data engineering, visual analytics, and practical business insights to illuminate factors shaping airline reliability and passenger experience.

## Dataset

- **Source:** U.S. Department of Transportation (DOT) Air Travel Consumer Report (2015)   
- **Prepared through:** [Kaggle (Maven Analytics)](https://www.kaggle.com)  
- **Rows:** ~5.8 million records across four tables (flights, airlines, airports, cancellations), ~40 columns  
- **Key Dimensions:** Carrier, origin/destination airport, route, time (month/week/day/hour), delay & cancellation metrics

## Purpose & Business Context  
The commercial aviation industry moves millions, yet travelers routinely face flight delays, cancellations, and disruptions. Understanding causes and patterns is key to improving operational reliability and customer satisfaction. This project aims to:  
- Evaluate U.S. commercial flight delays/cancellations for 2015 by airline, airport, and route.  
- Identify the most and least reliable airlines, busiest routes, and key temporal patterns.  
- Deep dive into BOS performance to benchmark against national trends and spotlight drivers.

## Solution Overview  

### Data Wrangling & Integration  
- Joined multiple tables, harmonized IATA codes, and resolved inconsistencies in airport/carrier names.  
- Created SQL views to preserve raw data while enabling scalable exploration.

### Descriptive & Comparative Analysis  
- Quantified national and city-specific rates of delays & cancellations, segmented by airline, airport, and time.  
- Combined Python (pandas, seaborn, matplotlib) with Tableau for dynamic, stakeholder-ready dashboards.

### Visualization & Storytelling  
- Developed bubble maps, stacked trends, pie charts, and alert tables for rapid pattern recognition.  
- Segmented delay/cancellation causes for actionable benchmarking.

### BOS Airport Deep Dive  
- Assessed busiest destinations and highest-risk routes for BOS flyers.  
- Compared BOS trends against national figures to identify weather and airline-specific variance.

_For detailed steps, code, and methods, see our [Jupyter notebook](./BA775%20B05%20Commercial%20Aviation%20Analysis.ipynb)._

## Tools & Tech Stack  

| Tool / Technology | Purpose                          |
|-------------------|----------------------------------|
| Python (pandas, seaborn, matplotlib) | Data cleaning, analysis, visualization |
| SQL               | Data joining and preprocessing   |
| Tableau           | Dashboarding & visual analytics  |
| Jupyter Notebook  | Interactive coding & analysis    |

## Dashboard Preview  

**National & Citywide Delay/Cancellation Patterns:**  
![Dashboard Sheet 1](Dashboard%20Sheet%201.png) 

**Airline Performance Breakdown:**  
![Dashboard Sheet 2](Dashboard%20Sheet%202.png)

## Business Impact & Key Results  

**National Patterns**  
- Only **61%** of flights were “on time”; severe delays impacted ~11%.  
- Spirit Airlines had the highest delay percentage (48.1%); Alaska Airlines was most reliable.  
- Weather drove the majority of cancellations, especially in winter and summer.

**Airports & Routes**  
- Delay issues were persistent for the Caribbean and Midwest.  
- BOS’s busiest routes were primarily East Coast hubs; delays common to Caribbean, Ohio, and NY regional airports.

**Boston-specific**  
- February was the worst for BOS delays due to winter weather; Spirit was least punctual.  
- Cancellation and severe delay risks peaked on certain carriers and routes.

**Temporal Patterns**  
- Nationally, Thursdays showed highest severe delay rates; for BOS, Tuesdays and February were critical.

## Reflections & Recommendations

- **For Airlines:** Invest in winter ops (esp. BOS), and prioritize comms for high-risk routes/months.
- **For Travelers:** Book earlier flights on consistently reliable carriers; watch for peak month/weekday risks.
- **For Planners:** Data consistency (e.g., code harmonization) is crucial; robust, interactive dashboards drive real-world value and stakeholder engagement.

## How to Run  
1. Clone the repository.  
2. Download datasets from Kaggle (Maven Analytics – US Flight Delay 2015) or DOT sources.  
3. Open the Jupyter Notebook (`BA775_US_Commercial_Aviation_Analysis.ipynb`) for end-to-end EDA.  
4. Explore Tableau dashboards in `/dashboards` or via the live link above.

## Future Improvements  
- Incorporate weather and ATC incident data for richer causal analysis.  
- Expand analysis to a multi-year time frame for trend tracking.  
- Deploy interactive web dashboards for public or operational use.

## Coursework & Contributors
- **Coursework:** Completed as part of **BA775 – Business Analytics Toolbox** (Boston University MSBA, Fall 2024)
- **Contributors:**   
  - Santiago Mazzei
  - Setu Shah
  - Sneha Ekka
  - Tiancheng Yang
  - Varun Kaza
  - Victor Floriano

## Additional Resources  
- 📊 Tableau Dashboards: [Sheet 1](https://public.tableau.com/app/profile/sneha.ekka/viz/ProjectDashboard_17021561609430/DashboardSheet1) and [Sheet 2](https://public.tableau.com/app/profile/sneha.ekka/viz/ProjectDashboard_17021561609430/DashboardSheet2)
- 📄 Final Project [Presentation Deck](https://www.canva.com/design/DAF2vFoYh3A/V7kNUmXT3iVcnZCJXHhSAw/view?utm_content=DAF2vFoYh3A&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd5e49b86f9) 
