# Air quality and healthcare Data Warehousing using API, Cloud data on AWS

## Title: Air Quality Data Warehouse and Business Intelligence on public health
![Image](./Proj_cover.webp)

## Table of Contents
- [Problem Statement](#problem-statement)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Data Visualization using Tableau](#tableau-visualizations)
- [Contributors](#contributors)

  
## Problem Statement
The primary objective of our Air Quality Data Warehouse for Exploring Impact on Public Health is to analyze air quality data from various sources, including OpenAQ, Healthcare, and Global Surface Temperature data, along with real-time API inputs. The focus is on understanding environmental factors contributing to asthma issues in California, with broad applications across healthcare, insurance, medical practitioners, and research teams.

Addressing the complexities of air quality monitoring, our project employs advanced data engineering and analytics techniques. The overarching goal is to craft a comprehensive solution that efficiently collects, processes, analyzes, and visualizes real-time air quality data. By achieving this, our aim is to empower stakeholders by providing accessible data in the data warehouse, facilitating its utilization for deriving valuable insights. Leveraging two additional datasets—Healthcare and air quality, GSOD data—our project addresses challenges associated with air quality monitoring and its profound impact on various domains

## Data Description
1. OpenAQ Archived Data:
Content: Air quality readings for various pollutants globally.
Significance: Crucial for a global perspective on air quality with data from diverse locations.

3. Healthcare Data: Asthma Data
Content: Dataset related to asthma, providing insights into health impacts of air pollution.
Significance: Essential for correlating air quality data with healthcare, supporting epidemiological studies.

5. ASDI Data: Global Surface Summary of the Day (GSOD)
Content: Comprehensive climate station data, including temperature, precipitation, and wind information.
Significance: Valuable for analyzing historical climate patterns, predicting future weather conditions on a global scale.


## Methodology: 
Our methodology is underpinned by a robust and scalable architecture designed to seamlessly integrate data from diverse sources and ensure its quality and accessibility. This architectural diagram visually represents the key components and their interactions within our data pipeline. 
We're leveraging AWS tools, utilizing Lambda for real-time OpenAq data, AWS Glue for seamless data transformations, and Amazon Redshift for our sophisticated data warehouse. Our design stands out with dimensional modeling and a star schema, ensuring seamless integration and high-powered analytics

Architecture Overview:

![Image](./architecture.png)


## Tableau Visualizations:
We harnessed Tableau to further visualize our data
Summary of Tableau analysis:

1. The analysis identifies the top 5 pollutants as the primary contributors to asthma-related fatalities in California pm2.5 seems to be the top pollutant for deaths.Pm2.5 emerges as a major pollutant affecting lungs, despite higher overall O3 values in certain counties.

![Image](./scatter.png)

2.	Los Angeles emerges as the leading county for Asthma Emergency Department (ED) visits, followed by Riverside, Orange, Alameda, Fresno, etc.

![Image](./hospitalizations.png)

3.	O3 and Co pollutants are identified as the key contributors to the rise in temperature levels. A notable trend is observed with increased pollutant levels during the first week of every month.

![Image](./dashboard_temp.png)

## Contributors:

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/phunswadkar>
            <img src=https://github.com/phunswadkar)?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Pallavi Hunswadkar/>
            <br />
            <sub style="font-size:14px"><b>Pallavi Hunswadkar</b></sub>
        </a>
    </td>
</tr>

  
<td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Bala-krishna-Batchu>
            <img src=https://github.com/Bala-krishna-Batchu?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Venkata Bala Krishna Batchu/>
            <br />
            <sub style="font-size:14px"><b>Venkata Bala Krishna Batchu</b></sub>
        </a>
    </td>    
</table>




