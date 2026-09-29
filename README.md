# Los Angeles Crime Analytics Dashboard

An interactive **Power BI dashboard** for analyzing crime patterns in Los Angeles.  
The project transforms and analyzes crime data to identify trends across time, geography, crime types, victims, reporting delays, and data quality.

## 📊 Project Overview

This project was created as a portfolio-level Data Analytics project using **Power BI**.

The dashboard provides an interactive view of Los Angeles crime data and allows users to explore:

- Crime trends over time
- Crime distribution by geographical area
- Crime categories and descriptions
- Victim demographics
- Crime reporting delays
- Crime status and case information
- Data completeness and quality
- Geographic crime patterns using latitude and longitude

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and analytical calculations
- **Data Visualization**
- **GitHub** – Project documentation and version control
- **Claude** - used for creating interactive and useful measures and calculations on Dataset

## 📁 Project Structure

```text
Los-Angeles-Crime-Analytics/
│
├── Cleaned Dataset/
│   └── Cleaned crime dataset
│
├── Screenshots/
│   ├── Overview
│   ├── Crime Trends
│   ├── Geography
│   ├── Victims & Crime
│   └── Reporting & Quality
│
├── video/
│   └── Dashboard demonstration
│
├── Los_Angeles_Crime_Analytics.pbix
│
└── README.md
```
## 📋 Cleaned Dataset – Column Description

The dataset was cleaned and prepared for analysis in Power BI. 
Unnecessary, redundant, or highly incomplete fields were removed during the data-cleaning process.

| Column | Description |
|---|---|
| `Date Rptd` | Date on which the crime was reported to the police. |
| `DATE OCC` | Date on which the crime occurred. |
| `Reporting Delay Days` | Calculated number of days between the occurrence date and reporting date. |
| `TIME OCC` | Time at which the crime occurred, maintained in 24-hour format. |
| `AREA NAME` | Name of the LAPD area associated with the incident. |
| `Rpt Dist No` | Reporting district number associated with the incident. |
| `Crm Cd Desc` | Description of the primary crime type. |
| `Vict Age` | Recorded age of the victim. |
| `Vict Sex` | Recorded sex of the victim. |
| `Vict Descent` | Recorded descent category of the victim. |
| `Premis Desc` | Description of the type of premise/location where the crime occurred. |
| `Weapon Desc` | Description of the weapon involved, when recorded. |
| `Status Desc` | Description of the current case status. |
| `LOCATION` | General location where the crime occurred. |
| `LAT` | Latitude coordinate of the crime location. |
| `LON` | Longitude coordinate of the crime location. |


## 🔍 Key Insights

- 📊 **269K total crime incidents** are represented in the analyzed dataset, including **250K incidents from complete years** and approximately **19K incidents from the partial 2024 period**.

- ⏱️ **65.4% of crimes were reported on the same day**, while only **2.7% were reported more than 30 days after occurrence**.

- 📅 The overall **average reporting delay was 6.0 days**. The average delay decreased consistently from approximately **8.8 days in 2020 to 2.1 days in 2024**.

- 📍 **Southwest** was identified as the area with the highest number of reported crime incidents.

- 🕐 Crime occurrence was highest during the **Afternoon (12–17)** and **Evening (18–23)** periods, with both accounting for substantially more incidents than the Night period.

- 📈 Annual reported crime counts were approximately **71K in 2020, 61K in 2021, 61K in 2022, and 57K in 2023**. The **2024 figure is approximately 19K because the dataset covers only part of the year**.

- 🗺️ **99.92% of location records contained valid geographic coordinates**, while only **0.08%** were identified as placeholder coordinates, supporting reliable geographic visualization.

- 🏷️ The Part 1–2 crime distribution shows a dominant category containing approximately **172K incidents (64.19%)**, followed by **53K (19.74%)**, **40K (14.98%)**, and **2K (0.72%)** across the displayed categories.

- 👥 The overall average recorded victim age was **38.7 years**.

- 📋 The dashboard identifies **130 distinct crime categories**, enabling analysis across a broad range of reported offenses.

