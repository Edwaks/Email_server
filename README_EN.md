# AiSaray Mail (Email_server) — Mail Server + DirectMail

> English version of [README.md](README.md).

> **To purchase this software, contact: itshumakher@ g m a il.com**

**AiSaray Mail** is a turnkey mail server with the built-in **DirectMail** bulk-email module.  
Corporate email on your own domain and professional email campaigns run in one environment, without separate subscriptions for mail and mailing services.

Website and account: **https://mail.aisaray.ru/**

> Documentation for people and indexing: purpose, roles, modules, scenarios, and screenshots.  
> Source code, secrets, private DNS standards, and infrastructure recipes **are not published**.

## Official Link

- https://mail.aisaray.ru/

## Screenshots

### Product Landing Page
![AiSaray Mail — home](docs/screenshots/mail_home.png)

### Full Page
![AiSaray Mail — full page](docs/screenshots/mail_home_full.png)

### Account Sign-In
![AiSaray Mail sign-in](docs/screenshots/login.png)

## Product Summary

| Field | Value |
|-------|-------|
| Name | AiSaray Mail / Email_server |
| Built-in module | DirectMail (mailing campaigns) |
| Type | Corporate mail server + email marketing |
| Website | https://mail.aisaray.ru/ |
| Webmail | Roundcube (Russian interface) |
| Model | Turnkey server: domains, mailboxes, and campaigns |
| Intended users | Companies, marketing teams, B2B, agencies, and IT |

## Two Products on One Server

### 1) Corporate Email
Mailboxes on your domain (`sales@`, `support@`, `info@`), a web interface, and IMAP access from phones or Outlook/Thunderbird. Includes folders, attachments, search, filters, automatic replies, and forwarding.

### 2) DirectMail — Mailing Module
HTML email campaigns, Excel/CSV import, segments, contact-list preflight checks, test messages, scheduling, rate limits, delivery and bounce statistics, automatic stopping when failures increase, and one-click unsubscribe.

## What Is Included

1. **Corporate email** — addresses on your domain, web and IMAP access, and multiple domains on one platform  
2. **DirectMail** — campaigns, contact database, throttling, and address validation before sending  
3. **Protection and deliverability** — DKIM, SPF, DMARC, anti-spam, and TLS; complaint and failure monitoring  
4. **Analytics** — sent, delivered, and bounced metrics, funnel reporting, and per-address history  
5. **Administration** — mailboxes, quotas, domains, and ready-made DNS guidance for registrars  
6. **Turnkey delivery** — the server is deployed and configured; daily work is performed through a browser  

## Intended Users

| Audience | Need |
|----------|------|
| Company with a domain | `@company.example` mailboxes without dependence on a third-party mail provider |
| Email marketing | Recurring campaigns, templates, segments, and statistics |
| B2B / cold leads | Large lists with validation and domain-reputation protection |
| Marketplaces | Seller campaigns, Excel imports, and throttling |
| Agency | Multiple client domains on one server |
| IT department | A ready SMTP/IMAP environment with a web account |

## Typical Scenarios

### Team Email
Create employee mailboxes → issue credentials → work through the web client or a phone.

### First Campaign
Create a campaign → upload a list or choose a segment → run preflight → send yourself a test → launch → review statistics.

### Multiple Brands
Connect project domains → use separate mailboxes and senders → run separate campaigns without mixing their reputations in one pool of settings.

## About the Public Documentation

This repository describes the **user-facing functionality** of one product: mail + DirectMail.  
The `Email_server` and `Direct_email` directories in the operating environment are parts of **one** product, publicly presented as **AiSaray Mail** at mail.aisaray.ru.

## Additional Materials

- [Features (detailed)](docs/FEATURES.md)
- [DirectMail — mailing module](docs/DIRECTMAIL.md)
- [Use Cases](docs/USE_CASES.md)
- [FAQ](docs/FAQ.md)
- [Product Profile](docs/DATASET.md)

## Key Terms

`AiSaray Mail`, `mail.aisaray.ru`, `Email_server`, `DirectMail`, `corporate email`, `mailing campaigns`, `DKIM`, `SPF`, `DMARC`, `bounce`, `preflight`, `Roundcube`

---

## Public Disclaimer

This repository contains **only user-facing and marketing documentation** for the product.  
Source code, keys, infrastructure configurations, passwords, contact lists, and internal procedures **are not published**.

© AiSaray / Edwaks, 2026
