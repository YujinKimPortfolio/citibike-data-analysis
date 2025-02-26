# CitiBike Usage Optimization Analysis

## Project Overview
This project analyzes CitiBike's bike-sharing system usage patterns in New York City to identify optimization opportunities. Our team, Fourcast, developed a comprehensive strategy to address system imbalances, weather-dependent usage patterns, and time-of-day variation to improve rider experience and operational efficiency.

![CitiBike Logo](presentation/citibike_logo.png)

## Problem Statement
CitiBike's system faces several operational challenges:

1. **Unbalanced Station Usage**: Some stations have too many bikes while others have too few, creating distribution issues across the network.

2. **Time of Day Variation**: Usage peaks during certain hours (morning/evening commute), leaving bikes underutilized during off-peak times.

3. **Weather Dependency**: Ridership drops significantly during subpar weather conditions, making revenue highly dependent on favorable weather.

4. **Seasonal Variation**: Summer months see over-capacity while winter months experience under-capacity.

5. **Ineffective Incentive Program**: The current Bike Angels program has limitations including exploitation by some users, limited scope, and lack of weather/time-based incentives.

## Key Findings

### Station Usage Analysis
- Bike distribution is significantly imbalanced across the network
- Neighborhoods in outer boroughs experience more unusable stations (no bikes/no docks)
- Certain high-traffic routes create predictable imbalances

### Time Analysis
- Peak usage occurs during 8-9 AM and 5-7 PM commute hours
- Weekdays have higher ridership than weekends
- Non-subscribers represent 15% of customers but 30% of total ride time

### Weather Impact Analysis
- Strong correlation between temperature and ridership
- Precipitation dramatically reduces system usage
- Winter months see significantly lower ridership

## Our Solution: Enhanced Incentive Program

We propose replacing the current Bike Angels program with a comprehensive incentive system that targets:

### 1. Route Optimization
- Leverage real-time station data
- Introduce capacity-based incentives for both subscribers and non-subscribers
- Address bike distribution imbalance with focus on underserved communities

### 2. Time-Based Incentives
- Implement dynamic pricing for non-subscribers during peak hours
- Apply Lyft's surge pricing model to manage demand
- Encourage subscription conversion through strategic pricing

### 3. Weather-Responsive System
- Factor weather variables into pricing/rewards algorithm
- Lower prices during inclement weather to maintain ridership
- Increase loyalty by encouraging year-round usage

### 4. Subscriber & Non-Subscriber Benefits
- **Subscribers**: Dynamic rewards through partnerships with DoorDash, Delta, etc.
- **Non-Subscribers**: Dynamic pricing to shift usage patterns and encourage subscription

## Expected Benefits

- **Increased Operational Efficiency**: Reduced need for manual rebalancing
- **Improved User Experience**: Better bike availability across all stations
- **Revenue Stabilization**: Less dependency on weather conditions
- **Greater System Equity**: Better service in historically underserved communities
- **Sustainability**: Lower reliance on trucks for rebalancing

## Project Deliverables
- Comprehensive data analysis of system usage patterns
- Strategic recommendations for incentive program redesign
- Implementation roadmap with KPIs for measuring success

## Team Members
- Madison Mintz
- Sofia Zarazaga del Saz
- Drew VanGoethem
- Yujin Kim
- Logan McKeown
- Andrew Wilson

## My Contribution
As a team member, I focused on analyzing weather pattern impacts on ridership and developing the data visualization framework for identifying usage trends. I leveraged Power BI to create interactive dashboards that helped identify key optimization opportunities. Additionally, I contributed to the strategy development for the enhanced incentive program, particularly focusing on weather-responsive pricing mechanisms.

## Tools & Technologies Used
- Power BI for data visualization and analysis
- Power BI DAX and SQL for data querying and aggregation
- Statistical analysis to identify usage patterns and correlations

## Project Context
This analysis was completed as part of TO 450 at the University of Michigan's Ross School of Business.
