E-Commerce Website Manual Testing (Myntra – Reference Application)

Project Description
This project focuses on manual testing of an e-commerce web application using Myntra as a reference. 
The objective is to validate core functionalities such as user authentication, product search, cart management, 
checkout, payment processing, and order management by creating and executing test scenarios and test cases, and reporting defects.

Application Overview
Myntra is an e-commerce web application that allows users to browse fashion products, add items to the cart, and place orders using multiple payment options. 
The application also supports order tracking, returns/exchanges, and user profile management.

User Roles
•	Guest / Unregistered User
•	Registered User

Modules Covered
1.	Signup / Login / Logout
2.	Product Search
3.	Product Listing & Product Details
4.	Add to Cart
5.	Update / Remove Items from Cart
6.	Checkout
7.	Payment (UPI, Card, COD)
8.	Order Placement
9.	Order History
10.	Track Order
11.	Exchange / Return
12.	Ratings & Reviews
13.	User Profile

Testing Types Performed
•	Functional Testing
•	Smoke Testing
•	Sanity Testing
•	Regression Testing
•	UI Testing
•	Negative Testing

Test Scenarios – Login Module
•	Verify user is able to login with valid username/email and password
•	Verify login fails with invalid username
•	Verify login fails with invalid password
•	Verify appropriate error message is displayed for invalid login attempts
•	Verify login is restricted after multiple consecutive failed attempts
•	Verify user is redirected to home page after successful login
•	Verify user is required to re-login after logout
•	Verify login is not allowed when username and/or password fields are empty
•	Verify password characters are masked
•	Verify “Forgot Password” option is available
•	Verify login button functionality
•	Verify placeholders are displayed correctly
•	Verify system behavior when page is refreshed after entering credentials


Sample Test Case – Login with Valid Credentials
![image alt](https://github.com/uttam512/Ecommerce-Manual-Testing-Project/blob/3b8c7c91d9724abe560dfec4b93015072976c9df/Defect%20report.png)








Defect Report:





Defect Reporting (Sample Defects)
Defect 1
•	Defect Title: Error message not displayed for invalid login
•	Module: Login
•	Severity: Medium
•	Priority: High
•	Status: Open
Defect 2
•	Defect Title: Cart total not updated after quantity change
•	Module: Cart
•	Severity: High
•	Priority: High
•	Status: Open
Defect 3
•	Defect Title: Order status not updated after cancellation
•	Module: Orders
•	Severity: Medium
•	Priority: Medium
•	Status: Open

Tools Used
•	Web Browser (Chrome)
Conclusion
This project helped in gaining hands-on experience in manual testing by understanding real-world e-commerce workflows, writing and executing test cases, and reporting defects effectively.

