Data and Automation Projects Gallery
---

🌌🚀 This repository serves as a collection of data automation techniques and solutions. It is our first step to exploring automation possibilities for the Finance & IS S.P.A.C.E mission. Feel free to dive in and explore the projects in this repository! 🛸 Happy paddling through the waves of data automation solutions! 🌊🛰️

## Internal data/automation tools


| Technology | Icon | Description |
|------------|------|-------------|
| Microsoft Office 365 | ![Microsoft Office 365](https://img.shields.io/badge/Product-Office_365-blue?logo=microsoft-office-365&logoColor=white&style=flat-square&s=50) | Comprehensive cloud-based Microsoft applications and services. |
| Power BI | ![Power BI](https://img.shields.io/badge/Analytics-Power_BI-yellow?logo=powerbi&logoColor=white&style=flat-square&s=50) | Data Model and Analysis with Power BI. |
| Python | ![Python](https://img.shields.io/badge/Programming-Python-blue?logo=python&logoColor=white&style=flat-square&s=50) | Main programming language for data projects. |
| VBScript | ![VBScript](https://img.shields.io/badge/Scripting-Visual_Basic-purple?logo=visual-studio&logoColor=white&style=flat-square&s=50) | Scripting tasks on Windows-based systems. |
|Microsoft Power Automate | ![Microsoft Power Automate](https://img.shields.io/badge/Automation-Power_Automate-grey?logo=microsoft-power-automate&logoColor=white&style=flat-square&s=50) | Automation platform for streamlining tasks and processes. |
| Microsoft SQL Server | ![Microsoft SQL Server](https://img.shields.io/badge/Database-Microsoft_SQL_Server-blue?logo=microsoft-sql-server&logoColor=white&style=plastic&s=75) | Relational database management system used for storing, managing, and retrieving data. |




## Details of Projects


### <u>**Project 1: Weekly reporting facilitated through the integration of Microsoft Planner and Power BI**</u>


**Problem statement** - Weekly reporting from team members to line managers relied on Microsoft Word templates, leading to manual consolidation efforts for divisional managers. This process lacked efficient project status tracking and consistency in reporting formats across teams. Moreover, limited visibility into ongoing projects hindered opportunities for cross-collaboration.

**Automation process** - We have implemented an efficient reporting system using Microsoft Planner, organizing tasks into buckets for easy categorization. Team members now input their weekly tasks, along with relevant details and timelines, to track progress effectively. The resulting reports, generated through Planner templates, seamlessly integrate with Power BI for streamlined consolidation. This allows management to gain a comprehensive, real-time view of team projects and status updates, with the flexibility to explore details at any level of interest. The automation of data transfer from Microsoft Planner to Power BI is facilitated through Microsoft Power Automate.

**Benefits to the team:**
- Structured, consistent, and transparent reporting method adopted
- Effortless and immediate access to project progress reports through automation
- Consolidation can be tailored at various levels and filtered by users in Power BI
- Offers personalized insights for a diverse audience


**Microsoft Planner navigation**

<p align="center">
  <img src="https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/Microsoft%20Planner%20navigation.gif" width="800" height="450" alt="Microsoft Planner navigation">
</p>



**Consolidated weekly report on Microsoft Power BI**

<p align="center">
  <img src="https://github.com/CarolMmai/Late-Product-Deliveries-Analysis/blob/main/Late%20Product%20Delivery%20Report.gif" width="800" height="450" alt="Late Product Deliveries Report">
</p>


---

### <u>**Project 2: Automated extraction/download of SAP reports for CAPEX Landing reporting**</u>


**Problem statement** - Users frequently encounter prolonged download times while manually downloading reports from SAP, particularly during peak reporting periods like month-end. This can result in timeouts on SAP sessions, causing delays in reporting. Additionally, report extraction often necessitates manual consolidation, preprocessing, and decentralized storage, further complicating the process.

**Automation process** - The automation process involves an end-to-end pipeline, beginning with the development of Visual Basic Scripts to automate data extraction. To prevent SAP timeouts, reports are divided into smaller segments and later combined using Python programming language, which also handles data preprocessing to make it analysis-friendly. The integrated data is stored in a Microsoft SQL Server database, serving as a structured and centralized data repository. Users can then connect to access clean, high-quality data ready for analysis in Power BI, that was developed as the endpoint of teh pipeline.


**Automation architecture:**

![Automated_SAP_report_extraction_Architecture](https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/Automated_SAP_report_extraction_Architecture.JPG)


**CAPEX Investments and CAPEX Landing Power BI reports**

<p align="center">
  <img src="https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/CAPEX%20Investments.gif" width="800" height="450" alt="CAPEX Investments">
</p>


<p align="center">
  <img src="https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/CAPEX%20Landing.gif" width="800" height="450" alt="CAPEX Landing">
</p>


**Benefits to the team:**

- Time saved through automated report retrieval
- Centralized platform for historical data access
- Standardized data transformation processes
- Transition from Excel to dynamic Power BI reporting


---

### <u>**Project 3: Use of Microsoft Forms to collect data from external contributors**</u>

**Problem statement** - Prior to implementing the solution, transporters reported vehicle breakdowns via email daily, necessitating manual consolidation into an Excel sheet by the admin clerk. This manual process was time-consuming, prone to errors, and sometimes resulted in delayed reporting. The new solution streamlines the collection of fleet breakdown data from transporters in real-time as incidents occur, eliminating the need for manual consolidation and improving efficiency.


**Automation process** - The process begins with creating a Microsoft Form for data collection, featuring customized category lists to streamline transporter responses. The form is designed to minimize text inputs and is publicly accessible, leveraging Microsoft's security measures to safeguard organizational data. A single, reusable link is shared with external contributors, enabling real-time data collection directly linked to an online Excel sheet. This sheet is then integrated into an existing Excel pivot report, allowing for easy refreshing as required.


**The Microsoft Form for Fleet Breakdown data collection**

<p align="center">
  <img src="https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/Fleet%20Breakdown%20data%20collection.gif" width="800" height="450" alt="Fleet Breakdown data collection">
</p>


**Benefits to the team:**

- Eliminated daily email overload for data collection and manual consolidation
- Decreased potential for human error in data preparation
- Reduced time spent on data-related administrative tasks
- Ensured timely daily reporting and enabled on-demand access to real-time data refreshes

---

### <u>**Project 4: Gains & Losses Teams Approvals solution**</u>

**Problem statement** - Finance needed high-level approvals for consolidated Gains & Losses from General Managers (GMs) across all departments. The sign-off process required adding observers and creating an approval trail for audit purposes. Previously, these approvals were managed via email, making it challenging to track the sign-offs effectively.


**Automation process** - Gains & Losses reporting was prepared in Power BI with tabs consisting of details for each department, including NBE. These reports were integrated seperately into dynamic Power Point presentations and attached into Teams via the Teams Approvals feature. The people identified as approvers and observers were added onto the routing list and this was sent for signature. Upon submission, a Teams notication was sent to the approvers in sequence of approval requirement and a approval pdf was generated and kept for audit trail upon completion of the approval.

**Microsoft Teams Approvals**

<p align="center">
  <img src="https://github.com/SPACE-Mission/Data-and-Automation-Projects-Gallery/blob/main/Gains%20%26%20Losses%20Approvals%20demonstration.gif" width="800" height="450" alt="Gains & Losses Approvals demonstration">
</p>


**Benefits to the team:**

- Utilized Dynamic Power BI seamlessly integrated into an existing PowerPoint layout
- Streamlined approval process through interactive Teams Approvals feature
- Exported PDF approvals for audit trail purposes
- Incorporated reminder functionality within the Approvals feature for added convenience

