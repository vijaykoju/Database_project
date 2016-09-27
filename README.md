Programmer: Vijay Koju, Viktor Reshniak

Database Project

This project is to develop a coursework deadline management system so that both students and teachers can manage deadlines at the same systems.

Requirement:

1. The following information will be imported from another system, so you don’t need to provide interfaces to manage them, but you still need to store them in your own database.

a. User information, such as First name, last name, user name, and password (password must be encrypted), email.

b. Course information such as: Course number, course name, course description.

c. Courses offered at current semester: CRN, section #, instructor. Assume each section is taught by one instructor only. A course may have several different sections that are taught by different instructors.

d. Courses enrolled by each student

2. The system has two types of users: student or instructor. To access the system, users must login with their username and password.

3. During each semester, instructor can specify an assign date and a due date for each coursework of courses he/she is teaching. The deadline has only one due date.

An instructor cannot assign a deadline to sections or courses he/she is not teaching.

4. The coursework must be one of the following: homework, project, close lab, presentation, research paper, survey, and other.

5. Each coursework must have a name to distinguish it from other coursework of the same course. When a coursework is created by an instructor, a document (.docx, .pdf or .txt file) of coursework description must be provided and stored in the database.

Functionality:

1. Student can only view information of courses he/she is taking:

a. View assign dates, due dates, and description of all coursework (of one or multiple courses) that is available. A coursework is available if its assign date has been passed.

b. View assign dates, due dates, and description of all coursework (of one or multiple courses) that is active. A coursework is active if its assign date has been passed, but not due date.

2. Instructor should be able to create, and edit assign date and due date for a coursework.

3. Instructor can delete a coursework only if the assign date of the coursework hasn’t been passed.

4. Instructor can view all assign dates, due dates, and description of all courses he/she is teaching. Preferably to display them in a calendar format.

5. For each course, student can decide whether to receive email alert or not. If yes, an email will be sent to students 24 hours before the due date of a coursework.

Language and platform:

You can use any programming language, such as C#, Java, Php. The database should be MySQL server.
