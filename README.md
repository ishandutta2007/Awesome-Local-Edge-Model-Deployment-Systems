# Awesome-Local-Edge-Model-Deployment-Systems

## Top Mail Merge Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Personalized Bulk Email, Gmail-Based Campaigns & Document Generation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mail Merge**. These tools help sales teams, recruiters, and marketers send personalized bulk emails directly from Gmail or generate customized documents at scale — combining spreadsheet-driven recipient lists with template variables, tracking, and scheduling.

**Examples** include Yet Another Mail Merge (YAMM), Mailmeteor, GMass, Mergo, Mixmax, Woodpecker, Streak, Vocus.io, QuickMail, and Saleshandy (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first Gmail sending, and transparent document generation — ideal for privacy-conscious teams, developers building outreach pipelines, and anyone avoiding per-recipient SaaS pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Yet Another Mail Merge (YAMM)](https://yamm.com/)**  
  Google Sheets-based mail merge tool for Gmail. Build contact lists in a spreadsheet, draft your email in Gmail with merge tags, and send personalized campaigns. Supports scheduling, open/click tracking, and per-recipient merge status columns. Free tier available with daily sending limits; Pro plans remove caps and add scheduling [citation:5][citation:11][citation:16].

- **[Mailmeteor](https://mailmeteor.com/)**  
  Gmail mail merge and cold email platform with Google Sheets integration, personalized templates, tracking, and follow-ups.

- **[GMass](https://www.gmass.co/)**  
  Gmail-based mass email platform with mail merge, auto follow-ups, segmentation, A/B testing, and campaign analytics. Integrates with CRM and outreach tools [citation:2][citation:8].

- **[Mergo](https://mergo.co/)**  
  Gmail mail merge tool with personalized emails, follow-up sequences, and tracking.

- **[Mixmax](https://mixmax.com/)**  
  Sales engagement platform for Gmail with sequences, templates, scheduling, tracking, and workflow automation [citation:3][citation:14].

- **[Woodpecker](https://woodpecker.co/)**  
  Cold email automation platform with mail merge, follow-ups, A/B testing, and deliverability tools.

- **[Streak](https://www.streak.com/)**  
  CRM inside Gmail with mail merge, tracking, snippets, and pipeline management.

- **[Vocus.io](https://vocus.io/)**  
  Gmail outreach platform with mail merge, email tracking, and automated follow-ups.

- **[QuickMail](https://quickmail.io/)**  
  Cold email platform with mail merge, inbox rotation, and deliverability optimization.

- **[Saleshandy](https://saleshandy.com/)**  
  Cold email outreach platform with mail merge, sequences, and email warmup.

## Open-Source GitHub Projects

- **[Group Merge](https://github.com/topics/mail-merge)**  
  **Open-sourced Google Workspace Add-on for Gmail mail merge.** Send personalized emails based on Gmail templates to multiple recipients using Google Sheets. Features a **Group Merge** capability that combines the contents of two or more rows into one row for a single recipient — useful for sending one email summarizing multiple records (e.g., multiple line items per vendor). JavaScript-based, installable from the Google Workspace Marketplace [citation:19].

- **[TinyMails](https://github.com/Gauthi3r/tinymails)**  
  **Local-first Gmail mail merge for small, permission-based outreach.** Your contacts, templates, sending history, and OAuth stay on your machine. Features bring-your-own Google OAuth (Desktop app client with `gmail.send` scope only — no inbox access), reviewed CSV imports with deduplication, reusable templates, a four-step campaign composer, Gmail delivery safeguards (daily caps, sending windows, delays), local backups, and a one-command launcher. **No tracking pixels, no hosted contact data, no AI-written copy, no inbox reading.** Node.js 22+, MIT-style local-first design [citation:10].

- **[MailNest](https://wordpress.org/plugins/mailnest/)**  
  **Open-source WordPress newsletter and email automation plugin.** 100% free with unlimited subscribers and campaigns — no monthly fees or upgrade walls. Features full WordPress rich-text editor, merge tags (`{{first_name}}`, `{{last_name}}`, `{{email}}`), SMTP support (any provider including Gmail, SendGrid, Amazon SES), double opt-in, CSV import/export, scheduled campaigns, welcome email sequences, re-engagement emails, open/click tracking, subscriber growth charts, and popup subscription forms. **No telemetry, no external calls, all data stays on your server** [citation:7].

- **[docx Mail Merge](https://github.com/iulica/docx-mailmerge)**  
  **Python library for performing mail merge on Office Open XML (.docx) files without Microsoft Word.** Install via `pip install docx-mailmerge2`. Features template field listing, kwargs-based field merging, **table row merging** with anchor fields, template merging with page/section breaks, field formatting (Numeric, Text, Conditional, Date), `{NEXT}` field support, and merge fields inside other fields (e.g., `{INCLUDEPICTURE}` for images). Works on any system without Office installed. Python 3.7+ [citation:4].

- **[DocuMint](https://github.com/jfaccioli/documint)**  
  **Lightweight Flask web app for bulk personalized Word document generation.** Upload a `.docx` template with placeholders and an Excel sheet — DocuMint creates and zips a separate document for each row automatically. Python/Flask stack, ideal for generating contracts, certificates, and letters at scale from spreadsheet data [citation:15].

- **[Python Bulk Email Sender](https://github.com/riteshkarmakar/bulk-email-sender)**  
  **Python GUI application for sending personalized emails in bulk with mail merge.** Features dynamic placeholders, attachment handling, real-time preview, SMTP support, and error handling. Python-based with Tkinter GUI [citation:15].

- **[linux-bash-mail-merge](https://github.com/spekulatius/linux-bash-mail-merge)**  
  **CLI helper to merge mail content based on a CSV file and trigger sending in your browser using mailto.** Lightweight shell-script approach to mail merge without a dedicated email platform [citation:15].

- **[NeoVim Mail Merge](https://github.com/martineausimon/nvim-mail-merge)**  
  **NeoVim plugin for mail merge** — bring mail merge capabilities into your editor workflow for developers who live in Vim [citation:15].

- **[PDF Mail Merger](https://github.com/hochanh/pdf-mail-merger)**  
  **PDF mail merger, editor, and generator for Excel and CSV files.** Generate personalized PDF documents in bulk from spreadsheet data [citation:15].

### Additional Strong Open-Source Options

- **Outreach Desk** — Self-hosted outreach desk with AI-drafted emails, approval queues, SMTP/IMAP sending, reply triage, pipeline board, and analytics. Integrates with n8n for lead flow. PyPI installable [citation:6].
- **OpenOutreach** — Open-source AI agent for B2B lead generation and outreach. Finds leads from a product description, exports CSV shaped for Instantly/Smartlead importers, and supports SMTP/IMAP sending. GPLv3 licensed [citation:12][citation:17].
- **Museletter** — Headless, agent-first newsletter engine with AWS SES and Cloudflare Email support, tracking, bounce handling, and API-driven campaign management [citation:13].
- **Google Apps Script Mail Merge** — Community scripts for mail merge using Google Docs/Sheets. Search GitHub topic `mail-merge` for 139+ public repositories [citation:19].
- **DevExpress Examples** — Official examples for Word document API mail merge in Blazor, WinForms, and Web applications [citation:15].

**Frameworks for building custom systems**: Combine **TinyMails** for local-first Gmail sending with OAuth security, **docx Mail Merge** or **DocuMint** for document generation, **MailNest** for WordPress-native newsletter campaigns, and **Group Merge** for Google Sheets-driven personalized outreach to build a complete self-hosted mail merge stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mail merge tools must comply with anti-spam regulations (CAN-SPAM, GDPR, CASL), Gmail sending limits, and consent requirements for recipient lists. **Bulk unsolicited email can result in domain reputation damage or account suspension.** Self-hosted solutions require proper SMTP configuration, bounce handling, and unsubscribe mechanisms.
- Self-hosted open-source solutions require proper security hardening, OAuth credential protection, and sending volume management.

---

**Made for sales teams, recruiters, marketers, and developers building personalized outreach platforms.**  
Let's make mail merge more open, privacy-conscious, and recipient-friendly.
