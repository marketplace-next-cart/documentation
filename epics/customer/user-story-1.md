## As a customer, I want to view my profile page, so that I can change important information

### Acceptance Criteria:

#### Access to Profile Page:

- Users must be able to access the profile page via a visible link or button (e.g., "My Account" or "Profile") in the navigation menu or user dropdown

#### Profile Page Header:

- The page header must clearly indicate "My Profile" or "Profile Settings."

#### Display of User Information:

- The profile page must display the following details:

  - Full Name
  - Email Address (non-editable or editable based on verification flow)
  - Phone Number (if applicable)
  - Shipping and Billing Addresses
  - Password management section (e.g., "Change Password" link)
  - Profile picture (optional)

#### Edit Option:

- Each section (e.g., Name, Address) should have an "Edit" button or icon
- Clicking "Edit" allows users to modify the relevant fields

#### Form Validation:

- Ensure all input fields validate user entries (e.g., proper email format, phone number format)
- Display error messages for invalid inputs (e.g., "Please enter a valid email address")

#### Save Changes:

- Provide a "Save" button to confirm changes
- Display a success message: "Your profile has been updated successfully."

#### Cancel Changes:

- Include a "Cancel" button to discard unsaved edits and revert to the original information

#### Password Management:

- Provide a separate section or link to change the password securely
- Require the current password and new password (with confirmation)
- Enforce password strength requirements (e.g., length, special characters)
- Display success/failure messages based on the outcome

#### Address Management:

- Allow users to add, edit, and delete shipping and billing addresses
- Include a "Set as Default Address" option for convenience

#### Profile Picture Management (Optional):

- Allow users to upload or change their profile picture
- Provide cropping or resizing tools for uploaded images

#### Error Handling:

- Display error messages for failed updates (e.g., "Unable to update profile. Please try again later")

#### Logout Option:

- Include a "Logout" button for users to securely log out from their account

#### Security Measures:

- Require re-authentication for sensitive changes (e.g., email address or password updates)
- Use HTTPS for secure data transmission

#### Responsive Design:

- Ensure the profile page is fully responsive, functioning seamlessly on all devices (desktop, tablet, and mobile)

#### Optional Features:

- Display recent orders or a link to order history on the profile page
- Provide a "Delete Account" option for users who want to close their account (with a confirmation step)

#### Performance:

- The profile page must load within 2 seconds, and saving changes should take no longer than 1 second
