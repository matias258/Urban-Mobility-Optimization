# Urban Mobility Optimization: Strategic Hubs in Buenos Aires
### Applying Graph Theory & Clustering to Logistics Expansion

## Project Overview
This project models an optimized entry strategy for a transportation service in **Buenos Aires (CABA)**. By analyzing historical transport infrastructure, it identifies the best locations to stage a fleet to minimize **ETA** and maximize coverage.

## Key Features
* **Optimal Localization:** Uses **K-Means Clustering** to solve the "Location-Allocation" problem, identifying 10 strategic supply hubs.
* **Graph Analysis:** Models the city as a network using **NetworkX** to identify critical nodes via **Centrality Metrics**.
* **Interactive Mapping:** Dynamic visualization with **Folium** to overlay the optimized network on the real urban grid.

## Tech Stack
* **Python** (Pandas, Scikit-Learn, NetworkX)
* **Visualization:** Folium (Interactive Maps), Seaborn & Matplotlib.

## Methodology
1.  **Data Proxy:** Used open data of taxi stops as a validated proxy for high-demand zones.
2.  **Clustering:** Identified "Gravity Centers" of supply to minimize distance to passengers.
3.  **Topology:** Built a connectivity graph to analyze fleet rebalancing feasibility between hubs.

## Structure
* `notebooks/expansion_strategy.ipynb`: Full analysis.
* `outputs/red_transporte_grafo.html`: Interactive map result.
* `data/paradas_taxis.csv`: Source dataset.

## Impact
This framework provides a **data-driven Go-to-Market strategy**, replacing intuition with mathematical optimization to ensure operational efficiency from Day 1.

---

 ## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://tinyurl.com/matiasgangui)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matias-gangui-660654175/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/matias258)
