# GE Aerospace Explore Digital Technology


## Project 
Digital Technology Intern at GE Aerospace

## Tools
- Vue.js
- Vue SFC Playground
- Visual Studio Code
- Google Docs

## Role 1: Software Developer
<p>Become familiar with one of the tools GE Aerospace uses for application development.  GE leverages Vue.js for building user interfaces.</p>

<p>Design a user interface using Vue.js. Add text, an image, a button, and compute the product of two numbers when the button is clicked.</p>

<p float=left>
<img src="https://github.com/Sarah269/bug-free-eureka/blob/main/GE%20Aerospace/Vue_1.png" width="49%">
<img src="https://github.com/Sarah269/bug-free-eureka/blob/main/GE%20Aerospace/Vue_2.png" width="49%">
</p>

# Role 2: Product Owner
<p>Convert business requirements into technical requirements for the technical team.</p>

<p>Write technical requirements for a new supply chain feature that suggests the optimal time to order new plane parts. GE management would like the system to provide order times that are early enough to avoid shortages but late enough to keep costs low.</p>

### Technical Requirements
Technical Requirements
1.  Dynamic Order Calculation Algorithm:
    - Implement an algorithm that calculates optimal order dates by integrating supplier lead times, historical demand, and forecasted demand. The algorithm should balance minimizing stockouts while reducing excess inventory.
2.  Configurable Business Rules Engine:
    - Develop a configurable rules engine that allows users to adjust parameters (e.g., safety stock levels, lead time buffers) to fine-tune order suggestions based on changing business needs.
3.  Automated Notification System:
     - Build an automated notification system that alerts users via email or in-app messages when an order needs to be placed, highlighting urgent cases based on priority thresholds.
4.  Reporting System:
     - Build a reporting feature that allows users to generate reports or download data on order times, inventory levels, cost impacts, past order times, and suggestions.
5.  Future Demand Algorithm:
      - Implement an algorithm to forecast demand for parts based on historical demand.
6.  Critical Parts Prioritization:
      - Identify and prioritize the procurement and storage of the most critical parts based on their operational importance and lead time sensitivity.
7.  Inventory Data Integration:
      -  Source real-time inventory data from the inventory database to ensure accurate and up-to-date order calculations.
8.  Historical Data Utilization:
      -  Use three years of historical demand data to enhance forecasting accuracy and optimize order timing.
9.  Calculated Data Points:
      -  Implement features that derive key data points from current, historical, and forecasted information:
          - Date of part's last replacement
          - Average time between replacements
          - Estimated shipping times
          - Average inventory quantity
          - Average part demand
          - Maximum time a supplier takes to deliver a part
          - Average lead time for a part
          - Forecasted part demand
          - Historical demand
          - Lead time for a part
10.  Key Formulas and Metrics:
      -  Lead Time:
          - Description: The length of time between ordering and receiving inventory
          - Formula: Part delivery date - Part order date
      -   Safety Stock:
          - Description: Amount of reserve inventory stored to avoid stockouts
          - Formula: (Maximum time supplier takes to deliver goods - Average lead time) * Average part demand
      -  Reorder Point:
          - Description: Ideal time to place an order
          - Formula: Safety stock + (Average consumption of part × Part lead time)
      -  Maximum Stock Level:
          - Description: Maximum inventory quantity that avoids excessive storage costs
          - Formula: (Reorder point + Replenishment quantity) - (Minimum part demand × Part lead time)
      -  Accuracy of Forecast Demand:
          - Description: Measure the accuracy of forecasted demand against actual demand
          - Formula: [(Actual - Forecast) / Actual] × 100
11.  System Performance Metrics:
      - The part inventory quantity should not fall below the safety stock level.
      - The part inventory level should not exceed the maximum stock level.
      - The system should send a reorder alert before the inventory level reaches the safety stock level.
      - The system should send a reorder alert when the inventory level reaches the reorder point.
      - The forecast demand accuracy should meet or exceed a defined percentage (e.g., 95%).

  
