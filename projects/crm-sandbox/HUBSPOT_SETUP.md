# Hands-on HubSpot setup checklist

This complements the interactive browser demo. It is important to complete the live account steps yourself and only describe steps you actually completed in an interview or resume.

## 1. Create a practice account

- Start at the [HubSpot CRM page](https://www.hubspot.com/products/crm) and create an account.
- Use fictional practice contacts only. The CSV in `data/sample_contacts.csv` uses reserved `.example` email addresses and cannot reach real people.
- HubSpot's exact menus and included features can change. Follow the current in-product instructions if the navigation labels differ from this guide.

## 2. Add contacts

- In the CRM's Contacts area, use its import or create-contact option.
- For a manual exercise, create at least three contacts and fill in name, email, company, source, and primary goal where available.
- To practice a CSV import, try `data/sample_contacts.csv`. Map the columns to matching contact properties; create the custom properties `Lead source` and `Primary goal` only if you need them and your account permits it.
- Search for a contact by email before creating another record to reduce duplicates.

## 3. Configure a deal pipeline

Create or customize a practice pipeline with stages that mirror the demo:

1. New Inquiry
2. Contacted
3. Qualified
4. Trial Started
5. Converted

In a deal record, use an amount, associate the right contact, select the stage, and record a specific next action. If the account's default labels cannot be edited, map your sample stages to the closest available stages and document that difference.

`data/sample_deals.csv` is a reference sheet for manual deal creation. It is not guaranteed to import directly: deal-stage values and associations depend on the exact pipeline and import mapping set up in your account. Associate deals using the contact email where the import tool supports it.

## 4. Create the welcome message

Use this example as draft copy:

**Subject:** Welcome, [First name] — here's your next step

Hi [First name],

Thanks for reaching out about [goal]. Your next step is [action]. You can reply to this email with any questions, and our team will help you get started.

Best,  
Customer Success Team

Before using it with real people:

- Use only approved contacts/audiences and follow consent and unsubscribe requirements.
- Preview the message and test personalization, missing-name behavior, links, mobile layout, and sender details.
- Confirm whether your account has an email template, form automation, or workflow feature that meets your use case. Feature availability varies by tool and subscription. HubSpot's current documentation states that full workflow automation is subscription-dependent; do not claim you configured a live automated send unless your account lets you build and test it.
- If automation is not included, keep the demo as a message-template exercise and explicitly record the limitation. Do not try to bypass subscription or consent controls.

References: [HubSpot CRM](https://www.hubspot.com/products/crm) · [Account setup](https://resources.hubspot.com/hubspot-account-setup) · [Automation availability](https://knowledge.hubspot.com/get-started/automate-your-processes).

## 5. Capture evidence for your portfolio

Take your own screenshots after configuring the live account:

- `01-contacts.png` — fictional contacts table
- `02-pipeline.png` — practice pipeline with sample deals
- `03-welcome-template.png` — welcome-message draft or automation workflow, clearly noting whether it is a draft, test, or active workflow
- `04-follow-up.png` — example contact/deal showing a recorded next action

Do not show actual customer data, access tokens, passwords, or personal email inboxes.

## 6. Completion checklist

- [ ] Created a practice HubSpot account.
- [ ] Added at least three fictional contacts.
- [ ] Created or customized a deal pipeline.
- [ ] Created and associated at least three sample deals.
- [ ] Drafted the welcome email and verified feature availability.
- [ ] Captured screenshots and wrote down what was actually configured.

## Resume-safe project description

**Before completing the live account exercise:** “Built an interactive CRM pipeline simulation with fictional contacts, deal-stage tracking, follow-up reminders, CSV export, and a personalized welcome-email preview.”

**After completing the live account exercise:** add a separate, precise statement about the specific HubSpot contacts, pipeline stages, templates, or automation you personally configured. Do not describe the browser simulation as an integration with HubSpot.
