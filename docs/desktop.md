<div class="product-roadmap-header">
  <h1>Desktop Roadmap</h1>
  <p>Thunderbird for Windows, macOS, and Linux. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.</p>
  <p style="font-size: 16px;">Last updated October 22, 2026</p>
  <p><a href="https://www.thunderbird.net/en-US/thunderbird/all/#select-download-desktop">Download Thunderbird for desktop</a></p>
</div>

## <i class="ph ph-pulse"></i> Active
- **Exchange (EWS, GraphAPI)** Finalize the work on the Exchange protocol in order to support all versions of Exchange and Microsoft 365, including calendar and address book support. Graph API support for email is finished, and calendar discovery and event sync have been implemented.
- **Global Database** Continue the work on the new Panorama database, allowing users to start testing the new database, and handle a consistent data migration.
- **Improve and extend existing add-ons APIs** Improve the currently available APIs, focus on giving access to new sections and core features, as well as introducing new APIs for specific sections.
- **Encryption and Security Improvements** Improve the support and discovery of OpenPGP and S/MIME, improve email tracking protection, and harden phishing email prevention. These will continue all year as we respond to high priority vulnerabilities, upstream changes, AI-powered sec reports and regressions. Post-quantum encryption has also come a long way, see the [PQC testing page](https://wiki.mozilla.org/Thunderbird:OpenPGP:PQCTesting). (Ongoing maintenance)
- **Settings Interface Improvements** Clean up and reorganize the settings into more discoverable sections and improve its search. User survey will heavily influence the end result. We are aiming to have all the strings, content navigation, and a first round of UI refresh completed by the end of 2026.
- **Calendar Dialogs UI/UX** Complete the refresh of the calendar interface and user experience. Some protocols handling changes might be needed. This work will also land a major part of the compose window refresh.
- **System Add-on Integration - Remote Updates** Building on the system add-on integration shipped in 153, enable system add-ons to be updated remotely, outside of the regular release train.

## <i class="ph ph-calendar-blank"></i> Planned
- **Conversation View** Display related messages together as a single conversation. This work depends on the new Global Database (Panorama).
- **JMAP** Add support for the JMAP protocol. This will be a priority in 2027 as Thundermail opens to the public and leverages JMAP.

## <i class="ph ph-rocket-launch"></i> Shipped
- **OAuth2 Enhancements** OAuth became a significant initiative due to evolving provider authentication requirements (including PKCE adoption), browser-based authentication improvements, and the need to deliver a seamless Thundermail sign-in experience. Delivery began in 154. <div class="date-badge">September 2026</div>
- **Thunderbird Enterprise** Thunderbird Enterprise work was completed, including extending the add-ons Account API to accommodate Enterprise requirements. <div class="date-badge">September 2026</div>
- **First Time User Experience: Account Hub** Complete Account Hub for all account creations, enable it for first time users. <div class="date-badge">March 2026</div>
- **Unobtrusive Signatures** This was part of the larger “Encryption and Security Improvements” initiative and has been completed to reduce confusion around OpenPGP signatures. <div class="date-badge">March 2026</div>
- **Exchange Email Support**  Full support of email operations and account creation. <div class="date-badge">November 2025</div>
- **Native OS Notifications** Add quick actions to reply, delete, mark messages as read/unread, and manage the notifications. <div class="date-badge">July 2025</div>
- **Implement Glean Telemetry** Move away from the old telemetry implementation and add the new Glean Telemetry. <div class="date-badge">April 2025</div>
- **In-App Notifications** Implement a new notification system that allows the Thunderbird team to push important, time-sensitive information directly to a user's Thunderbird desktop client. <div class="date-badge">May 2025</div>
- **First Time User Experience** We had to refocus on the email onboarding section of the Account Hub due to Exchange, Graph, and Thundermail release. User feedback & telemetry data points at a large percentage of manual config usage, and the new protocols come with very complex manual user flows. First introduction of a 1-click setup OAuth for Thundermail. <div class="date-badge">June 2026</div>
- **System add-on integration** Allowing to ship ad-hoc features faster for objectives that supersede the release train. This will be in 153! <div class="date-badge">June 2026</div>

