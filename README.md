<div align="center">
    <img src="./public/images/main-logo.png"  height="100%" width="40%" alt="logo">
</div>

<hr>


<p>
    Complete Modular HR Managemenet Sytem developed with the laravel framework. 
</p>


## Features 
1. One To One Chat App for users
2. Employees
    - Crud Management of employees
    - Well Structured Employee Profile For managing
        1. Personal Information
        2. Emergency Contacts
        3. Educations
        4. Workexperiences and their family members
        5. Assigned Assets.
        6. Raise Issues about asset to notify admin

    - Attendance
        Curated Tabular view of employees attendance with filters for employee name, month and year of the attendance.
    - Department Management
    - Designation Management
    - Holidays management
        
3. Clients
    Card and Tabular view for Clients. Making management of clients a breeze. 

4. Tickets
    Crud management of Tickets. 
    Edit Ticket to assign user(employee) to the ticket. so that, they can have conversation with the one who opened the ticket.
    
    Note: you can't assign admins to ticket. But they can view all tickets and partake in the conversation.

    Also, for now only admins are emailed when new tickets are opened.

5. Users
    Crud management of users in the system.
    Every user you add here will be an admin and they have certain privilages over employees and clients.

6. Backups
    Simple panel to manage backups of the application.
    You can start a backup for the whole application (code + db) or just the database. Ofcourse you can also download or delete backups if you are given the permission.

7. Settings
    - Company
        Enter the details of your company here. This details will be used when generating invoices 
    - Localization
    - Basic Localization for the application
        This includes your country, timezone, language, date format , currency and currency code.
    - Invoice 
        Basic settings for your invoice.
        For now, you can only set the logo and prefix

    - Theme
        General Theme Settings. Note that, settings done here will affect the whole application.
    
8. Assets
    Crud management of assets.
    When assets are assigned to an employee and you view their profile, you will see the assets tab. Which will show all the assets assigned to that particular employee
9. Accounting
    1. Budgets
        - Budget category management
        - Budget Management
            Add and Management your budgets either for a project or base on a category.
        
        - Manage Budget Expenses
        - Manage Budget Revenues

10. Projects
    Complete Project management with taskboard and task management.

    - CRUD project management
    - Assign Project Lead and a team for the project
    - Detailed View of a project with all the brief description, detailed description and uploaded files.
    - Project Taskboard management
    You can add new tasks to a taskboard or even add a new board to the default taskboards
    - Assign Tasks to an employee through the taskboard.
    Move tasks from one board to the other just by dragging them to the next one.
    - You can also set the default taskboards that will be loaded for every new project

11. Roles & Permissions
    Manage user roles and permissions for the whole application here.
    - You can add new Roles, edit the ones that's already there and also update the permissions for each of the roles you choose.


12. Sales 
    At sales, You will be able to manage your Taxes, Estimates and Invoices.
    - Crud management of taxes
    - Crud management of Estimates. You can also view an estimate in detail. Add new items to it and download it as pdf or print it.
    - Crud management of Invoices
        Just like Estimates, you can create, edit, view, print, download pdf and delete it.
        
13. Payroll
    Generate and manage payslips for employees.
    Manage payslip allowances and deductions.
