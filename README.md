# Exploring Cell Phone Metadata

A Tableau case study exploring the movements and daily routines of Australian journalist **Will Oendon** through his voluntarily shared **cell phone metadata**. The project demonstrates how location-based data can reveal patterns about an individual’s life, including their **home, work, commute, and travel habits**.

---

## 📊 Project Overview

In this analysis, we examine a dataset containing over 10,000 records of Will Oendon’s mobile connections to cell towers across Australia from **2014–2015**.  
The goal is to visualize and interpret his location data to uncover personal behavioral patterns — a compelling example of how much information metadata alone can reveal.

This project involves connecting, cleaning, and preparing the data in Tableau, followed by exploratory mapping to extract insights.

---

## 🧠 Case Context

In 2014, Australian journalist **Will Oendon** conducted a public experiment to demonstrate how cell phone metadata can be used to infer personal details.  
By sharing his own connection records — including timestamps and cell tower locations — he highlighted privacy risks associated with digital footprints.  
This Tableau project re-creates a similar exploration for analytical and educational purposes.

---

## 🧩 Key Steps

### 1. Connecting the Data Source
- Imported the provided CSV file containing metadata records.
- Set connection type to **Text File**.
- Reviewed 13 fields, including latitude, longitude, timestamp, and connection type.

### 2. Initial Data Quality Checks
- Confirmed **10,476 total records** in the dataset.
- Verified **no duplicates** by comparing total and distinct ID counts.
- Used the `'Number of Records'` field as a measure of connection frequency.

### 3. Preparing Geographic Data
- Identified incorrect **decimal separators** (commas instead of dots) in latitude and longitude.
- Adjusted locale settings to ensure Tableau recognized them as numeric values.
- Assigned geographic roles:
  - Latitude → *Latitude*
  - Longitude → *Longitude*
- Enabled geographic plotting of cell towers for mapping movements.

---

## 🌍 Insights & Findings

| Insight | Description |
|----------|-------------|
| 📱 Smartphone adoption | Will got his smartphone in **September 2014**. |
| 🏠 Home location | He lives **north of Sydney**. |
| 💼 Workplace | He works in **downtown Sydney**. |
| 🚗 Commute patterns | Regular commute at around **9:00 AM**, sometimes working remotely or in shifts. |
| ✈️ Travel behavior | At least **two international trips** during 2014–2015. |
| 🎄 Holiday visit | Spent **Christmas in Tasmania** visiting family. |
| 🌤️ Lifestyle hint | “Will needs to go out more.” (Based on recurring geolocation patterns.) |

---

## 🧹 Data Summary

- **Records:** 10,476 total observations  
- **Duplicates:** None detected  
- **Fields:** 13 (including timestamps, tower coordinates, and communication type)  
- **Communication Types:** SMS, phone data, and internet usage  
- **Data Period:** 2014–2015  


---

## 📍 Interactive Dashboards

Interactive dashboards are published on Tableau Public:

🔗 [Will's Work and Commute](https://public.tableau.com/shared/WCJ99TSW7?:display_count=n&:origin=viz_share_link)  

---

