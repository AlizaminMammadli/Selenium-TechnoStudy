##  Selenium Projects 

This project provides a comprehensive set of user stories and test scenarios aimed at testing user account management and e-commerce transactions on the Akakce.com, Demo Webshop, and e-Junkie platforms. The project is designed to test the core functions of each platform and includes acceptance criteria and test preconditions. The tests have been conducted using Selenium and IntelliJ IDEA.

---

## **Table of Contents**

1. **Overview**
2. **User Stories**
    - **Akakce.com User Account Management**
        - US_101 - Create User Account
        - US_102 - Account Validation Check
        - US_103 - Log Out
        - US_104 - Log In
        - US_105 - Order List Check
        - US_106 - Message Inbox Check
        - US_107 - Delete Account
    - **Demo Webshop User Operations**
        - US_201 - User Registration
        - US_202 - Invalid User Registration
        - US_203 - Log Out
        - US_204 - User Login
        - US_205 - Invalid User Login
        - US_206 - Place Order
        - US_207 - Survey Response
        - US_208 - Coupon and Gift Card Usage
        - US_209 - Download Order History
    - **e-Junkie eBook Purchase Transactions**
        - US_301 - Add eBook to Cart
        - US_302 - Failed Payment and Bank Card
        - US_303 - Failed Payment and Invalid Credit Card
        - US_304 - Successful Payment and Confirmation
        - US_305 - Payment and Download
        - US_306 - Send Contact Message
        - US_307 - Access e-Junkie Homepage
3. **Test Environment and Requirements**
4. **Negative Scenarios**

---

## **Overview**

This project aims to test user account management and e-commerce operations on the Akakce.com, Demo Webshop, and e-Junkie platforms. Each user story details the operations performed on the website and provides acceptance criteria for verifying the correctness of these operations. Tests are conducted using Selenium and IntelliJ IDEA to ensure the accuracy of user interactions.

---

## **User Stories**

### **Akakce.com User Account Management**

- **US_101 - Create User Account**  
  The user should be able to create an account on Akakce.com with personal information.

- **US_102 - Account Validation Check**  
  After logging in, the user's name should appear in the profile section.

- **US_103 - Log Out**  
  The user should be able to log out from their account after logging in.

- **US_104 - Log In**  
  The user should be able to log in to Akakce.com using correct credentials.

- **US_105 - Order List Check**  
  After logging in, the user should be able to view their order list.

- **US_106 - Message Inbox Check**  
  After logging in, the user should be able to access their message inbox.

- **US_107 - Delete Account**  
  The user should be able to delete their account to protect their personal data.

### **Demo Webshop User Operations**

- **US_201 - User Registration**  
  The user should be able to register on the online store.

- **US_202 - Invalid User Registration**  
  An error message should be shown if the user tries to register with the same email address.

- **US_203 - Log Out**  
  The user should be able to log out from their account.

- **US_204 - User Login**  
  The user should be able to log in to the online store.

- **US_205 - Invalid User Login**  
  An error message should be shown when attempting to log in with an invalid email and password.

- **US_206 - Place Order**  
  The user should be able to place an order on the online store.

- **US_207 - Survey Response**  
  The user should be able to respond to surveys.

- **US_208 - Coupon and Gift Card Usage**  
  The user should see an error message when using an invalid coupon or gift card.

- **US_209 - Download Order History**  
  The user should be able to view and download their order history.

### **e-Junkie eBook Purchase Transactions**

- **US_301 - Add eBook to Cart**  
  The user should be able to add a demo eBook to their cart.

- **US_302 - Failed Payment and Bank Card**  
  The user should receive an error message if they try to make a payment with missing information.

- **US_303 - Failed Payment and Invalid Credit Card**  
  An error message should be shown when trying to make a payment with an invalid credit card.

- **US_304 - Successful Payment and Confirmation**  
  The user should receive a confirmation message after completing a payment with valid details.

- **US_305 - Payment and Download**  
  The user should be able to download the eBook after completing the payment.

- **US_306 - Send Contact Message**  
  The user should be able to send a message using the contact form.

- **US_307 - Access e-Junkie Homepage**  
  The user should be able to access the e-Junkie homepage after being redirected.

---

## **Test Environment and Requirements**

- **Test Environment**:
  - Akakce.com: https://www.akakce.com
  - Demo Webshop: https://demowebshop.tricentis.com
  - e-Junkie: https://shopdemo.e-junkie.com/

- **Browser Requirements**:
  - Chrome, Safari, or Firefox

- **Test Software**:
  - IntelliJ IDEA
  - Selenium

---

## **Negative Scenarios**

The robustness of the test scenarios has been verified with negative scenarios, including user errors and invalid inputs. Example negative scenarios:

- Entering invalid or incomplete login information.
- Attempting transactions with incorrect payment details.
- Using invalid promo codes and coupons.

These scenarios are essential for improving the application's resilience.

---

This README serves as a guide for testing user operations on the Akakce.com, Demo Webshop, and e-Junkie platforms. Each user story is supported by acceptance criteria and preconditions to properly test the functionality of the application.

---

Let me know if you need any further adjustments or translations!
