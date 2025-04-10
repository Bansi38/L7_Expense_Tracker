# L7_Expense_Tracker
## Overview

Expense Tracker is an efficient web application developed using Flask to help users manage their financial transactions, such as earnings, expenditure, investment, and savings. Users can simply record, monitor, and classify their expenditures, deriving useful knowledge about their spending patterns. The application also has advanced analysis and visualization capabilities that allow users to make informed financial choices.

## Prerequisites

To make the most out of Expense Tracker's features and functionality, have the following installed on your system:

Python 3.6 or later
Flask web framework
Plotly for data visualization
Pandas for data manipulation
Basic knowledge of HTML, CSS, and JavaScript for front-end interface design
These technologies and tools can be used to run the application and access its feature-rich expense tracking, analysis, and visualization. It even facilitates front-end interface customization based on individual needs.

## Project File Structure

myproject/
    main.py
    support.py
    requirements.txt
    templates/
        login.html
register.html
        home.html
        analysis.html
        profile.html
        contact.html
    static/
        css/
            style.css
js/
            script.js

## Installation

Clone the repository:
git clone https://github.com/Bansi38/L7_Expense_Tracker.git
Install the required packages:
pip install -r requirements.txt
Run the application:
python main.py

## Features

User Authentication: Secure login and registration system ensuring authorized access.
Dashboard: Provides an overview of the user's records, statistics, and data visualization tools to help understand expenses and add new records.
Expense Management: Insert, update, and delete expense, income, savings, and investment records.
Data Analysis: Interactive and complex charts to offer in-depth analysis of expense trends.
Profile Management: Update personal details like name, email, and password.
Contact Support: Offers different methods to contact the support team and raise queries or feedback regarding the application.
Session Management: User session will be closed after 5 minutes of inactivity for security purposes.

## Usage

## 1. Login Page Functionalities
Login: Users are able to log in to the web application with their proper credentials. After successful login, the user will be directed to the home page of their account. If the credentials are incorrect, an alert message will be shown.
Forgot Password: Users are able to reset their password by entering their registered email address and new password. If the email is present in the database, the password will be reset successfully.
Navigation: Links to navigate to the new user registration page and a support contact page.

##  2. Registration Page Functionality
Register: New users can register by entering their name, email, and password. If the email is not in the database, the user will be registered and taken to the home page. If the email is already in the database, an alert message will notify the user.
Navigation: Referrals to login and contact page in case of support.

## 3. Home Page
Overview: It shows a user overview of his/her records in terms of statistics, table records, graphs, and graphical charts, and giving detailed information regarding spending behaviors.
Add Records: Additions of new records by users for expenditures, incomes, savings, and investments.
Record Management: Feature to modify or remove the available records.  

## 4. Analysis Page
Data Visualization: Gives a strong insight into the user's data in the form of interactive graphs, which can be used to understand patterns in expenses.
Trends and Insights: Users can see patterns and trends in expenses over time, compare spending and earnings with savings, and export graphs in picture formats.

##  5. Profile Page
Manage Information: Enables users to change their personal details like name, email address, and password. Updates by email must have a unique new email and one that has not been registered before.

##  6. Contact Page
Support: Users can fill in a query or feedback on the application via a form. The page gives several means of contacting the support team, which include phone, email, and postal address.

## Session Termination

Security Measure: The session of the user will expire after 5 minutes of inactivity for security purposes. A warning will be given to the user before the session expires, and they can save any unsaved data.

## Conclusion

Expense Tracker is a robust and intuitive application that helps users effectively manage their financial transactions and achieve their financial objectives. The application offers an in-depth and simple-to-use interface that enables users to track, record, and analyze their expenses. With sophisticated data visualization and analysis features, users can better understand their financial information and make effective financial decisions. The application also has a secure login and registration mechanism, an easy-to-use profile management system, and an easy contact page for support and feedback. With the use of the features and functionality of Expense Tracker, users can manage their finances and become financially successful.
