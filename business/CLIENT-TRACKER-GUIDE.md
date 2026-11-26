# Rapabi Digital — Internal Client Tracker Guide

## Purpose
Use `client-tracker.html` to keep a simple record of enquiries, quotes, project progress, client approvals, payment status and delivery. Use `quote-calculator.html` to prepare a clear quotation estimate before manually recording the agreed amount in the tracker.

## Open the tools
- Client tracker: `/business/client-tracker.html`
- Quote calculator: `/business/quote-calculator.html`

The website deployment remains protected by Vercel SSO. These are internal tools, not public customer portals.

## Quote calculator
- Add one or more service/deliverable line items, quantities and unit prices.
- Add an optional discount and deposit percentage to calculate the balance.
- Fill in scope, timeline, revisions, validity date, payment terms and exclusions.
- Copy the quote text or use Print / Save PDF, then review it carefully before sending.
- The calculator does not send messages, create invoices, apply tax automatically, or save data. Copy or print the quote before leaving the page.
- Confirm the correct tax treatment with an appropriate South African tax professional before representing any amount as VAT-inclusive or VAT-exclusive. Do not assume VAT registration status.
- Prices are estimates until the scope and terms are agreed in writing. Third-party costs such as domains, hosting, stock assets and paid subscriptions must be identified separately.

## How the tracker works
- Records are saved in the browser's local storage on the device/browser profile where you use the tracker.
- They do not automatically sync between your phone and another device or browser.
- Use **Export backup** regularly and keep the JSON backup somewhere private.
- Use **Import backup** to restore or combine a previous backup. Matching record IDs are replaced; other records are kept.
- Clearing browser/site data, changing browser profiles, or losing the device may remove local records if you do not have a backup.

## Suggested workflow
1. Add a record when a genuine enquiry arrives.
2. Record only the details needed to respond and scope the work.
3. Move the stage from New enquiry through Discovery and Quote sent.
4. Prepare a quotation with the calculator; check the scope, price, validity and exclusions.
5. Record the agreed quote and written client approval before production.
6. Update payment, approval, delivery and target date as the project progresses.
7. Mark Completed only after the agreed deliverables are handed over.

## Privacy and safety
- Do not store passwords, identity numbers, bank/card details, private credentials, or sensitive personal information.
- Do not store client passwords or account access in notes.
- Use a device lock and keep exported backups private.
- The tracker is browser-only and is not encrypted storage or a regulated client-record system. The quote calculator does not retain data. These are lightweight operational aids, not legal, tax or accounting software.

## Current limits
- No automatic email or WhatsApp capture.
- No invoices, payment processing, reminders, or customer messaging.
- No cloud sync or multi-user access.
- No customer outreach or publishing actions.
