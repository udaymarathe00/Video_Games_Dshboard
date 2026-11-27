# PixelVault: Video Games Sales Dashboard (Power BI)

An interactive 3-page Power BI dashboard that analyses video game sales from 1980 to 2024: which genres, platforms, publishers and developers sell the most, where the games sell, and how sales changed over the years. Built with a futuristic gaming theme (black background, neon green, cyan, purple and orange accents).


<img width="2201" height="1238" alt="page1-overview" src="https://github.com/user-attachments/assets/a1164574-b43a-4147-9175-0963ae53924a" />


---

## Business questions this dashboard answers

- How many games sold in total, and how are sales spread across the years?
- Which genres and platforms sell the most?
- Which regions bring the most sales?
- Which publishers and developers are the top performers?
- What are the best-selling games of all time?
- Do games with higher critic scores sell more?

---

## Dataset

| Item | Detail |
|---|---|
| Source file | `Video Games Sales 1980-2024 (Raw).csv` |
| Raw size | 64,016 rows and 14 columns |
| Used in the report | 18,919 games that have sales figures |
| Sales unit | Millions of units |
| Coverage | Games released from 1980 to 2024, across genres, platforms, publishers, developers and four sales regions (North America, Europe, Japan, Other) |

---

## Dashboard pages

### Page 1: Overview
Headline numbers and the big picture of the market.



<img width="2201" height="1238" alt="page1-overview" src="https://github.com/user-attachments/assets/add3940e-2d54-4228-b981-dd36f2aa01b4" />


- KPI cards: **Total Sales (6,605)**, **Games With Sales (18,919)**, **Top Genre (Sports)** and **Top Platform (PS2)**
- Area chart of **Sales by Release Year**
- Donut chart of **Sales by Region**
- Bar charts for **Top Genres** and **Top Platform**
- **Top 10 Games** table with a total

### Page 2: Genres & Platforms
How genres and platforms relate to each other and to regions.


<img width="2201" height="1238" alt="page2-genres-platforms" src="https://github.com/user-attachments/assets/f0385aa9-1ad2-48f3-ad6a-859b30b13340" />


- **Genre and Platform Heatmap**: a matrix of genre against platform, with colour showing sales volume
- **Genre Sales by Region**: stacked bars for North America, Japan, Europe and Other
- **Platform Sales by Year**: line chart showing when each console generation peaked
- A ranked bar chart of the top studios

### Page 3: Publishers & Titles
The companies and the games behind the sales.


<img width="2201" height="1238" alt="page3-publishers-titles" src="https://github.com/user-attachments/assets/fa616e97-8792-4558-a77b-3c4379f9dde3" />


- **Best Selling Games** list with publisher
- **Top Publisher** bar chart
- **Top Developers** column chart
- **Critic Score vs Sales** bubble chart by genre
- Spotlight card with the best-selling game and the top publisher

---

## Interactivity

- Custom **page navigation buttons** at the top of every page (Overview, Genres & Platforms, Publishers & Titles)
- **Three dropdown filters** at the top of every page, which update all the visuals on the page
- Cross-filtering: clicking any bar, slice or bubble filters the other visuals

---

## Key insights

- **Total sales are 6,605 million units** across 18,919 games.
- **Sports is the top genre (1,187)**, followed by Action (1,126) and Shooter (995).
- **PS2 is the top platform (1,028)**, ahead of the Xbox 360 (860) and PS3 (840).
- **North America drives about half of all sales (50.68%)**. Europe adds 29.04%, Japan 10.41% and the rest of the world 9.86%.
- **Sales peaked around 2008** at roughly 500 million units a year and have declined since.
- **Grand Theft Auto V is the best-selling game with 64.3 million units.** Seven of the Top 10 games are Call of Duty titles, and the Top 10 together sold 304 million.
- **Activision is the top publisher (723)**, followed by Electronic Arts (644), EA Sports (486) and Ubisoft (463).
- **EA Canada is the top developer (276)**, ahead of EA Tiburon (178) and Ubisoft Montreal (173).
- **Shooter games on the Xbox 360 are the strongest genre and platform pair in the heatmap (231).**

---

## Design

| Element | Choice |
|---|---|
| Theme | Futuristic gaming HUD |
| Background | Black with soft glass panels |
| Main accent | Neon green `#00FF9C` |
| Supporting colours | Cyan `#00E5FF`, purple `#9D4EDD`, orange `#FF9F1C` |
| Navigation | Pill buttons at the top, with the active page highlighted |

---

## Repository contents

```
.
├── README.md
├── report/        Power BI file (.pbix)
├── data/          Source CSV
└── screenshots/   Dashboard page images
```

To open the report, download the `.pbix` file from the `report` folder and open it in **Power BI Desktop**.

---

## Tools used

- **Power BI Desktop**: data modelling, DAX measures and report design
- **Power Query**: data cleaning and shaping
- **DAX**: measures for sales, rankings and KPIs

---

## Author

**Uday Marathe**
Vadodara, Gujarat

- LinkedIn: [linkedin.com/in/uday-marathe](https://linkedin.com/in/uday-marathe)
- Email: udaymarathe00@gmail.com
- GitHub: [udaymarathe00](https://github.com/udaymarathe00)
