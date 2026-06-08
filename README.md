# 🎬 SS Rajamouli — Box Office Analytics Dashboard



![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**A cinematic, data-driven deep dive into the career of India's greatest filmmaker**

[View Live Dashboard](https://public.tableau.com/app/profile/phani.naidu.kondapalli/viz/SSRAnalysis-1/Dashboard1) &nbsp;·&nbsp;



---

## Table of Contents :

- [Project Overview](#-project-overview)
- [Why SS Rajamouli?](#-why-ss-rajamouli)
- [Dashboard Preview](#-dashboard-preview)
- [Key Insights](#-key-insights)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Dashboard Design Decisions](#-dashboard-design-decisions)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [Challenges & Learnings](#-challenges--learnings)
- [Future Improvements](#-future-improvements)
- [Connect with Me](#-connect-with-me)

---

## Project Overview

This project is a **one-page interactive Tableau dashboard** that analyzes the complete filmography of acclaimed Indian filmmaker **SS Rajamouli** — spanning from his debut in 2001 to his global blockbuster RRR in 2022.

The dashboard answers questions like:
-  How did Rajamouli's box office numbers grow across his career?
-  Which films delivered the highest Return on Investment (ROI)?
-  What verdict does each film carry — Hit, Blockbuster, or Industry Hit?
-  How did his budgets scale as his ambitions grew globally?
-  Is there a correlation between IMDb ratings and box office collections?

---

## Why SS Rajamouli?

SS Rajamouli is not just a filmmaker — he is a **phenomenon**. With a 100% success rate across 12 films and the only Indian director to have back-to-back ₹1000 Cr+ grossers, his career is a masterclass in consistent excellence. His journey from a ₹3 Cr Telugu film in 2001 to a globally acclaimed ₹1810 Cr blockbuster makes for a uniquely compelling data story.

---

## Dashboard Preview

###  Main Dashboard — Career Summary Analysis
![SS Rajamouli Dashboard](https://github.com/user-attachments/assets/0fc66a69-ef53-4481-9723-9dec216bbf83)

> The landing page features a **cinematic dark theme** with SS Rajamouli's portrait, a signature quote, key identity cards, and an interactive navigator bar with **10 chart tiles** — each clickable to jump directly to its respective worksheet.


![dashboard 2](https://github.com/user-attachments/assets/8d034b23-566b-4667-8e11-270fa5f92ca2)


### 📊 Individual Chart Worksheets
> 📌 *Replace the image paths below with your actual worksheet screenshots*

| Box Office vs Year | Budget vs Collections | Films & Verdict |
|---|---|---|
| ![Box Office](https://github.com/user-attachments/assets/4a55aead-aae1-4fe2-8706-f2df071d3913) | ![Budget](https://github.com/user-attachments/assets/2bfb7144-e2ea-4607-ba38-d238e1b3a106) | ![Verdict](https://github.com/user-attachments/assets/140a0fe5-4c56-4d83-a6fc-14ac0fc8f125) |

| Budget vs ROI | Career Timeline | Legacy Impact |
|---|---|---|
| ![ROI](https://github.com/user-attachments/assets/d6e94fc9-d4e5-4287-8267-e8d8f1e9c748) | ![Timeline](https://github.com/user-attachments/assets/259b41c7-ac64-4b9e-a0fd-f7c5d10f4049) | ![Legacy](https://github.com/user-attachments/assets/844a46b3-4089-443a-8116-130c2f0276d2) |



---

##  Key Insights

> Derived directly from the dashboard analysis

###  Career Growth
- Rajamouli's box office collections grew by **over 60,000%** from Student No.1 (₹12 Cr) to Baahubali 2 (₹1810 Cr)
- His budget investments scaled proportionally — from ₹3 Cr in 2001 to ₹550 Cr in RRR (2022)

###  Best ROI Films
| Film | Budget | Collection | ROI |
|---|---|---|---|
| Baahubali: The Conclusion | ₹250 Cr | ₹1810 Cr | **624%** |
| Baahubali: The Beginning | ₹136 Cr | ₹600 Cr | **341%** |
| Student No.1 | ₹3 Cr | ₹12 Cr | **300%** |

###  Verdict Distribution
- **3 Industry Hits** — Films that redefined Indian cinema (Magadheera, Baahubali 1 & 2)
- **5 Blockbusters** — Consistent mega-successes
- **2 Super Hits** — Strong commercial performers
- **2 Hits** — Solid returns
- **0 Flops** — A remarkable 100% success rate across 22 years

###  Rating vs Revenue
- IMDb ratings range from **6.8 to 8.2** — consistently strong across all films
- Higher budgets correlate strongly with both higher ratings AND higher collections
- Maryada Ramanna (7.8 rating, ₹14 Cr budget) is the outlier — highest rating per rupee spent

###  Era-wise Career Breakdown
| Era | Films | Total Box Office |
|---|---|---|
| Early Career (2001–2005) | 4 | ₹68.5 Cr |
| Growth Phase (2006–2007) | 2 | ₹48.25 Cr |
| Breakthrough (2009–2010) | 2 | ₹179 Cr |
| Peak Phase (2012–2017) | 3 | ₹2452 Cr |
| Global Era (2022) | 1 | ₹1275 Cr |

---

##  Dataset

The dataset was **manually curated** from public sources including Wikipedia, Box Office India, and Sacnilk.com — since no single API provides complete Telugu film financial data.

### Columns
| Column | Description |
|---|---|
| `Movie_Name` | Title of the film |
| `Year` | Release year |
| `Language` | Primary language of release |
| `Lead_Actor` | Main cast |
| `Genre` | Film genre |
| `Budget_Crore` | Production budget in Indian Rupees (Crore) |
| `Box_Office_Crore` | Worldwide box office gross (₹ Crore) |
| `ROI_Percentage` | Return on investment — auto-calculated |
| `Verdict` | Hit / Super Hit / Blockbuster / Industry Hit |
| `Era` | Career phase label |
| `Awards` | Notable awards won |
| `IMDb_Rating` | IMDb user rating |
| `Runtime_Minutes` | Film duration |
| `Producer` | Film producer |

### Data Sources
-  [Box Office India](https://www.boxofficeindia.com)
- [Wikipedia — SS Rajamouli filmography](https://en.wikipedia.org/wiki/S._S._Rajamouli_filmography)
-  [IMDb](https://www.imdb.com)
-  [Sacnilk](https://sacnilk.com)

---

##  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau Public** | Primary dashboard and visualization tool |
| **Microsoft Excel** | Data structuring, ROI formula calculations, multi-sheet organization |
| **Python (pandas)** | Initial data fetch exploration via TMDb API |
| **TMDb API** | Reference for metadata (ratings, genres, release dates) |
| **GitHub** | Version control and project hosting |

---

##  Dashboard Design Decisions

The dashboard follows a **Dark Cinematic theme** — inspired by OTT platforms and film festival aesthetics — to match the subject matter.

### Color Palette
| Element | Color | Hex |
|---|---|---|
| Main Background | Near Black | `#0D0D0D` |
| Panel / Sheet Background | Dark Navy | `#1A1A2E` |
| Chart Plot Area | Card Blue | `#16213E` |
| Primary Bars (Box Office) | IMDb Gold | `#F5C518` |
| Secondary Bars (Budget) | Steel Blue | `#4A90D9` |
| Highlight / Peak Value | Cinematic Red | `#E50914` |
| Gridlines | Subtle Navy | `#2A2A4A` |

### Verdict Color Coding
| Verdict | Color |
|---|---|
| Industry Hit | `#E74C3C` Red |
| Blockbuster | `#8E44AD` Purple |
| Super Hit | `#2980B9` Blue |
| Hit | `#27AE60` Green |

### Typography
- **Tableau Book** for body text and axis labels
- Font sizes: 24–28px for KPI values, 12–14px for labels


### Interactive Navigator Bar
One of the standout UX features of this dashboard is the **custom navigation system** built directly inside Tableau:

- The main landing dashboard contains **10 clickable chart tiles** arranged in a 2-row grid
- Each tile represents a specific worksheet — Box Office vs Year, Budget vs Collections, Films & Verdict, Budget vs ROI, Total Films, Total Awards, Average IMDb Rating, Highest Grossing Movie, Career Timeline, Legacy Impact
- Clicking any tile uses Tableau's **Navigate to Sheet** button action to jump directly to that worksheet
- A **back button** on each worksheet brings the user back to the main dashboard
- This creates a seamless, app-like experience inside Tableau Public — no scrolling, no confusion

---

## How to Use

### Option 1 — View Online
Click the **[Live Dashboard](https://public.tableau.com/app/profile/phani.naidu.kondapalli/viz/SSRAnalysis-1/Dashboard1)** link above to explore the interactive Tableau Public dashboard directly in your browser.

### Option 2 — Run Locally
1. Clone this repository
   ```bash
   git clone https://github.com/phaninaidu2612-analytics/ss-rajamouli-dashboard
   ```
2. Open `ss_rajamouli_filmography.xlsx` in Excel to explore the raw data
3. Download [Tableau Public](https://public.tableau.com/en-us/s/download) (free)
4. Open the `.twbx` Tableau workbook file included in this repo
5. The dashboard will load with all data connected

---


## Challenges & Learnings

### Challenges Faced
- **No API for Telugu box office data** — TMDb and OMDb have very limited financial data for regional Indian films. Had to manually curate budget and collection data from multiple sources and cross-verify.
- **Tableau string centering** — Centering a dimension/string KPI card in Tableau requires changing the Mark type to unlock alignment options — not intuitive for beginners.
- **Multi-sheet Excel in Tableau** — Tableau Public can connect to multiple sheets from the same Excel file but they need to be used as separate data sources or joined, since the Filmography and Summary sheets have different structures.
- **Dynamic calculations** — Used Tableau LOD (Level of Detail) expressions like `{ FIXED : MAX([Box Office]) }` to dynamically surface the highest grossing film without hardcoding values.

### Key Learnings
- **LOD Expressions** are incredibly powerful for dynamic KPI cards — `FIXED`, `INCLUDE`, and `EXCLUDE` unlock calculations that go beyond the current view level
- **Dark themed dashboards** require careful layering — Dashboard background → Sheet background → Pane background each needs its own color to create visual depth
- **Sorting dimensions by a measure** (sorting movies by Year instead of alphabetically) requires using the Sort dialog on the pill, not the axis sort button
- **Verdict color coding** in Tableau requires manually assigning hex codes in Edit Colors — Tableau doesn't accept `#` prefix, just the raw hex

---

## Future Improvements

- [ ] Add **OTT performance data** (Netflix/Amazon viewership estimates)
- [ ] Include **opening weekend** vs **lifetime collection** breakdown
- [ ] Add **comparison mode** — Rajamouli vs other top Indian directors (Shankar, Mani Ratnam)
- [ ] Integrate **real-time data refresh** via TMDb API + Python automation
- [ ] Add **audience demographics** data if available
- [ ] Mobile-optimized version of the dashboard

---

## Connect with Me

If you found this project interesting or have suggestions, feel free to reach out!



[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phani-pravyakth-naidu-kondapalli-89200a1a1)
[![Tableau Public](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://public.tableau.com/app/profile/phani.naidu.kondapalli)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/phaninaidu2612-analytics)




---



**⭐ If this project helped or inspired you, please give it a star!**

*Made with ❤️ and a deep love for Telugu cinema*
