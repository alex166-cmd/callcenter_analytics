Call Centre Analytics Dashboard — FY 2024
Data Analyst Portfolio Project | Fiscal Year 2024

Table of Contents
Business Problem
Project Objective
Dataset Overview
Key Metrics & KPIs
Dashboard Overview
Key Findings & Insights
Agent Performance Analysis
Recommendations
Tools & Technologies
File Structure
How to Use
Author
Business Problem
Call centres are critical customer touchpoints for telecom companies. Operational inefficiencies — such as high call abandonment, low first-call resolution, or agent underperformance — directly impact customer satisfaction, revenue, and brand loyalty.

The call centre handled over 219,000 inbound calls in FY 2024 across a 20-agent workforce. Without a consolidated view of performance trends, leadership struggled to:

Identify months with service deterioration before issues escalated
Pinpoint which agents and teams needed coaching or recognition
Correlate operational metrics (SLA, FCR, AHT) with revenue outcomes
Forecast staffing needs based on call volume patterns
Project Objective
Build an end-to-end Call Centre Performance Analytics Dashboard in Excel that:

Consolidates 12 months of raw call data into a single, actionable view
Tracks key operational KPIs (SLA, FCR, CSAT, Abandon Rate, AHT)
Surfaces agent-level and team-level performance tiers
Reveals monthly trends in revenue, escalations, and customer satisfaction
Supports data-driven decisions on staffing, coaching, and process improvement
Dataset Overview
Sheet	Description
Raw_Data	Monthly granular records: call volumes, handle times, SLA, CSAT, revenue
KPI_Summary	Calculated KPIs per month including MoM revenue change
Chart_Data	Clean chart-ready extract of key metrics
Agent_Performance	Individual agent metrics, team assignment, and performance tier classification
Dashboard	Executive-level summary view with KPI cards and visualisations
Period Covered: January 2024 – December 2024 (FY 2024)

Total Records: 12 monthly periods × 15 KPI columns + 20 agent profiles

Key Metrics & KPIs
Metric	Definition	FY 2024 Result
Total Calls	All inbound calls received in the period	219,816
Calls Answered	Calls successfully connected to an agent	203,161
Calls Abandoned	Calls disconnected before reaching an agent	16,655
Abandon Rate	Abandoned ÷ Total Calls	7.59%
Average Handle Time (AHT)	Avg. seconds per call (talk + hold + wrap)	264.8 sec
First Call Resolution (FCR)	% of issues resolved without a callback	76.4%
CSAT Score	Customer satisfaction (1–5 scale)	4.08 / 5.0
Average Speed of Answer (ASA)	Avg. seconds before a call is answered	58.5 sec
SLA %	% of calls answered within the target time	82.1%
Occupancy %	% of agent time spent on calls vs. idle	83.3%
Escalations	Calls escalated to a supervisor or senior tier	2,149
Complaints	Formal complaints lodged by customers	1,274
Total Revenue (MWK)	Revenue attributed to the call centre	MWK 137,043,469
Dashboard Overview
The Excel dashboard provides an at-a-glance executive summary alongside interactive trend charts.

KPI Summary Cards (Top Row)
Eight headline KPI cards display FY 2024 annual totals and averages:

Total Calls · Calls Answered · Avg Abandon Rate · Avg FCR
Avg CSAT Score · Avg SLA % · Total Escalations · Total Revenue (MWK)
Visualisations Included
Chart	Purpose
Monthly Call Volume (Answered vs Abandoned)	Tracks call traffic and service failure points across the year
Monthly SLA % Trend	Monitors service level agreement compliance month-on-month
FCR % Trend	Shows first-call resolution rate movement over time
CSAT Score Trend	Customer satisfaction progression across 12 months
Monthly Revenue (MWK)	Correlates operational performance with revenue generation
Monthly Escalations	Highlights months with high supervisor intervention
Agent Performance Tier Distribution	Classifies agents into Top Performer / Meets Target / Needs Coaching
Team-Level Comparison	Compares Team A, B, C, D across FCR, CSAT, and Calls Handled
Key Findings & Insights
1. Call Volume Peaks in Q4
November recorded the highest call volume (20,406 calls), followed by October (20,025). This seasonal surge correlated with increased escalations (295 in November — the highest of the year) and a dip in FCR to 73.3%, suggesting the team was stretched.

2. Abandon Rate Spikes in Q3–Q4
Three months — May (10.8%), September (10.9%), and October (11.5%) — had abandon rates significantly above the annual average of 7.59%. These months coincide with lower staffing levels and longer ASA times, pointing to a capacity constraint.

3. SLA Compliance is Inconsistent
SLA performance ranged from 74.0% (January) to 93.0% (November). Despite November's high volume, SLA improved — suggesting temporary staffing or process interventions were deployed. January and March remain outliers that need investigation.

4. Revenue Does Not Always Track Call Volume
September had the highest single-month revenue (MWK 13.84M) despite having fewer calls (16,692) than peak months, indicating that call quality and FCR efficiency drive revenue more than raw volume.

5. CSAT Improved Mid-Year
CSAT scores were lowest in January (3.6/5) and May (3.6/5), but climbed significantly in July (4.7/5) and September (4.5/5). This suggests mid-year process changes or coaching had a positive effect on customer experience.

6. Escalations Concentrated in Q3–Q4
Escalations surged from July (244) through November (295), potentially linked to complex customer issues, new product launches, or agent skill gaps during high-volume months.

Agent Performance Analysis
20 agents across Team A, B, C, and D were evaluated across six dimensions:

Performance Tier	Count	Key Traits
Top Performer	6 agents	High FCR, CSAT ≥ 4.6, consistent call volume
Meets Target	11 agents	Average-to-good across metrics, minimal coaching risk
Needs Coaching	3 agents	Low FCR or CSAT < 3.5, elevated complaints
Standout Agents:

ID 018 — Highest FCR at 93.7%, indicating exceptional issue resolution ability
ID 013 — FCR 87.9%, CSAT 4.7 — strong balanced performer (Top Performer)
ID 019 — Highest call volume (1,892 calls), CSAT 4.8, escalations managed
Coaching Flags:

ID 005 — CSAT 3.1 (lowest), AHT 322 sec, occupancy only 65.2%
ID 012 — FCR 65.0%, 37 complaints — needs structured support plan
ID 006 — CSAT 3.4, high AHT (298 sec) — efficiency coaching recommended
Recommendations
Address Q3–Q4 Capacity Gaps — Hire seasonal agents or redistribute workloads in September–November to reduce abandon rates and escalations during peak periods.

Investigate January & March SLA Failures — Both months had SLA below 75%. A root cause analysis (staffing, system downtime, call routing) should be conducted.

Implement Targeted Coaching for 3 Agents — ID 005, 006, and 012 show consistent underperformance. A 60-day coaching plan with bi-weekly reviews is recommended.

Leverage Top Performers as Peer Coaches — Agents like ID 013, ID 019, and ID 003 demonstrate best practices in FCR and CSAT that can be institutionalised through knowledge-sharing sessions.

Correlate Revenue Drivers — September's high revenue despite low volume warrants a deeper product/call-type analysis to replicate conditions in lower-performing months.

Set FCR Improvement Target — At 76.4%, FCR is below the industry benchmark of ~80%. A structured knowledge base and better call scripting can close this gap.

Tools & Technologies
Tool	Usage
Microsoft Excel	Data storage, KPI calculation, dashboard build, charting
Excel PivotTables	KPI aggregations and team-level summaries
Excel Charts	Line charts, bar charts, donut chart for visualisations
Conditional Formatting	Performance tier colour coding and KPI highlighting
Excel Formulas	AVERAGEIF, SUMIF, IF, TEXT, percentage calculations
File Structure
call-centre-analytics/
│
├── CallCentre_Dashboard.xlsx       # Main Excel dashboard file
│   ├── Dashboard                   # Executive summary view
│   ├── Raw_Data                    # Monthly raw data (12 months)
│   ├── KPI_Summary                 # Calculated KPI table with MoM changes
│   ├── Chart_Data                  # Clean data for chart series
│   └── Agent_Performance           # Individual agent metrics & tiers
│
├── Call_Centre_Dashboard_Report.pdf   # Full PDF interpretation report
└── README.md                          # This file
🚀 How to Use
Clone or download this repository
Open CallCentre_Dashboard.xlsx in Microsoft Excel (2016 or later recommended)
Navigate to the Dashboard sheet for the executive summary view
Review the KPI_Summary sheet for monthly trend breakdowns
Check the Agent_Performance sheet to evaluate individual agent metrics
Refer to Call_Centre_Dashboard_Report.pdf for the full written interpretation
Author
Data Analyst Portfolio Project Designed to demonstrate skills in data cleaning, KPI development, dashboard design, and business insight generation using call centre operations data.

FY 2024 | Call Centre Analytics | Built with Microsoft Excel
## Author
Alex Maseko
Data Analyst | Applied Statistician
