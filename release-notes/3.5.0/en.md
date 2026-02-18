## v3.5.0

This release delivers a major upgrade to security, account management, and usability, along with key enhancements to shipping, tracking, and notifications.

### Security & Account Protection

#### Stronger Login Protection

 - Accounts temporarily lock after multiple failed login attempts to protect against unauthorized access
 - Login responses are now consistent whether an account exists or not, reducing the risk of account discovery
 - Clear on-screen messaging explains when an account is locked and when it can be accessed again

#### Improved Session Management

 - More reliable sign-in experience - users stay logged in during normal activity
 - Sessions automatically extend while active (up to a maximum duration)
 - All sessions are securely ended on logout or after password changes
 - Removed legacy “Remember Me” behavior in favor of modern, secure sessions
 - Additional production security hardening applied

### Password & Credential Management

#### Stronger Password Requirements

 - Clear, real-time password rules shown during registration and password changes
 - Password validation is enforced consistently across the system
 - Show/hide password option added to all password fields
 - Fully supported in English and French

#### Password Expiry & Notifications

 - Passwords now expire after 12 months
 - Users receive advance notifications before expiration and alerts when a password has expired
 - Clicking a notification opens the password change screen directly

#### Easier Password Changes

 - All users can change their own passwords
 - Forgot-password now works for all users with a valid email address
 - When an admin resets a password, users are notified and required to update it on next login

#### Email & Username Improvements

 - New users must use an email-format username
 - Existing users with non-email usernames are prompted to update for better security and recovery
 - Users can update their email/username directly from the user menu
 - Admins can update other users' email addresses (with appropriate permissions)
 - When a primary account email changes, the organization's contact email updates automatically

#### Notifications & Alerts

 - Support for targeted, scheduled notifications that can expire automatically
 - Notifications can include direct actions (for example: change password or update email)
 - Improved alert reliability and display behavior
 - Fully localized notification content

### Shipping & Tracking Enhancements

#### Proof of Delivery (POD)
 - PODs can now be emailed directly to one or more recipients
 - Professional email formatting with POD attached

#### Dangerous Goods
 - Improved detection and labeling of dangerous goods
 - Dangerous goods documents are now easier to access from shipment screens

#### Tracking Improvements
 - Refreshed tracking experience with more consistent data and naming
 - Cleaner and more reliable shipment tracking across the platform

#### Guest Ship Pickup Validation
 - Improved validation for pickup bookings, including:
   - Same-day pickup cutoffs
   - Minimum time windows
   - Clear visibility of terminal cutoff times
 - Reduced unpaid shipment hold time for faster cleanup and better system accuracy

#### Registration & Localization
 - New registrations are limited to Canadian addresses
 - Comprehensive French translation fixes and UI text improvements
 - Corrected bilingual routing and page titles

### Summary

This release focuses on:

- Enterprise-grade security with stronger login protection, session handling, and password controls
- Greater user independence, allowing all users to manage credentials and recover access securely
- Improved communication, with smarter notifications and clearer alerts
- Operational enhancements to POD delivery, dangerous goods handling, and pickup validation
- A more reliable, polished experience across tracking, registration, and localization
