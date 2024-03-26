# student-python-admission-system
University Admission System

This is a simple application to manage student admissions in a university. It provides functionality to insert new student records and display existing records from a MySQL database.

Prerequisites:

- Python installed on your system.
- MySQL installed on your system.

Installation:

1. Clone the repository:

   git clone...repo link

2. Install the required Python dependencies:

   pip install mysql-connector-python

3. Set up the MySQL database:
   - Import the provided SQL script (database.sql) into your MySQL database management tool (e.g., phpMyAdmin).
   - Alternatively, you can manually create a database named "student" and a table named "admission" with appropriate columns (Fullname, Course, City).

Usage:

1. Navigate to the project directory in your terminal or command prompt.

2. Run the main.py script to launch the application:

   python main.py

3. The GUI window will open, allowing you to interact with the application.

Inserting Records:
- Enter the student's fullname, select the course from the dropdown menu, and enter the city in the respective input fields.
- Click the "Insert Record" button to add the student record to the database.
- If any input field is left empty, an error message will be displayed, and the record will not be inserted.

Displaying Records:
- Click the "Display Records" button to view all existing student records from the database.
- A new window will open displaying the records in a tabular format.
- Close the window to return to the main application window.

**Contributing:**

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.


