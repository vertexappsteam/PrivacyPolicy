# Privacy Policy for JobPilot AI

**Last Updated:** September 2026

JobPilot AI ("we", "our", or "the extension") is committed to protecting your privacy. This Privacy Policy explains how JobPilot AI handles user data.

## 1. Data Collection and Usage
JobPilot AI is designed with a **privacy-first, client-side architecture**:
- **Personal Information:** Information provided by the user (such as full name, email address, phone number, location, work experience, education, skills, and resume files) is stored **locally on your device** via Chrome's local storage API (`chrome.storage.local`).
- **Single Purpose:** This data is used solely to autofill job application forms on websites navigated to by the user.
- **Zero Remote Tracking / Telemetry:** We do not collect, transmit, store, or sell any personal data on external servers or databases.

## 2. Permissions Used
- **`storage`:** Required to save user profile data, settings, and application history locally on the user's browser.
- **`activeTab` & `tabs`:** Used to identify the active job application tab URL and communicate form-filling instructions.
- **`scripting` & `<all_urls>`:** Required to scan and autofill form input fields across various company career portals and ATS platforms.

## 3. Third-Party Sharing & AI Services
- We do not sell, rent, or transfer any user data to third parties.
- If you optionally enable AI question resolution with your own Google Gemini API key, prompt queries are sent directly from your browser to the Google Gemini API in accordance with Google's API Terms of Service.

## 4. Data Deletion
Users have full control over their data. You can delete all stored profile and history data at any time directly within the extension under **Settings -> Clear Profile Data** or by uninstalling the extension.

## 5. Contact
If you have any questions regarding this Privacy Policy, please contact the developer via the GitHub repository or support email.
