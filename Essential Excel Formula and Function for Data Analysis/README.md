# Excel Data Analysis - HR Employee Salaries

This project showcases Excel-based data analysis using advanced functions. 
The analysis is focused on employee salary data and answers 10 key business questions.
![image](https://github.com/user-attachments/assets/7245771e-5869-4421-a67f-2ea59f26afae)

1. **Total Salary and Headcount by Department**
- 📘 Functions: `SUMIFS`, `COUNTIFS`,`AverageIFS`
- Using those function we found the Total no of Headcounts in the Department, What is the amount of Salary we are paying to the Department, We calculated Average salary to the department and Counted the people only in Permanent Position.
 ![image](https://github.com/user-attachments/assets/d2d7e283-3ff0-4e7a-b031-3da04d6bf7d7)

2. **All Employees with More Than $100k Salary**
- 📘 Function: `FILTER` dynamic cell reference : 116000
- I have added the automatically generated header on the subset of the data
- excel formula =Filter(Staff,Staff[salary]>referencecell)
 ![image](https://github.com/user-attachments/assets/90f0e607-0476-4f78-bf5a-0d9182e59498)

3. **All Female Employees with More Than $100k Salary (Joined in 2020 or After)**
- 📘 Functions: `FILTER`, logical operators (`*`)
- With conditions
- condition 1.Only for the all the Female Emplyee with 100000 dollars
- condition 2 : Bring those female only after the Year  2020  using DATE function
 ![image](https://github.com/user-attachments/assets/c23cc6ca-5b61-4a8d-8269-0c8e8e893d70)


4. **Lowest, Highest, and Top 5 Salary Values**
- 📘 Functions: `MIN`, `MAX`, `LARGE`, `SORT`, `TAKE`
![image](https://github.com/user-attachments/assets/d66197ae-a553-42a5-bb22-c6850539e253)
