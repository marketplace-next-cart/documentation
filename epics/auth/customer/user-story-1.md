## As a guest user, I want to register for a customer account with my email, and password, so that I can access and use the web store

### Acceptance Criteria:

#### Registration Form Fields:

- The registration form must include the following required fields:

  - Full name
  - Email
  - Password (minimum 8 characters, including at least one uppercase letter, one number, and one special character)
  - Terms and Conditions checkbox

- All fields should be required before submission

#### Validation:

- All fields should be filled
- The email field should only accept valid email formats (user@example.com)
- The password should meet the security criteria (e.g., a minimum of 8 characters, including at least one uppercase letter, number, and special character)

#### Error Handling:

- An error message should be displayed if any field is empty
- An error message should be displayed if the email is already associated with an existing account
- A descriptive error message should indicate the requirements if the password does not meet the criteria

#### Successful Registration:

- Upon successful form submission, the user's account should be created
- The user should receive a confirmation email to verify their account
- The user should be automatically logged in after successful registration and redirected to the home page

#### Confirmation Email:

- A confirmation email should be sent to the registered email address
- The email should contain a link for the user to verify their account
- The account should remain inactive until the user verifies their email

#### Security:

- The password should be securely hashed before being stored
- The application should implement measures to prevent brute-force attacks, such as rate-limiting login attempts

#### Responsive Design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices
