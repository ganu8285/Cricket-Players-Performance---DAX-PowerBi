# Cricket Players Performance – DAX and Power BI

## Decoding Legends: A Visual Intelligence System for India's Cricket Titans

---

## Project Overview

This project is architected as a comprehensive Visual Intelligence System that transforms raw match statistics into a strategic decision-support framework. It deploys sophisticated statistical modeling to evaluate the longitudinal career arcs of elite athletes — MS Dhoni, Rohit Sharma, and Virat Kohli — synthesizing granular data points into a cohesive performance narrative.

The goal is to move beyond surface-level statistics and provide analysts, enthusiasts, and decision-makers with a structured, data-driven lens through which to assess player contribution, consistency, and competitive dominance.

---

## Player-Specific Dashboard Breakdown

### Virat Kohli – The Run Machine

- Visualizes batting dominance with over 24,000 runs and 77 international centuries, tracking consistency and form across all formats
- Highlights the Annual Scoring Trajectory to map peak performance windows and form cycles
- Identifies specific dominance patterns against key rivals, including Australia and England
- Enables format-wise comparison to contextualize career phases and milestone progression

---

### MS Dhoni – Captain Cool

- Analyzes wicket-keeping performance through detailed dismissal mode breakdowns, focusing on catches and stumpings
- Maps wicket-keeping efficiency against different nations to surface tactical contributions behind the stumps
- Showcases record-breaking keeping statistics with visual comparisons across career phases
- Supports evaluation of his impact as both a keeper and a match finisher

---

### Rohit Sharma – The Hitman

- Tracks his evolution into a world-class opening batsman, including highest score metrics and format-specific dominance
- Uses a Career Batting Progression timeline to illustrate how innings are constructed against top-tier opposition
- Highlights scoring patterns and big-match performances using trend-based visualizations
- Provides context around his transformation from a middle-order batsman to a record-setting opener

---

## Key Metrics Tracked

| Metric                    | Description                                                  |
|---------------------------|--------------------------------------------------------------|
| Total Runs                | Cumulative runs scored across all international formats      |
| Centuries and Half-Centuries | Milestone tracking across Test, ODI, and T20I formats     |
| Strike Rate and Average   | Efficiency and consistency indicators                        |
| Highest Score             | Peak individual innings performance                          |
| Dismissal Modes           | Breakdown of how batsmen and the keeper perform under pressure |
| Opponent-wise Analysis    | Performance segmented by rival nations                       |
| Annual Scoring Trajectory | Year-on-year run accumulation and form trends                |
| Career Batting Progression| Timeline-based progression from debut to present             |

---

## Tools and Technologies

| Tool / Technology  | Purpose                                          |
|--------------------|--------------------------------------------------|
| Power BI Desktop   | Dashboard design and interactive visualization   |
| DAX (Data Analysis Expressions) | Custom measures, KPIs, and calculated columns |
| Power Query (M)    | Data transformation and preparation              |
| Microsoft Excel / CSV | Source data storage and preprocessing        |

---

## DAX Highlights

The project makes extensive use of DAX for statistical modeling, including:

- **Cumulative Run Totals** – Rolling aggregations across career timelines
- **Strike Rate Calculations** – Dynamic measures filtered by format and opponent
- **Conditional KPIs** – Performance flags based on thresholds (e.g., centuries, high scores)
- **Time Intelligence Functions** – Year-over-year comparisons and trend analysis
- **Opponent Segmentation** – Filtered measures for nation-specific performance views

---

## Dashboard Structure

```
Root
├── Welcome / Navigation Page
├── Virat Kohli – Batting Analysis
│   ├── Career Run Summary
│   ├── Annual Scoring Trajectory
│   └── Opponent-wise Dominance
├── MS Dhoni – Wicket-Keeping Analysis
│   ├── Dismissal Mode Breakdown
│   ├── Catches vs Stumpings
│   └── Nation-wise Keeping Efficiency
└── Rohit Sharma – Opening Batsman Analysis
    ├── Career Batting Progression
    ├── Highest Score Metrics
    └── Format-wise Scoring Trends
```

---

## How to Use

1. Clone or download this repository
2. Open the `.pbix` file in Power BI Desktop
3. Navigate between player dashboards using the top navigation panel
4. Use slicers to filter by format (Test / ODI / T20I), year range, or opponent
5. Hover over visuals for detailed tooltips and drill-down options

---

## Getting Started

**Prerequisites:**
- Power BI Desktop (latest version recommended)
- Basic understanding of cricket statistics is helpful but not required

**Steps:**
```
1. Download the repository
2. Open CricketDashboard.pbix in Power BI Desktop
3. If prompted, refresh the data source connection
4. Explore player dashboards using the navigation controls
```

---

## Project Reference

Full source code, dataset, and project walkthrough are available on LinkedIn:  
[View Project on LinkedIn](https://www.linkedin.com/posts/ganesh-gangarde_%F0%9D%97%97%F0%9D%97%B2%F0%9D%97%B0%F0%9D%97%BC%F0%9D%97%B1%F0%9D%97%B6%F0%9D%97%BB%F0%9D%97%B4-%F0%9D%97%9F%F0%9D%97%B2%F0%9D%97%B4%F0%9D%97%B2%F0%9D%97%BB%F0%9D%97%B1%F0%9D%98%80-%F0%9D%97%94-%F0%9D%97%A9%F0%9D%97%B6%F0%9D%98%80%F0%9D%98%82%F0%9D%97%AE%F0%9D%97%B9-activity-7405282744148156416-prme?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEsbVUABoQdqHvkwNGYX6luFLstTeYdkS9g)

**Author:** Gangarde Ganesh  
**LinkedIn:** [linkedin.com/in/ganesh-gangarde](https://www.linkedin.com/in/ganesh-gangarde-/)

---

## Future Enhancements

- Expand player coverage to include bowlers (e.g., Bumrah, Ashwin)
- Integrate live data feeds via API for real-time dashboard updates
- Add predictive modeling to forecast future performance trends
- Include fielding metrics and all-round contribution scoring
- Build a comparative multi-player view for head-to-head analysis

---
