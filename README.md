<h1>Apply filters To SQL queries</h1>


<h2>Project Description</h2>
<br> My organization is working to make their system more secure. It is my job to ensure the system is safe, investigate all potential security issues, and update employee computers as needed. 
The following steps provide examples of how I used SQL with filters to perform security-related tasks.
<br/>
<h2>Retrieve After Hours Failed Login Attempts
</h2>
<br>There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.</br>
<br>The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.<br>


<h2>Risk Register</h2>

   <table border="1">
  <tr>
    <th>Asset</th>
    <th>Risk(s)</th>
    <th>Description</th>
    <th>Likelihood</th>
    <th>Severity</th>
    <th>Priority</th>
  </tr>
  <tr>
    <td>Business email compromise</td>
    <td>An employee is tricked into sharing confidential information.</td>
    <td>2</td>
    <td>2</td>
    <td>4</td>
    <td>4</td>
  </tr>
  <tr>
    <td>Compromised user database</td>
    <td>Customer data is poorly encrypted.</td>
    <td>2</td>
    <td>3</td>
    <td>6</td>
    <td>6</td>
  </tr>
  <tr>
    <td>Financial records leak</td>
    <td>A database server of backed up data is publicly accessible.</td>
    <td>3</td>
    <td>3</td>
    <td>9</td>
    <td>9</td>
  </tr>
  <tr>
    <td>Theft</td>
    <td>The bank's safe is left unlocked.</td>
    <td>1</td>
    <td>3</td>
    <td>3</td>
    <td>3</td>
  </tr>
  <tr>
    <td>Supply chain disruption</td>
    <td>Delivery delays due to natural disasters.</td>
    <td>1</td>
    <td>1</td>
    <td>2</td>
    <td>2</td>
  </tr>
</table>
<p>Notes:</p>
<p>How are security events possible considering the risks the asset faces in its operating environment? 
  
  Doing business with other companies may increase the risk of data being stolen. The risk of theft is important, but the bank is in an area with a low crime rate. So, this makes the priority low.</p>
