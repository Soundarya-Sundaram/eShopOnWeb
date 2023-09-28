# eShop Test Plan!

# Purpose
To verify that users can successfully sign in, add items to their basket, and place orders without issues.

# Test Objectives and Scope
## In-Scope:
  * User registration and sign-in.
  * Product Details page and Search feature.
  * Adding/Removing items to the basket.
  * Placing orders.
  * Order History
  * Managing Accounts
  * Sign out
## Out of Scope:
  * Payment processing

# Automation Testing Approach
I have chosen to employ the Selenium framework in combination with the Cucumber BDD (Behavior Driven Development) Framework for automating tests on a web-based application. The chosen programming language for this task is Java. This framework has been selected due to its utilization of feature files that contain comprehensive automation steps written in plain English, making them easily comprehensible to non-technical team members.

Using Existing Libraries such as Lombok for getter, Setters, Log4j statement injection, Owner API for Configuration Loading and Mapping, Google Guice for Dependency Injection, AssertJ library for Assertion and Extent Report-Grasshoper Cucumber 6 Adapter for Reporting

# Automation Test Cases
Refer the Resources folder which contains feature files with all scenarios and detailed steps.

# Automation Script

# Run the Test
For Triggering the execution use below command:
* mvn clean install -Dbrowser=chrome -DexecType=local





