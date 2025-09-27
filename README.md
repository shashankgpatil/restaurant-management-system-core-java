📌 Project Title

Restaurant Management System (RMS)

A Core Java-based desktop application to efficiently manage restaurant operations including menu handling, staff management, and order processing.

The Restaurant Management System is a standalone desktop application designed to streamline restaurant operations by digitizing order management, employee handling, and payment tracking. Built purely on Core Java, it provides managers and staff with an easy-to-use graphical interface (GUI) for everyday tasks such as creating orders, editing menus, monitoring staff activities, and generating reports.

📌 Problem Statement

Managing restaurant operations manually is time-consuming, error-prone, and inefficient. Issues such as misplaced orders, inaccurate billing, and difficulty in managing employees can reduce customer satisfaction and increase operational costs. Therefore, there is a need for a digital solution that automates these processes, minimizes errors, and improves overall efficiency.

📌 Tools and Technologies Used

-> Programming Language: Core Java
-> GUI Framework: Swing / AWT (Java GUI components)
-> Database / File Handling: File-based storage (dataFiles)
-> IDE: Eclipse / IntelliJ IDEA / NetBeans (any Java IDE)
-> Build Tool: JAR Packaging (RMS_GUI.jar)

📌 Features of the System

-> Authentication System – Manager and staff login with role-based access.
-> Menu Management – Managers can add, edit, or delete food and drink items.
-> Order Processing – Staff and managers can create, edit, close, or cancel orders.
-> Employee Management – Managers can add, edit, delete staff, and monitor working hours.
-> Payment Management – Daily payment tracking, staff clock-in/out, and report generation.
-> File-based Reporting – Reports for payments and orders.

📌 Key Insights

-> Role-based access ensures secure operations (Manager vs. Staff).
-> Easy GUI navigation allows both technical and non-technical staff to use the system.
-> Automation of order processing reduces human error and improves accuracy.
-> Payment and report modules enhance transparency and financial management.

📌 Dashboard

-> Login Screen – Separate access for Manager and Staff.
-> Manager Dashboard – Options for employee management, menu management, and reports.
-> Staff Dashboard – Order processing and viewing assigned tasks.
-> Menu Panel – Categories (Drinks, Alcohol, Main, Dessert) with quick filtering.
-> Reports Panel – Payment reports, order reports, and staff working hours.

📌 How to run the project?

### Execution
Double click RMS_GUI.jar

### Login
You can use test data for the first time. You can add new staff when you log in as manager.

### Manager
- ID:1000 Password:789456
- ID:1001 Password:789456

### Staff
- ID:100 Password:123456
- ID:101 Password:123456
- ID:102 Password:123456   

### Show menu
You can see all menu items by clicking ALL button, and items in particular categories by clicking Drink, Alcohol, Main, or Dessert button.  

view images related to project @ readme_images

### Taking order(Both Manager and Employee can use options )

### Create new order
1. Click "Show menu" button on the left
2. Click "New" button to create new order
3. Select adding items by clicking from the menu list on the right side.
4. Enter quantity and click "Add" button on the left side.(If quantity is emputy, one item will be added)
5. You can delete ordered item from the order detail by clicking "Delete" button  

### Edit order
1. Click "Show menu" button on the left
2. Select the order from the order list to edit
3. Click "Edit" button
4. You can add, delete ordered items

### Close or Cancel order
1. Select the order from the order list
2. Click "Close" button or "Cancel" button
3. The order closed or canceled can not edit

### Manage Employees (Manager only)

### Add new staff
1. Click "Manage Employees" Button on the left
2. Click "New" button
3. Fill in all information and click OK

### Edit staff
1. Click "Manage Employees" Button on the left
2. Select a staff from the employees list
3. Click "Edit" button
4. Fill in all information and click OK

### Delete staff
1. Click "Manage Employees" Button on the left
2. Select a staff from the employees list
3. Click "Delete" button

### Manage Menu Items (Manager only)

### Add new item
1. Click "Manage menu items" Button on the left
2. Click "Add new menu item" button
3. Fill in all information and click OK

### Edit menu item
1. Click "Manage menu items" Button on the left
2. Select a menu item from the menu list
3. Click "Edit menu item" button
4. Fill in all information and click OK

### Delete menu item
1. Click "Manage menu items" Button on the left
2. Select a menu item from the menu list
3. Click "Delete menu item" button

### About payments
* When you log in, the system automaticaly set start working time.
* Clock out button will set finish working time of the person currently logged in.
* Manager can make staff clocked out via manage employees, by selecting staff and clicking Clock out button.
* You can see a payment details for a day by clicking "Show payment" button on the left 
* Manager can generate like - Payment report, Order report (access here- dataFiles>reports) 

📌 Result and Conclusion

The RMS successfully automates essential restaurant activities, reducing manual errors and improving operational efficiency. Managers can easily control menu and employee data, while staff can focus on order processing with accuracy. Overall, the system improves restaurant workflow, reduces costs, and enhances customer satisfaction.

📌 Future Work

-> Integration with SQL Database for better scalability.
-> Development of mobile or web-based version for cross-platform accessibility.
-> Implementation of real-time inventory management to track stock levels.
-> Integration of digital payment gateways (UPI, cards, wallets).
-> Advanced analytics and customer feedback system for better insights.

📌 Contact

https://www.linkedin.com/in/shashank-girish-patil-9684511b1
