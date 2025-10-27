Welcome to the **Thunderbird Desktop** client roadmap! 

# 🏗️ Active
* **Conversation View** - Implement an optional threaded layout allowing to view a whole conversation with collapsable and expandable messages.This text is inside an HTML div with a border.
* **Calendar UI/UX Overhaul** - Refresh and modernize the interface of the calendar space.
* **First Time User Experience** - Implement a new account setup flow and simplify the creation and discovery of calendars and address books.
* **Global Message Database** - Improve a new global database and replace the existing per-folder model.

# 📋 Planned
* **Unified Toolbar Completion** - Consume the Unified Toolbar in all other needed spaces and replace the old customizable code.
* **Rearchitect Tabs and Spaces** - Rebuild the spaces and tabs so that each space handles their own tabs.
* **System Tray** - Implement a native system tray with common actions.
* **Compose Window Improvements** - Modernize and improve the current message editor.
* **Settings Interface Improvements** - Clean up and reorganize the settings into more discoverable sections and improve its search.

# 🚀  Launched
* **Exchange Email Support** - Full support of email operations and account creation. [[link](https://support.mozilla.org/en-US/kb/thunderbird-and-exchange)]
* **Native OS Notifications** - Add quick actions to reply, delete, mark messages as read/unread, and manage the notifications. [[link](https://blog.thunderbird.net/2025/08/monthly-release-141-recap/)]
* **Implement Glean Telemetry** - Move away from the old telemetry implementation and add the new Glean Telemetry. [[link](https://bugzilla.mozilla.org/show_bug.cgi?id=1899602)]
* **In-App Notifications** - Implement a new notification system that allows the Thunderbird team to push important, time-sensitive information directly to a user's Thunderbird desktop client. [[link](https://support.mozilla.org/en-US/kb/notifications-thunderbird)]

# 🗃️  Backlog
_These initiatives have not been fully planned out yet with a timeline and a Scope of Work (SoW) but we are planning on planning them._

* **Chat Design Kickoff** - Initial exploration and planning for a new Chat implementation.
* **Revamp Email Encryption** - Streamline onboarding, configuration, and consumption of email encryption.
* **Exchange Calendar** - Integrate the Exchange Calendar and support exchange-specific features.
* **Exchange Address Book** - Integrate the Exchange Contacts and support exchange-specific features.
* **Exchange Graph API** - Add support for the Graph API protocol that will eventually replace EWS.
* **Notes** - Implement the ability to store notes in the user's profile and in Sync. Support markdown in addition to HTML and plain text inputs
* **Tasks** - Provide a more modern UI, provide an optional kanban board, and integrate tasks into the calendar, address book, and emails.
* **Home Space** - Improve the starting page to provide a summary of accounts, informative statistics about usage, and quick links to common actions.
