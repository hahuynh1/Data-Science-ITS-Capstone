# Vizion Zero Philly

## What is the data science problem to be solved and why is it important?
    Problem: Identifying and recommending the optimal Intelligent Transportation System (ITS) devices for accident-prone locations in Philadelphia to enhance public safety and infrastructure.
    Importance: This project aims to: Reduce the number of accidents in Philadelphia, leading to fewer injuries and fatalities. Lower the frequency of accidents, improve public road safety, and identify and address contributing factors to accidents, enabling targeted infrastructure improvements (installation of ITS devices).
## Solutions:
    Data Visualization: Develop an interactive platform showcasing historical accident locations and contributing factors using:
        Visually represent accident locations.
        Analyze trends and patterns in accident data by using charts and graphs.
    Recommendation System: Create a model that recommends the most suitable ITS device for each location based on:
        Prioritize locations with higher severity and frequency.
        Recommend devices tailored to specific accident types (e.g., vehicle to vehicle, vehicle to pedestrian).
        Consider existing infrastructure and compatibility with potential ITS devices.

## Deliverables and Usefulness:
    Reports and visualizations: Offer insights into accident patterns and justifications for device recommendations.
    Transportation Decision Making: PennDOT to choose data-driven strategies for enhancing road safety.

## Quantifying Success
## Success Metrics:
    Reduction in accident rates: Analyze accident data before recommendations are made, to existing locations where those devices are already implemented.
    Cost-benefit analysis: Evaluate the cost of implementing and maintaining ITS devices against the economic benefits of accident reduction.

## Common Metrics in the Domain:
    Number of accidents
    Accident severity (fatal, injury, property damage)
    Accident type (e.g., collision, pedestrian involved)
    Traffic volume
    Road infrastructure quality
    Neighborhood income, education level
    Assumption that its in the past worked
    Lead to safety improvement when placed
    Type of accident correlates to ITS
    Number of lanes as a feature, intersection
    Accidents before and after ITS implementation

## Data Nature:
    Accident data: Includes location, date, time, severity, type, contributing factors, etc. (potentially from PennDOT)
    Traffic data: Provides information on traffic volume, flow, and speed (potentially from city agencies)
    Road infrastructure data: Details on road characteristics, lane markings, signage, etc. (potentially from PennDOT)
    
## Operations:
    Utilize data processing tools like pandas and machine learning libraries like scikit-learn for analysis and modeling.
    
## Project Phases and Timeline
## Phase 1:
    Dataset Selection: Choose a comprehensive accident dataset covering Philadelphia.
    Model Selection: Identify a suitable machine learning model for recommending ITS devices based on accident data.
## Phase 2:
    Data Cleaning: Preprocess and clean the chosen dataset to ensure accuracy and consistency.
    Feature Engineering: Identify and extract relevant features from the data for model training.
    Model Training and Evaluation: Train and evaluate the chosen model using appropriate metrics.
    Location Selection: Select representative locations with varying accident characteristics for analysis.
## Phase 3:
    ITS Device Recommendation: For each chosen location, utilize the trained model to recommend the most suitable ITS device, providing justification for the recommendation.
## Phase 4:
    Presentation Development: Create a comprehensive presentation for PennDOT, showcasing project findings, recommendations, and potential impact.
    
## Communication Plan
    Project Management: Utilize Trello for task organization, progress tracking, and collaboration.
    Code Management: Employ GitHub for version control, code sharing, and collaborative development.
    Team Communication: Maintain regular communication through the existing Discord server for discussions and updates.

### This plan provides a structured approach to tackling the data science problem, offering valuable insights and recommendations for PennDOT to enhance road safety in Philadelphia. Remember to adapt and refine the plan as needed throughout the project lifecycle.