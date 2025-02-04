BigBasket Manual Testing Project

Project Overview

This project focuses on manually testing the core functionalities of the BigBasket application. The test scenarios include Login, Search, Add to Cart, and Logout, ensuring a smooth user experience and proper application behavior.

Scope of Testing

Functional Testing

UI/UX Testing

Usability Testing

Compatibility Testing

Regression Testing

Tested Features

Login

Search for Products

Add Products to Cart

Logout

1. Login Functionality

Test Scenarios:

Verify that the user can log in with valid credentials.

Verify that an error message is displayed for invalid credentials.

Verify the "Forgot Password" functionality.

Verify if login persists after closing and reopening the app.

Validate login with social media accounts (if applicable).

Verify login with an unregistered email or phone number.

Test Data:

Valid Username & Password

Invalid Username & Password

Blank Fields

Social Media Login (if available)

Expected Result:

Successful login should redirect the user to the home page.

Proper error messages should be displayed for invalid inputs.

2. Search Functionality

Test Scenarios:

Verify search with a valid product name.

Verify search with an invalid product name.

Verify if product suggestions appear when typing.

Validate the search filter and sorting options.

Verify if the search results match the entered keyword.

Verify search history functionality.

Test Data:

Product Name (e.g., "Apples", "Rice")

Invalid Product (Random Strings)

Category-Based Searches

Expected Result:

Relevant products should be displayed for valid searches.

No results or suggestions should appear for invalid searches.

3. Add to Cart Functionality

Test Scenarios:

Verify adding a product to the cart.

Verify updating the product quantity in the cart.

Verify removing a product from the cart.

Verify adding multiple products to the cart.

Validate cart persistence after logout/login.

Check stock availability messages when adding to the cart.

Test Data:

Single Product

Multiple Products

Out-of-Stock Products

Expected Result:

Products should be successfully added to the cart.

The cart should update accordingly when quantity is changed.

4. Logout Functionality

Test Scenarios:

Verify successful logout from the application.

Verify that the user is redirected to the login page after logout.

Ensure that session data is cleared after logout.

Verify if the user can log back in immediately after logout.

Check if any security warnings appear when logging out.

Test Data:

Logged-in User

Expired Session

Expected Result:

The user should be logged out and redirected to the login page.

The session should be terminated.

Test Execution & Reporting

Tools Used: Excel, Google Sheets, or Test Management Tools (like JIRA, TestRail)

Bug Reporting: Issues will be documented with proper screenshots, steps to reproduce, expected vs actual results, and severity.

Pass/Fail Criteria: Each test case will be marked as Passed, Failed, or Blocked.

Conclusion

This project ensures that essential functionalities of the BigBasket application work as expected, providing users with a seamless online shopping experience. Further enhancements in testing will be based on exploratory findings and feedback.

Author: [jay singh narvariya
Date: 2/04/2025

