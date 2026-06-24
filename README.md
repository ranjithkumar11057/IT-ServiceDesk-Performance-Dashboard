
# IT Service Desk Performance & SLA Analytics Dashboard 2026

## Project Overview

This project is an interactive Excel dashboard developed to analyze IT Service Desk operations, monitor SLA compliance, evaluate ticket resolution performance, and measure agent productivity.

The dashboard transforms raw ticket data into actionable business insights using Excel analytics techniques such as Pivot Tables, Pivot Charts, Slicers, Data Validation, Conditional Formatting, and KPI calculations.

---

## Business Objective

The primary objective of this project is to:

* Monitor IT service desk performance.
* Measure SLA compliance and breach rates.
* Track ticket resolution efficiency.
* Analyze agent productivity.
* Identify operational bottlenecks.
* Improve customer service quality through data-driven insights.

---

## Dataset Information

The dataset contains IT support ticket information including:

| Column Name           | Description                      |
| --------------------- | -------------------------------- |
| Ticket_ID             | Unique ticket identifier         |
| Created_Date          | Ticket creation date             |
| Created_Time          | Ticket creation time             |
| Closed_Date           | Ticket closure date              |
| Closed_Time           | Ticket closure time              |
| Department            | Department handling the ticket   |
| Issue_Type            | Type of issue reported           |
| Priority              | Ticket priority level            |
| Agent_Name            | Assigned support agent           |
| Status                | Open or Closed                   |
| Resolution_Time_Hours | Time taken to resolve the ticket |
| SLA_Target_Hours      | Target resolution time           |
| Customer_Rating       | Customer satisfaction rating     |
| Escalated             | Escalation status                |

---

## Data Validation Implemented

To improve data quality and prevent invalid entries, Data Validation was applied.

### Status

Allowed Values:

* Open
* Closed

### Department

Allowed Values:

* IT
* Operations
* HR
* Finance
* Sales

### Priority

Allowed Values:

* High
* Medium
* Low

### Issue Type

Allowed Values:

* Network Issue
* Password Reset
* Hardware Failure
* Software Install
* Access Request
* Email Problem

### Customer Rating

Rules:

* Whole Number
* Minimum = 1
* Maximum = 5

### Resolution Category

Allowed Values:

* Fast
* On-Time
* Delayed
* Critical

### Additional Controls

* Input Messages
* Error Alerts
* Stop Warning Validation

---

## Calculated Columns

Several calculated columns were created using Excel formulas.

### SLA Status

Determines whether a ticket met the SLA target.

### SLA Breach Flag

Identifies SLA violations.

### Resolution Category

Classifies ticket resolution speed:

* Fast
* On-Time
* Delayed
* Critical

### Escalated Numeric

Converts escalation status into numeric values for reporting.

### Rating Category

Groups customer ratings into categories.

### Days to Close

Calculates the total days required to close a ticket.

### Within SLA

Indicates whether the ticket was resolved within SLA limits.

### Data Quality Flag

Identifies incomplete or invalid records.

---

## Conditional Formatting

Conditional Formatting was implemented to improve visibility and highlight critical records.

### Applied On

#### SLA Status

* Green → Within SLA
* Red → Breached

#### Priority

* High → Highlighted
* Medium → Highlighted
* Low → Highlighted

#### Within SLA

* Yes → Green
* No → Red

---

## Dashboard KPIs

The dashboard provides the following key performance indicators:

* Total Tickets
* Closed Tickets
* Open Tickets
* Resolution Rate (%)
* SLA Compliance (%)
* SLA Breach Rate (%)
* Average Resolution Time
* Average Customer Rating

---

## Dashboard Components

### Monthly Ticket Trend Analysis

Visualizes ticket volume trends over time.

### Average Resolution Time by Issue Type

Compares resolution efficiency across issue categories.

### SLA Breach Analysis

Analyzes SLA violations by department and priority.

### Agent Performance Scorecard

Measures agent productivity and resolution efficiency.

### Interactive Slicers

Dashboard filtering available by:

* Department
* Priority
* Status
* Agent Name
* Issue Type

---

## Excel Features Used

* Pivot Tables
* Pivot Charts
* Slicers
* Data Validation
* Error Alerts
* Input Messages
* Conditional Formatting
* IF Functions
* COUNTIF Functions
* AVERAGE Functions
* Calculated Columns
* Dashboard Design

---

## Key Business Insights

* SLA Breach Rate is significantly higher than SLA Compliance Rate.
* Certain departments contribute more to SLA violations.
* High-priority tickets require faster resolution.
* Agent performance varies based on ticket volume and resolution speed.
* Customer satisfaction can be monitored using rating metrics.

---

## Skills Demonstrated

### Excel

* Advanced Excel Reporting
* Dashboard Development
* KPI Design
* Data Cleaning
* Data Validation

### Data Analysis

* Business Analysis
* Trend Analysis
* Performance Monitoring
* SLA Reporting

### Visualization

* Pivot Charts
* Interactive Dashboards
* Data Storytelling

---

## Project Files

* IT_ServiceDesk_Performance_2026.xlsx
* IT_ServiceDesk_Project_Presentation.pptx
* Dashboard_Screenshot_1.png
* Dashboard_Screenshot_2.png
* Dashboard_Screenshot_3.png

---

## Author

Ranjithkumar M

Aspiring Data Analyst | Excel | SQL | Power BI | Data Visualization
