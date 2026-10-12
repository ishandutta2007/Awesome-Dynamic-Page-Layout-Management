# Awesome Dynamic Page Layout Management

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Tracked Category](https://img.shields.io/badge/Ecosystem-Headless%20CMS%20%26%20Visual%20Builders-blue.svg)](https://github.com/ishandutta2007/Awesome-Dynamic-Page-Layout-Management)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)

> A curated list of leading **SaaS platforms** and **open-source developer tools** for **Dynamic Page Layout Management**, visual page building, component composition, dynamic zones, and headless content modeling.

Dynamic Page Layout Management empowers developers, product teams, and content editors to compose dynamic web and mobile layouts visually from modular, reusable code components without redeploying code.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Architecture & Composition Patterns](#architecture--composition-patterns)
- [How to Contribute](#how-to-contribute)
- [License & Disclaimer](#license--disclaimer)

---

## Sector Overview & Market Dynamics

The Dynamic Page Layout and Headless CMS market is estimated at **$1.8B – $3.9B in 2025** and projected to reach **$2.0B – $5.4B by 2026** (scaling past **$22B by 2035** at a ~17%–26% CAGR), with visual website and web experience builders contributing an additional **$2.9B – $5.4B**. 

The sector is **moderately fragmented**: enterprise mega-vendors (Salesforce, Adobe AEM, Contentful) capture massive high-ACV corporate contracts, yet the market resists a single "winner-take-all" outcome due to sharp architectural divides between Git-backed code workflows, open-core self-hosted systems (Strapi, Directus, Payload CMS), drag-and-drop React component trees (Builder.io, Puck, GrapesJS), and visual design environments (Webflow).

---

## SaaS & Hosted Platforms

The table below lists the top commercial SaaS solutions for visual page layout management, component orchestration, and content modeling, sorted descending by company scale (market capitalization, latest venture valuation, or parent company valuation).

| Platform | Company Scale (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Core Focus & Layout Features |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Dynamic Pages](https://www.salesforce.com/)** | ~$190B Market Cap (NYSE: CRM) | **$25/user/month** (Starter Suite) | **30-day free trial**; full CRM suite evaluation with sample data, no credit card required | Lightning App Builder with dynamic record pages, conditional field visibility rules, component-level permissions, and zero-code responsive layouts. |
| **[Webflow Enterprise](https://webflow.com/)** | $4.0B Valuation ($200M+ ARR) | **$15/month** (Basic plan, billed annually) | **Free Forever**; up to 2 static pages, 50 CMS items, 20 collections, 1,000 monthly visits on `webflow.io` domain | Visual canvas with CSS/HTML abstractions, component nesting up to 3 layers, 40 collection lists per page, and up to 1M CMS items for enterprise apps. |
| **[Contentful Studio](https://www.contentful.com/)** | $1.25B Valuation (Acquired by Salesforce) | **$300/month** (Basic / Lite plan) | **Free Forever**; 1 space, 10 users, 2 roles, 25 content types, 10,000 records, 100,000 API calls/month, 50 GB CDN bandwidth | Visual Studio canvas for composing component-driven landing pages and omnichannel experiences on top of Contentful's headless content models. |
| **[Sanity Studio](https://www.sanity.io/)** | ~$750M Valuation (Series C) | **$15/user seat/month** (Growth tier) | **Free Forever**; up to 20 user seats, 2 public datasets, 10,000 documents, 500,000 API CDN requests/month, 20 GB assets, 10 GB bandwidth | Real-time collaborative content workbench with code-defined schemas, live visual preview, mutation patches, and custom React component extensions. |
| **[Builder.io](https://www.builder.io/)** | ~$150M Valuation ($37M+ funding) | **$24/user/month** (Pro plan, billed annually) | **Free Forever**; 1 space, up to 5 users (admin roles), 10,000 visual views/month, 15 daily / 60 monthly AI credits | Drag-and-drop visual development directly on existing codebases (React, Next.js, Vue, Angular, Svelte) with Visual Copilot and Figma-to-code sync. |
| **[Storyblok Visual Editor](https://www.storyblok.com/)** | ~$140M Valuation ($138M funding) | **$99/month** (Growth plan; $90.75 billed annually) | **Free Forever**; 1 user seat (max 2), 1 space, 20,000 stories, 200 components, 100,000 API requests/month, 100 GB traffic, 2 locales | Real-time visual editor with inline component preview, nested component blocks, preset libraries, and live click-to-edit layout assembly. |
| **[Strapi Cloud](https://strapi.io/)** | ~$45M Valuation (~$10M ARR) | **$35/project/month** (Starter tier; $29/mo billed annually) | **14-day free trial**; up to 5 trial projects, 10 CMS seats, 1,000 database entries, 10,000 API requests, 5 GB storage, 50 GB bandwidth | Managed cloud for the leading headless CMS; includes dynamic zones, repeatable component blocks, media library, and REST/GraphQL APIs. |
| **[ButterCMS](https://buttercms.com/)** | Tiugo Technologies portfolio (~$60M ARR) | **$79/month** (Basic plan, billed annually) | **Free Forever** (Developer); 2 editor templates, 50,000 read API calls/month, 100 GB bandwidth | Component Picker for drag-and-drop page composition, central component library for cross-page reuse, collections, and multi-site management. |
| **[Prismic Slices](https://prismic.io/)** | ~$35M Valuation ($20M funding, ~$15M ARR) | **$10/month** (Starter plan, billed annually) | **Free Forever** (Community); 1 user, 2 locales, unlimited custom types, 4M API requests/month, 100 GB CDN bandwidth | Slice Machine architecture allowing developers to define reusable React/Vue Slices with automated mock generation while marketers visually stack them. |
| **[Plasmic](https://plasmic.app/)** | ~$25M Valuation ($4.5M funding, ~$1.2M ARR) | **$39/month** (Starter plan, billed annually) | **Free Forever**; 3 collaborators, unlimited apps/sites, headless CMS, 10,000 page views/month, 7-day version history | Visual builder and headless CMS that connects directly to React codebases via Headless API or Codegen, supporting custom coded component registration. |

---

## Open-Source GitHub Projects

Explore top open-source page builders, headless CMS platforms, and low-code dynamic layout engines. Entries are sorted descending by GitHub star count and feature live badges linking directly to each repository's stargazers.

| Project & Repository | Stars | License | Tech Stack & Description |
| :--- | :---: | :---: | :--- |
| **[Strapi](https://github.com/strapi/strapi)** | [![GitHub stars](https://img.shields.io/github/stars/strapi/strapi?style=social&color=white)](https://github.com/strapi/strapi/stargazers) | MIT | Node.js / TypeScript. Industry-leading open-source headless CMS featuring Dynamic Zones and Repeatable Components for flexible visual page assembly. |
| **[Payload CMS](https://github.com/payloadcms/payload)** | [![GitHub stars](https://img.shields.io/github/stars/payloadcms/payload?style=social&color=white)](https://github.com/payloadcms/payload/stargazers) | MIT | Next.js / TypeScript / React. Modern fullstack headless CMS and application framework with native block-based layout modeling and local TypeScript APIs. |
| **[ToolJet](https://github.com/ToolJet/ToolJet)** | [![GitHub stars](https://img.shields.io/github/stars/ToolJet/ToolJet?style=social&color=white)](https://github.com/ToolJet/ToolJet/stargazers) | AGPL-3.0 | TypeScript / NestJS / React. Low-code platform with a drag-and-drop visual UI builder for connecting databases and creating dynamic internal tools and dashboards. |
| **[Appsmith](https://github.com/appsmithorg/appsmith)** | [![GitHub stars](https://img.shields.io/github/stars/appsmithorg/appsmith?style=social&color=white)](https://github.com/appsmithorg/appsmith/stargazers) | Apache-2.0 | Java / React / TypeScript. Low-code engine for building customizable web pages, workflows, and dynamic layouts connected to APIs and enterprise databases. |
| **[Directus](https://github.com/directus/directus)** | [![GitHub stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers) | BUSL-1.1 | Node.js / Vue.js. Instant headless data platform converting any SQL database into REST and GraphQL APIs with an intuitive no-code layout studio. |
| **[Refine](https://github.com/refinedev/refine)** | [![GitHub stars](https://img.shields.io/github/stars/refinedev/refine?style=social&color=white)](https://github.com/refinedev/refine/stargazers) | MIT | React / TypeScript. Meta-framework for rapid development of web apps, admin panels, and content interfaces with modular layout providers. |
| **[GrapesJS](https://github.com/GrapesJS/grapesjs)** | [![GitHub stars](https://img.shields.io/github/stars/GrapesJS/grapesjs?style=social&color=white)](https://github.com/GrapesJS/grapesjs/stargazers) | BSD-3-Clause | JavaScript. Extensible open-source web builder framework for embedding drag-and-drop visual page editors, newsletter builders, and canvas UIs. |
| **[Wagtail](https://github.com/wagtail/wagtail)** | [![GitHub stars](https://img.shields.io/github/stars/wagtail/wagtail?style=social&color=white)](https://github.com/wagtail/wagtail/stargazers) | BSD-3-Clause | Python / Django. Leading open-source CMS featuring `StreamField`, enabling developers to define structured blocks and editors to compose polymorphic page layouts. |
| **[TinaCMS](https://github.com/tinacms/tinacms)** | [![GitHub stars](https://img.shields.io/github/stars/tinacms/tinacms?style=social&color=white)](https://github.com/tinacms/tinacms/stargazers) | Apache-2.0 | React / Next.js. Git-backed headless CMS providing live contextual visual editing directly on your React frontend with Markdown and MDX persistence. |
| **[Puck](https://github.com/measuredco/puck)** | [![GitHub stars](https://img.shields.io/github/stars/measuredco/puck?style=social&color=white)](https://github.com/measuredco/puck/stargazers) | MIT | React / TypeScript. Pure React drag-and-drop visual page editor with React Server Components (RSC) support and zero vendor lock-in. |
| **[KeystoneJS](https://github.com/keystonejs/keystone)** | [![GitHub stars](https://img.shields.io/github/stars/keystonejs/keystone?style=social&color=white)](https://github.com/keystonejs/keystone/stargazers) | MIT | TypeScript / GraphQL. Scalable open-source headless CMS with schema-driven content modeling and custom component blocks. |
| **[Builder.io SDK](https://github.com/BuilderIO/builder)** | [![GitHub stars](https://img.shields.io/github/stars/BuilderIO/builder?style=social&color=white)](https://github.com/BuilderIO/builder/stargazers) | MIT | Multi-framework (React, Vue, Angular, Qwik). Open-source client SDKs and rendering runtimes for Builder.io visual headless drag-and-drop layouts. |
| **[Craft.js](https://github.com/prevwong/craft.js)** | [![GitHub stars](https://img.shields.io/github/stars/prevwong/craft.js?style=social&color=white)](https://github.com/prevwong/craft.js/stargazers) | MIT | React / TypeScript. Unopinionated framework for building extensible drag-and-drop page builders where every React component is an editable node. |
| **[form-create](https://github.com/xaboy/form-create)** | [![GitHub stars](https://img.shields.io/github/stars/xaboy/form-create?style=social&color=white)](https://github.com/xaboy/form-create/stargazers) | MIT | Vue.js. Dynamic form builder and visual layout designer that renders complex nested layouts directly from JSON schemas. |
| **[Plasmic](https://github.com/plasmicapp/plasmic)** | [![GitHub stars](https://img.shields.io/github/stars/plasmicapp/plasmic?style=social&color=white)](https://github.com/plasmicapp/plasmic/stargazers) | MIT (Core) | TypeScript / React. Visual page builder and headless CMS engine featuring code component registration, codegen pipelines, and self-hosted runtimes. |
| **[Sanity Studio](https://github.com/sanity-io/sanity)** | [![GitHub stars](https://img.shields.io/github/stars/sanity-io/sanity?style=social&color=white)](https://github.com/sanity-io/sanity/stargazers) | MIT | React / TypeScript. Open-source workspace for Sanity content operating systems, featuring real-time collaborative editing and custom layout blocks. |
| **[Vue Form Making](https://github.com/gavinzhulei/vue-form-making)** | [![GitHub stars](https://img.shields.io/github/stars/gavinzhulei/vue-form-making?style=social&color=white)](https://github.com/gavinzhulei/vue-form-making/stargazers) | LGPL-3.0 | Vue.js. Visual drag-and-drop form layout designer with dynamic component generation and data binding. |
| **[Deco.cx](https://github.com/deco-cx/deco)** | [![GitHub stars](https://img.shields.io/github/stars/deco-cx/deco?style=social&color=white)](https://github.com/deco-cx/deco/stargazers) | Apache-2.0 | TypeScript / Deno / Fresh. Composable web visual editor platform generating high-performance storefronts and landing pages directly from TypeScript types. |
| **[Prismic Slice Machine](https://github.com/prismicio/slice-machine)** | [![GitHub stars](https://img.shields.io/github/stars/prismicio/slice-machine?style=social&color=white)](https://github.com/prismicio/slice-machine/stargazers) | BSD-3-Clause | Node.js / React. Local developer workflow tool for modeling, configuring, and testing reusable Prismic Slices before deployment. |

---

## Architecture & Composition Patterns

When implementing dynamic page layout management, engineering teams typically choose between four core paradigms:

1. **Dynamic Zones / Block Stacking (Headless CMS pattern):**  
   Developers define schemas for independent components (`Hero`, `Carousel`, `Features`, `PricingTable`), and content editors stack, order, and populate them in an approved canvas (used by Strapi, Wagtail StreamField, Payload, and Sanity).
2. **Visual In-Page Composition (Component-to-Canvas pattern):**  
   Production React/Vue components from your actual frontend codebase are registered with a visual editor. Non-technical users assemble pages via drag-and-drop within defined layout constraints (used by Builder.io, Puck, Craft.js, and Plasmic).
3. **Git-Backed Content Blocks (Developer-first pattern):**  
   Page content and layout metadata live inside markdown/JSON files within the Git repository itself, enabling pull requests, branch previews, and full version history (used by TinaCMS).
4. **Decoupled Data Platforms (BaaS pattern):**  
   Database-driven architectures where an administrative UI automatically wraps relational schemas, using JSON attributes or relational tables to configure layout hierarchies (used by Directus).

---

## How to Contribute

Contributions are welcome! Please help keep this directory accurate, up-to-date, and useful for the community:

1. **Fork** this repository.
2. **Check criteria**: Ensure your project or SaaS tool is actively maintained and directly related to dynamic page layout management, visual site builders, or block-based content modeling.
3. **Follow the formatting**:
   - For SaaS tools: Include specific starting tier pricing, explicit free tier / free trial limits, valuation or revenue metric, and factual features.
   - For Open-Source projects: Include the GitHub star badge (`style=social&color=white`), SPDX license, tech stack, and star count ranking.
4. **Submit a Pull Request** with a concise description of your changes.

---

## License & Disclaimer

- **License:** Released under [Creative Commons Zero v1.0 Universal](LICENSE) (CC0 1.0).
- **Disclaimer:** All product names, logos, and brands are property of their respective owners. Company valuations and pricing figures represent publicly available financial disclosures and vendor pricing as of early 2026. This list is community-curated for informational purposes and does not constitute an endorsement.
