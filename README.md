# Awesome-Online-Form-Builder-Data-Collection

# Awesome Online Form Builder & Data Collection

> A curated list of top Online Form Builder and Data Collection platforms — both SaaS/Hosted commercial solutions and open-source alternatives for creating forms, surveys, and data collection workflows.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Typeform](#typeform)
  - [Jotform](#jotform)
  - [Google Forms](#google-forms)
  - [Formstack](#formstack)
  - [Wufoo](#wufoo)
  - [Microsoft Forms](#microsoft-forms)
- [Open-Source Software](#-open-source-software)
  - [Formbricks](#formbricks)
  - [HeyForm](#heyform)
  - [OpnForm](#opnform)
  - [LiberaForms](#liberaforms)
  - [Formy](#formy)
  - [QuillForms](#quillforms)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Online Form Builder and Data Collection platforms. These are not open-source but are included as reference points for feature comparison.

### Typeform
**Type:** Conversational, design-focused form builder
Typeform popularized the one-question-at-a-time conversational form experience, with a strong focus on design and completion rates. It is the primary commercial reference for open-source alternatives like HeyForm, OpnForm, and Formbricks.

### Jotform
**Type:** Form builder with extensive integrations and payment support
Jotform offers form creation with drag-and-drop building, payment processing, and a large integration library. It is positioned for businesses needing forms beyond simple surveys, including registrations and payments.

### Google Forms
**Type:** Free, simple form builder within Google Workspace
Google Forms provides basic survey and form creation at no cost, integrated with Google Sheets for response collection. It is the default entry point for simple surveys, though it lacks advanced logic and customization.

### Formstack
**Type:** Enterprise form builder with workflow automation
Formstack provides form building with workflow automation, document generation, and e-signature capabilities. It is positioned for organizations needing forms as part of broader business process automation.

### Wufoo
**Type:** Long-standing form builder with reporting
Wufoo (SurveyMonkey) provides form creation with a focus on ease of use and built-in reporting. It is positioned for small businesses and teams wanting straightforward form collection without complexity.

### Microsoft Forms
**Type:** Form builder within Microsoft 365
Microsoft Forms provides survey and form creation integrated with the Microsoft 365 ecosystem, with response collection in Excel. It is the natural choice for organizations standardized on Microsoft.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Online Form Builder and Data Collection tools. The open-source ecosystem spans **experience management suites**, **Typeform-style conversational builders**, **GDPR-focused European platforms**, and **framework-specific solutions**.

### Formbricks
**Stack:** TypeScript / Next.js / PostgreSQL / Redis | **License:** AGPLv3 (core) / Enterprise (separate)
Formbricks is the leading open-source **experience management (XM) suite**, explicitly positioned as an open-source alternative to Google Forms, Typeform, and Qualtrics [citation:2][citation:7]. It goes beyond simple surveys with:
- **In-app surveys** with precise user targeting based on attributes, events, and segments
- **Website surveys** embeddable via a tiny 7KB script, with no-code triggers based on clicks, page views, scroll depth, or exit intent [citation:14]
- **Link surveys** with custom branding for standalone sharing
- **20+ question types** including NPS, CES, CSAT, matrix, ranking, and file upload
- **Skip logic and conditional branching**
- **Built-in analytics** with charts and CSV/JSON export

Self-hosting is available via Docker with PostgreSQL (pgvector-enabled) and Redis. The core is AGPLv3, with enterprise features requiring a license key. A hosted cloud version with a generous free plan is also available, hosted in Germany with GDPR and CCPA compliance [citation:14].
**Best for:** Product teams wanting in-app and website surveys with precise targeting and a modern UI, accepting the AGPL licensing and Docker deployment.

### HeyForm
**Stack:** TypeScript / Node.js | **License:** AGPL-3.0
HeyForm is an open-source **Typeform alternative** with **9,000+ GitHub stars** and a focus on conversational, interactive forms [citation:6][citation:10]. Key features include:
- **AI form generation** from a description, plus smart logic that adapts questions based on responses
- **Conditional logic** and **multiple endings** (different results, redirects, or next steps based on answers)
- **Full branding customization** for fonts, colors, layouts, and flow
- **Responsive design** built for completion on mobile, tablet, and desktop
- **Template library** for starting quickly
- **Integrations** with payments, analytics, CRM, and automation tools

HeyForm is fully bootstrapped with no investor pressure, described as built by its users [citation:6]. The project is actively maintained with recent commits [citation:10].
**Best for:** Teams wanting a polished, conversational form experience with AI generation and strong branding, accepting the AGPL licensing.

### OpnForm
**Stack:** Laravel / Nuxt / PostgreSQL / Redis | **License:** AGPL-3.0
OpnForm is an open-source **Typeform alternative** with a drag-and-drop form editor, shareable links and embeds, conditional logic, and file uploads [citation:9]. It is positioned for contact forms, surveys, lead capture, and internal request forms. Self-hosting via Railway or Docker spins up the Laravel API, Nuxt frontend, PostgreSQL, and Redis. The free community edition allows 2 users, with additional users requiring a paid plan. Optional features include AI form generation via OpenAI API key and SMTP for email notifications.
**Best for:** Teams wanting a Typeform-style form builder with conditional logic and file uploads, accepting the Laravel/Nuxt stack and AGPL licensing.

### LiberaForms
**Stack:** Python / Flask / PostgreSQL / VueJS | **License:** AGPLv3
LiberaForms is an easy-to-use open-source software for creating and managing simple web forms and their collected data, developed with a strong focus on GDPR compliance and European digital sovereignty [citation:5]. Key features include:
- **Easy form creation** with standard elements (input, textarea, date, etc.), conditional fields, and custom styling
- **End-to-end encrypted form answers** using OpenPGP.js, where private keys never leave the client and the server cannot read encrypted responses [citation:12]
- **GDPR features**: GDPR statement templating, a GDPR wizard, and the ability to publish forms on the Fediverse [citation:5]
- **Answer management**: edition history log, anonymous answer editing, and export in Graphs, CSV, JSON, and PDF
- **Collaboration**: share form editing and answers (read-only) with other users
- **Moderator and admin tools**: user management, site configuration, and custom translations

LiberaForms is funded through NGI Zero PET and NGI Assure, with releases announced on its blog [citation:5].
**Best for:** Organizations prioritizing GDPR compliance and end-to-end encryption for form responses, particularly European public sector and privacy-sensitive contexts.

### Formy
**Stack:** Python / Django / React / Tailwind | **License:** MIT
Formy is a production-oriented customizable forms platform with a Django backend and React/Tailwind frontend . Key features include:
- **Drag-and-drop form builder** with 10 field types (text, textarea, email, number, select, multi-select, checkbox, date, phone, file upload)
- **Submissions table** with raw JSON view and **analytics** (charts for submissions over time, per-field response breakdowns, 7/30/90-day windows)
- **CSV/JSON export** and formatted PDF reports
- **Custom branding** per form (logo, colors, theming)
- **Submission limits and availability windows** with custom closed messages
- **Reusable Django app**: vendor `formy` into an existing Django project or run it standalone
- **Embeddable widget** and full REST API
- **Multi-language UI** (English, Spanish, Chinese)

Deploys via Docker with Postgres, Redis, gunicorn, and nginx . The MIT license makes it permissive for commercial use.
**Best for:** Django developers wanting a customizable, embeddable form builder they can integrate into existing projects, accepting the Python/React stack.

### QuillForms
**Stack:** React / TypeScript | **License:** Open Source (per GitHub)
QuillForms is an open-source **Typeform clone** built with React and TypeScript, focused on conversational multi-step forms . It is a **WordPress plugin**, making it the natural choice for WordPress sites needing Typeform-style forms. It has 581 GitHub stars and is actively maintained, with Next.js support noted in community references .
**Best for:** WordPress site owners wanting Typeform-style conversational forms without a separate platform, accepting the WordPress plugin dependency.

---

## 📊 Comparison at a Glance

| Software | License | Stack | In-App/Website Surveys | Conditional Logic | AI Generation | Self-Hosted | Best For |
|----------|---------|-------|------------------------|---------------------|---------------|-------------|----------|
| **Typeform** | Proprietary | Cloud | ❌ | ✅ | (Check) | ❌ | Conversational forms |
| **Jotform** | Proprietary | Cloud | ❌ | ✅ | (Check) | ❌ | Forms + payments |
| **Google Forms** | Proprietary | Cloud | ❌ | Limited | ❌ | ❌ | Simple free surveys |
| **Formbricks** | AGPLv3 | Next.js/Postgres | ✅ In-app + website | ✅ | (Check) | ✅ | Open-source XM suite |
| **HeyForm** | AGPL-3.0 | TypeScript/Node | ❌ | ✅ + Multi-endings | ✅ | ✅ | Conversational Typeform alt |
| **OpnForm** | AGPL-3.0 | Laravel/Nuxt | ❌ | ✅ | ✅ (OpenAI) | ✅ | Typeform-style forms |
| **LiberaForms** | AGPLv3 | Python/Flask | ❌ | ✅ | ❌ | ✅ | GDPR + E2EE forms |
| **Formy** | MIT | Django/React | ❌ | ✅ | ❌ | ✅ | Django embeddable forms |
| **QuillForms** | Open Source | React/TS | ❌ | ✅ | ❌ | ✅ (WordPress) | WordPress conversational forms |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Online Form Builder or Data Collection tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The form builder landscape splits between **experience management suites** (Formbricks, for in-app and website surveys with targeting), **Typeform-style conversational builders** (HeyForm, OpnForm, QuillForms), **GDPR-focused European platforms** (LiberaForms, with end-to-end encryption), and **framework-specific solutions** (Formy for Django, QuillForms for WordPress). **Formbricks** is the most feature-complete open-source option for product teams wanting targeted in-app feedback [citation:2][citation:7], while **HeyForm** offers the most polished conversational form experience with AI generation and 9k+ stars [citation:6][citation:10]. **LiberaForms** is uniquely positioned for organizations needing end-to-end encrypted form responses and GDPR compliance [citation:5][citation:12]. No open-source project fully replicates the marketing automation depth of Formstack, but these tools cover the majority of practical form and data collection needs.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
