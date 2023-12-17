# Air Quality Data warehouse and analysis using Business Intelligence

## Title: Air Quality Data Warehouse and Business Intelligence on public health
## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Data Description](#Data-Description)
- [Methodology](#Methodology/Approach)
- [Data Visualization using Tableau](#Tableau-Visualizations)
- [Contributors](#Contributors)

  
## 1: Problem Statement
The primary objective of our Air Quality Data Warehouse for Exploring Impact on Public Health is to analyze air quality data from various sources, including OpenAQ, Healthcare, and Global Surface Temperature data, along with real-time API inputs. The focus is on understanding environmental factors contributing to asthma issues in California, with broad applications across healthcare, insurance, medical practitioners, and research teams.

Addressing the complexities of air quality monitoring, our project employs advanced data engineering and analytics techniques. The overarching goal is to craft a comprehensive solution that efficiently collects, processes, analyzes, and visualizes real-time air quality data. By achieving this, our aim is to empower stakeholders by providing accessible data in the data warehouse, facilitating its utilization for deriving valuable insights. Leveraging two additional datasets—Healthcare and air quality, GSOD data—our project addresses challenges associated with air quality monitoring and its profound impact on various domains

## 2. Data Desciption
1. OpenAQ Archived Data:
Content: Air quality readings for various pollutants globally.
Significance: Crucial for a global perspective on air quality with data from diverse locations.

2. Healthcare Data: Asthma Data
Content: Dataset related to asthma, providing insights into health impacts of air pollution.
Significance: Essential for correlating air quality data with healthcare, supporting epidemiological studies.

3. ASDI Data: Global Surface Summary of the Day (GSOD)
Content: Comprehensive climate station data, including temperature, precipitation, and wind information.
Significance: Valuable for analyzing historical climate patterns, predicting future weather conditions on a global scale.


## 3. Methodology/Approach: 
Our methodology is underpinned by a robust and scalable architecture designed to seamlessly integrate data from diverse sources and ensure its quality and accessibility. This architectural diagram visually represents the key components and their interactions within our data pipeline. 

Architecture Overview:

![Image](./architecture.png)


## 3: Tableau Visualizations:
Summary of Tableau analysis:

● The analysis identifies the top 5 pollutants as the primary contributors to asthma-related fatalities in California pm2.5 seems to be the top pollutant for deaths.Pm2.5 emerges as a major pollutant affecting lungs, despite higher overall O3 values in certain counties.

![Image](./scatter.png)

●	Los Angeles emerges as the leading county for Asthma Emergency Department (ED) visits, followed by Riverside, Orange, Alameda, Fresno, etc.

![Image](./hospitalizations.png)

●	O3 and Co pollutants are identified as the key contributors to the rise in temperature levels.A notable trend is observed with increased pollutant levels during the first week of every month.

![Image](./dashboard_temp.png)

## Contributors:
[<img src="https://github.com/{{ phunswadkar }}.png" width="60px;"/><br /><sub><ahref="https://github.com/{{ phunswadkar }}">{{ phunswadkar }}</a></sub>](https://github.com/{{ phunswadkar }}/{{ AirQualityDataWarehouse_CloudBasedSolution }}
[<img src="https://github.com/{{ Bala-krishna-Batchu }}.png" width="60px;"/><br /><sub><ahref="https://github.com/{{ Bala-krishna-Batchu }}">{{ Bala-krishna-Batchu }}</a></sub>](https://github.com/{{ Bala-krishna-Batchu }}/{{ capstoneproject }}




