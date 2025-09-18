# OrangeHRM Performance Testing with JMeter

## Project Overview

This project focuses on **Performance Testing (load and stress)** of the [OrangeHRM Website](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login) using **Apache JMeter**.  
The goal of this project was to analyze the **response times**, **throughput**, and **stability** of critical user flows to ensure that the application performs reliably under load.

## Test Scenario

**The performance test covers the following end-to-end scenario:**

* **Login** – Authenticate with valid admin credentials.  
* **Add User** – Navigate to Admin → Add User and fill in required details.  
* **Save** – Submit the form to successfully create the new user.  
* **Logout** – End the session and return to the login page.  

## Tools & Technologies

* **Performance Testing Tool:** Apache JMeter
* **Tested Website:** [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)  

## Key Metrics Measured

* **Response Time**  
* **Throughput**  
* **Error Rate**

