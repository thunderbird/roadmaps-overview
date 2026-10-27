<div class="product-roadmap-header">
  <h1>iOS Roadmap</h1>
  <p>Thunderbird for iOS. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.</p>
  <p style="font-size: 16px;">Last updated October 22, 2026</p>
  <p><a href="https://testflight.apple.com/join/ER3hRBSz">Download TestFlight app</a></p>
</div>

## <i class="ph ph-pulse"></i> Active
- **Full Email Writing and Reading Experience** Implement the full reading and writing email experience on mobile. Compose, reading, and writing are in place; the remaining piece is rendering the inbox.
- **Calendar Exploration** Exploring calendar support with a platform-agnostic approach alongside Android, while looking for some quick wins on iOS.


## <i class="ph ph-calendar-blank"></i>Planned
- **JMAP Support - Complete Implementation** Support the JMAP protocol as one of the first extra protocols we ship with by default outside of IMAP. Currently we are prioritizing IMAP so the first release covers all email users. Now planned for 2027.
- **Database - Phase 2** Split out from the protocol and framework work to provide more fully featured database operations. The first version of the app can ship using an in-memory cache with minimal database functionality.
- **Email Encryption Support** Initial support for encrypted messages (OpenPGP and S/MIME with existing libraries). This was previously part of the Full Email Writing and Reading Experience initiative and is now planned for 2027. We are focusing on the core app experience first: encryption needs an app that reliably loads emails for reading and writing, and because every provider implements the mail standards (IMAP/SMTP/MIME) a little differently, we are making sure every case is covered and reliable before building on top of it.


## <i class="ph ph-rocket-launch"></i> Shipped
- **Architecture** Establish a robust and scalable architecture to begin the Thunderbird for iOS project and create the backend. This architecture will include strategies for code sharing across platforms, taking into account the Android and Desktop clients. <div class="date-badge">July 2025</div>
- **Autoconfiguration** Add DNS MX lookup to autoconfig feature library and move SRV record lookup into autoconfig feature library and delete Autodiscover core library <div class="date-badge">September 2025</div>
- **Account Creation Flow** Implement a full automated and manual setup, including autodiscovery and OAuth. <div class="date-badge">March 2026</div>
- **iOS Create Protocol & Framework** Implement the IMAP protocol first as it's the most widespread protocol currently in use. We completed the protocol work and basic framework. <div class="date-badge">June 2026</div>
- **JMAP Support - Exploration** Initial exploration of the JMAP protocol is complete. The full scaffolding will be done as part of the complete implementation. <div class="date-badge">September 2026</div>
