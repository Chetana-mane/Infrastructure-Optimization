
---

# EV Infrastructure Optimization Project

## Objective and Strategic Direction

**Objective**: Transition from internal combustion engine (ICE) vehicles to electric vehicles (EVs), focusing on strategies to establish sustainable and accessible EV infrastructure.

**Strategic Decisions**:
- Infrastructure development
- Policy incentives
- Market trends
- Social impact
- Technology adoption
- Stakeholder engagement

---

## Operational Research and AI/ML Integration

- **Key Techniques**: Genetic algorithms, Mixed-Integer Linear Programming (MILP), GIS-based Multi-Criteria Decision Analysis (MCDA), and simulated annealing were utilized to determine optimal EV charging station locations.
- **AI/ML Applications**: Leveraged AI/ML to enhance OR models, focusing on battery management, strategic planning, energy optimization, and supporting policy-making.

---

## Data Collection and Preprocessing

- **Data Sources**: Collected geographic data on petrol stations in Southampton, UK, using coordinates from Google Maps, and validated via multiple mapping tools.
- **Data Processing**: Cleaned and standardized data, converted postcodes for calculations, and generated distance matrices for analysis.

---

## Distance Matrix Calculations

- **Euclidean Distance Matrix**: Used to analyze spatial proximity patterns.

  ![Euclidean Distance Matrix Heatmap](https://github.com/user-attachments/assets/5b47cafa-9c98-4894-b1ef-ca684318d3b8)

- **Haversine Distance Matrix**: Applied to calculate real-world distances on Earth’s surface, supporting realistic infrastructure planning.

  ![Haversine Distance Matrix Heatmap](https://github.com/user-attachments/assets/14283f71-8edc-45e6-b310-e2df0462bc1a)

---

## Clustering Analysis

- **Cluster Visualization**: Employed Principal Component Analysis (PCA) for clustering, identifying high-density (potential closure) and low-density (critical coverage) zones.

  ![PCA Plot - Clustering Using ED](https://github.com/user-attachments/assets/e0476407-96f6-4a43-9f8c-38cae007c624)
  ![PCA Plot - Clustering Using Euclidean Distance](https://github.com/user-attachments/assets/bca5cafb-5a68-4401-b50d-1edfeb6056ea)

- **Cluster Density Insights**: Highlighted high-density clusters for EV conversions and low-density areas needing improved coverage.

  ![Stations Names under Each Cluster](https://github.com/user-attachments/assets/6c73befb-1a6a-4a3e-a492-fb4aead21791)
  ![Cluster Coverage Density](https://github.com/user-attachments/assets/4af5241a-0c15-4361-8751-1891872ded83)

---

## Facility Location Optimization Model

- **Objective**: Created a model to close 60% of petrol stations while maintaining maximum coverage for ICE vehicles.
- **Model Constraints**: Geographic proximity, minimum station count, and specific station closures were considered to maximize area coverage.

  ![Optimization Model Table](https://github.com/user-attachments/assets/0a8b9e71-1542-4892-865a-3d537da1df20)

---

## Optimization Results and Sensitivity Analysis

- **Optimal Coverage Distance**: Achieved optimal coverage at 2.5 km, encompassing 15 districts with 8 strategically chosen stations.

  ![Sensitivity Analysis Results](https://github.com/user-attachments/assets/eefbf334-ddc0-45bb-af67-590174df8d2b)

- **Key Locations**: Identified critical stations to optimize network distribution, minimizing redundancy and maximizing reach.

  ![Optimal Petrol Stations by District and Distance](https://github.com/user-attachments/assets/c0079396-6b7c-4a59-ac00-71f17d635f2b)

---

## Visualization and Recommendations

- **Maps and Heatmaps**: Created visualizations of distance matrices, cluster distributions, and optimized station locations to assist in decision-making.

  ![Optimal Coverage Map](https://github.com/user-attachments/assets/07509e7a-67c0-4305-a3e6-82ba89458384)
  
  ![Open Stations Map (2.5 km Radius)](https://github.com/user-attachments/assets/315f8131-8951-42b7-9172-6887a05bcbd9)

- **Recommendations**: Suggested optimal configuration, ongoing monitoring, and adjustments based on emerging trends.

---

> This project presents a comprehensive approach to EV infrastructure optimization, integrating operational research techniques with AI/ML, clustering analysis, and facility location optimization to aid strategic decision-making in transitioning to EV infrastructure.

---
