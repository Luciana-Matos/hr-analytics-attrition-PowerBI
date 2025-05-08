# HR Analytics: Employee Attrition & Engagement Insights
This PowerBI dashboard analyzes employee attrition and satisfaction trends across departments in a growing company. By uncovering key drivers of turnover, it supports HR in designing targeted interventions to boost retention, improve employee experience, and reduce recruitment costs — ultimately fueling sustainable growth.

**Power BI Project | 2025**  
By Luciana Matos  
**Dataset Source**: DataCamp (synthetic HR data)

## 📁 Dataset Overview

The analysis uses a synthetic HR dataset simulating employee records from 2012 to 2022. Key tables include:

- **Fact_PerformanceRating**: Contains annual review data such as performance ratings (manager/self) and satisfaction scores across job, environment, relationships, and work-life balance.
- **Dim_Employee**: Holds demographic and employment data — employee ID, gender, age, department, role, marital status, compensation, business travel frequency, tenure, stock options, and attrition status.
- **Dim_EducationalLevel**: Maps education levels such as Doctorate, Master's, Bachelor's, High School, No Formal Education.
- **Dim_RatingLevel / Dim_SatisfiedLevel**: Lookup tables for rating descriptions — "Very Satisfied", “Satisfied”, "Neutral", “Dissatisfied”, “Very Dissatisfied".

## 📌 Dashboard Sections

**1\. Company Overview**

- **KPIs**: Total headcount, active employees, attrition rate.
- **New Hires by Year**: Hiring trends from 2012–2022.
- **Department Composition**: Treemap of headcount by department and role.
- **Growth Trend**: Headcount grew from 151 in 2012 to 1,234 in 2022.

💡 Most employees are in Technology, followed by Sales and HR. Hiring remained consistent, with over 100 hires per year throughout the period.

**2\. Demographics Breakdown**

- **Age**: Most employees are aged 18–34.
- **Education**: Majority hold at least a Bachelor's degree.
- **Gender Diversity**: 46% female, 44% male, 8% non-binary.
- **Ethnicity Breakdown**: Includes White, Black or African American, Mixed/Multiple ethnicities, etc.
- **Distance from Work**: Evenly distributed; no correlation found with attrition.
- **Location**: Employees are based across California, Illinois, and New York.

**3\. Attrition Analysis**

- **Attrition by Year**: Peaked in 2021.
- **By Department & Role**: Highest turnover among Sales Reps, Recruiters, and Data Scientists.

**4\. Attrition Influencers**

- **Business Travel**: “Some travel” had the highest churn — higher than “frequent” or “no travel”.
- **Stock Options**: Employees without stock options were **2.46x more likely** to leave.
- **Tenure**: Highest attrition occurred within the first two years.

**5\. Employee Satisfaction**

Tracked across years, roles, and locations in four dimensions:

- **Environment Satisfaction**
- **Work-Life Balance**
- **Job Satisfaction**
- **Relationship Satisfaction**

💡 Environment Satisfaction was the highest-rated area, staying above the 3.5 target across all years — but declining since 2020, hitting its lowest point in 2022.

💡 On average, over the entire analysis period, the HR department had the lowest satisfaction scores across all four dimensions — environment, work-life balance, job satisfaction, and relationship satisfaction — compared to other departments.

## 🔍 Key Insights & Recommendations

- **Overtime as a Red Flag**:  
    Employees working overtime were **2.93x more likely** to leave.  
    → _Recommendation_: Monitor overtime by role; trial workload balancing in high-burnout teams.  

- **Early Tenure Churn**:  
    Most turnover happens in the first 2 years.  
    → _Recommendation_: Strengthen onboarding, offer mentorship, and introduce 6–12 month pulse checks.
- **Travel Discontent**:  
    Employees with “some travel” churned at higher rates than those with frequent or no travel.  
    → _Recommendation_: Investigate job design and employee expectations around moderate travel demands.
- **2021 Attrition Spike**:  
    The year with the highest turnover also had the lowest job satisfaction and a slowdown in YOY growth.  
    → _Recommendation_: Given that 2021 recorded the highest attrition and lowest job satisfaction, consider retroactively surveying employees who remained with the company during that period. Their insights may help reconstruct the work environment context and inform strategies to better manage employee experience during future growth slowdowns.

## 🛠️ Power BI Features Used

- KPIs & Cards
- Custom visuals (Treemaps, Maps, Bar Charts, key influencers)
- DAX Measures for attrition rate, tenure bands, and satisfaction scoring
- Drill-through navigation for department-level views
- Buttons and bookmarks for enhanced UX

## 💬 Personal Reflection

This project helped me strengthen my Power BI skills, particularly in data modeling, DAX, and user-centric dashboard design. It also deepened my understanding of workforce dynamics and improved my ability to generate insights that are actionable for HR decision-makers.

Looking ahead, I plan to:

- Integrate with SharePoint for real time reporting and use Power Automate for alerts (for example, alert when attrition reaches a certain threshold).
