# HR Analytics Dashboard

## Project Overview
This project is an interactive **HR Analytics Dashboard** built using **Power BI** and **Tableau**. It provides insights into employee performance, attrition trends, job satisfaction, and salary distribution using CSV-based datasets. The dashboard includes KPIs such as employee tenure, attrition rates, and performance ratings to help HR teams make data-driven decisions.

Project Files  
All datasets, dashboards, and related resources are available in the shared Google Drive folder:
 [👉 Access Project Files on Google Drive](https://drive.google.com/drive/folders/1aULA5kmbX6lqfPdpashVaoz3gPZ_Pb6O?usp=sharing)

---

## Features
- **Employee Performance Analysis**: Track performance ratings and trends.
- **Attrition Rate Insights**: Identify patterns in employee attrition.
- **Job Satisfaction Trends**: Evaluate satisfaction levels across departments.
- **Salary Distribution Overview**: Analyze salary trends by role and department.
- **Interactive Dashboards**: Filter and visualize key metrics dynamically.

---

## Project Planning & Management

### **Objective**
Build an interactive dashboard to analyze employee performance, satisfaction, and retention trends.

### **Scope**
- Analyze employee demographics, performance ratings, and attrition.
- Include KPIs like **average salary, job satisfaction levels, attrition rates, and tenure trends**.

### **Project Timeline (Milestones)**
| Milestone | Task | Start Date | End Date |
|-----------|------|------------|----------|
| Data Preparation | Collect and clean employee datasets | March 1, 2025 | March 7, 2025 |
| Dashboard Design | Define KPIs | March 8, 2025 | March 14, 2025 |
| Data Modeling | Transform and integrate datasets using Power Query | March 15, 2025 | March 21, 2025 |
| Visualization Development | Build Power BI and Tableau dashboards | March 22, 2025 | March 28, 2025 |
| Interactivity & Refinement | Implement filters, slicers, and optimizations | March 29, 2025 | April 4, 2025 |
| Final Review & Documentation | Test, validate insights, and finalize the report | April 5, 2025 | April 10, 2025 |

### **Task Assignments**
- **Data Cleaning & Transformation**: Mohammad Walid Hosny Hussein
- **Dashboard Design & KPIs**: Kerolos Hani Nabil Zaki, Yassen Khaled Lotfy Ahmed
- **Report Storytelling & Interactivity**: Yousef Abdalla Agaiby Faleh , Noreen Mohamed Ashraf Hassen
- **Tableau Implementation**: Taghrid Yasser Gomaa Eid
- **Documentation & Final Report**: All Team Members

### **Risk Assessment & Mitigation**
- **Risk: Inconsistent employee data** → Solution: Data validation techniques.
- **Risk: Dashboard performance issues** → Solution: Optimize DAX queries and data model.

---

## Dataset Overview
The project uses multiple CSV datasets, including:
- **Employee.csv**: Contains details such as EmployeeID, Name, Age, Gender, Job Role, etc.
- **EducationLevel.csv**: Employee education levels.
- **PerformanceRating.csv**: Performance rating scores.
- **RatingLevel.csv**: Rating categories.
- **SatisfiedLevel.csv**: Employee satisfaction levels.

### **Primary Dataset Structure (Employee.csv)**
| Column Name | Description |
|-------------|------------|
| EmployeeID | Unique identifier for each employee |
| FirstName | Employee’s first name |
| LastName | Employee’s last name |
| Gender | Employee gender |
| Age | Employee age |
| BusinessTravel | Travel frequency |
| Department | Employee's department |
| DistanceFromHome | Distance from home to work (KM) |
| State | Location state |
| Ethnicity | Employee ethnicity |
| Education | Education level |
| EducationField | Field of study |
| JobRole | Job position |
| MaritalStatus | Marital status |
| Salary | Employee salary |
| StockOptionLevel | Stock options granted |
| OverTime | Whether the employee works overtime |
| HireDate | Date of hiring |
| Attrition | Whether the employee has left the company |
| YearsAtCompany | Total years with the company |
| YearsInMostRecentRole | Years in current role |
| YearsSinceLastPromotion | Years since last promotion |
| YearsWithCurrManager | Years with current manager |

---

## Data Preparation & Cleaning
1. **Handling Missing Values**:
   - Identify and fill or remove null values in important columns.
2. **Data Formatting**:
   - Convert HireDate to datetime format.
   - Standardize categorical values (e.g., Yes/No to 1/0).
3. **Merging Datasets**:
   - Use EmployeeID as the primary key to join relevant CSV files.
4. **Creating Calculated Columns**:
   - `Employee Tenure = Current Year - Hire Year`
   - `Attrition Status = Binary classification for attrition analysis`

---

## System Design
### **Problem Statement**
HR teams struggle to get real-time insights into employee performance and attrition trends.

### **Use Case Diagram**
Actors include **HR Manager, Data Analyst, and CEO**.

### **Software Architecture**
Power BI with data imported from CSV files.

### **Database Design & Data Modeling**
- **ER Diagram**: Tables for Employees, Performance Ratings, Satisfaction Levels, and Attrition.
- **Logical & Physical Schema**: Primary keys, foreign keys, indexing for performance.

### **Data Flow & System Behavior**
- **DFD (Data Flow Diagram)**: Shows data extraction from CSV, transformation in Power Query, and visualization in Power BI.
- **Activity Diagram**: Steps from loading data to generating insights.

### **UI/UX Design & Prototyping**
- **Wireframes**: Dashboard layout with KPIs on top, filters on the left, and graphs below.
- **UI/UX Guidelines**: Professional color palette, interactive slicers, and readable fonts.

---

## System Deployment & Integration
### **Technology Stack**
- **Data Visualization**: Power BI, Tableau
- **Data Processing**: Power Query, DAX
- **Data Sources**: CSV files

### **Deployment Diagram**
- Data sources → Power BI → Cloud-based sharing (Power BI Service)

### **Component Diagram**
- Shows datasets, data model, visualizations, and reports.

---

## Key Performance Indicators (KPIs)
- **Employee attrition rate**
- **Average salary per job role**
- **Performance rating distribution**
- **Job satisfaction levels**
- **Years at company vs. attrition trends**

---

## Contributors
- **Mohammad Walid Hosny Hussein**
- **Yassen Khaled Lotfy Ahmed**
- **Kerolos Hani Nabil Zaki**
- **Yousef Abdalla Agaiby Faleh**
- **Taghrid Yasser Gomaa Eid**
- **Noreen Mohamed Ashraf Hassen**

---

## How to Use
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-repo/hr-analytics-dashboard.git
   ```
2. **Open the Power BI or Tableau Dashboard**
3. **Interact with Filters & Visuals**
4. **Analyze Trends & Generate Reports**

---



