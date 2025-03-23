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
# **Business Insights from HR Analysis Dashboard**

## **1. Employee Overview**
- The company has a **total of 310 employees**, with **133 terminations**, resulting in an attrition rate of **43%**.
- The **gender split** shows that **57%** of employees are female, while **43%** are male.
- **Employee headcount by age group** reveals that the majority fall within the **40-59 years** range (**192 employees**), followed by **96 employees aged 20-39** and **22 employees aged 60-79**.
- This suggests a predominantly middle-aged workforce, highlighting the need for **succession planning** and talent pipeline development.

## **2. Hiring & Attrition Trends**
- The **hiring count peaked between 2010 and 2015**, with over **60 employees hired annually** in certain years.
- However, attrition also spiked in the same period, suggesting potential **employee retention issues**.
- Proactive retention strategies, such as **career growth opportunities and workplace engagement programs**, could help mitigate high turnover rates.

## **3. Recruitment Cost Analysis**
- The **total recruiting cost is distributed across different months**, with **January spending around $4K (5.2%)** and **September reaching $9K**.
- Costs remain **relatively stable across months**, with occasional spikes indicating **seasonal hiring trends**.
- HR should analyze which recruitment sources **yield the highest ROI** and optimize recruitment spending accordingly.

## **4. Employee Distribution by Position**
- The **largest workforce segment is in production**, with **136 Production Technicians** and **57 additional Production roles**.
- Other key roles include **Area Sales Managers (27), Production Managers (14), Software Engineers (9), Data Analysts (8), and IT Support (8)**.
- A **significant reliance on production staff** suggests that workforce planning and upskilling initiatives should focus on this segment to maintain efficiency.

## **5. Employee Headcount Under Managers**
- The employee distribution across managers is **fairly balanced**, with **most managers overseeing 17-22 employees**.
- This suggests **manageable team sizes**, but performance evaluations could determine if leadership support needs to be optimized.

## **6. Marital Status Distribution**
- The workforce is predominantly **single (137 employees)**, followed by **married (123 employees)**.
- A small proportion of employees are **divorced (30), separated (12), or widowed (8)**.
- Understanding demographic trends can help HR design **employee benefits and wellness programs** tailored to different life situations.

## **Strategic Recommendations**
✔ **Improve retention strategies** by addressing attrition spikes and analyzing employee exit reasons.  
✔ **Optimize recruitment spending** by investing in the most effective hiring sources.  
✔ **Develop workforce planning initiatives** to address an aging workforce and ensure skill continuity.  
✔ **Enhance employee engagement programs** to reduce turnover and improve productivity.  
✔ **Leverage demographic data** to tailor benefits and wellness programs that align with employee needs.  

# **Business Insights from Payrate and Recruiting Cost Analysis**

## **1. Payrate Overview**
- The **total payrate across employees is $10K**, with a **maximum payrate of $80** and a **minimum of $14**.
- The **active payrate is $6K**, indicating that a significant portion of payroll expenses is actively utilized.
- Understanding pay distribution can help **optimize salary structures** and ensure competitive compensation for retaining talent.

## **2. Payrate Distribution by Department**
- The **Production department** has the highest total payrate of **$4.8K**, followed by **IT/IS ($2.3K), Sales ($1.7K), and Software ($0.5K)**.
- The **low payrate in administrative and executive roles** suggests a lean management structure.
- Companies should **benchmark salaries** against industry standards to ensure competitive compensation.

## **3. Performance Score Analysis**
- The **majority of employees (243) have a "Fully Meets" performance score**, while **37 employees "Exceed" expectations**.
- However, **18 employees "Need Improvement" and 12 are under "PIP" (Performance Improvement Plan)**.
- Focused **training programs and performance incentives** can help improve employee effectiveness.

## **4. Employee Satisfaction Insights**
- Employee satisfaction is **fairly balanced**, with **108 employees having the highest satisfaction level, 98 at the second highest, and 93 at the third**.
- A small number of employees have **very low satisfaction** scores, indicating potential areas for workplace improvements.
- **Employee engagement initiatives** should be prioritized to maintain high satisfaction levels.

## **5. Employee Abutments & Workload Analysis**
- **Most employees work between 7-12 abutments per hour in week 2**, peaking at **37 employees working at 10 abutments per hour**.
- Identifying workload trends can help **optimize workforce allocation** and prevent burnout.

## **6. Special Projects Participation**
- **242 employees are not engaged in special projects**, while **only 31 employees participate in 1 project, 21 in 2 projects, and very few in higher numbers**.
- Encouraging **collaborative projects** can **boost innovation and cross-departmental engagement**.

## **7. Recruitment Source Effectiveness**
- The **top recruitment sources** include:
  - **Employee Referral (31 hires)**
  - **Diversity Job Fair (29 hires)**
  - **Indeed (8 hires)**
  - **Glassdoor (14 hires)**
  - **Billboards (16 hires)**
- **Traditional sources like CareerBuilder and Company Intranet** have yielded minimal hires.
- Investing in **high-performing recruitment sources** can improve hiring efficiency and reduce costs.

## **8. Total Recruiting Cost**
- The company has spent **$84K on recruitment**.
- Analyzing **cost per hire by source** can help **optimize recruitment spending**. 

# Dashboards
## **1. ER Diagram**  
This image illustrates how various HR datasets such as employee details, production data, recruiting costs, and salary grid are interconnected. It helps in understanding data flow and relationships within the organization.  
The following ER diagram represents the relationship between employees, departments, recruitment costs, and salary structures.  

![ER Diagram](Resources/ER_Diagram.png)  

## **2. Employment Analysis**  
This chart provides insights into employee headcount, attrition rates, and workforce demographics. It highlights key metrics such as gender distribution, age groups, and termination trends.  
 
![Employment Analysis](Resources/Employment_Analysis.png) 

## **3. Payrate and Recruiting Cost Analysis**  
This visual representation shows the distribution of employee salaries and the cost associated with recruitment. It aids in identifying cost efficiency and pay equity within departments. 
![Payrate and Recruiting Cost Analysis](Resources/Payrate_and_recrutingcost_Analysis.png)

## **4. Salary Category Analysis**  
This dashboard highlights salary ranges across different job titles. It provides insights into minimum, mid, and maximum salary structures, enabling the organization to maintain competitive compensation practices.   

![Salary Category Analysis](Resources/Salary_Category_Analysis.png)

## **Conclusion**  

The HR dataset analysis provides valuable insights into workforce dynamics, recruitment efficiency, and compensation structures. Key findings include:  

- **High Attrition Rate:**  
  With an overall attrition rate of **43%**, retention remains a significant challenge. Implementing better engagement programs and career development opportunities could help reduce turnover.  

- **Balanced Workforce Distribution:**  
  The **gender ratio (57% female, 43% male)** and diverse age groups indicate a relatively inclusive workplace. However, an aging workforce calls for proactive **succession planning**.  

- **Recruitment Efficiency:**  
  The analysis of recruitment sources shows that **employee referrals and diversity job fairs** yield better hires at lower costs. Optimizing recruitment spending on these channels can improve cost efficiency.  

- **Payrate and Performance Alignment:**  
  The **payrate distribution** highlights the need for periodic salary benchmarking to ensure competitive and fair compensation. Aligning pay with performance scores could improve motivation and retention.  

- **Workforce Productivity:**  
  Performance data suggests most employees **"Fully Meet" expectations**, with room to enhance productivity through targeted training and development programs.  

- **Engagement and Satisfaction:**  
  Satisfaction scores indicate a **balanced but improvable engagement level**, with some employees showing low satisfaction. Improving workplace culture and recognizing achievements may enhance overall satisfaction.  

---

## **Strategic Recommendations:**  

✔ **Implement retention strategies** targeting at-risk employees to reduce attrition.  
✔ **Optimize recruitment spending** by focusing on high-ROI hiring channels.  
✔ **Develop succession planning** to address aging workforce concerns.  
✔ **Enhance compensation strategies** to ensure fair and competitive pay.  
✔ **Invest in targeted training** to improve performance and productivity.  
✔ **Foster workplace engagement** to boost employee satisfaction and retention.  

By leveraging HR data analytics, organizations can make **evidence-based decisions** to enhance workforce management, improve retention, and maintain a motivated, high-performing workforce. 