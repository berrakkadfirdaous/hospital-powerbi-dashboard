# Hospital Data Analysis Dashboard (Power BI)
## Project Overview
This project is a Power BI dashboard developed to analyze hospital activity, including patient consultations, services, and revenue.  
It aims to provide clear insights for decision-making through data visualization and reporting.
## Objectives
- Analyze hospital consultations data
- Track revenue and patient activity
- Identify trends by service, department, and city
- Build an interactive dashboard for decision support
## Tools & Technologies
- Power BI
- Power Query (Data Cleaning)
- DAX (Measures & Calculations)
- Data Modeling (Star Schema)
##  Project Structure
hospital-project/
│
├── hospital_dashboard.pbix
├── report.pdf
├── README.md
└── screenshots/
## Data Preparation
- Imported datasets: Patients, Services, Consultations, Calendar
- Cleaned missing values and corrected data types
- Created additional columns: Year, Month Name
##  Data Model
A **star schema** was used:
- Fact table: Consultations
- Dimension tables: Patients, Services, Calendar

Relationships:
- Consultations ↔ Patients
- Consultations ↔ Services
- Consultations ↔ Calendar
##  Key Measures (DAX)
- Total Consultations
- Total Revenue
- Distinct Patients
##  Dashboard Preview
### Exploration Page
![Exploration](screenshots/exploration.png)

### Summary Page
![Summary](screenshots/synthese.png)

###  Drillthrough Page
![Details](screenshots/drillthrough.png)

##  Key Insights
- Monthly evolution of consultations
- Revenue distribution per service
- Patient distribution by city and department
- Service performance comparison
##  Author
- Trainee in Artificial Intelligence (Data Analyst specialization)
- OFPPT ( Institute specialized in offshoring professions ) , Morocco 🇲🇦 

##  Note
This project is part of academic training and portfolio development in data analysis and Power BI.
