## As a vendor, I want to stay signed-in after return back or reload the page, so that I can access to my dashboard

### Acceptance Criteria:

#### Session Persistence:

- The user’s session should persist across page reloads and when they navigate back to the application after closing the browser
- The user should remain signed in unless they explicitly log out or their session expires

#### Remember Me:

- If a "Remember Me" option is available during login, selecting it should ensure the user stays signed in even after closing and reopening the browser
- If the user does not select "Remember Me," the session should only persist for the current browsing session
- Ensure the session token expires after a set period of 30 days for security

#### Session Management:

- The session token should be securely stored (in cookies with the HttpOnly and Secure flags) to maintain the user's signed-in state
- The application should handle token expiration appropriately by automatically logging the user out when the token expires

#### Security:

- If the session expires, the user should be redirected to the login page when they try to access protected resources

#### Cross-Device Sign-In:

- The user should be able to stay signed in on multiple devices simultaneously, with each session being managed independently
- If the user logs out on one device, the session on other devices should not be affected unless a global logout feature is implemented

#### Responsive Design:

- The product creation form must be fully responsive and work seamlessly on desktops, tablets, and mobile devices
