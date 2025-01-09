# Optimizing Solar Panel Deployment in Uganda

## Project Overview
This project focuses on developing an optimization model to determine the optimal deployment of solar panels across Uganda. By addressing the country’s energy access challenges, the model aims to maximize energy production, minimize costs, and ensure sustainable energy access in rural and underserved regions. The solution aligns with Uganda’s Energy Transition Plan, supporting economic growth, environmental sustainability, and improved quality of life.

---

## Features of the Project
- **Optimization Objectives**:
  - Maximize energy production based on regional solar potential.
  - Minimize installation and transportation costs.
- **Data Integration**:
  - Combines solar potential, population, and electricity demand data.
- **Decision Variables**:
  - Number of solar panels installed in each region.
  - Panels transported between suppliers and regions.
- **Constraints**:
  - Satisfy regional electricity demand.
  - Adhere to budgetary limitations.
  - Balance energy production within region groups.
  - Ensure non-negativity of installed and transported panels.
- **Visualization**:
  - Maps and charts illustrating solar potential, energy production, and panel distribution.

---

## Dataset Description
### Primary Data Sources:
- **Solar Potential Data**:
  - Derived from Global Solar Atlas (1994-2018).
- **Electricity Demand Data**:
  - Population-based demand estimates from Uganda’s Bureau of Statistics.
- **Geospatial Information**:
  - District-level maps of Uganda including transmission lines and protected areas.

### Key Variables:
- **Xi**: Number of solar panels installed in region i.
- **Tik**: Panels transported from supplier k to region i.
- **EP**: Energy production per panel.
- **EDi**: Electricity demand for region i.
- **CS**: Installation cost per panel.
- **CTik**: Transportation cost per kilometer.
- **Dik**: Distance between supplier k and region i.

---

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed Uganda’s solar potential, population, and energy demand distributions.
2. **Optimization Model**:
   - **Objective Functions**:
     - Maximize energy production.
     - Minimize total costs (installation + transportation).
   - **Constraints**:
     - Ensure demand satisfaction.
     - Maintain budget compliance.
     - Limit energy exports to surplus regions.
3. **Implementation**:
   - Developed using Python and the Gurobi optimization library.
4. **Validation and Visualization**:
   - Visualized panel distribution, installed capacity, and energy flows.

---

## Key Results
- **Optimization Outcome**:
  - Total cost: $3.2 billion.
  - Energy generation: 2857.79 MW.
  - Total panels installed: 9,525,969.
- **Regional Focus**:
  - Prioritized rural and off-grid regions for solar panel deployment.
- **Policy Impact**:
  - Supports Uganda’s sustainable development goals and rural electrification efforts.

---

## Future Improvements
- **Dynamic Costs**: Integrate seasonal variations in transportation and installation costs.
- **Stakeholder Engagement**: Collaborate with local governments and energy experts.
- **Environmental Considerations**: Incorporate protection for national parks.
- **Enhanced Demand Models**: Refine electricity demand estimates using real-time data.

---

## Getting Started
### Dependencies
- **Programming Language**: Python
- **Libraries**:
  - pandas, numpy, matplotlib, seaborn, gurobipy

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uganda-solar-optimization.git
   ```
2. Load the datasets provided in the repository.
3. Run the Jupyter Notebook to replicate data preprocessing, optimization modeling, and visualizations.

---

## Contact
For questions or collaboration opportunities, please reach out to:

**Name**: Arturo Medina  
**LinkedIn**: [linkedin.com/in/arturo-medina](https://linkedin.com/in/arturo-medina)
