# 📺 YouTube Trending History Analysis

Data-driven analysis of YouTube’s historical trending videos to uncover **consumption patterns** by **category** and **country**, aimed at informing **advertising campaign planning** (audience targeting, budget allocation, and content mix). 

---

## 🔎 Overview

This project consolidates a time-based dataset of trending videos and provides a dashboard with:
- **Stacked Area Chart:** daily trend volume by category (temporal evolution)
- **Circular Distribution:** relative share of trending videos by country/region
- **Correspondence Table:** category ↔ country cross-analysis for targeting decisions

**Primary objective:** deliver **actionable intelligence** for media and marketing teams to optimize category focus by market and adjust spend using historical trend dynamics.

---

## 📂 Data

- `trending_by_time.csv` — pre-aggregated trending history used to build the visuals (time series by day, category, and geography).

> The CSV powers the temporal, geographic, and cross-category analyses described in the dashboard.

---

## 📊 Dashboard

- **Public Tableau:**  
  `YouTube Video Trending History Dashboard`
  https://public.tableau.com/views/YouTubevideotrendinghistory/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

**How visuals work together:** the area chart explains **when** categories rise/fall, the circular chart shows **where** attention concentrates, and the correspondence table reveals **what** to prioritize in each market. 

---

## 🔑 Key Insights (Examples)

1) **Top categories**: *Entertainment* dominates, followed by *People & Blogs*, *Music*, and *News & Politics*. 
2) **Regional distribution**: five main markets concentrate volume — US (~23.75%), France (~22.18%), Russia (~21.68%), India (~21.58%), Japan (~10.82%).  
3) **US profile**: Entertainment leads (≈19,638 videos), then Music (≈12,874), Howto & Style (≈8,280), Comedy (≈6,870), People & Blogs (≈6,122).   
4) **Cross-regional differences**: India shows outsized Entertainment (≈32,924 vs 19,638 in US); Russia favors People & Blogs more than the US. 

**Strategic takeaway:** leverage Entertainment globally, then **localize** secondary categories by market; rebalance budgets as **daily trends** shift. 

---

## 🧭 Use Cases

- **Media planning:** prioritize categories by market before flighting.
- **Budget allocation:** weight spending according to regional trend shares.
- **Content strategy:** adapt creatives to local category preferences. 

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your_username>/<your_repo>.git
   cd <your_repo>
