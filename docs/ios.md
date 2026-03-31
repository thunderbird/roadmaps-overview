<div class="product-roadmap-header">
  <h1>iOS Roadmap</h1>
  <p>Thunderbird for iOS. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.</p>
  <p style="font-size: 16px;">Last updated March 17, 2026</p>
  <p><a href="https://testflight.apple.com/join/ER3hRBSz">Download TestFlight app</a></p>
</div>

## <i class="ph ph-pulse"></i> Active
- **iOS Create Protocol, Database, & Framework** Implement the IMAP protocol first as it's the most widespread protocol currently in use.
- **Full Email Writing and Reading Experience** Implement the full reading and writing email experience on mobile, including initial support for encrypted messages (OpenPGP and S/MIME with existing libraries).

## <i class="ph ph-calendar-blank"></i>Planned
- **JMAP Support** Support the JMAP protocol as one of the first extra protocols we ship with by default outside of IMAP.

## <i class="ph ph-rocket-launch"></i> Shipped
- **Account Creation Flow** Implement a full automated and manual setup, including autodiscovery and OAuth. <div class="date-badge">March 2026</div>
- **Architecture** Establish a robust and scalable architecture to begin the Thunderbird for iOS project and create the backend. This architecture will include strategies for code sharing across platforms, taking into account the Android and Desktop clients. <div class="date-badge">July 2025</div>
- **Autoconfiguration** Add DNS MX lookup to autoconfig feature library and move SRV record lookup into autoconfig feature library and delete Autodiscover core library <div class="date-badge">September 2025</div>
