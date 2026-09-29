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

