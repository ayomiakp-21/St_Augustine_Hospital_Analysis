# St_Augustine_Hospital_Analysis

## Dataset Used
- <a href="https://github.com/ayomiakp-21/St_Augustine_Hospital_Analysis/blob/main/St.%20Augustine's%20Hospital.xlsx">Dataset View</a>

## Interactive Dashboard
- <a href="https://app.powerbi.com/reportEmbed?reportId=e672fa7e-8338-48e2-b290-17606315a6b0&autoAuth=true&ctid=ff0f3e3a-3e53-454f-b2b5-6c68753b8ee4">Interactive Dashboard</a>

## Project Goals

- Analyze hospital performance using Power BI
- Identify operational inefficiencies and performance bottlenecks
- Optimize resource utilization and patient flow
- Support data-driven decision-making with predictive insights
- Improve patient outcomes and overall service quality

## Overall Hospital Operations

- Departments Analyzed: 4 (Oncology, Cardiology, Emergencyand Pediatrics)
- Admitted Percentage: 66.77%, meaning two-thirds of patients seen are admitted
- Waiting Cases: 34.2%, which is relatively high and may indicate bottlenecks in patient processing or limited bed availability
- Hospital utilization is strong but high waiting cases suggest operational constraints that could affect patient satisfaction

##  Bed Occupancy by Department

- Pediatrics operates near full capacity with a 91.67% bed occupancy rate, signaling sustained high demand and potential capacity constraints that may impact service delivery if not addressed
- Cardiology maintains a high utilization level at 88.57%, indicating strong demand and efficient use of available resources, though continued monitoring is required to prevent overcrowding
- Oncology records a 76.25% occupancy rate, reflecting balanced utilization with some flexibility to absorb fluctuations in patient volume
- Emergency shows a markedly low occupancy rate of 29%, which may mean quick discharges  but it could also point to resource over-allocation, lower admission rates or opportunities to reallocate resources to higher-demand departments

## Admission Status by Department

- Oncology records the highest number of admissions at 131, closely followed by Cardiology with 128 admissions, indicating strong and consistent demand for specialized care services
- The Emergency department reports 122 admissions, reflecting steady patient inflow that aligns with its role as a primary access point for acute care
- Pediatrics follows with 119 admissions, showing slightly lower but still comparable demand relative to other departments
- Overall, admissions are fairly balanced across all departments, suggesting stable and evenly distributed demand for hospital services, with no single department experiencing extreme pressure or underutilization

## Visits by Time and Day

- Visits peak between 8:00 AM and 3:00 PM with the heaviest activity around 12:00 PM – 2:00 PM
- Weekdays (Tuesday–Thursday) show the highest visit density
- Patient inflow is concentrated during midday hours and midweek, creating predictable peak load times for staffing and scheduling

## Patient Analysis 

- The hospital has a total patient count of 30, which has remained stable with no significant month-to-month fluctuations, indicating consistent service demand
- New patient intake is high at 29, reflecting steady growth and ongoing community engagement, while 30 returning patients demonstrate strong retention and patient loyalty
- However, the readmission rate of 34.6% is moderately high, suggesting the presence of chronic illness cases or potential quality-of-care issues that warrant further investigation 
- Overall, while patient retention is strong, the elevated readmission rate highlights an area for operational and clinical review to improve outcomes

## Visits by Month

- Total Visits: 500 annually
- Peak Months: Around July and December, suggesting seasonal surges (possibly flu season or year-end checkups)
- Low Months: March and October
- Hospital demand fluctuates seasonally ,staff scheduling and supply inventory should adjust accordingly

## Patient Demographics

- The largest patient group falls within the 18–35 age range, comprising 11 patients, indicating that young adults form the core of the hospital’s patient base 
- A significant portion of patients, 8 in total, are aged 60 and above, highlighting a notable elderly population that may require focused chronic disease management and geriatric care services
- Pediatric patients (0–18 years) are stable at 6 individuals, suggesting consistent demand for pediatric care
- The 35–60 age group represents the smallest segment with 5 patients, indicating lower utilization among middle-aged adults
- Overall, the hospital serves a diverse demographic, with the bulk of patients being young adults and seniors, underscoring the need for a broad range of services spanning preventive care, acute treatment, and chronic disease management

## Patient Geography

- Top Locations: United Kingdom, France, Ireland, Spain
- Suggests international patient base, possibly due to specialized treatment offerings or medical tourism
- International reach presents opportunities for brand expansion and premium care services

## Chronic Illness & Marital Status

- Many patients have chronic conditions, particularly among married males
- Average visit duration ranges 32–42 minutes, indicating moderate consultation complexity
- Chronic illness management programs and longer consultations align with patient needs but these require efficient doctor scheduling and support systems

## Doctors Performance

- The hospital operates with a total of 10 doctors, each managing an average of 50 patient visits, indicating a moderate and balanced patient workload. Despite this manageable volume, the overall patient recovery rate stands at 22.4%, which is low for a healthcare setting
- This disparity between workload and outcomes suggests underlying inefficiencies in clinical processes, including treatment protocols, patient-to-doctor allocation or post-treatment follow-up practices

### Doctor-Level Performance Variance

- Top Performer: Samantha Singleton (highest recovery %)
- High Visit Load: Kimberly Lin (64 visits), Gregory Chen and Kelly Green (55 visits each)
- Recovery % Spread: Ranges roughly from 15% to 30%
- There is significant inconsistency in doctor outcomes. Some doctors are handling more patients without proportionally better recovery rates, which can hurt both patient outcomes and staff morale

### Deceased % by Doctors

- Doctors like Jamie Smith and Kelly Green show higher deceased percentages
- Doctors with moderate workloads sometimes outperform those with heavier caseloads
- Patient outcomes may be negatively impacted by workload pressure, specialization mismatch or delayed interventions

### Gender Distribution

- Male: 50% , Female: 50%
- Good gender balance. Performance gaps are not gender-driven, which is useful for fair policy design

## Treatment Analysis

### Overall Treatment Performance

- Treatments Covered: 6
- Overall Treatment Success Rate: 77.4%
- Average Treatment Duration: 48m.33s 
- Average Treatment Cost: $683.33
- Readmission Rate: 34.6%
- Success rate looks decent on paper but the high readmission rate is a red flag. That can translate to treatments working initially but patients are coming back due to complications, incomplete recovery or poor follow-up care

### Treatment Success by Department

- Top Performers are Pediatrics (90%) and Cardiology (88%) while Underperformers are Oncology (72%) and Emergency (65%)
- Emergency and Oncology treatments are less predictable and higher risk, but the gap is still too wide. This points to inconsistent protocols, resource strain or possibility of rushed treatment decisions

### Treatment-Level Effectiveness

-The treatment portfolio includes 6 treatment types, with an overall treatment success rate of 77.4%. While this indicates moderate effectiveness, it is offset by a high readmission rate of 34.6%, signaling gaps in post-treatment care, follow-up protocols or treatment suitability
- Diagnostic treatments such as X-Ray, ECG and MRI scans demonstrate consistently high success rates (above 90%), indicating strong reliability and low risk. In contrast, complex and invasive treatments such as Chemotherapy (72%) and Heart Surgery (75%) show lower success rates and contribute disproportionately to readmissions and costs
- Department-level analysis shows higher success rates in Pediatrics and Cardiology, while Emergency and Oncology departments underperform. This pattern reflects the operational challenges of time-sensitive and high-severity cases, as well as potential inconsistencies in emergency treatment workflows
- Chronic illness trends reveal a mid-year increase in cases, suggesting predictable seasonal demand that is not currently being addressed through proactive care planning

# Strategic Recommendations

## Operational Efficiency

1. Reduce Waiting Cases (34.2%)

- Implement an online appointment and triage system to prioritize emergency and chronic cases
- Reassess staff allocation during peak hours (12–2 PM)
- Review discharge and admission workflows to speed up bed turnover

2. Balance Department Capacity
 
- Pediatrics and Cardiology may require additional beds or staffing to prevent overcapacity issues
- Consider shifting non-critical patients from high-demand units to departments with available capacity (e.g., Oncology)

##  Clinical and Quality Improvement

3. Address Readmission Rate (34.6%)

- Conduct root cause analysis on common readmission cases (e.g., follow-up compliance, chronic disease relapse)
- Introduce a 42-72 hour post-discharge follow-up programs and teleconsultations for high-risk patients
- Strengthen patient education on medication adherence and home care

4. Enhance Preventive Care for Key Age Groups

- Develop wellness and screening packages targeting: Young adults (fitness, mental health) and Seniors (chronic illness monitoring, rehabilitation)
- Launch chronic illness management plans before mid-year spike
- Assign care coordinators to high-risk patients
- Partner with local employers for corporate wellness programs

## Resource & Staff Management

5. Optimize Staffing Patterns/ Standardize best Practices from Top Performers

- Audit treatment workflows of Samantha Singleton and Laurie York and convert them into hospital-wide treatment SOPs
- Provide clinical reviews and mentorship for doctors with high deceased % and Low recovery %
- Redistribute cases based on doctor recovery performance, not availability alone
- Align shift schedules with visit peaks (midday and weekdays)
- Offer flexible shifts to handle morning rush hours effectively
- Ensure pediatric and cardiology units have adequate nursing and diagnostic support

6. Departmental Resource Reallocation

- Evaluate Emergency department resources , reduce excess beds or shift staff to higher-demand departments

## Strategic Growth

7. Expand International Patient Services

- Strengthen partnerships with overseas healthcare agents
- Offer concierge or telehealth pre-arrival consultations
- Highlight successful specialty treatments (e.g., cardiology, oncology) in marketing campaigns

8. Implement Predictive Analytics

- Use patient data to forecast seasonal demand and adjust supply chains (medications, staff, beds)
- Predict readmission likelihood using chronic illness and visit history data

# Overall Business Impact 

By implementing these recommendations, the hospital can achieve:

1. Financial Impacts

- Higher patient throughput without additional infrastructure
- Increased revenue from preventive care and international services
- Reduced operational costs from smart staffing and resource optimization

2. Operational Impacts

- Streamlined workflow and reduced delays
- More efficient use of beds, staff and equipment

3. Clinical Impacts

- Better patient outcomes and lower readmissions
- Higher compliance with healthcare quality standards

4. Customer Experience Impacts

- Shorter wait times
- Improved satisfaction and loyalty
- Enhanced hospital reputation and trust

# Tools Used

- Power BI for dashboard design and interactive analytics
- Data Modeling and DAX Measures for KPIs


<img width="1282" height="700" alt="St Augstine Doctors Analysis Dashboard" src="https://github.com/user-attachments/assets/5e81f484-5e96-4c61-b3cd-34e6a196771e" />

<img width="1278" height="688" alt="St Augustine Department Analysis Dashboard" src="https://github.com/user-attachments/assets/eea7dbca-6b6a-4a85-9fb8-a66fea571991" />

<img width="1250" height="693" alt="St Augustine Patient Analysis Dashboard" src="https://github.com/user-attachments/assets/2dc3d840-a684-42f9-967f-f98305d4236a" />

<img width="1271" height="689" alt="St Augustine Treatment Analysis Dashboard" src="https://github.com/user-attachments/assets/363c56b0-e831-4b9e-b2d3-4298ebb496af" />


