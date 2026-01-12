Welcome to the **Thunderbird Services** roadmap!

# :construction_site: Active
* **AWS Account Migration** - One of the items flagged from the Send security review was that we're using one AWS account for all of our products. To increase security, we'd like to split our operations into multiple accounts.
* **Observability and Alerting** - While we have a few alerts and reporting set up right now, as we grow our customers we should be more proactive on events that lead to degraded performance or outages.  
With this goal we intend to implement SLO and SLAs that will prepare us for a general release, and combine them in a reporting solution that can be viewed regularly. We shall have meaningful alerts that put us in front of customer inquiries.
* **Thunderbird Sync Infrastructure** - In the past we were looking to get Thunderbird Sync set up. This effort was paused, and we'd like to pick it up again in 2026.  
For this project we will get the sync storage set up and connected to our IaC solution, ensure effective use of storage to minimize cost, and do the financial modeling required to make it attainable.
* **Integrate Thunderbird Appointment into Pro add-on** - As a Pro user, you want to be able to quickly copy your scheduling link when in Thunderbird. Integrate so it can be inserted into emails, or easily copied from the main toolbar.
* **Active Sessions** - Give the user a view on their active sessions and allow them to end the session. We didn't get to this in 2025.  
<https://ideas.tb.pro/p/show-active-login-sessions>
* **Thundermail receivability improvements and spam filtering** - The spam filtering is currently very aggressive, so that many emails land in spam that aren't intended to be. While some adjustments may land in 2025 Q4, we need to spend dedicated time to improve receiving email.  
This includes defining and tracking measurable KPI that show us spam rates and user impact.  
To optimize, we will determine how to pre-train the bayes filtering, make adjustments to how we send our own email to avoid the spam trap, and experiment with LLM-based spam filtering using confidential compute for additional privacy. There are some additional designs from 2025 for an allowlist we should also integrate.
* **Send UI Completion** - Send was the one product we haven't been able to complete UI overhaul work. We don't need to block the rollout for this, but we should work on this to keep it up to par with the other products and create consistency.
* **MFA Support** - Multifactor authentication via TOTP or similar. We didn't get to this in 2025, and it is an essential security feature.  
<https://ideas.tb.pro/p/multifactor-authentication>
* **Offboarding process** - Our offboarding process is currently reaching out to support and having a developer shut down the account. We need to automate the offboarding process so that it automatically occurs when the subscription ends, or can be accelerated by support if requested. Here we'll also make sure to learn from the user why they are leaving, and encourage them to either stay, or convert to a financial contribution.
* **Additional Product Tiers** - As we learn more from our users, we need to consider that not everyone will want an annual plan, and some users might need more storage or aliases.  
Based on the feedback we receive we will investigate pricing tier improvements in time for the first users ending their 1 year annual membership. This could include monthly options, adjustments to the default payment tier, and additional storage/alias options.  
<https://ideas.tb.pro/p/additional-pricing-tiers>
* **Website Revamp 2026** - As we continue to grow our product palette, there are some ways we can organize the website in a more structured way. This goal complements initiatives from Marketing to implement the changes they suggest.
* **Financial Contributions Appeals** - As an organization primarily funded by financial contributions from users, we need to implement a number of appeals in the year. This goal serves to implement the design/marketing changes for the appeals and roll them out using our infrastructure.

# :clipboard: Planned
* **Security Audit and Remediation** - As a regular practice, we'd like to engage in multiple security audits to improve both operational and product security. While the audit is external, potential followup tasks include infrastructure and product mitigations that need to be scoped.
* **Pulumi and CI/CD improvements** - We're using Pulumi as an IaC solution, so that our deployments are reproducible and reviewable. As a foundational project we can make some improvements in this area that make deployments to stage and production seamless and don't impact developer time.  
As an example, our network configuration is mostly a manual setup. If we're able to codify this setup, we can more easily migrate to other systems or ensure that our settings are intact.
* **Staff OIDC instance for MZLA services.** - Most of the services we're currently running have username/password authentication through a shared password manager. As we continue to grow, this approach becomes more risky. Having our own OIDC instance that we can administrate makes it easier to onboard new services and separates operational burden from Mozilla Corporation.
* **Dev environments for PRs** - We'd like to make it easier to test pull request changes without setting up too much infrastructure locally. Using dev environments will help us achieve this.
* **DANE TLSA and DNSSEC** - Support DANE TLSA and DNSSEC for our pro services. This increases security and protects against downgrade attacks.  
<https://ideas.tb.pro/p/dnssec-dane-support>
* **Thunderbird Pro Niche** - Thunderbird Pro is filling a gap in our user base and allows us to build a sustainable service. We'd like to take it further and make it something people outside of the Thunderbird bubble care much about deeply.  
We're entering into a saturated market, therefore it is even more important that we find the right niche. This could be anything from providing the best possible support for encryption, or making Thunderbird Pro as extensible as Thunderbird Desktop is.  
With this roadmap item we'll first focus on product exploration to make sure we're hitting the right mark, and then work out some prototypes or features based on the investigation results.
* **Improve Reporting Feature** - Our content reporting mechanism is very basic right now. Explore ways to ensure our systems are not abused while keeping confidentiality.
* **Shipping as a system add-on** - For launch we will ship as an add-on on ATN. We want to integrate the Pro features into Thunderbird, but keep the flexibility of shipping features.  
We propose using a system-addon as the delivery mechanism. An alternative may be to integrate the features into Thunderbird Desktop, though we lose some flexibility when it comes to server side API changes.
* **Thunderbird Sync** - In the past we were looking to get Thunderbird Sync set up. This effort was paused, and we'd like to pick it up again in 2026.  
As part of this effort, Thunderbird Sync will serve as the free option within the Thunderbird Pro family. People can create an account and keep their data consistent across their devices. If they ever want additional features, we can offer Thunderbird Pro as an optional upgrade, especially as we get closer to general availability.
* **Appointment: Additional calendaring and meeting support** - We currently support CalDAV, Google Calendar, and Zoom. To appeal to a broader set of users, we need to implement connectors to other video conferencing platforms as well as calendaring providers.  
We prefer open standards as are available, though we need to accept the reality that users have existing closed services they use for leisure or work. We may be able to leverage RFC6503 to support multiple video conference services and encourage vendors to support it.  
<https://ideas.tb.pro/p/appointment-google-meet-support>  
<https://ideas.tb.pro/p/appointment-microsoft-teams-support>  
<https://ideas.tb.pro/p/appointment-jitsi-meet-integration>  
* **Community Placeholder** - No doubt the community will have a bunch of great ideas that we can build on. Let's make sure we reserve some time to work on one of the top community suggestions that fit well into the Thunderbird Pro ecosystem.
* **addons.thunderbird.net** - We need to do something with addons.thunderbird.net to make it more viable and a better tool for add-on developers.  
This goal includes some product and devrel exploration to figure out what would serve the community best: investing time into the current addons.thunderbird.net infrastructure to make it more modern, attempting to get closer to the latest upstream, or developing alternative ways that add-ons for Thunderbird can be maintained.
* **Community Building: Good first bugs** - Train our engineers to identify good first bugs for community members and mentor contributors. Make this a regular part of engineering's activities.

# :card_box: Backlog
* **Build attestations** - For supply chain security, and verifying that the builds we make actually land in our production infrastructure, we will investigate and deploy changes to reach the Build L2 or above level of the SLSA v1.0 framework.
* **Blue/Green Deployments** - In order to increase uptime and reduce customer disruption, we plan to introduce blue/green deployments into our infrastructure. This way we can ensure a seamless rollback in case there are issues.  
This item adds additional complexity and cost, therefore we'll first investigate the best approach and financial modeling.
* **Services Logging** - We're collecting various logging in our services which can give us useful indicators of failure or debugging for common issues. By creating a more streamlined process for log analysis, we can reduce the risk of bugs in our services.
* **Additional Encryption at Rest with OpenPGP or S/MIME** - Stalwart, the email server we are using, supports a feature where all incoming email is encrypted with the user's OpenPGP or S/MIME key before it is stored. This is great because only the user can decrypt the email and it is encrypted at rest, and complements us storing the email data in an encrypted volume.  
This is an exciting feature for power users, though we need to be intentional on how we present this option to the user. Once enabled, searching email in Thunderbird will be more complicated as the messages are encrypted. If the user loses the keys, they will no longer have access to their email. Webmail will not work with this feature enabled. Further, there can be a false sense of security, as in theory we could put a proxy in front of the mail server and "read" the email before it is encrypted.  
All that said, giving the user the ability to upload their keys and optionally enable this feature may be a compelling part of Thundermail's story Once we've found our niche we will evaluate how to approach this item.  
<https://ideas.tb.pro/p/additional-encryption-at-rest-with-openpgp-or-s-mime>
* **Send cross-validation** - When you sign in to a browser or Thunderbird instance, you need to provide your recovery key. You might not always have this handy, but you might have another device ready. We'd like to set up a secure mechanism where you can deliver the key from the instance that has the recovery key to the instance you are signing in on. This would be similar to Matrix' device verification.  
<https://ideas.tb.pro/p/send-e2e-cross-device-login-verification>
* **Send: Folder support** - Currently, all files are stored in one folder. We should allow the user to organize their files as they see fit, and allow entire folders to be shared. Work in this goal depends on product explorations and feedback on how people are using our service.  
<https://ideas.tb.pro/p/send-multiple-folder-support>
* **Thundermail: Webmail** - What would an email service be without webmail? We should spend some time bringing the proof of concept closer to release, and enable this as an experimental feature for users willing to try things early.  
Scoping should be limited to basic folder visibility and message display.  
Webmail will be built with JMAP as a backend, and we need to explore how users can benefit from Webmail while still being encouraged to use end to end encryption and allowing search across folders.  
<https://ideas.tb.pro/p/webmail-for-thundermail>
* **Accessibility improvements** - All of our services need functional accessibility, across platforms (web/mobile). While our engineers are looking at this from the start, we should spend some foundational time to ensure we're adhering to standards related to accessibility and creating an accessible experience for Thunderbird Pro.
