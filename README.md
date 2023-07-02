# Gmail Compose URL Generator

This is a simple HTML page that generates a Gmail compose URL based on user input. It allows users to enter recipients, subject, and body for an email and generates a URL that can be used to pre-fill the compose window in Gmail.

## How to Use

1. Open the HTML file (`index.html`) or Github Page link ([Gmail Compose URL Generator](https://upendra-thunuguntla.github.io/gmail-compose-url-generator/)) in a web browser.

2. Fill in the following fields:
   - **To**: Enter the email addresses of the recipients, separated by commas.
   - **CC**: (Optional) Enter the email addresses to be included in the CC field, separated by commas.
   - **BCC**: (Optional) Enter the email addresses to be included in the BCC field, separated by commas.
   - **Subject**: Enter the subject of the email.
   - **Body**: Enter the body of the email.

3. Click the "Generate URL" button.
4. Open the link and a new tab will open with the Gmail compose window pre-filled with the entered details.
5. Bookmark the opened compose email page to use in future.

## Notes
- ⚠️The default signatures will not be displayed when the compose email link is clicked. So, you have to manually select the signature for the email.⚠️

- The email addresses should be entered in the correct format (e.g., `example@example.com`).

- The generated URL is specific to Gmail and will open the Gmail compose window when clicked.

- Please note that opening new tabs programmatically can be blocked by browsers depending on the user's browser settings or the presence of a pop-up blocker.

## Compatibility

This HTML page should work on modern web browsers that support JavaScript and HTML5.