## As an admin (manager), I want to sign-in with my email and password, so that I can access admin dashboard

### Acceptance criteria:

#### Sign-in form:

- The sign-in form must include the following required fields:

  - Email
  - Password

- All fields should be required before submission

#### Validation:

- The email field should only accept valid email formats (user@example.com)
- If the user enters an incorrect email or password, an error message should inform them that the login credentials are invalid

#### Successful sign-in:

- If the user enters valid credentials, they should be logged in and redirected to the application
- A session token should be generated and stored securely (e.g., in cookies with the HttpOnly and Secure flags)

#### Error handling:

- If the email does not exist in the system, an error message should prompt the user to check their credentials
- If the password is incorrect, an error message should prompt the user to re-enter the correct password
- The error messages should not reveal whether the email or password was incorrect to avoid information leakage

#### Security:

- Implement rate limiting on login attempts to prevent brute-force attacks
- After a certain number of failed login attempts (e.g., 5), the account should be temporarily locked, and the user should be notified via email

#### Responsive design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices

### Tasks:

1. Create auth module, user storage, and admin sign-in and refresh token requests
2. Create sign-in page
3. Create auth context
