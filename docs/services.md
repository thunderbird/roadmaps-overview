<div class="product-roadmap-header">
  <h1>Services Roadmap</h1>
  <p>Thunderbird Pro Services and Infrastructure Support. Follow the roadmap from active work to future ideas. Timelines may change as we learn and iterate.</p>
</div>

## <i class="ph ph-pulse"></i> Active
- **Send UI Completion** Send was the one product we haven't been able to complete UI overhaul work. We don't need to block the rollout for this, but we should work on this to keep it up to par with the other products and create consistency.
- **Dev environments for PRs** We'd like to make it easier to test pull request changes without setting up too much infrastructure locally. Using dev environments will help us achieve this.
- **Financial Contributions Appeals** As an organization primarily funded by financial contributions from users, we need to implement a number of appeals in the year. This goal serves to implement the design/marketing changes for the appeals and roll them out using our infrastructure.
- **Active Sessions** Give the user a view on their active sessions and allow them to end the session. <bolt-primary-button
      variant="outline"
      href="https://ideas.tb.pro/p/show-active-login-sessions">
      ideas.tb.pro
    </bolt-primary-button>
- **Services Logging** We're collecting various logging in our services which can give us useful indicators of failure or debugging for common issues. By creating a more streamlined process for log analysis, we can reduce the risk of bugs in our services.

## <i class="ph ph-calendar-blank"></i> Planned
- **MFA Support** Multifactor authentication via TOTP or similar. We didn't get to this in 2025, and it is an essential security feature. <bolt-primary-button
      variant="outline"
      href="https://ideas.tb.pro/p/multifactor-authentication">
      ideas.tb.pro
    </bolt-primary-button>
- **Community Selected Initiative** No doubt the community will have a bunch of great ideas on https://ideas.tb.pro that we can build on. We're making sure we have time to work on one of the top community suggestions that will fit well into the Thunderbird Pro ecosystem.
- **Integrate Thunderbird Appointment into Pro add-on** As a Pro user, you want to be able to quickly copy your scheduling link when in Thunderbird. Integrate so it can be inserted into emails, or easily copied from the main toolbar.
- **Observability and Alerting** While we have a few alerts and reporting set up right now, as we grow our customers we should be more proactive on events that lead to degraded performance or outages.
With this goal we intend to implement SLO and SLAs that will prepare us for a general release, and combine them in a reporting solution that can be viewed regularly. We shall have meaningful alerts that put us in front of customer inquiries.
- **Improve Pro Add-on Integration** For launch we are shipping as an add-on on addons.thunderbird.net. For a low barrier of entry we want to improve integration by using the system add-on or new account add-on mechanism. This allows us to ship new Pro features while remaining flexible.
- **Thundermail: Webmail** What would an email service be without webmail? We will spend time making the proof of concept more usable, and enable this as an experimental feature for users willing to try new things earyly. The scope will initially be limited to basic folder visibility and message display.
Webmail will be built with JMAP as a backend, and we need to explore how users can benefit from Webmail while still being encouraged to use end to end encryption and allowing search across folders. <bolt-primary-button
      variant="outline"
      href="https://ideas.tb.pro/p/webmail-for-thundermail">
      ideas.tb.pro
    </bolt-primary-button>
