I. Project Overview

Watt Ease Matters is designed to help individuals manage their energy consumption and budget effectively. The application allows users to log in or sign up, enter their appliances' power consumption data, and calculate the associated energy costs. This tool not only assists users in budgeting for their energy expenses but also promotes energy efficiency and sustainability.

II.  Python Concepts and Libraries

Python Tkinter
Tkinter is the standard interface for the Tk GUI toolkit in Python, used for creating graphical user interfaces (GUIs). It allows developers to build the main application window, as well as login and signup forms, along with various input fields and buttons to facilitate user interaction.

Messagebox
This module provides a mechanism to show simple message boxes to users. It is particularly useful for displaying error messages, warnings, and informational alerts based on user actions, such as input errors during login or signup, or notifications of successful operations.

TTK (Themed Tkinter)
TTK is a submodule of Tkinter that offers a more modern aesthetic for widgets, enhancing the overall appearance of the application compared to traditional Tkinter widgets.

Font
This component allows customization of the fonts utilized in the GUI. By varying font styles for labels and buttons, developers can improve the visual appeal and readability of the text in their applications.

JSON
JSON (JavaScript Object Notation) is used for parsing and managing JSON data. It enables reading and writing JSON data in Python, making it suitable for storing user information (like usernames and passwords) in an organized format when saving and loading user data from files.

OS
The os module allows interaction with the operating system, facilitating file and directory manipulation. It can be used to check for the existence of a directory and to create one if it is not already present, which is helpful for storing user data files.

MySQL Connector
This library enables Python programs to establish connections with MySQL databases. It is used for interacting with a MySQL database where user credentials (username and password) are maintained. The ‘Database’ class manages database connections and operations related to user data.

Error
Part of the ‘mysql.connector’ library, this is used for handling exceptions that may arise during MySQL operations. It allows the program to catch and manage errors that occur while connecting to the database or executing queries, ensuring a graceful handling of potential database connection issues.

III. Sustainable Development Goals

The "Watt Ease Matters" program is an innovative initiative aimed at empowering users with the tools necessary to effectively understand and manage their energy consumption. By calculating the energy usage and associated costs of various appliances, the program enhances awareness of energy efficiency and encourages users to make informed energy-related decisions. This initiative is in line with several Sustainable Development Goals (SDGs) set by the United Nations, particularly those that focus on sustainability, energy efficiency, and responsible consumption.

Primarily, it supports SDG 7: Affordable and Clean Energy by promoting access to affordable, reliable, and sustainable energy. The program enables users to monitor their energy usage and budget accordingly. Additionally, it aligns with SDG 12: Responsible Consumption and Production, as it encourages mindful energy consumption and the use of energy-efficient appliances. The program also contributes to SDG 13: Climate Action, as minimizing energy waste aids in combating climate change and reducing greenhouse gas emissions linked to energy production. Furthermore, "Watt Ease Matters" supports SDG 11: Sustainable Cities and Communities by enhancing energy practices at the household level, which contributes to urban sustainability. Lastly, the initiative aligns with SDG 4: Quality Education by serving as an educational resource that raises awareness about energy consumption and sustainability, fostering a culture of lifelong learning and responsible energy practices.

IV. Instructions for running the program

I.Login Form
First, this screen serves as a gateway to the application. Before accessing the calculator and other features, users must provide their username and password to verify their identity and gain access. When a user enters their credentials and clicks the "Login" button, the application checks the provided information against its database. If the username and password match an existing account, the user is granted access to the calculator and other features of the Watt Ease Matters application. If the credentials are incorrect, an error message is likely displayed, prompting the user to try again. Clicking the “LOGIN” button submits the entered username and password for authentication. "Don't have an account? Sign up!", if the users clicked this it directs users to a registration page where they can create a new account if they don't have one.

II.Sign up Form 
After the user directs to the registration or sign up page, the users can enter their desired username and password into the respective fields on the sign-up screen. If the sign-up process is successful, the user is presented with a success message and redirected to a login page to access the calculator or application. 

III.Device Power Ratings Feature 
In the third picture, the top section allows users to enter their target budget (in pesos), the name of an appliance (in this case, a TV), and its power consumption (85 watts). When users click the “DEVICE POWER RATINGS” button, a new window will display a list of appliances with their power ratings with a scrollable list. A “SEARCH” button that input field to search for specific appliances within the list. A “GO BACK” button that allows users to return to the previous action.

IV.Inputting Information
In the fourth picture, users first input their target monthly electricity budget. Then, they add each appliance, specifying its name, power consumption in watts, and usage pattern which the user can choose if daily or monthly hours. Additionally, they need to enter the cost per kilowatt-hour (kWh) of electricity.

V.Add Appliance Button
In the fifth picture, once all the appliance details are entered. By clicking the “ADD APPLIANCE” button, a message will pop up that indicates that the program has successfully added the "TV" appliance. After that the program can now calculate the daily and monthly cost for the appliance.

VI.Show Results Button
The image shows a message that appears after the user has entered the details of an appliance and clicked the "SHOW RESULTS" button. The message displays a table summarizing the following information for the added appliance, the name of the appliance, power consumption of the appliance in watts, the number of hours the appliance is used per day or per month, cost of one kilowatt-hour (kWh) of electricity in pesos, and the estimated daily cost of running the appliance.

VII.Calculate Costs Button
After clicking the “CALCULATE COSTS” button, it shows a message indicating that “your total monthly cost is within your budget.”  It also displays the remaining budget amount, which is 892.90 pesos. Having a green row that represents the total monthly cost of the appliances which the user  added so far does not exceed the target budget.

VIII.Save Data Button
When the user clicks the “SAVE DATA”, it will show a message that allows the user to choose a slot to save the current data. The user has five slots (SLOT1 to SLOT5) to store different sets of appliance data. Once the user selects a slot, they can confirm the save operation or cancel it.

IX.Load Data Button
The “LOAD DATA” button allows the user to choose a slot to load previously saved data. They have five slots (SLOT1 to SLOT5) to load different sets of appliance data. Once the user selects a slot, they can confirm the load operation or cancel it.

X.Delete Last Appliance Button
When the user clicks the "DELETE LAST APPLIANCE", it shows a pop-up message that asks for confirmation before deleting the last appliance that was added to the list.

XI.Delete Saved Data Button
The “DELETE SAVED DATA” button allows the user to choose a slot to delete the saved data. The user has five slots (SLOT1 to SLOT5) to choose for deletion of data with different sets of appliance data. Once the user selects a slot, they can confirm the deletion or cancel it.

XII.Energy Saving Tips
After clicking the “CALCULATE COSTS” and the budget exceeds the target budget it will show a pop-up window with energy-saving tips. It provides several suggestions to help users reduce their energy consumption and lower their utility bills.

XIII.Total Monthly Cost Exceeds
This table provides a clear overview of the energy consumption and cost associated with each appliance and the total monthly cost. It also shows that the total monthly cost exceeds the original budget, resulting in a negative remaining budget and having a red color of row.










