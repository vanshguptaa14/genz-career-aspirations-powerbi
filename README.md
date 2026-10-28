# Gen Z Career Aspirations – Power BI Dashboard

An interactive two-page Power BI dashboard that explores what Gen Z (born 1997+) expect from employers: career paths, manager style, feedback, reasons to leave, values alignment, and pay-versus-purpose trade-offs.

> **Data note:** The dataset is **simulated (synthetic)**. Only the India 2022–23 baseline is calibrated to a real career-aspirations survey (n = 3,343); all other markets, years, and trends are modelling assumptions. This project is for learning, dashboard design, and analysis practice. It must not be used for real hiring or policy decisions.

## Project Overview

- **Goal:** Turn a large survey dataset into clear, interactive visuals that answer HR-style questions about Gen Z career preferences.
- **Tool:** Power BI Desktop.
- **Data:** 25,000 survey responses, 18 countries, December 2022 – September 2026, 87 columns per response.

## Dashboard Pages

### 1. Manager Aspirations
- KPI cards: respondent count and starting salary (monthly, USD)
- Country slicer
- Long-term career path (donut chart)
- Manager style preference by gender (clustered bar chart)
- Feedback frequency preference by city type (column chart)
- Top reasons to leave an employer (treemap)
- Wellbeing support importance by survey year (line chart)

### 2. Mission Aspirations
- KPI cards: respondent count and values-alignment importance
- Country slicer
- Willingness to decline a job if values are misaligned (funnel chart)
- Values-alignment importance over time (line chart)
- Purpose vs. pay trade-off by survey year (100% stacked column chart)
- Top employee value proposition by year (ribbon chart)
- Values alignment vs. wellbeing support by field of study (scatter chart)

## Dataset

**File:** `GenZ_Career_Aspirations_Dashboard_slider_ready.xlsx`

| Sheet | Contents |
|---|---|
| Responses | 25,000 survey rows, 87 columns (the main table used by the dashboard) |
| Questionnaire | Every survey question, response type, and options |
| Markets & Waves | Number of responses by country and year |
| FX Rates | Currency conversion assumptions |
| Baseline Calibration | Comparison of the synthetic India baseline with the real 2023 survey |
| Trends, Dash_Calc, Dashboard | Excel-based trend and dashboard calculations |
| Read Me | Dataset description and the simulated-data notice |

The Responses sheet includes a `quality_status` column (valid responses plus flagged rows such as speeders, failed attention checks, and inconsistent salaries).

## Repository Structure

```
.
├── README.md
├── dashboard/
│   └── genz_aspiration_manager_and_mission_dashboards.pbix
├── data/
│   └── GenZ_Career_Aspirations_Dashboard_slider_ready.xlsx
└── screenshots/
    ├── manager_aspirations.png
    └── mission_aspirations.png
```

## How to Open

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
2. Download or clone this repository.
3. Open `dashboard/genz_aspiration_manager_and_mission_dashboards.pbix`.
4. If Power BI asks for the data source, point it to the Excel file in the `data/` folder and refresh.

## Screenshots

![Manager Aspirations](screenshots/manager_aspirations.png)
![Mission Aspirations](screenshots/mission_aspirations.png)

## Limitations

- The data is synthetic, so findings illustrate dashboard design and do not describe real Gen Z behaviour (apart from the India 2022–23 calibration).
- Results may differ depending on whether flagged responses are included or filtered out.

## Skills Demonstrated

Power BI dashboard design, data visualization, exploratory analysis, KPI cards and slicers, trend analysis across years and countries, and clear documentation.

## Author

**Vansh Gupta**
GitHub: [github.com/vanshguptaa14](https://github.com/vanshguptaa14)
LinkedIn: [linkedin.com/in/vansh-gupta-62a117305](https://linkedin.com/in/vansh-gupta-62a117305)
