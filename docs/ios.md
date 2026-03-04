# iOS Roadmap

Thunderbird for iOS. Follow the roadmap from active work to future ideas. Timelines may shift as we learn and iterate.

## <i class="ph ph-pulse"></i> Active
**Account Creation Flow** - Implement a full automated and manual setup, including autodiscovery and OAuth.
**IMAP Support** - Implement the IMAP protocol first as it's the most widespread protocol currently in use.
**Full Email Writing and Reading Experience** - Implement the full reading and writing email experience on mobile, including initial support for encrypted messages (OpenPGP and S/MIME with existing libraries).

## <i class="ph ph-calendar-blank"></i>Planned
**JMAP Support** - Support the JMAP protocol as one of the first extra protocols we ship with by default outside of IMAP.
**HTML Signatures** - A long time requested feature that alongside Sync will strengthen the continuity between our apps and the first step towards a working ecosystem.

## <i class="ph ph-rocket-launch"></i> Launched
**Architecture** - Establish a robust and scalable architecture to begin the Thunderbird for iOS project and create the backend. This architecture will include strategies for code sharing across platforms, taking into account the Android and Desktop clients.
**Autoconfiguration** - Add DNS MX lookup to autoconfig feature library and move SRV record lookup into autoconfig feature library and delete Autodiscover core library
