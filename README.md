# Task Manager and Reminder System
This is a completely Java based Task Manager and Remainder System with Java Database Connectivity and also have implementations of file-handling.

# Steps to run this project:

**1. Fork or directly clone this repository into your destination folder.**

**2. Go to Pack3 folder and open the code that is present in the TaskRemainder.java file.**

  - Replace the FILE_PATH with your actual file path of your tasks.txt by simply choosing copy as path.
  - Change the " \ " in the path URL with " / "
    -     private static final String FILE_PATH = "path/to/Text_File_Handling/tasks.txt";
  - Replace MySQL username and password with your own username and password
    -     try (Connection connection = DriverManager.getConnection("jdbc:mysql://localhost:3306/java", "username", "password"))
  - Save and close the file.

**3. Open MySQL Workbench and run the following queries one by one in new query tab.**

  - Creating a database named java
    -     create database java;
  - Using database
    -     use java;
  - Create table named tasks
    -     CREATE TABLE tasks(taskId int auto_increment primary key , name varchar(25),
          due_date date,due_time time, category varchar(25),priority int,completed boolean);
  - View table
    -     select * from tasks;
  - Delete data from table (if needed, optional)
    -     truncate table  tasks;

**4. Open command prompt and set to your current directory as the project directory by using command " cd " in the command prompt.**

  - Run the following commands one by one in the terminal (command prompt)
    -     javac Pack1/Task.java
    -     javac -cp . Pack2/TaskManager.java
    -     javac -cp .;lib/mysql-connector-j-8.2.0 Pack3/TaskRemainder.java
    -     java -cp .;lib/mysql-connector-j-8.2.0.jar Pack3/TaskRemainder
  - Now you will be able to see the menu panel of the project.

# Contributers for this project.

- [Sapare Aravind](https://github.com/Aravind3454)
- [Siva Gopal Krishna](https://github.com/gopalkrishna2004)
- [Abhinav Vuddagiri](https://github.com/Abhinav7370)
- [Vemula Chetan Nihith](https://github.com/chetannihith)😎

 _If you find our work helpful, please consider giving this repository a star ⭐. We appreciate your support!_ 
