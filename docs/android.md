Welcome to the **Thunderbird for Android** roadmap!

# 🏗️ Active
* **Account Drawer Improvements** - Redesign the account drawer to enhance the usability and clarity of the drawer. This adds the ability to set a different icon for each account, displays account names and associated email addresses in a wide format, and adds a visual indication that an account is selected.
* **Sync Debug Tooling** - Implement a better logging mechanism to enable fixing commonly reported sync/push issues.
* **In-app Error Notifications** - Inform the user of errors that occurred while the app was performing foreground or background operations.
* **Android 15 Compat (Edge to Edge)** - Update the app to target Android 15.

# 📋 Planned
* **Display current "push state" to the use** - Inform the user of errors that occurred while the app was waiting for new messages via push to make receiving emails more reliable and actionable.
* **Refactor Message Synchronization** - Automatically fetch messages from the server when a user opens a folder or when scrolling down the message list and reaches the end of the downloaded messages.
* **Telemetry Prompt and Crash Reporting** - Integrate the Glean SDK into Thunderbird for Android to be able use its telemetry to inform development.
* **Refactor Message Compose** - Improve the HTML parsing for sending emails
* **Clean Up Folder Settings UX** - Make it easier for the user to understand the dependencies between different folder settings.
* **Set better defaults for QR code import** - Improve the experience of users importing their accounts from Thunderbird desktop.
* **Refactor Message List** - Limit the amount of memory used to display the message list by only loading information about a limited number of messages into memory at a time. 
* **HTML Signatures** - Give users a way to set HTML signatures.
* **Quick Filters and Email Actions** - allow the user to quickly filter the message list using certain message attributes like read state, star state, whether or not there is an attachment present.

# 🚀 Launched
* **CASA Approval** - Complete the Cloud Application Security Assessment (CASA)

# 🗃️ Backlog
* **Send Later / Undo Send** - Provide a scheduled mail feature where mail would only be sent at a specific time as well as the ability to undo a sent email within some period of time.
* **Thunderbird Android Sync** - Implement Mozilla Sync to Thunderbird for Android to allow users to store data (mail server settings, identities, and passwords) in an end-to-end encrypted stream and be able to sync between devices.
* **JMAP Support** - Add support for mail servers that use the JMAP protocol.
* **Conversation View** - In addition to the current threaded view, add support for a conversation view that displays all messages in a conversation.
* **Material You** - Implement Material You support for a more modern feel.
* **Smart Email Summaries** - Offer users the option to have an LLM parse the content of the email, and create a short digest, providing a more meaningful overview of a new message.
* **Folder Hierarchy** - Show the list of folders in a hierarchy and collapse folders as needed to enable users to better navigate between folders and be more productive when finding an email.
* **Simplified Settings** - Review the settings and make it more simple to use, while providing more advanced users with an opportunity to customize.
* **Inline PDF Viewer** - Use Pdf.js to open PDF files before prompting the user to open the PDF in another application.
* **Migrate to the new Preferences System** - Modernize the preferences system, allowing the application to better react to preferences changes.
