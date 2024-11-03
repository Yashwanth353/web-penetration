# web-penetration
Team Members:<br>
1.Annem Venkata Kishan Kumar Reddy(22bcs013)<br>
2.Modugu Yashwanth Reddy(22bcs072)<br>
3.Nelli Vivek Reddy(22bcs076)  
4.Peddisetty Teja Vinay(22bcs084)<br>

Overview<br>

1 Discover and document security vulnerabilities in the target web application.<br>
2 Demonstrate how these vulnerabilities could be exploited by attackers.<br>
3 Provide remediation recommendations for each discovered vulnerability.<br>
4 Improve security testing skills by hands-on practice on a real-world application.<br>

Project Features:

1 Reflected XSS (Cross-Site Scripting): Detected vulnerabilities that allow reflected XSS attacks through improper input validation in parameters such as act.<br>
2 IDOR (Insecure Direct Object References): Identified parameters vulnerable to unauthorized access of other users’ data by manipulating identifiers.<br>
3 Credential Leaks: Discovered ways to access sensitive credential information through insecure API endpoints.<br>
4 Information Leaks: Found sensitive tokens and other information that could assist attackers in gaining unauthorized access.<br>

Security Measures:

To mitigate the vulnerabilities identified in Zseano’s Playground, we recommend the following security measures:

1 Input Validation and Output Encoding:<br>

Implement server-side input validation for all user inputs to prevent malicious payloads.<br>
Use output encoding techniques (e.g., HTML encoding) to prevent script execution in the browser.<br>

2 Access Control and Authentication:<br>

Apply role-based access control to restrict access to sensitive resources.<br>
Use session-based access tokens to ensure users can only access their own data, mitigating IDOR vulnerabilities.<br>

