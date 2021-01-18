# Expense Reimbursement System # 


## Project Description 


The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

     
## Technologies used
* Servlets 
* Java
* JavaScript 
* HTML 
* CSS
* JDBC 
* SQL 
* AJAX
* Bootstrap
* RDS
* Tomcat 9
* Git
* Maven  

## Features
Features which are ready are : 
* Login
* Employee can see all its reimbursements.
* Employee can request for a new reimbursement.
* Finance Manager can approve/deny a reimbursement.
* Finance manager can filter between reimbursement by their status :
     * Approved
     * Pending
     * Denied
* A button which changes the theme of the application.

To-Do List :
* User can add an image of the reimbursement receipt.
* The system reads everything in the ticket and adds a reimbursement ticket.
* UI more user interactive.

## Getting started 
Open Git bash and enter the command :
git clone https://github.com/2011Canada/project-1-bhushanmanik.git


For SSH, enter :
git@github.com:2011Canada/project-1-bhushanmanik.git

## Usage
* Clone the project and open it by importing in VS Code.
* Install and run the tomcat server. 
* Run the project and then login with the username & password.
* Enter as an employee and then add a reimbursement ticket and logout.
* Now login as the finance manager and approve/reject the reimbursement tickets.

## Licenses
The GNU Lesser General Public License.

## Reimbursement Types 

Employees must select the type of reimbursement as: 
* LODGING
* TRAVEL
* FOOD
* OTHER.



## Technical Requirements - >

The back-end system shall use JDBC/Hibernate ( if adventurous) to connect to a PostgreSQL database. The application shall deploy onto a Tomcat Server. The middle tier shall use Servlet technology for dynamic Web application development. The front-end view can use JavaScript or React to make a single page application that uses AJAX to call server-side components. (stretch goal ) Passwords shall be encrypted in Java and securely stored in the database. (stretch goal ) Users can upload a document or image of their receipt when submitting reimbursements.
