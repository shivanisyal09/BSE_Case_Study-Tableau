# 📊 BSE Case Study – Tableau Dashboard

**Project Overview**  
This project uses Tableau to analyse and visualise the performance of blue-chip stocks listed on the Bombay Stock Exchange (BSE). It presents interactive views of price trends, company comparisons, and index benchmarking to turn raw stock-market data into actionable insights.

---

## 1) Business & Analytical Objective  
### Goal  
Provide an intuitive dashboard that enables investors, analysts or business learners to:  
- Understand how major BSE companies have performed over time.  
- Compare company-level trends with the benchmark index (Sensex).  
- Identify outperformers/under-performers and visualise dynamics via interactive charts.

### Key Questions Addressed  
- How have the top blue‐chip stocks moved over the selected period?  
- What is the relative performance of each company vis-à-vis the index?  
- Are there patterns or anomalies in price movements that can guide decision-making?

---

## 2) Technology & Tools  
- **Tableau Desktop / Tableau Public**: For dashboard design & interaction  
- **Data Source(s)**: <List the data source(s) here e.g., BSE website, Yahoo Finance, Company annual data>  
- **Data Preparation**: <Mention if you used Excel, Python, etc for cleaning or transformations>  
- **File Format**: `.twb` or `.twbx` workbook file is included along with supporting data files in `/data` directory.

---

## 3) Dashboard Walk-through  
### Visuals / Highlights  
- **Price Trend Analysis**: A line chart showing historical price evolution for selected companies and the index.  
- **Blue-Chip Comparative View**: Bar/heat-map chart comparing key metrics (e.g., % change) across companies.  
- **Smart Filters & Interactivity**: Dropdown menus for company selection, time-range sliders, hover tooltips for deeper insight.

### User Experience  
- Easy filter selection to switch companies or time periods.  
- Hovering over charts reveals additional detail (e.g., daily/weekly change).  
- Colour-coded views for quick visual understanding (e.g., red = decline, green = growth).

### Business Value  
- Enables decision-makers to quickly identify trends and anomalies.  
- Provides educators and students a visual, real-world finance dataset for learning.  
- Demonstrates how Tableau turns raw data into meaningful dashboards.

---

## 4) Data & Methodology  
- **Data Source 1**: <Name & link> — Description  
- **Data Source 2**: <Name & link> — Description  
- **Data Preparation Steps**:  
  1. Cleaned out nulls and duplicates.  
  2. Normalised date formats and merged company meta-data.  
  3. Calculated additional fields (e.g., % change, rolling averages).  
- **Assumptions & Limitations**:  
  - Data covers period from <Start Date> to <End Date>.  
  - Only considers companies listed at time of extraction.  
  - Does not account for dividends, splits, or corporate actions (unless included).

---

## 5) How to Use / Reproduce  
1. Download the workbook (`.twbx` or `.twb`) and the data folder from this repo.  
2. Open the file in Tableau (version <version used>).  
3. If data sources are relative paths, ensure the `/data` directory is in place.  
4. Use the filter pane to select company and time-period of interest.  
5. Export or publish to Tableau Public (optional) to share interactive version.

---

## 6) Screenshots  
Below are sample views from the dashboard.  
![Price Analysis]()  
![Blue-Chip Companies Overview](https://github.com/shivanisyal09/BSE_Case_Study-Tableau/blob/main/BSE%20Case%20Study%20-%20Blue%20Chip%20Companies.png)  

*Click the images to zoom for detail.*

---

## 7) Future Enhancements  
- Expand to include more companies and sectors (beyond blue chips).  
- Integrate fundamentals (P/E, market-cap, dividend yield) for richer analysis.  
- Build real-time or near-real-time data refresh via an API.  
- Publish an embedded version for web/portal access (via Tableau Public/Server).  
- Add user-driven annotation features (investor notes, event markers).

---

## 8) Acknowledgements  
- Data courtesy of the respective sources (see Data & Methodology above).  
- Inspiration from the repositories by Shivani Syal such as *Global Superstore Analytics*, *Spotify-Track Analysis Dashboard*, and *Finance Executive Dashboard*.  
- Thanks to the Tableau community for tips and tricks on interactivity and design.

---

## 📝 License  
This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.  
