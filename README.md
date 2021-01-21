# Community Health Status Indicator
# Objectives
To find multiple sources of data to form a substantial SOR required for warehousing.
To provide a brief walk through of building a data warehouse that will house Health-centric demographic data granularized at the ‘county’ level.
To implement advanced Data- warehousing techniques while answering questions with a Business perspective.
To provide an overview of the Data Flow Process.
Serve as Version - log for future references 
 
 
 
# Table of Contents:
1. Description of the data to be stored and moved into the analytics system
2. Data Source Description
3. Joining Data sets
4. Data Transformations
5. Dataset Dimensions
6. Field/Type Details

# High level data flow
1. Data flow
2. Dimensional Model
3. Incremental Loads
4. Lookup Tables
5. Data marts/ OLAP cubes


# Analytics Design
1. Reporting tools and visualizations

# Analytics outcomes

# Dataset Dimensions: These datasets have following dimensions.
1. Age
2. Race
3. State and County
4. Disease
5. Cases
6. Testing
7. Risk factors

# OLAP Cubes
Keeping reporting and analysis in mind the data can be franchised into different data marts. This is done for snappy reporting and ease of access to relevant data. For e.g. the team that looks after risk factor analysis does not require data related to preventive measures.
A data mart will be created where it will aggregate the data of all the counties of an individual state so we can perform state wise analysis related to the leading cause of death. A sample use case - deaths caused by cancer in NewYork compared to deaths caused by Cancer in Florida.
The other data mart will consist of data comparing the deaths and population data at a county level granularity. This can be done by pulling relevant fields and aggregating to find effective death rate, poverty level, population density, etc. This provides the BI team to look at the overall status of the country and pin-point as to which areas require assistance in terms of medicare and other resources.

# Reporting and Visualization Tools
Tableau is an interactive data visualization tool. It’s an application that is used for translating raw data into valuable insights. A few advantages of using tableau over using any other visualization tool are : 

Remarkable Visualization Capabilities
1. Multiple Data Source Connections	
2. Ease of Use	
3. High Performance
4. Mobile Friendliness






