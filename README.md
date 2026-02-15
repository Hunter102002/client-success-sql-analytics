# Client Success SQL Analytics

## Objective

Designed and implemented a practical SQL reporting project to model a customer support environment and surface actionable insights used in Client Success workflows.
Built using SQLite and SQL, this project simulates real internal reporting used by CSMs and Support Ops teams to track backlog risk, SLA performance, customer health, and agent workload.

The goal was to practice writing business-relevant SQL queries and build reporting outputs that mirror how support data is used in a corporate environment.

## Reports Included

1.	Calendly → Welcome Prep Email
2.	New Demo Request → Automated Email Sequence
3.	New Client → Welcome Email & Onboarding Guide
4.	Closed Handoff

### Skills Learned

- SQL Data Modeling
Designed a relational schema to represent customers, agents, tickets, categories, and ticket history.

- Operational Reporting
Built queries that mirror real Client Success and Support Ops dashboards.

- Business Analysis
Translated raw support data into actionable insights for backlog management, escalation prioritization, and customer health.

- Data Quality and QA Signals
Used reopen rates, aging tickets, and status history to surface potential quality issues.

- Stakeholder Reporting
Structured outputs that could be used in QBRs, client calls, and internal reporting.

### Tools Used

- SQLite
Local relational database used to model support operations and reporting data.

- SQL
Core language used to write reporting queries, joins, aggregations, and time-based metrics.

- DB Management Tool
Used a local SQLite client to create schema, seed test data, and run reports.

### Outcome

- Built a reusable SQL reporting framework that simulates how Client Success teams monitor account health and operational risk
- Improved comfort writing multi-table joins, aggregations, and time-based analysis
- Created realistic reporting outputs suitable for portfolio and interview walkthroughs
- Demonstrated practical SQL usage tied to business workflows rather than academic exercises
- Established a foundation for expanding into dashboards or BI tools in the future

Notes

All data in this project is fictional and used for demonstration purposes only.
Company names and individuals are placeholders and do not represent real customer data.

## Steps

Create the database tables

CUSTOMERS - <img width="1473" height="1307" alt="Screenshot 2026-02-14 213716" src="https://github.com/user-attachments/assets/b2a885bf-aeba-4a4d-8833-8ef6a5ee936a" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

AGENTS - <img width="1610" height="1239" alt="Screenshot 2026-02-14 213742" src="https://github.com/user-attachments/assets/abb45edd-d818-4d01-a440-5a58aeaffe01" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

TICKET CATEGORIES - <img width="1468" height="1183" alt="Screenshot 2026-02-14 213802" src="https://github.com/user-attachments/assets/ccea7a70-1ddc-463f-9513-cb92fce721fe" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SUPPORT TICKETS - <img width="1595" height="1509" alt="Screenshot 2026-02-14 213526" src="https://github.com/user-attachments/assets/cd725c0f-e5ec-4167-a2b8-87282f66c7ae" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

TICKET HISTORY - <img width="1509" height="1272" alt="Screenshot 2026-02-14 213850" src="https://github.com/user-attachments/assets/0ddb1337-a095-4aa0-a0eb-79f57b9f9472" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

INDEXES - <img width="1547" height="1178" alt="Screenshot 2026-02-14 213951" src="https://github.com/user-attachments/assets/307e73ee-41c0-4a09-b920-481faf6d4a92" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




