

# Patient Waitlist Dashboard

A comprehensive Power BI dashboard designed to track and analyze patient waiting lists across multiple specialties and case types — showcasing the full lifecycle of BI development from data collection to deployment.


  
## Patient Waitlist Analytics: End-to-End Power BI Dashboard

An interactive and dynamic Power BI solution built to monitor patient waiting lists, analyze historical trends, and assess specialty-level and age-profile performance using healthcare data (2018–2021).


   <br>

🎯 **Short Description / Purpose**


The Patient Waitlist Dashboard helps healthcare professionals and administrators visualize and analyze key metrics like total waiting list volume, monthly trends, and specialty performance. It serves as a decision-support tool for improving operational efficiency, identifying bottlenecks, and tracking progress across inpatient, outpatient, and day-case categories.


  
🧰 **Tech Stack**


The dashboard was built using the following tools and technologies:

Power BI Desktop – for visualization and report design

Power Query – for data transformation and cleaning

DAX (Data Analysis Expressions) – for creating calculated measures, KPIs, and dynamic titles

Data Modeling – establishing relationships between patient data and specialty mappings

Power BI Service – for publishing, applying Row-Level Security (RLS), and scheduling refreshes

PowerPoint / Canva – for creating dashboard backgrounds and layout design

Adobe Color – for extracting and applying consistent color palettes


  

🗂️ **Data Source**


Source: Publicly available Healthcare Patient Waiting List data
Scope: 2018 – 2021
Data Includes:

Specialty Name

Case Type (Inpatient, Outpatient, Day Case)

Age Profile

Time Band

Archive Date

Total Patients Waiting

Supplementary data:

Specialty Mapping File (for grouping and categorization)


  
✨ **Features / Highlights**


🏥 Business Problem

Hospitals and healthcare authorities need clear visibility into their patient waiting lists — segmented by specialty, age, and case type — to optimize resource allocation and improve service delivery.
However, raw data alone makes it difficult to:

Track backlog trends over time

Compare performance year-over-year

Identify overburdened specialties or demographic segments


🎯 Goal of the Dashboard


To deliver an interactive, self-service Power BI dashboard that enables stakeholders to:

Track current and historical patient waiting list volumes

Compare average and median waiting lists dynamically

Analyze trends by specialty, case type, and time band

Support data-driven decision-making for healthcare operations


📊 Walkthrough of Key Visuals


Key KPIs (Top Section)

Total Waitlist (Latest Month): Current month total

Previous Year Waitlist: Year-over-year comparison

Dynamic Toggle: Users can switch between Average and Median metrics

Case Type Split (Donut Chart)

Displays distribution of patient cases: Outpatient, Inpatient, and Day Case

Time Band vs Age Profile (Clustered Column Chart)

Compares patient counts across different waiting time bands and age groups

Top 5 Specialties (Multi-row Card)

Highlights specialties with the highest number of waiting patients

Monthly Trend Analysis (Line Chart)

Shows historical trend of total waitlists from 2018–2021, separated by case type

Detailed View (Matrix Table)

Provides granular data for further exploration by specialty, case type, and time band

Tooltip Page

Displays contextual insights on hover, including specialty-level totals


💡 Business Impact & Insights


Operational Efficiency: Identify departments with increasing backlogs

Performance Tracking: Compare monthly progress across specialties

Resource Allocation: Prioritize staffing or capacity for overloaded departments

Data Transparency: Empower decision-makers with real-time, visually clear data


  
⚙️ **Development Workflow**


Requirement Gathering: Stakeholder interviews, scope definition, and metric identification

Data Collection: Folder connection for centralized data refresh

Data Transformation: Cleaning, renaming, appending, and trimming columns in Power Query

Data Modeling: Relationship creation with Specialty Mapping table

Visualization Blueprint: Wireframe design and layout alignment using grid & snap features

Dashboard Design: DAX measures for KPIs, dynamic titles, and interactivity

Adding Interactivity: Navigation buttons, slicers, and tooltip integration

Testing & Sharing: UAT, data validation, and deployment with Row-Level Security (RLS)

Routine Refresh: Scheduled monthly data updates and performance maintenance


  
🔐 **Security**


Row-Level Security (RLS) implemented to restrict data visibility based on specialty or hospital access — ensuring privacy and compliance in healthcare data visualization.
