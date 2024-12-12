## As a registered vendor, I want to log in with my email and password, so that I can access my dashboard

### Acceptance Criteria:

#### Login Form:

- The user should be presented with a login form that includes fields for email and password
- All fields should be required before submission

#### Validation:

- The email field should only accept valid email formats (e.g., user@example.com)
- If the user enters an incorrect email or password, an error message should inform them that the login credentials are invalid

#### Successful Login:

- If the user enters valid credentials, they should be logged in and redirected to the dashboard
- A session token should be generated and stored securely (e.g., in cookies with the HttpOnly and Secure flags)

#### Error Handling:

- If the email does not exist in the system, an error message should prompt the user to check their credentials
- If the password is incorrect, an error message should prompt the user to re-enter the correct password
- The error messages should not reveal whether the email or password was incorrect to avoid information leakage

#### Security:

- Implement rate limiting on login attempts to prevent brute-force attacks.
- After a certain number of failed login attempts (e.g., 5), the account should be temporarily locked, and the user should be notified via email.
- The password should be hashed using a strong algorithm before being stored in the data storage

#### Responsive Design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices
