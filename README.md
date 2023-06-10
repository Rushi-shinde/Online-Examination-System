
# Online-Examination-System

This is a web-based Online Examination System built using PHP and MySQL. It allows users to take exams online and provides an admin panel to manage exams, questions, and users.




## Features


- User Registration and Login: Users can create accounts and log in to the system.
- Exam Management: Admin can create exams, manage exam categories, and set the number of questions per exam. 
- Question Bank: Admin can add, edit, and delete questions in the question bank.
- Exam Taking: Users can select and take exams. The system tracks the time taken and displays the result after completion.
- Exam History: Users can view their past exam results.
- Admin Dashboard: Admin can view statistics, manage users, and generate reports


## Installation

- Clone the repository:

```bash
  git clone https://github.com/Rushi-shinde/Online-Examination-System.git
```

- Import the database:

    - Create a new database in phpMyAdmin.
    
    - Import the SQL file located in the database directory into the newly created database.

- Configure the database connection:

    - Open the conn.php file in the includes directory.

    - Update the database credentials (hostname, username, password, and database name) as per your XAMPP server configuration.

- Start the XAMPP server and make sure Apache and MySQL are running.

- Access the application:

    ## for Admin Login 
    Open a web browser and enter http://localhost/Online-Examination-System/adminpanel/index.php in the address bar.

    ## for Student Login 
    Open a web browser and enter http://localhost/Online-Examination-System/index.php in the address bar.

    - Default admin credentials:

        Username: admin@username

        Password: admin@password

        
## Contact

For any questions, suggestions, or support, please email us at shinderushi327@gmail.com

