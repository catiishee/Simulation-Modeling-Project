# Simulation Modeling of Bar Operations Using AnyLogic

## Overview
This project focuses on developing a discrete-event simulation model of a bar using AnyLogic. The model aims to reflect the operational processes of the bar accurately, where events occur at discrete moments in time. This simulation provides insights into optimizing service strategies and resource management within the bar environment.

## Objectives
- **Create a detailed simulation model** to analyze the efficiency of bar operations.
- **Optimize resource allocation and customer flow management** to improve service quality.
- **Evaluate the impact of various factors** such as seating capacity, number of staff, and peak hours on the overall performance of the bar.

## Key Features of the Model
- **Discrete-Event Simulation**: The model uses discrete-event principles to mimic bar operations, capturing the sequence of customer interactions, from arrival to departure.
- **Flexible Customer Behavior**: Customers are modeled with attributes such as seating preferences, order types, group sizes, and payment behaviors.
- **Dynamic Staff Allocation**: The number of waitstaff adjusts dynamically based on the time of day and customer demand, optimizing labor costs while maintaining service quality.

## Modeled Scenario
- **Bar Description**: The bar operates from Monday to Friday, from 7:00 AM to midnight. It features 30 seating areas and can accommodate up to 90 standing customers. A kitchen is available for serving hot meals during lunchtime (12:00 PM - 3:00 PM).
- **Customer Flow**: The model simulates different types of customers, including seated patrons, standing bar guests, and regulars, each with unique service expectations and behaviors.

## Methodology
1. **Conceptual Modeling**: Defined key entities such as customers, orders, and waitstaff. Developed a conceptual model that outlines how these entities interact within the bar environment.
   
2. **Computer Implementation**: Implemented the conceptual model in AnyLogic using a combination of discrete-event and agent-based modeling techniques. Customers are represented as agents with dynamic attributes, influencing their decisions throughout the simulation.

3. **Performance Analysis**: Analyzed the simulation results using various charts and diagrams to assess the average waiting times, service efficiency, and resource utilization.

## Key Findings
- **Peak Hours Impact**: During peak hours, especially in the evening, the bar experiences significant congestion, leading to longer wait times and potential customer loss.
- **Seating vs. Standing**: Seated customers tend to spend more time in the bar, impacting overall throughput, whereas standing customers receive faster service but are more prone to leaving due to delays.
- **Staff Efficiency**: Proper allocation of waitstaff during peak times significantly reduces waiting times, enhancing customer satisfaction.

## Results and Recommendations
- **Increase Outdoor Seating**: To accommodate more guests during peak evening hours, consider expanding outdoor seating options.
- **Adjust Staff Levels**: Reduce the number of waitstaff during less busy hours to cut costs while ensuring sufficient coverage during peak periods.
- **Optimize Service Flow**: Implement strategies to reduce wait times, such as prioritizing frequent customers and optimizing order processing during peak hours.

## How to Run the Model
1. Download the `.alp` file from this repository.
2. Open the file in AnyLogic.
3. Run the simulation by clicking the **Run** button in the AnyLogic environment.

## Requirements
- **AnyLogic Software**: This model requires AnyLogic to run simulations. Download it from the [AnyLogic Official Website](https://www.anylogic.com/downloads/).

## Authors
- **Ekaterina Shcherbinina** - Student, Group B21-901, National Research Nuclear University MEPhI.

## Acknowledgments
This project was supervised by D.S. Smirnov and includes insights from his lectures on simulation modeling.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
