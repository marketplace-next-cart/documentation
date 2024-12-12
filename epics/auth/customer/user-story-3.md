## As a customer, I want to log out of my account, so that I can securely end my session and prevent unauthorized access

### Acceptance Criteria:

#### Logout Option:

- The user should have access to a visible "Logout" button or link on all pages of the application, typically in the header or user profile menu

#### Session Termination:

- Clicking the "Logout" button should immediately terminate the user's session on the client side by removing session tokens, cookies, or any other session-related data
- The server should also invalidate the user's session token to ensure the session cannot be reused

#### Redirection:

- After logging out, the user should be redirected to the login page or the public-facing homepage
- The user should see a confirmation message indicating that they have successfully logged out

#### Security:

- The session token should be invalidated on the server side to prevent any reuse of the token
- All user-specific data should be cleared from the browser’s storage (e.g., local storage, session storage) to ensure no information remains accessible

#### Preventing Unauthorized Access:

- After logging out, if the user attempts to access any protected pages, they should be redirected back to the login page
- The application should not allow the use of the "back" button to view pages from the previous session

#### Multi-Device Considerations:

- If the user is logged in on multiple devices, logging out from one device should not automatically log them out from others

#### Responsive Design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices
