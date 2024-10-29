Here are summary points for showcasing the project:

1. **Objective and Strategic Direction**
   - **Objective**: Transition from ICE vehicles to electric vehicles (EVs), focusing on strategies for sustainable and accessible EV infrastructure.
   - **Strategic Decisions**: Covered aspects like infrastructure development, policy incentives, market trends, social impact, technology, and stakeholder engagement.


2. **Operational Research and AI/ML Integration**
   - **Key Techniques**: Used genetic algorithms, mixed-integer linear programming (MILP), GIS-based MCDA, and simulated annealing for optimally locating EV charging stations.
   - **AI/ML Applications**: Enhanced OR models with AI/ML for battery management, strategic planning, energy optimization, and policy-making support.

3. **Data Collection and Preprocessing**
   - **Data Sources**: Gathered geographic data on petrol stations in Southampton, UK, including coordinates from Google Maps and validated through multiple mappings.
   - **Data Processing**: Cleaned and standardized data, converted postcodes for mathematical calculations, and developed distance matrices.

4. **Distance Matrix Calculations**
   - **Euclidean Distance Matrix**: Provided insights into spatial patterns of proximity.

   ![Ecludian Distance matrix Heatmap](https://github.com/user-attachments/assets/5b47cafa-9c98-4894-b1ef-ca684318d3b8)

   - **Haversine Distance Matrix**: More accurate for real-world distances on Earth’s surface, essential for realistic planning.

5. **Clustering Analysis**
   - **Cluster Visualization**: Employed PCA to visualize clusters, showing areas of high density (potential closures) and low density (critical coverage zones).
   - **Cluster Density Insights**: Identified high-density clusters for potential EV conversion and low-density areas needing coverage.

6. **Facility Location Optimization Model**
   - **Objective**: Developed a model to optimize petrol station closures (60% reduction) while maximizing coverage for ICE vehicles.
   - **Model Constraints**: Included geographic proximity, minimum station count, and specific station closures while maximizing area coverage.

7. **Optimization Results and Sensitivity Analysis**
   - **Optimal Coverage Distance**: Found optimal distance at 2.5 km, covering 15 districts with 8 strategically located stations.
   - **Key Locations**: Identified critical stations for optimized network distribution, minimizing redundancy and maximizing reach.

8. **Visualization and Recommendations**
   - **Maps and Heatmaps**: Visualized distance matrices, cluster distributions, and optimized station locations to support decision-making.
   - **Recommendations**: Suggested optimal configuration, regular monitoring, and adaptation based on future trends.

