# HR Data Analysis

1. HR Data Analysis involves collecting, processing, and interpreting employee-related data to enhance decision-making.  
2. It helps organizations track key HR metrics like employee turnover, retention rates, and performance.  
3. By using data analytics, HR professionals can identify trends and patterns that impact workforce management.  
4. It supports talent acquisition by assessing hiring efficiency and candidate quality.  
5. HR analytics also aids in predicting future workforce needs through data-driven insights.  
6. Employee engagement and satisfaction can be measured using surveys and feedback analysis.  
7. Predictive analytics helps in reducing attrition by identifying at-risk employees.  
8. Workforce productivity and efficiency can be optimized by analyzing work patterns.  
9. HR Data Analysis ensures compliance by monitoring policies and regulations.  
10. Ultimately, it enables organizations to make strategic, evidence-based HR decisions.  

# About Datasets
# **Detailed Explanation of HR Datasets**  

## **1. HR Dataset**  
This dataset contains detailed employee information, including demographics, performance, and employment status. It is crucial for analyzing employee retention, engagement, and compensation trends.  

### **Key Columns:**  
- **EmployeeID** – Unique identifier for each employee.  
- **Name** – Employee’s full name.  
- **Department** – The department in which the employee works.  
- **JobTitle** – The employee’s position within the company.  
- **HireDate** – Date when the employee was hired.  
- **TerminationDate** – Date when the employee left the company (if applicable).  
- **Employment Status** – Whether the employee is active, terminated, or on leave.  
- **Performance Score** – Employee’s performance rating based on internal evaluations.  
- **Engagement Survey Score** – Employee engagement level, useful for analyzing satisfaction and retention.  
- **PayRate** – The salary or hourly wage of the employee.  

### **Use Cases:**  
- Identifying employees at risk of leaving based on performance and engagement trends.  
- Analyzing salary distribution and pay equity.  
- Examining workforce diversity and inclusion efforts.  

---

## **2. Production Staff Dataset**  
This dataset focuses on employees working in production roles, capturing productivity and performance metrics. It helps HR and management analyze workforce efficiency.  

### **Key Columns:**  
- **EmployeeID** – Unique identifier linked to the HR dataset.  
- **Department** – Production department where the employee works.  
- **AbutmentsPerHour** – The number of tasks/products completed per hour.  
- **ErrorRate** – The percentage of defective or incorrect products produced.  
- **Performance Score** – Individual performance rating in the production environment.  
- **Days Late in Last 30 Days** – Measures attendance trends and punctuality.  

### **Use Cases:**  
- Identifying high-performing vs. low-performing employees.  
- Analyzing the impact of absenteeism on productivity.  
- Providing insights for workforce training and development.  

---

## **3. Recruiting Costs Dataset**  
This dataset tracks recruitment-related expenses, helping HR assess cost efficiency in hiring strategies.  

### **Key Columns:**  
- **RecruitmentSource** – The channel used for hiring (e.g., job portals, employee referrals, recruitment agencies).  
- **Month** – The month for which recruitment costs are recorded.  
- **Total Cost** – The total expenses associated with each recruitment source for that month.  

### **Use Cases:**  
- Comparing the cost-effectiveness of different hiring channels.  
- Identifying the sources that result in high retention and performance.  
- Optimizing recruitment budgets to focus on the most successful hiring methods.  

---

## **4. Salary Grid Dataset**  
This dataset defines salary structures for different job roles, allowing HR to analyze pay equity and industry benchmarking.  

### **Key Columns:**  
- **JobTitle** – The role for which the salary range applies.  
- **MinSalary** – The lowest salary offered for the position.  
- **MidSalary** – The average or benchmark salary for the role.  
- **MaxSalary** – The highest salary range for the position.  

### **Use Cases:**  
- Identifying underpaid or overpaid employees based on their job title.  
- Ensuring fair and competitive compensation within the organization.  
- Supporting HR in making data-driven salary adjustment decisions.  

---
# **Business Insights from the HR Datasets**

## **1. Employee Demographics & Retention**
- **High Turnover in Production:** A significant portion of terminations occur in the **Production** department, indicating potential issues with job satisfaction or workload.  
- **Diversity Gaps:** The workforce is predominantly **White (140 employees in production alone)**, highlighting the need for better diversity initiatives.  
- **Recruitment Source Effectiveness:** **Employee referrals** are the primary hiring source, suggesting that investing in referral programs could further reduce hiring costs.  

## **2. Compensation & Pay Rate Analysis**
- **Salary Distribution Imbalance:** Some employees earn as low as **$14/hour**, while others earn up to **$80/hour**, raising concerns about **pay equity** and job satisfaction.  
- **Production Pay Rate vs. Performance:** Higher-paid production employees tend to have **better performance scores**, suggesting a link between compensation and productivity.  

## **3. Recruitment Cost Efficiency**
- **Overinvestment in Certain Sources:** Some recruitment sources cost up to **$10,980 annually** but contribute minimally to hiring. Optimizing recruitment budget allocation can **reduce hiring costs** while maintaining quality hires.  
- **Seasonal Hiring Trends:** Recruitment spikes in **February, August, and September**, indicating a pattern that HR can leverage for proactive hiring strategies.  

## **4. Performance & Productivity Trends**
- **Engagement vs. Satisfaction Mismatch:** Employee **engagement scores (3.33)** are lower than **satisfaction scores (3.89)**, suggesting that employees may feel content but not actively engaged in their roles.  
- **Production Performance Metrics:**  
  - **Abutments per Hour** increased from **9.5 to 10.2** in two weeks, indicating **positive efficiency trends**.  
  - **Daily Error Rate** is **0.9 errors/day**, requiring quality control improvements to reduce errors further.  

## **5. Salary Grid & Compensation Strategy**
- **Role-Based Salary Gaps:**  
  - Some roles have **high midpoints** (**$30.81/hour on average**), which can impact internal pay equity.  
  - A structured **pay grade system** can help standardize salaries and minimize disparities.  
- **Opportunity for Salary Adjustments:** Given the **large pay gap**, HR should conduct a **compensation review** to ensure fair and competitive pay across roles.  

## **Strategic Recommendations**
✔ **Optimize recruitment spend** by focusing on high-yield sources like employee referrals.  
✔ **Enhance retention strategies** for production staff, potentially through better compensation, career growth, and workplace improvements.  
✔ **Boost employee engagement** with development programs and recognition initiatives.  
✔ **Address diversity gaps** by implementing structured diversity hiring programs.  
✔ **Improve quality control** in production to reduce errors and enhance efficiency.  

# Dashboards

## **Entity-Relationship Diagram**  

The following ER diagram represents the relationship between employees, departments, recruitment costs, and salary structures.  

![ER Diagram](Resources/ER_Diagram.png)  
 
![Employment Analysis](Resources/Employment_Analysis.png) 

![Payrate and Recruiting Cost Analysis](Resources/Payrate_and_recrutingcost_Analysis.png)

![Salary Category Analysis](Resources/Salary_Category_Analysis.png)