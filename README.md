# Test Automation Assignment
Purpose of this Assignment is to create a Test Automation Framework and automate test cases mentioned below. This is a replica of a live interview assignment given to few candidates. Try to complete this assignment in 3-4 hours of time.

---

#### Author:
Created by: Akash Tyagi.
Date: 8-Jan-2021
Reach me out: akashdktyagi@gmail.com / sarangholey@gmail.com for any questions and queries.
---

#### Description of the assignment
This is a practice Automation Testing Assignment.
We are using automation practice url to practice Automation Testing.
In this assignment you will have to create a Cucumber/TestNG Framework to automate the scenarios listed below.
Application URL is : http://automationpractice.com/
Estimated time to complete this assignment is: 4 hrs - 8 hrs (so clock your time)
You can use internet or any old reference to do this assignment.
Rules and directions:
* It should be a Maven project
* Use Cucumber with Junit (latest version: v 6 and above)
* If you are not familiar with Cucumber, you may try to do it in TestNG, but recommendation is that you try to do this in cucumber as TestNG is no longer a tool of choice for many projects. Cucumber is on the rise.
* Use Before and After Hook
* Use Back ground
* Use Cucumber Reporting (html) for reports

#### Selenium:
* Use Page Object Model (page factory or any other method)
* Use Implicit Wait wherever required.
* Use Web Driver factory to return the browser
* Use Default driver as "chrome" or "firefox"
* Use Desired Capabilities to init your driver
* Quit Driver after end of each test case
* Use log4J for logging

* Scenarios should be executable using Maven command line
* Scenarios should be executable on Chrome and firefox (cross browser)
* FW should be able to Take Screen shot:
    * If test case fails, take a screen shot
    * After end of each test case, take a screen shot
    * Hint: Use Before and After hook to take screen shot
* Scenarios:
    * Assume below scenarios are written by BA but not in Gherkin format.
    * You need to understand the steps and convert them in to cucumber steps.
    * You can choose to divide the scenarios in to multiple scenarios for simplicity and modularity.
    
### Scenario

* Scn 0: Sign Up
    * Open URL http://Automationpractice.com /
    * Sign Up for the Account
    * Fill the Form
    * Check User account is created and User is logged in immediately.
    
* Scn 1: Send a Friend Feature
    * Login to http://Automationpractice.com /
    * Select the category as T-Shirts
    * Click on the product: Faded Short Sleeve T-shirts
    * Click Send to a Friend Link, fill the details and click on Send.
    * Check the Message appeared that Email sent in a pop up.
    
* Scn 2: Write a Review Feature
    * Login to http://Automationpractice.com /
    * Select the category as T-Shirts
    * Click on the product: Faded Short Sleeve T-shirts
    * Click on Send a Review and enter the details in the form.
    * Check the Message appeared that New comment added.

* Scn 3: Change in the image using Color Feature
    * Login to http://Automationpractice.com /
    * Select the category as T-Shirts
    * Click on the product: Faded Short Sleeve T-shirts
    * Click on Color Blue link
    * Check the Image is changed
    
* Scn 4: End To End User Journey Feature
    1. Login to http://Automationpractice.com /
    2. Select the category as T-Shirts
    3. Click on the product: Faded Short Sleeve T-shirts
    4. Fetch the Amount of the product in a variable
    5. Increase Quantity to 2
    6. Increase Size to L
    7. Click on Add to Cart 
    8. You need to do below validations:
    9. Check the User sees the Pop Up: Product Successfully Added to Cart
    10. Check the Quantity and Color
    11. Check Total Price is twice the amount fetched earlier.
    12. Click on Proceed to Checkout.
    13. You need to validate below things again:.
    14. Check the User sees the product name
    15. Availability as Instock
    16. Unit Price equal to what was captured previously
    17. Quantity to what was set earlier
    18. Check the Total is equal to twice the amount with $ 2 for shipping
    19. Click on Proceed to Check out again and reach till payment and click on Terms and condition check box
    20. On Payment Page click on Pay by bank wire and Click on I confirm my Order
    21. Check the order submit page and message "Your order on My Store is complete." also check is amount is right.
    
