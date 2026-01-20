# Netflix Content Strategy Overview Dashboard

## Introduction
This project presents a Power BI dashboard designed to analyze Netflix’s content strategy using a cleaned dataset of available titles. The dashboard provides insights into Netflix’s content composition, audience targeting, genre focus, geographic production trends, and historical growth patterns. The objective is to understand how Netflix structures its content library to support global reach, audience preferences, and long-term sustainability.

---

## Objectives
1. To analyze Netflix’s content portfolio strategy by evaluating the balance between Movies and TV Shows and the concentration of content across genres.
2. To assess Netflix’s audience and market targeting approach through the distribution of content ratings and country-wise content availability.
3. To evaluate the freshness and sustainability of Netflix’s content library by analyzing the release-year composition of available titles.

---

## Dataset Overview
- Total titles analyzed: 5,333
- Content types: Movies and TV Shows
- Latest release year in the dataset: 2021
- Data cleaning involved removal of duplicates, missing values, and corrupted rows using Python.

---

## Key Insights

### 1. Library Composition
Netflix’s content library is overwhelmingly dominated by feature-length films rather than serialized content.
- Massive Movie Bias: Movies account for 97.24% (5,185 titles) of the library, while TV Shows represent only 2.76% (147 titles).
- Total Scale: The dataset tracks 5,333 titles, highlighting Netflix’s strong focus on movie-based content delivery.

---

### 2. Audience & Genre Strategy
Netflix’s content strategy is clearly oriented toward mature audiences with a strong emphasis on globally appealing genres.
- Mature Audience Focus: The most common content rating is TV-MA, followed by TV-14, indicating prioritization of adult and teenage viewers.
- Top Genres: International Movies and Dramas dominate the library, reflecting a global-local strategy that supports cross-border content consumption.
- Portfolio Variety: Genres such as Comedies, Action & Adventure, and Independent Movies also feature prominently, ensuring diversity in content offerings.

---

### 3. Production Origins
While Netflix remains US-centric, it has made significant investments in international markets.
- Dominant Producer: The United States is the leading producer of content in the dataset.
- India’s Role: India emerges as the second-largest content producer, outperforming other major markets such as the UK, Canada, and Spain. This highlights Netflix’s strategic focus on the rapidly growing Asian market.

---

### 4. Historical Trends (Release Year Analysis)
The release-year analysis reveals Netflix’s rapid expansion phase.
- Exponential Growth: Content production increased sharply starting around 2014, reaching a peak between 2017 and 2018.
- Recent Decline: A noticeable drop in releases during 2020–2021 likely reflects global production disruptions caused by the COVID-19 pandemic, as well as possible incomplete data for the final year.

---

## Summary of Key Metrics

| Metric | Value |
|------|------|
| Dominant Format | Movies (97%) |
| Primary Audience | Mature (TV-MA) |
| Key Growth Period | 2015–2019 |
| Top Secondary Market | India |

---

## Repository Contents
- `netflix.pbix` – Power BI dashboard file  
- `Netflix_dashboard.png` – Screenshot of the dashboard  
- `README.md` – Project documentation

---

## Conclusion
The dashboard highlights Netflix’s strong preference for movie-based content, mature audience targeting, and global expansion strategy, particularly in emerging markets like India. The historical trends further demonstrate Netflix’s rapid growth phase prior to recent global disruptions, offering valuable insights into the platform’s evolving content strategy.

