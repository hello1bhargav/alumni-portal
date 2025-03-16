Alumni Portal Test Cases

1. User Authentication
Login Functionality
- Valid username and correct password
- Valid username and incorrect password
- Invalid username and password
- Empty username and password fields
- Login session timeout behaviour

Registration
- Valid data with correct email and phone format
- Duplicate email or phone entry
- Invalid email/phone format
- Required fields left blank

Password Management
- Successful password reset
- Incorrect old password attempt
- Password strength validation
- Forgot password email delivery


2. Profile Management
Profile Creation/Editing**
- Add complete profile details (name, batch, branch, etc.)
- Missing mandatory fields
- Uploading a profile picture (valid & invalid formats)
- Field validation for contact details

Profile Privacy
- Visibility control for email, phone, etc.
- Unauthorized profile access attempt


3. Event Management
Event Creation
- Valid data entry (date, venue, description)
- Invalid date format or past date entry
- Notification to alumni upon event creation

Event Registration
- Successful event registration
- Duplicate registration prevention
- Cancellation and refund process


4. Job Board
**Job Posting**
- Posting jobs with valid/invalid details
- Job expiry and removal
- Notification for new job postings

Job Applications
- Successful application submission
- Duplicate application prevention


5. Messaging & Notifications**
Inbox/Message System
- Sending/receiving messages between alumni
- Attachment support in messages
- Spam/malicious content detection

Email Notifications
- Email alerts for important updates (e.g., events, jobs)
- Email formatting and broken links check


6. Search & Filter
**Alumni Search**
- Search by name, batch, branch, etc.
- Filter results accuracy
- Empty result handling


7. Security & Permissions
Security
- SQL Injection prevention
- Cross-site scripting (XSS) prevention
- Role-based access control

Session Management
- Auto-logout after inactivity
- Preventing simultaneous logins from multiple devices


8. Performance
Load Testing
- Handling multiple concurrent users
- Response time under peak load

Stress Testing
- System behavior under maximum data entries


9. Usability & UI
Navigation
- Smooth navigation across sections
- Clear error messages for failed actions

Accessibility
- Keyboard navigation support
- Screen reader compatibility


10. Database Testing
Data Integrity
- Correct storage of alumni data
- Data consistency after updates/deletes

Backup & Recovery
- Successful database restoration after crash

