# Hello Candidate

This recruitment task is designed to evaluate your coding skills in React.

## Getting Started

1. Fork or download the repository and upload it to your GitHub account or another similar platform.
2. After downloading, run `npm install` in the main folder to install the necessary dependencies.
3. To start the mocked server along with the React application, execute `npm run start`.

Access the application here: http://localhost:3000

### Test Credentials for loginApi

email: <i>candidate@test.com</i> </br>
userName: <i>tester</i> </br>
password: <i>test1234</i>

## Task Overview

### Primary Objectives:

- **Data Fetching:** Retrieve data from the login endpoint at `http://localhost:8080/login` using the test account credentials listed above.
- **Form Division:** Organize the form into two segments:
  - **First Page (First Step):** Should include the "email" field and a "next" button.
  - **Second Page (Second Step):** Should contain "username", "password" fields, and a "submit" button. After form submission, the user should be notified of a successful login.
- **Session Management:** Save the "token" obtained from a successful login response in `sessionStorage`.
- **Validation Feedback:** Display backend validation messages in red beneath the form fields.
- **Front-end Validation:** Implement front-end validation to notify users of any missed fields. You are encouraged to use external libraries or tools.
- **User Information Display:** Show the full name of the logged-in user in the Navbar. Ensure user session persistence using the `http://localhost:8080/authUser` endpoint. A token sent in the authorization header is required to fetch the full name of the user.

### Additional Objectives:

- **UI Enhancement:** Improve the visual appearance of the application with CSS. You are given complete creative freedom.
- **Styling Tools:** Feel free to use additional styling libraries/tools to enhance aesthetics.

## Good Luck! :)

If you have any questions, please don't hesitate to reach out at: pawkaniak@gmail.com
