# Customer Success & SaaS Onboarding Portfolio

A deployable, no-build-tools portfolio with three practical demonstrations aligned to a Self-Serve Apprentice / Customer Success role.

## Projects

1. **CRM Pipeline Sandbox** — interactive sample pipeline with dummy contacts, searchable deals, stage updates, an onboarding-email preview, and CSV export. It runs entirely in the browser and does not send actual emails or connect to HubSpot. Includes a separate [hands-on HubSpot setup checklist](projects/crm-sandbox/HUBSPOT_SETUP.md) and sample CSV files.
2. **Notion Onboarding Teardown** — a concise product teardown built from public Notion help resources, with evidence separated from hypotheses and a hands-on validation checklist for the account owner to complete.
3. **CRM Knowledge Base** — searchable how-to articles for onboarding a new lead, maintaining a pipeline, and setting expectations around welcome-email automation.

## Stack

HTML5, CSS3, vanilla JavaScript, browser `localStorage`, CSV export, Git/GitHub Pages. No build step, API key, paid service, or package installation is required.

## Run locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repository, for example `customer-success-saas-portfolio`.
2. Upload the **contents** of this folder (the `index.html`, `styles.css`, `script.js`, `projects/` folder, and this README) to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After GitHub Pages finishes publishing, open the URL shown on the Pages settings screen.

Because all project links are relative, they work from a GitHub Pages project URL.

## Important project integrity notes

- The CRM sandbox is a **front-end simulation**. It stores demo edits in your browser only. The welcome-email action displays a preview and status message; it does not send an email.
- To make the CRM project a genuine HubSpot hands-on exercise, sign up for a HubSpot account, create the same sample contacts/deals in the live product, and take your own screenshots. HubSpot offers contact and deal pipeline features in its CRM; available automation features depend on the current subscription and tool.
- The Notion teardown is a **public-documentation desk review**, not a claim that a live signup flow was personally tested. Use the included validation checklist to test the current Notion flow yourself and record dated observations/screenshots before describing it as a hands-on experiment.
- All names, companies, email addresses, deal values, and funnel metrics inside the demo are fictional sample data.

## Source links

- HubSpot CRM: https://www.hubspot.com/products/crm
- HubSpot account setup: https://resources.hubspot.com/hubspot-account-setup
- HubSpot process automation availability: https://knowledge.hubspot.com/get-started/automate-your-processes
- Notion templates guide: https://www.notion.com/help/guides/getting-started-with-templates-for-your-team

## Suggested portfolio description

**Customer Success & SaaS Onboarding Lab** — Built a browser-based CRM pipeline simulation with contact and deal management, stage tracking, onboarding-email preview, and CSV export; researched a SaaS onboarding journey using public documentation; and created a searchable CRM knowledge base with practical user guidance and troubleshooting.
