<h1>Apply Filters To SQL queries</h1>


<h2>Project Description</h2>
<br> My organization is working to make their system more secure. It is my job to ensure the system is safe, investigate all potential security issues, and update employee computers as needed. 
The following steps provide examples of how I used SQL with filters to perform security-related tasks.
<br/>
<h2>Retrieve After Hours Failed Login Attempts
</h2>
<br> Scenario: There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.</br>
<br>The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.<br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/9e4121bb-1d3e-48d9-be19-133ea0f4aef3" alt="1707187000943">
<H2>Retrieve login attempts on specific dates</H2>
<br> Scenario: A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred on specific dates.</br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/a5b742d9-9cc6-4e4c-9b92-a43b323ab511" alt="1707189042692">

<h2>Retrieve login attempts outside of Mexico</h2>
<br> Scenario: After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred outside of Mexico.</br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/a1582050-6d31-4362-b15f-e9c8d17a18db" alt="1707189394904">
<h2>Retrieve employees in Marketing</h2>
<br> Scenario: My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.

The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Marketing department in the East building.</Br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/b74a19fa-9a6c-45a0-9ad5-d9507b6c13d0" alt="1707189682247">

<h2>Summary</h2>
<br>I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. 

I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.</br>






