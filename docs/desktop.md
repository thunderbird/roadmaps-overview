# Desktop Roadmap

Thunderbird for Windows, macOS, and Linux. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.

[Download Thunderbird for desktop](https://www.thunderbird.net/en-US/thunderbird/all/)

## Active
**Exchange (EWS, GraphAPI)** - Finalize the work on the Exchange protocol in order to support all versions of Exchange and Microsoft 365, including calendar and address book support.
**Global Database** - Continue the work on the new Panorama database, allowing users to start testing the new database, and handle a consistent data migration.
**Improve and extend existing add-ons APIs** - Improve the currently available APIs, focus on giving access to new sections and core features, as well as introducing new APIs for specific sections.

## Planned
**First Time User Experience** - Complete Account Hub for all account creations, enable it for first time users, and show a customization wizard after first account creation.
**Calendar Dialogs UI/UX** - Complete the refresh of the calendar interface and user experience. Some protocols handling changes might be needed.
**Settings Interface Improvements** - Clean up and reorganize the settings into more discoverable sections and improve its search.
**Encryption and Security Improvements** - Improve the support and discovery of OpenPGP and S/MIME, improve email tracking protection, and harden phishing email prevention.

## Launched
**Exchange Email Support** (November 2025) - Full support of email operations and account creation. [link](https://support.mozilla.org/en-US/kb/thunderbird-and-exchange)
**Native OS Notifications** (July 2025) - Add quick actions to reply, delete, mark messages as read/unread, and manage the notifications. [link](https://blog.thunderbird.net/2025/08/monthly-release-141-recap/)
**Implement Glean Telemetry** (April 2025) - Move away from the old telemetry implementation and add the new Glean Telemetry. [link](https://bugzilla.mozilla.org/show_bug.cgi?id=1899602)
**In-App Notifications** (May 2025) - Implement a new notification system that allows the Thunderbird team to push important, time-sensitive information directly to a user's Thunderbird desktop client. [link](https://support.mozilla.org/en-US/kb/notifications-thunderbird)

## Backlog
**Unified Toolbar Completion** - Continue the work on the unified toolbar to apply to all sections and remove the old m-c forked customizable toolbar code.
**Compose Window** - Modernize the composition editor to support modern widgets and markdown. Rebuild the UI of the compose window.
**Improve add-ons API documentation and release changelog** - Keep up to date the official API documentation and ensure that monthly changelogs incorporate API changes.
**Conversation View** - Complete the work on the new conversation view UI to consume the new Panorama database.
**Spaces Toolbar Completion** - Continue the work on the spaces toolbar to implement a better spaces distinction, easy entry point to add extensions, vertical toolbars, and more customization options.
**Settings Refresh** - Audit and reorganize the settings and account settings into a single modal window. Improve the searchability and discoverability of settings.
**Customizable Shortcuts** - Continue the work on customizable shortcuts to move away from XUL keys and allow users control of default keyboard combinations.
**OS Integration** - Improve the integration with native OS features like notifications, status bar, and system tray.
**JMAP** - Explore the implementation of the JMAP protocol.
