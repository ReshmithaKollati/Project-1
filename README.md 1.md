# Student-Teacher Application 

This is a simplified web-based application designed to demonstrate basic student-teacher interaction. It allows students and teachers to log in using user-defined credentials. **This version does not use any external databases or backend services.**

**Important Note:** This application is for demonstration only. In a real-world scenario, you would need to implement secure authentication and data persistence.

## Features

**Student Section:**

* **Login:** Students can log in using any username and password they choose.
* **Teacher Search:** Students can search for teachers (placeholder functionality).
* **Appointment Booking:** Students can book appointments with teachers (placeholder functionality).
* **Messaging:** Students can send messages to teachers (placeholder functionality).

**Teacher Section:**

* **Login:** Teachers can log in using any username and password they choose.
* **Schedule Appointments:** Teachers can schedule appointment slots (placeholder functionality).
* **Approve/Cancel Appointments:** Teachers can approve or cancel appointment requests (simulated).
* **View Messages:** Teachers can view messages from students (simulated).
* **View All Appointments:** Teachers can view all scheduled appointments (simulated).
* **Logout:** Teachers can safely log out.

## Technologies Used

* **HTML:** For the structure of the web pages.
* **CSS:** For styling the web pages.
* **JavaScript:** For client-side logic and interactivity.

**Note:** This application intentionally does not use a database or any backend. All data is simulated within the browser's memory.

## Setup and Execution

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Open `index.html` in your web browser:**
    Simply double-click the `index.html` file or open it using your preferred web browser (Chrome, Firefox, Safari, etc.).

## Basic Workflow

**User-Defined Login Credentials:**

* Users can create any username and password during login.

**Student:**

1.  Open the application in a web browser.
2.  Click the "Student" toggle button.
3.  Enter any username and password to log in.
4.  Use the placeholder functionalities for searching teachers, booking appointments, and sending messages.

**Teacher:**

1.  Open the application in a web browser.
2.  Click the "Teacher" toggle button.
3.  Enter any username and password to log in.
4.  Use the buttons to navigate to different sections of the teacher's dashboard.
5.  Use the placeholder functionalities for scheduling appointments, approving/canceling requests, viewing messages, and viewing all appointments.
6.  Use the logout button to log out.

## Important Limitations

* **No Data Persistence:** All data (appointments, messages, etc.) is lost when the browser is closed or refreshed.
* **Placeholder Functionality:** Many features are simulated and do not perform actual database operations.
* **No real Authentication:** The login does not check with any database, so any combination of username and password will work.

## Project Structure 
├── index.html
├── student_placeholder.png
├── teacher_placeholder.png
└── README.md

## Images

Below are the images used in the application:

* **Student Placeholder:**
    ![Student Placeholder](student_placeholder.png)

* **Teacher Placeholder:**
    ![Teacher Placeholder](teacher_placeholder.png)


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.