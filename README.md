# Student Attendance System

This project is a student attendance management system implemented in C programming language. It allows users to perform various tasks related to managing student attendance records. The system provides functionalities for adding students, displaying attendance records, generating warning letters for low attendance, searching for students by PRN (Permanent Registration Number), editing attendance records, and displaying attendance statistics.

## Features

- **Add a Student**: Users can add new students to the system by providing their name, PRN (8 digits), total number of lectures, and number of days attended.
- **Display Attendance Records**: Users can view the list of students along with their PRN, name, and attendance percentage.
- **Create Data File**: The system can create a data file containing the attendance records of all students.
- **Generate Warning Letters**: Warning letters are automatically generated for students with attendance below 75%.
- **Search by PRN**: Users can search for a student's attendance record by entering their PRN.
- **Edit Attendance**: Allows users to edit the attendance record of a student by providing their PRN and the new number of days attended.
- **Display Attendance Statistics**: Provides statistics such as total number of students, total attendance, and average attendance percentage.
- **Admin Login**: Admin authentication is required to access the system. The default admin username and password are both 'admin'.
- **Student Login**: Students can log in to view their own attendance records by entering their PRN.

## Usage

To use the system, follow these steps:

1. Run the program.
2. Choose an option from the main menu:
   - **Admin Login**: Access administrative functionalities.
   - **Student Login**: View your attendance record.
   - **Exit**: Terminate the program.
3. Depending on your choice:
   - If you log in as an admin, you can perform various tasks such as adding students, generating warning letters, and viewing statistics.
   - If you log in as a student, you can view your attendance record.

## Dependencies

This project depends on the following libraries:
- `stdio.h`
- `stdlib.h`
- `string.h`
- `time.h`
- `windows.h`
