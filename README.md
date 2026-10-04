# MAA Safety Culture Analytics & Power BI Dashboard

## Project Overview

During my internship with the Maryland Aviation Administration (MAA) Office of Safety and Risk Management, I developed an end-to-end Safety Culture Survey analytics solution designed to help leadership better understand employee perceptions of safety, reporting culture, communication, and organizational risk.

I owned the project from concept through implementation, including survey development, data preparation, analytical modeling, dashboard development, validation, user interface design, and executive presentation.

The final solution transformed raw survey responses into a structured, leadership-facing Power BI dashboard that made both quantitative and qualitative safety data easier to interpret, compare, and act upon.

### [View the Full Power BI Dashboard](https://github.com/zoozibear/MAA-Safety-Culture-PowerBI-Dashboard/blob/main/Mock%20Version%20-%20MAA%20Safety%20Culture%20Survey%20Dashboard%20-%20Portfolio.pdf)

---

## Project at a Glance

| Area | Details |
|---|---|
| Organization | Maryland Aviation Administration |
| Office | Office of Safety and Risk Management |
| Project | Safety Culture Survey & Power BI Analytics Dashboard |
| Primary Tool | Microsoft Power BI |
| Supporting Tools | Power Query, DAX, Microsoft Forms, Excel |
| Focus Areas | Data Analytics, Business Intelligence, Risk Management, Data Modeling, Survey Analytics |
| My Role | End-to-end project development, analysis, dashboard design, validation, and presentation |

---

## The Business Need

Safety culture extends beyond incident counts. Leadership also needs visibility into how employees perceive safety, whether employees understand reporting procedures, whether they feel comfortable raising concerns, and whether reported issues are being addressed effectively.

The goal of this project was to create a structured way to collect that information and translate it into actionable insights.

I developed the MAA Safety Culture Survey to capture employee perspectives across areas including:

- Management commitment to safety
- Employee voice and participation
- Knowledge of safety reporting procedures
- Comfort reporting concerns
- Safety communication
- Follow-up on reported concerns
- Observed safety concerns and near misses
- Employee-identified safety priorities
- Open-ended feedback and recommendations
- Interest in future safety engagement opportunities

---

## My Role & Project Ownership

I was responsible for developing the analytical solution from the ground up.

My work included:

- Developing the Safety Culture Survey structure and analytical framework
- Preparing and transforming raw survey data for analysis
- Designing the Power BI data model
- Restructuring Likert-scale responses into an analysis-ready format
- Creating dedicated fact tables for quantitative and qualitative responses
- Developing more than **60 DAX measures and validation checks**
- Building calculations for favorable, neutral, and unfavorable response rates
- Developing safety culture and reporting-focused performance measures
- Creating participation and written-feedback metrics
- Analyzing open-ended employee feedback
- Developing logic to identify recurring themes across written comments
- Building dedicated backend validation and measure-testing pages
- Performing extensive quality assurance across calculations, filters, relationships, and visuals
- Designing the complete dashboard interface for leadership usability
- Presenting the completed dashboard and findings to senior leadership

---

## Technical Implementation

### Data Transformation

Power Query was used to clean, restructure, and prepare the survey data before analysis.

This included separating different response types and transforming the survey structure into tables that could support flexible reporting and filtering.

The final analytical model included dedicated structures for:

- Cleaned survey responses
- Likert-scale responses
- Written employee feedback
- Centralized analytical measures

This approach allowed the dashboard to analyze both structured survey responses and qualitative feedback while maintaining consistent filtering across department, job role, tenure, and other survey dimensions.

---

## DAX & Analytical Measures

A significant portion of the project involved developing the analytical layer of the dashboard.

I created more than **60 DAX measures and validation checks** supporting metrics such as:

- Total survey responses
- Written feedback participation
- Average Likert scores
- Favorable response rates
- Neutral response rates
- Unfavorable response rates
- Safety culture scores
- Reporting and communication scores
- Safety concern observation rates
- Near-miss observation rates
- Town hall participation interest
- Response-count validation
- Duplicate-response checks
- Missing-response checks
- Expected-versus-actual Likert response validation

The goal was not only to calculate dashboard metrics, but also to create checks that verified that those metrics were producing reliable results.

---

## Qualitative Feedback Analysis

The survey included multiple open-ended questions designed to capture concerns, suggestions, observations, and employee recommendations.

I created an analytical framework for organizing written feedback into recurring themes so leadership could move beyond reading individual comments and begin identifying broader patterns.

This required reviewing and categorizing written responses and developing extensive word and phrase associations to support theme identification.

The resulting analysis allowed the dashboard to surface recurring topics while still preserving access to the underlying written feedback.

---

## Dashboard Structure

The final Power BI report was designed as a multi-page leadership tool rather than a single static dashboard.

### Home

Provides navigation and introduces users to the dashboard structure.

### Executive Overview

Provides a high-level summary of overall survey performance and major safety culture indicators.

### Safety Culture

Focuses on employee perceptions of organizational safety priorities, management commitment, and employee voice.

### Reporting & Communication

Examines whether employees understand reporting procedures, feel comfortable raising concerns, and believe safety information and follow-up are communicated effectively.

### Safety Observations

Analyzes reported observations of safety concerns and near misses.

### Employee Feedback

Organizes and presents qualitative employee comments, concerns, and recommendations.

### AI Insights

Provides a dedicated area for exploring how AI-assisted analysis could support future review of qualitative survey feedback and recurring themes.

### Measure Check

A backend testing page developed specifically to verify analytical measures and confirm that calculations behaved correctly.

### Backend Validation

A dedicated quality-assurance page used to validate response totals, scoring logic, missing values, duplicates, and other data-quality conditions.

---

## Quality Assurance

One of my priorities throughout development was ensuring that the dashboard was not only visually effective but analytically reliable.

I created dedicated backend validation processes to test:

- Total response counts
- Expected versus actual Likert responses
- Favorable, neutral, and unfavorable calculations
- Survey-domain calculations
- Department filtering
- Relationship behavior
- Missing responses
- Duplicate responses
- Written-comment counts
- Participation calculations
- Individual DAX measures

This validation layer helped ensure that the leadership-facing visuals were supported by calculations that had been independently tested.

---

## Dashboard Design

The dashboard was designed with executive usability in mind.

Rather than simply displaying every available metric, I organized the report into focused pages that allow leadership to move from high-level organizational indicators into more detailed analysis.

Design priorities included:

- Clear visual hierarchy
- Consistent navigation
- Executive-level KPI presentation
- Interactive filtering
- Department-level analysis
- Simple interpretation of Likert-scale results
- Integration of quantitative and qualitative findings
- Easy movement between organizational trends and detailed feedback

---

## Project Impact

Within the first two weeks of the official survey launch, approximately **one in five MAA employees participated**.

I presented the completed survey findings and live Power BI dashboard to senior leadership.

Following the presentation, executives and managers requested continued access to the dashboard and expressed interest in how the solution had been developed.

The project was designed not only as a one-time survey report, but as a framework that could support future Safety Culture Surveys and allow leadership to compare future results against an established baseline.

---

## Skills Demonstrated

### Data & Business Intelligence
- Power BI
- DAX
- Power Query
- Data Modeling
- Data Transformation
- Data Validation
- Business Intelligence
- Dashboard Development
- KPI Development

### Analytics
- Survey Analytics
- Quantitative Analysis
- Qualitative Analysis
- Likert-Scale Analysis
- Trend Identification
- Data Quality Assurance

### Project & Business Skills
- End-to-End Project Ownership
- Requirements Development
- Risk Management
- Stakeholder Communication
- Executive Presentation
- User Interface Design
- Leadership Reporting
- Project Management

---

## Portfolio Version

The dashboard presented in this repository is a **mock-data portfolio version** created to demonstrate the technical architecture, analytical methodology, dashboard design, DAX development, validation framework, and overall scope of the original project.

The Power BI source file is not distributed through this repository.

### [View the Full Power BI Dashboard](./MAA-Safety-Culture-PowerBI-Dashboard.pdf)
