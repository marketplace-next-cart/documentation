## As a vendor, I want to recover my password if I forget it so that I can regain access to my dashboard

### Acceptance Criteria:

#### Forgot Password Option:

- The user should be able to click on a "Forgot Password" link available on the login page
- Clicking the link should redirect the user to a password recovery page

#### Forgot Password Form:

- The user should be prompted to enter the email address associated with their account
- The email field should only accept valid email formats

#### Email Validation:

- If the user enters an email that is not registered, an error message should inform the user that the email address is not found in the system
- If the email is registered, a password recovery email should be sent to the user’s email address

#### Password Recovery Email:

- The email should contain a unique, time-sensitive link to reset the password
- The link should expire after a set period of 24 hours for security purposes
- The email should include instructions on how to reset the password

#### Reset Password Form:

- Clicking the link in the email should redirect the user to a secure page where they can set a new password
- The user should be required to enter and confirm the new password
- The new password should meet the security criteria (e.g., a minimum of 8 characters, including at least one uppercase letter, one number, and one special character)

#### Successful Password Reset:

- After successfully setting a new password, the user should receive a confirmation message indicating that their password has been reset
- The user should be able to log in immediately with the new password
- The user should be automatically logged in and redirected to their dashboard or home page after resetting the password

#### Security:

- The password reset token should be securely generated and stored
- The application should ensure that only valid reset tokens can be used and that tokens are invalidated after use or expiration
- The user should receive a notification if multiple password reset attempts are made, to alert them of potential unauthorized access attempts

#### Responsive Design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices
