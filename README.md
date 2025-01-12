# webTech
**BAL Management System**

**Problem Statement**:
--------------------------------
The Basketball Africa League (BAL), like many modern organizations, faces challenges in managing its growing number of users, administrators, and related data. The league requires a secure, scalable, and efficient system to handle various aspects of user management, administrative oversight, and role-based access control. The absence of such a system can lead to inefficiencies, security vulnerabilities, and poor user experiences.

**Key Challenges:**
------------------------------
1.User Management:
Ensuring that users (players, staff, and fans) can securely register, log in, and manage their accounts.
Providing tools for administrators to manage user accounts efficiently.

2.Security:
Preventing unauthorized access to sensitive information.
Ensuring robust session handling and secure password recovery mechanisms.

3.Administrative Oversight:
Keeping track of actions performed by administrators (e.g., account creation, updates, deletions).
Allowing administrators to send notifications and announcements to users.

4.Data Accessibility:
Simplifying the process of searching, sorting, and filtering user data.
Enabling data export in multiple formats (PDF, CSV, XLS) for reporting and record-keeping.

5.Scalability:
Designing a system that can accommodate a growing number of users and administrators as the league expands.

6.User Experience:
Providing users with real-time notifications and intuitive tools to update their profiles and interact with the system.
Ensuring multi-language support to make the system accessible to users across different regions in Africa and beyond

7.Data Insights:
Equipping administrators with visual tools (charts and graphs) to analyze user statistics and role distributions.
Audit and Compliance:
Maintaining a robust audit trail to track all significant actions performed in the system for accountability and compliance.


**How the BAL Management System Solves These Problems:**
-------------------------------------------------------------

1.Streamlined User Management:
The system provides secure user registration and login functionality.
Users can easily update their profiles, including uploading profile pictures.
Administrators have tools to create, update, and delete user accounts.

2.Enhanced Security:
Role-based access control ensures that users only access resources relevant to their roles.
Password recovery uses time-sensitive reset links (valid for 15 minutes), enhancing security.

3.Administrative Tools:
Administrators can monitor user activity and track actions through an audit trail.
Notifications can be sent to users directly via their portals.

4.Efficient Data Handling:
Search, sort, and filter functionalities make it easy to manage large datasets.
Data export options allow administrators to download user lists in various formats for reporting and analysis.

5.Scalability and Localization:
Built using Spring Boot and MySQL, the system is designed for scalability.
Multi-language support ensures the system is accessible to a diverse audience.

6.Improved User Experience:
Real-time notifications keep users informed of updates and announcements.
An intuitive and modern interface ensures ease of use.

7.Data Visualization:
Administrators can analyze user statistics and role distributions through interactive charts and graphs.

8.Audit and Accountability:
All actions performed by administrators are logged in an audit trail for transparency and compliance.

**Key Business Requirements of the BAL Management System**
--------------------------------------------------------------
1. User Account Management
   
Registration and Login:
Users must be able to register securely using their email addresses and create unique usernames.
Registered users should log in with a secure authentication mechanism.

Profile Management:
Users must be able to update their profile information, including uploading and modifying profile pictures.

Password Recovery:
A password reset feature must allow users to recover their accounts via email using time-sensitive reset links.

3. Role-Based Access Control (RBAC)
Role Definition:
Define roles such as User, Administrator, and Super Administrator with specific permissions.

Access Management:
Restrict access to certain features and data based on the user's role.

Administrators should have access to advanced features such as user account management, data exports, and reporting tools.

4. Administrative Tools

User Account Management:
Administrators must be able to create, update, and delete user accounts.

Notifications:
Administrators must be able to send real-time announcements and notifications to users.

Audit Trail:
All administrator actions (e.g., creating, updating, deleting accounts) must be logged in an audit trail for accountability.

5. Data Handling and Management
Search, Sort, and Filter:
Users and administrators must be able to efficiently search, sort, and filter user records by role, email, or username.

Data Export:
Administrators must be able to export user data in multiple formats, including PDF, CSV, and XLS.

Session Management:
Securely handle user sessions and prevent unauthorized access to restricted URLs.

6. Reporting and Data Insights
Data Visualization:
Administrators must have access to interactive charts and graphs that provide insights into user statistics, role distributions, and system usage.

Report Generation:
Administrators should be able to generate and download reports in predefined formats for meetings and documentation.

7. Notifications and Alerts
User Notifications:
Users must receive real-time notifications about updates, announcements, or system changes.

Administrator Alerts:
Notify administrators about critical system activities, such as failed login attempts or password reset requests.

8. Scalability and Performance
Scalable Infrastructure:
The system must support a growing number of users and administrators as the Basketball Africa League expands.

Pagination:
Limit the number of records displayed per page (e.g., 3 items per page) to optimize performance for large datasets.

9. Security and Compliance
Authentication and Authorization:
Ensure secure login using encrypted passwords.
Prevent unauthorized access through role-based permissions.

Data Security:
Encrypt sensitive data such as passwords and session tokens.

Password Reset Security:
Password reset links must expire after 15 minutes to prevent misuse.

Audit Compliance:
Maintain detailed logs of administrator actions to comply with security and organizational policies.

10. Localization and Accessibility
Multi-Language Support:
The system must provide support for multiple languages using internationalization (I18n).
Users should be able to change the language dynamically on the landing page.

User-Friendly Interface:
Ensure a modern and intuitive interface for users of all technical skill levels.

11. System Maintenance and Monitoring
Error Handling:
Implement robust error handling to provide meaningful error messages to users.

System Monitoring:
Track and log system activities to monitor performance and identify potential issues.

--------------------------------------------------------------------------------------------------


**Conceptual Domain Diagram of my system**
![conceptual domain model drawio](https://github.com/user-attachments/assets/2db7dbd9-f25f-4ecb-b6f4-908e67bd1341)

**Technical Domain Model of my System**
![Technical domain model drawio](https://github.com/user-attachments/assets/c6fbf3d3-0866-4a40-b773-491c889066f8)

**Database Domain Model for my Diagram**
![Database Domain Model drawio](https://github.com/user-attachments/assets/0fc1780f-fe04-4e16-b396-9dd312f13280)



