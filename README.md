Expense Reimbursement System
Executive Summary
The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.
State-chart Diagram (Reimbursement Statuses)


Reimbursement Types
Employees must select the type of reimbursement as: LODGING, T RAVEL, F OOD, or O THER.
Logical Model

Technical Requirements
The back-end system shall use JDBC/Hibernate ( if adventurous) to connect to a PostgreSQL database. The application shall deploy onto a Tomcat Server. The middle tier shall use Servlet technology for dynamic Web application development. The front-end view can use JavaScript or React to make a single page application that uses AJAX to call server-side components. (stretch goal ) Passwords shall be encrypted in Java and securely stored in the database. (stretch goal ) Users can upload a document or image of their receipt when submitting reimbursements.
