# HR Analytics Dashboard

## **Project Overview**

This project is an interactive **HR Analytics Dashboard** built using **Power BI** and **Tableau**. It provides insights into employee performance, attrition trends, job satisfaction, and salary distribution using CSV-based datasets. The dashboard includes KPIs such as employee tenure, attrition rates, and performance ratings to help HR teams make data-driven decisions.

## **1. Project Planning & Management**

### **Objective:**

Build an interactive Power BI dashboard to analyze employee performance, satisfaction, and retention trends.

### **Scope:**

- Analyze employee demographics, performance ratings, and attrition.
- Include KPIs like average salary, job satisfaction levels, attrition rates, and tenure trends.

### **Project Plan:**

- **Timeline:** Gantt chart approach with stages like data transformation, modeling, and visualization.
- **Milestones:** Data preparation, dashboard design, interactivity, and final review.
- **Resources:** Power BI, SQL for data transformation, CSV files.

### **Task Assignment:**

- **Data Cleaning & Transformation:** Yassen Khaled Lotfy Ahmed
- **Dashboard Design & KPIs:** Kerolos Hani Nabil Zaki
- **Report Storytelling & Interactivity:** Yousef Abdalla Agaiby Faleh, Mohammad Walid Hosny Hussein
- **Tableau Implementation:** Taghrid Yasser Gomaa Eid
- **Documentation & Final Report:** Noreen Mohamed Ashraf Hassen

### **Risk Assessment & Mitigation:**

- **Risk:** Inconsistent employee data → **Solution:** Data validation techniques.
- **Risk:** Dashboard performance issues → **Solution:** Optimize DAX queries and data model.

### **KPIs:**

- Employee attrition rate
- Average salary per job role
- Performance rating distribution
- Job satisfaction levels
- Years at company vs. attrition trends

## **2. Dataset Overview**

### **CSV Files Used:**

- **Employee.csv**: Contains employee details (EmployeeID, Name, Age, Gender, etc.).
- **EducationLevel.csv**: Employee education levels.
- **PerformanceRating.csv**: Performance rating scores.
- **RatingLevel.csv**: Rating categories.
- **SatisfiedLevel.csv**: Employee satisfaction levels.

### **Primary Dataset Structure (Employee.csv):**

| Column Name             | Description                               |
| ----------------------- | ----------------------------------------- |
| EmployeeID              | Unique identifier for each employee       |
| FirstName               | Employee’s first name                     |
| LastName                | Employee’s last name                      |
| Gender                  | Employee gender                           |
| Age                     | Employee age                              |
| BusinessTravel          | Travel frequency                          |
| Department              | Employee's department                     |
| DistanceFromHome        | Distance from home to work (KM)           |
| State                   | Location state                            |
| Ethnicity               | Employee ethnicity                        |
| Education               | Education level                           |
| EducationField          | Field of study                            |
| JobRole                 | Job position                              |
| MaritalStatus           | Marital status                            |
| Salary                  | Employee salary                           |
| StockOptionLevel        | Stock options granted                     |
| OverTime                | Whether the employee works overtime       |
| HireDate                | Date of hiring                            |
| Attrition               | Whether the employee has left the company |
| YearsAtCompany          | Total years with the company              |
| YearsInMostRecentRole   | Years in current role                     |
| YearsSinceLastPromotion | Years since last promotion                |
| YearsWithCurrManager    | Years with current manager                |

## **3. Data Preparation & Cleaning**

### **Data Preprocessing Steps:**

1. **Handling Missing Values:**
   - Identify and fill or remove null values in important columns.
2. **Data Formatting:**
   - Convert `HireDate` to datetime format.
   - Standardize categorical values (e.g., `Yes/No` to `1/0`).
3. **Merging Datasets:**
   - Use `EmployeeID` as the primary key to join relevant CSV files.
4. **Creating Calculated Columns:**
   - `Employee Tenure` = `Current Year - Hire Year`
   - `Attrition Status` = Binary classification for attrition analysis.

## **4. System Analysis & Design**

### **Problem Statement:**

HR teams struggle to get real-time insights on employee performance and attrition trends.

### **Use Case Diagram:**

Actors include HR Manager, Data Analyst, and CEO.

### **Software Architecture:**

Power BI with data imported from CSV files.

### **Database Design & Data Modeling:**

- **ER Diagram:** Tables for Employees, Performance Ratings, Satisfaction Levels, and Attrition.
- **Logical & Physical Schema:** Primary keys, foreign keys, indexing for performance.

### **Data Flow & System Behavior:**

- **DFD:** Shows data extraction from CSV, transformation in Power Query, and visualization in Power BI.
- **Activity Diagram:** Steps from loading data to generating insights.

### **UI/UX Design & Prototyping:**

- **Wireframes:** Dashboard layout with KPIs on top, filters on the left, and graphs below.
- **UI/UX Guidelines:** Professional color palette, interactive slicers, and readable fonts.

## **5. System Deployment & Integration**

### **Technology Stack:**

Power BI, CSV files, DAX for calculations.

### **Deployment Diagram:**

Data sources to Power BI, cloud-based sharing (Power BI Service).

### **Component Diagram:**

Shows dataset, data model, visualizations, and reports.

## **6. Contributors**

- Mohammad Walid Hosny Hussein
- Yassen Khaled Lotfy Ahmed
- Kerolos Hani Nabil Zaki
- Yousef Abdalla Agaiby Faleh
- Taghrid Yasser Gomaa Eid
- Noreen Mohamed Ashraf Hassen
