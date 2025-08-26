
# HR-Dashboard
Interactive HR analytics dashboard built in Tableau to analyze hiring, turnover, demographics, performance, and salary trends. Uses simulated data to demonstrate workforce insights and decision-making support

## 📖Project Description
Human resources data often sits in silos, hidden inside spreadsheets or transactional systems that don’t reveal the bigger picture. This project demonstrates how those same data points can be transformed into an interactive, decision-ready dashboard using Tableau.

The dashboard is built around a simulated dataset of ~8,000 employee records, including demographics, education, performance ratings, salaries, and employment status. It goes beyond simple reporting by asking sharper questions: 

- Where are hiring and terminations concentrated?
- Which departments are losing talent fastest?
- How do education levels actually relate to performance?
- What signals of pay inequity might HR otherwise overlook?
- Is the workforce skewed by age, education, or location?

These aren’t just visuals; they’re structured to drive actions.

<img width="1400" height="802" alt="Screenshot for Dashboard" src="https://github.com/user-attachments/assets/36a8264b-033a-4545-b9de-1cc2f8f50a3a" />


## 📊Features

**Interactive filtering** → Users can click on charts to filter the entire dashboard dynamically. A collapsible filter panel allows customization by gender, hire status, location, and timeframe.

**Hover-to-inspect tooltips** → Each visual includes hover-over details to reveal context without cluttering the main view.

**Export capability** → The dashboard can be exported directly to PDF or image format for reporting and presentations.

**Info panel** → A built-in guide helps users understand how to interact with the dashboard (filters, tooltips, export), ensuring accessibility for non-technical audiences.

## 📈 Dashboard Components
  
**Headcount Overview**: Active employees, hires, terminations

**Demographic Insights**: Age, gender, and education breakdowns

**Performance vs. Education**: Comparative analysis across groups

**Salary Trends**: By gender, education, and managerial role

**Geographic Distribution**: HQ vs. branch workforce splits

**Scatterplot Analysis**: Age vs. salary with managerial outliers



## 🔎Findings 

**Pay dynamics shift with education**: Men earn more at lower education levels, but women out-earn men at advanced degrees, especially among PhDs (+$13K).

**Role comparison reveals structural inequities**: HR managers average $82K at age 35, while financial analysts earn a compatable $86K despite being, on average, ten years older.

**Education positively correlates with performance**:  60% of staff hold a bachelor’s degree. Higher education levels align with stronger reviews. The likelihood of receiving an “Excellent” rating rises with degree level — from just 12% among bachelor’s holders to nearly half of PhDs.

**Education and salary variation**: Salary spread widens with higher education — advanced degrees come with both higher pay and greater dispersion in earnings.

**Age–salary patterns differ by gender**: Men cluster into comparable salary bands within a narrow mid-career window (38–44), while women reach similar salary levels across a wider span and often later (38–48), pointing to differences in career progression timing.

 **Age and workforce share**: Mid-career employees (35–44) dominate the staff at 30%, making this the pivotal age group for retention and succession planning.  60% of all staff hold bachelor’s degrees.

**Workforce** is stable at 7,900+ employees, with hires (8.950) far outpacing terminations (966). Turnover patterns mirror department size, with Operations naturally highest. Gender balance is close (54% male, 46% female).

## 📑 Data dictionary
| Field               | Description                                      | Type              |
| :------------------ | :----------------------------------------------- | :---------------- |
| Employee_ID         | Unique identifier for each employee              | String / ID       |
| First Name          | Employee’s first name                            | String            |
| Last Name           | Employee’s last name                             | String            |
| Gender              | Employee gender (e.g., Male, Female)             | String            |
| State               | State of employment location                     | String            |
| City                | City of employment location                      | String            |
| Education Level     | Highest education attained (H-School, Bachel      or, Master, PhD) | String / Categorical    String            |
| Birthdate           | Employee date of birth                           | Date              |
| Hiredate            | Date employee was hired                          | Date              |
| Termdate            | Date employment ended (if applicable)            | Date              |
| Department          | Department employee belongs to                   | String            |
| Job Title           | Employee’s job role/title within the company     | String            |
| Salary              | Annual salary (USD)                              | Numeric           |
| Performance Rating  | Evaluation outcome (Excellent, Good,     Satisfactory, Needs Improvement)            | String / Ordinal  |



## 👩‍💻 About Me  

I am an analyst with 7+ years of experience in research and data analytics, backed by a Ph.D in Economics with applied expertise in business intelligence and institutional research. My work centers on transforming complex datasets into clear, actionable insights that inform strategic decisions.  

I am particularly passionate about designing dashboards and conducting research that don’t just display numbers, but guide conversations and decisions — bridging the gap between data and leadership action.  
