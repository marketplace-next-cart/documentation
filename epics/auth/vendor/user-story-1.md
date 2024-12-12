## As a guest user, I want to register for a vendor account with my email, and password, so that I can access and use the vendor dashboard

### Acceptance Criteria:

#### Registration Form Fields:

- The registration from must contain the next steps: credentials, business
- The registration form must include the following required fields:

  - Full Name
  - Email Address
  - Password (minimum 8 characters, including at least one uppercase letter, one number, and one special character)
  - Business Name
  - Business Type (dropdown or multi-select, e.g., retailer, wholesaler)
  - Contact Number (optional or required based on business needs)
  - Terms and Conditions checkbox

#### Registration Form:

- The user should be presented with a registration form that includes fields for email and password
- All fields should be required before submission

#### Optional Features:

- Allow users to upload a business logo or other basic information during registration
- Provide a progress indicator

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

#### Functionality and usability:

- Responsive device compatibility (mobile, tablet, desktop)
