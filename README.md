Download Link: https://assignmentchef.com/product/solved-dbs301-lab-5-joins
<br>
This week’s lab continues using the SELECT command in addition to now incorporating multiple tables in the FROM statement to gather information together.

<h2>Tasks</h2>

<h2>Part-A – Simple Joins</h2>

<strong>(FROM &lt;table1, table2&gt;)</strong>

<ol>

 <li>Display the department name, city, street address and postal code for departments sorted by city and department name.</li>

 <li>Display full name of employees as a single field using format of “Last, First”, their hire date, salary, department name and city, but only for departments with names starting with an A or S sorted by department name and employee name.</li>

 <li>Display the full name of the manager of each department in states/provinces of Ontario, New Jersey and Washington along with the department name, city, postal code and province name. Sort the output by city and then by department name.</li>

 <li>Display employee’s last name and employee number along with their manager’s last name and manager number. Label the columns Employee, Emp#, Manager, and Mgr# respectively.</li>

</ol>

<h2>Part-B – Non-Simple Joins</h2>

<strong>Using the JOIN statement</strong>

<ol start="5">

 <li>Display the department name, city, street address, postal code and country name for all Departments. Use the JOIN and USING form of syntax. Sort the output by department name descending.</li>

 <li>Display full name of the employees, their hire date and salary together with their department name, but only for departments which names start with A or S.

  <ol>

   <li>Full name should be formatted: First / Last.</li>

   <li>Use the JOIN and ON form of syntax.</li>

   <li>Sort the output by department name and then by last name.</li>

  </ol></li>

 <li>Display full name of the manager of each department in provinces Ontario, New Jersey and Washington plus department name, city, postal code and province name.

  <ol>

   <li>Full name should be formatted: Last, First.</li>

   <li>Use the JOIN and ON form of syntax.</li>

   <li>Sort the output by city and then by department name.</li>

  </ol></li>

 <li>Display the department name and Highest, Lowest and Average pay per each department. Name these results High, Low and Avg.

  <ol>

   <li>Use JOIN and ON form of the syntax.</li>

   <li>Sort the output so that department with highest average salary are shown first.</li>

  </ol></li>

 <li>Display the employee last name and employee number along with their manager’s last name and manager number. Label the columns Employee,

  <ol>

   <li>Emp#, Manager, and Mgr#, respectively.</li>

   <li>Include also employees who do NOT have a manager and also employees who do NOT supervise anyone (or you could say managers without employees to supervise).</li>

  </ol></li>

</ol>