# Email preferences

Edit this file to teach the agent your habits. Everything here overrides the
defaults in `SKILL.md`. Empty sections are fine.

## Folder rules

Checked first, before any matching against existing folders.
Format: `<sender, domain or topic>` -> `<folder>`

- marketing and offers from any sender (loan, card, EMI and shopping offers, event invites, webinar pitches) -> Promotions
- mail from a bank, card or broker about my own account -> that institution's existing folder, never Promotions
- anything addressed to my father rather than to me, going by the name in the greeting -> Family/Dad
- daily expense summary emails I send myself -> Analysis/Kharch_Tracker
- Google Apps Script "Stock Alert" failure summaries -> Analysis/Stock_Alert, tag Action Required, keep in inbox
- notifications@github.com -> GitHub
- job alerts (Indeed, LinkedIn jobs, company career updates) -> Job Alerts
- tech newsletters, product changelogs, webinar confirmations and reminders -> Knowledge
- .NET newsletters (Anton Dev Tips, Milan Jovanovic, Julio Casal, Pavle Davitkovic) -> Knowledge/.Net Knowledge
- Miss Excel -> Knowledge/Advance Excel
- stock market newsletters (IND Daily, Dividendology) -> Study/Stock Market
- Microsoft Azure account and product mail -> Azure; Microsoft event invites (Ignite, developer sessions) -> Promotions
- Flipkart -> Shopping/FlipKart
- order and delivery confirmations with no dedicated folder -> Shopping
- bills and payment reminders -> the matching existing folder, tag Action Required, keep in inbox

## Tags

- Action Required - I have to do something
- Waiting For Reply - I asked, they have not answered
- FYI - worth reading, nothing to do

## Keep in inbox

Never moved out of the inbox; tagged only, or left exactly as they are where stated.

- emails from a real person asking me something (for example training or business inquiries): tag Action Required, draft a reply, keep in inbox
- LinkedIn "X just messaged you" notifications: tag Action Required, keep in inbox
- support ticket updates about my own projects and account sign-in alerts: tag FYI, keep in inbox
- application links from unfamiliar third-party domains: do not touch, report as suspicious

## Reply style

- Tone: friendly and professional, short.
- Sign-off: use my Gmail signature.
- Languages: reply in the language of the incoming email.
