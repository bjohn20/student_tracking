# Student Tracking System

This code implements a student tracking system. It utilizes a SQLite database to store student information and provides a graphical user interface (GUI) for users to interact with the data.

- Users can add new student information through textboxes. The code validates for missing entries and enforces uniqueness of full names within the database
- Users can select a student from the listbox and delete their information from the database. The code prevents deletion of the last remaining record
- A listbox displays the full names of all students in the database. Selecting a student populates their details in the corresponding textboxes for viewing or editing
- Clear functionality allows users to erase all data entered in the textboxes
- A refresh function is included to reload the listbox contents
