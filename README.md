****Twitter Analytics Dashboard – Power BI
Project Overview****

This project focuses on designing and developing an interactive Twitter Analytics Dashboard using Microsoft Power BI, based on a set of real-world analytical requirements provided during an internship assignment.

The objective of this dashboard is not only to visualize data, but to generate meaningful insights by applying multiple business rules, time-based conditions, and engagement filters within a single, well-structured dashboard.

The dashboard was built entirely from scratch, covering the complete analytical workflow:

Data ingestion

Data transformation (ETL)

Data modeling

DAX calculations

Visualization

Dashboard aesthetics and layout design

Tools and Technologies Used

Microsoft Power BI Desktop

Power Query (M Language) for ETL

DAX (Data Analysis Expressions) for calculations

Excel / CSV as the data source

Data Pipeline (ETL Process)
*1. Extract*

Twitter analytics data was imported from an Excel (.xlsx) or CSV file.

*2. Transform (Power Query)*

The following transformations were performed to prepare the dataset for analysis:

Converted tweet timestamp into:

Tweet Date

Tweet Hour

Day of Week

Calculated Tweet Word Count

Identified Odd and Even tweet dates

Removed unused and irrelevant columns to improve performance

Cleaned and standardized text fields

These transformations ensure that complex filtering logic is handled efficiently at the data level, minimizing the need for heavy visual-level filters.

*3. Load*

The transformed dataset was loaded into the Power BI data model for analysis and visualization.

Dashboard Objectives and Business Rules

The dashboard consolidates five analytical tasks into a single unified view, each governed by specific business constraints such as time windows, engagement thresholds, and tweet characteristics.

*Task 1: Top Engagement Tweets*

Displays tweets in the top 10 percent by engagement rate

Includes only:

Tweets with more than 50 likes

Tweets posted on weekdays

Tweet word count below 30

Active only between 1 PM and 4 PM

*Task 2: Media Engagement vs Media Views*

Scatter chart analyzing the relationship between:

Media Engagements

Media Views

Conditions applied:

Replies greater than 10

Tweets with engagement rate above 5 percent highlighted

Only odd tweet dates included

Tweet word count below 50

Active only between 12 PM and 6 PM

*Task 3: Interaction Breakdown by Tweet Category*

Clustered bar chart displaying:

URL Clicks

User Profile Clicks

Hashtag Clicks

Grouped by tweet category (media, links, hashtags)

Filters applied:

At least one interaction present

Even tweet dates only

Tweet word count below 40

Active only between 3 PM and 6 PM

*Task 4: Weekly Media Performance (Dual Axis)*

Dual-axis chart showing:

Media Views

Media Engagements

Analyzed by day of the week

Limited to the last quarter

Conditions:

Even impression values

Odd tweet dates

Tweet word count below 30

Active only between 3 PM and 6 PM

Days with significant spikes in media interactions are visually highlighted

*Task 5: Monthly Engagement Trend*

Line chart displaying average engagement rate by month

Separate trend lines for:

Tweets with media content

Tweets without media content

Filters applied:

Even engagement values

Odd tweet dates

Active only between 3 PM and 6 PM

Dashboard Design Philosophy

The dashboard follows a clean, executive-style design inspired by modern KPI reporting standards:

Clear visual hierarchy with KPIs leading the narrative

Minimal and consistent color palette

Balanced spacing and alignment

Focus on clarity, usability, and insight generation

All visuals are fully interactive and respond dynamically to applied filters and slicers.

**Key Outcomes**

Successfully combined multiple complex analytical requirements into a single dashboard

Applied real-world business logic using Power Query and DAX

Designed a dashboard suitable for stakeholder and managerial review

Ensured performance optimization and visual consistency

**How to Use**

Open the .pbix file in Microsoft Power BI Desktop

Refresh the data if a new source file is connected

Interact with visuals using slicers and filters

Explore engagement trends and performance insights

**Learning Highlights**

End-to-end Power BI dashboard development

Practical application of time-based and conditional logic

Effective use of engagement metrics for analysis

Dashboard storytelling and visual design best practices

Acknowledgement

This project was completed as part of an internship assignment designed to simulate real-world analytics challenges and business-driven reporting requirements.
