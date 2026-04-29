# Power_BI_Project_Real_Estate_Stock_Report

## Project Overview
This project is a comprehensive Real Estate Inventory Management Dashboard designed to provide stakeholders with end-to-end visibility into stock health, sales performance, and construction progress. It transforms complex raw data into actionable insights for high-level decision-making.

Note: This dashboard utilizes a creative dummy dataset with location names inspired by One Piece (e.g., Alabasta, Dressrosa, Marineford) to demonstrate professional BI capabilities within a unique, portfolio-friendly context.

## Dashboard Previews

### 1. Interactive Landing Page
A clean entry point featuring a modular navigation system for seamless access to different report levels.
(Insert image_dce2a2.jpg here)

### 2. Executive Overview
Focuses on high-level KPIs: Stock Total Price (Mio IDR), Available vs. Hold units, and Price Point distribution.
(Insert image_dce27e.jpg here)

### 3. Inventory Summary & MoM Analysis
A detailed hierarchical view comparing Month-over-Month (MoM) stock status (Under Construction, Ready Stock, Not Assigned) with automated deviation tracking.
(Insert image_dcdf5a.jpg here)

### 4. Advanced Filtering System
A dedicated, pop-out filter panel designed using bookmarks and selection panes to maintain a clutter-free user experience.
(Insert image_dcdebe.png here)

## Technical Highlights
### Data Modeling
- Architecture: Implemented a Star Schema to optimize query performance and ensure data integrity.

- Granularity: Data flows from Group Pillar and SBU levels down to specific Unit IDs.

### DAX Engineering
- Time Intelligence: Custom DAX measures to calculate "Month-before" snapshots and percentage deviations.

- Dynamic Categorization: Used SWITCH logic to bucket units into specific price points (e.g., "Below 2 Bn", "2Bn - 3Bn").

- Conditional Formatting: Visual cues for stock status to highlight "Obsolete" or "Critical" inventory levels.

## UI/UX Design
- Navigation: Built-in buttons for "Overview," "Summary," and "Detail" views.

- Scalability: The dashboard is designed to handle thousands of unit records while maintaining fast load times through Dremio/Data Virtualization optimization.
