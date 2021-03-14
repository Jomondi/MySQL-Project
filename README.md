# Description of the Exercise

   1. Using Python and MySQL, create a database called Academics and create a database schema with below values: 

           a) College:
               College_id
               College_Name
               College_Address
               College_city
               College_country


           b) Professor:
               Teacher_id
               Teacher_Name
               Teacher_Email
               College_id
               Date_joined
               Speciality
               Salary
               Experience

           c) Student:
               Student_id
               Student_Name
               Student_Email
               College_id
               Date_joined
               Major_taken
               College_Level

      2. Populate the created tables with records from a CSV/text file.

      3. Join these three tables by College_Id and then print and display the records on the screen.


# Exercise Resolution
      The program is intended to allow user to be able to create a MySQL database using Python and be able to write and run queries so as to fetch           data from the different tables. 

      The success of this code run is dependent on a user having the following readily installed in their local machine:
                - Python (https://www.python.org/downloads/)
                - Python interpreter e.g.
                        - PyCharm (https://www.jetbrains.com/pycharm/download/)
                - MySQL (https://www.mysql.com/downloads/)


      # Description of the file functions

        create_database()
                - Creates the database instance 'Academics'

        create_college_table()
                - Creates college table

        create_professor_table()
                - Creates professor table

        create_student_table()
                - Creates student table

        insert_college_data(), database.commit()
                - Inserts and commits data into into the college table

        fetch_college_table_values()
                - Fetches and displays the contents of the college table

        insert_professor_data(), database.commit()
                - Inserts and commits data into into the professor table

        fetch_professor_values()
                - Fetches and displays the contents of the professor table

        insert_student_data(), database.commit()
                - Inserts and commits data into into the student table

        fetch_student_values()
                - Fetches and displays the contents of the student table

        join_tables()
                - Joins and displays the columns of the 3(student, college, professor) tables.

