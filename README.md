# Threat Management & Resolution Dashboard

## Overview
This repository contains a Tableau dashboard designed to monitor and analyze key performance indicators (KPIs) and key risk indicators (KRIs) for threat management and task resolution processes. The dashboard provides insights into task volume, completion rates, average resolution times, and backlog trends by division, assignee, and component. It is intended to support executive-level decision-making and operational efficiency in cybersecurity and threat management.

## Key Features
- **Total Task and Sub-Task Intake**: Displays total counts of tasks and subtasks to give an overall view of workload.
- **Resolution Rates**: Shows the percentage of tasks resolved, giving insight into overall task completion efficiency.
- **Mean Time to Resolve (MTTR)**: Calculates the average time taken to resolve tasks, aiding in identifying areas that may require faster response times.
- **Pending Resolution Time**: Measures the average time unresolved tasks have been open, helping to pinpoint potential backlogs.
- **Task Trends**: Visualizes monthly task and sub-task trends, highlighting fluctuations in workload.
- **Breakdown by Division and Assignee**: Analyzes unresolved task distribution by division and assignee to help target resources effectively.
- **Component-Level Analysis**: Shows average age of unresolved tasks by component and mean time to resolve for each component, allowing a granular view of potential bottlenecks.

## Repository Contents
- `Threat-Resolution-Dashboard.twbx`: Packaged Tableau workbook containing the dashboard and data source.
- `README.md`: Documentation file for understanding and using the dashboard.
- `Definitions.md`: Descriptions and definitions of all visuals, KPIs, and KRIs for detailed reference.

## Dashboard Visuals
1. **Main Task Status**: A bar chart displaying the status distribution for main tasks (e.g., Completed, In Progress).
2. **Sub-Task Status**: A bar chart showing the status of subtasks, such as Completed and In Progress.
3. **Monthly Task and Sub-Task Trendline**: A line chart showing task trends over time, helping to identify periods with increased or decreased task volume.
4. **Unresolved Tasks Breakdown**: Bar charts displaying unresolved tasks by division and assignee, aiding in identifying high-backlog areas.
5. **Component Metrics**:
   - **Component Avg Age Unresolved**: Shows the average unresolved time per component.
   - **Component MTTR**: Displays mean time to resolve by component for identifying specific delays.

## How to Use
1. **Clone or Download the Repository**: Clone the repository or download it directly from GitHub.
2. **Open the .TWBX File**: Open the `Threat-Resolution-Dashboard.twbx` file in Tableau Desktop to explore and interact with the dashboard.
3. **Filter Options**: Apply filters on division, assignee, or time period as needed to drill down into specific data.
4. **Definitions**: For details on each metric and visual, refer to the `Definitions.md` file.

## Requirements
- **Software**: Tableau Desktop (2020.2 or later recommended)
- **Data Source**: Packaged within the .twbx file

## Glossary
- **MTTR**: Mean Time to Resolve – The average time taken to resolve a task or sub-task.
- **Pending Resolution Time**: Average duration unresolved tasks have been open.
- **KPI**: Key Performance Indicator – Metrics to measure success in specific areas, such as resolution rates.
- **KRI**: Key Risk Indicator – Metrics to measure potential risks, such as high backlogs.

---

For more details on specific visuals and definitions, refer to the [Definitions.md](./Definitions.md) file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions, suggestions, or contributions, please message.
