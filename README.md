# Awesome-Collaborative-Editorial-Software

## Top Collaborative Editorial Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Editorial Workflows, Print/Digital Publishing & Self-Hosted Collaboration Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Collaborative Editorial Software**. These tools enable editorial teams to plan, write, review, and publish content collaboratively—handling version control, approval workflows, and multi-channel output—ranging from InDesign-integrated copy editing to open-source Markdown-based collaboration platforms.



**Examples** include Adobe InCopy, WoodWing Studio, vjoon K4, QuarkCopyDesk, GatherContent, and the open-source leaders Etherpad, HedgeDoc, and TINO (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-seat licensing, and controlling the editorial pipeline. The open-source landscape is anchored by **Etherpad** (the real-time collaborative editor), **HedgeDoc** (the Markdown collaboration platform), and **TINO** (the Typst-based self-hosted publishing platform), with **Scribegate** providing Git-based editorial workflows and **PressForward** serving WordPress editorial teams.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global collaborative authoring and digital publishing workflow software market is estimated at approximately **$2.9B to $3.4B** (projected to reach over **$8.8B+** by the early 2030s at an ~12–13% CAGR). The sector is **moderately fragmented**: mega-cap creative giants (notably Adobe) capture dominant mindshare and standard file formats, while a diverse tier of specialized publishing lifecycle providers (WoodWing, Bynder/GatherContent, Quark, and vjoon) compete across enterprise multi-channel publishing and custom compliance workflows alongside emerging open-source platforms.

## SaaS/Hosted Platforms

| Product | Description | Company Size (Revenue / Valuation) | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe InCopy](https://www.adobe.com/products/incopy.html)** | Professional copy editing and writing tool that integrates with Adobe InDesign for print/digital publishing workflows. | **~$26B ARR** (~$100B Market Cap, NASDAQ: ADBE) | **$4.99/mo** (annual plan billed monthly) or **$7.49/mo** (month-to-month); standalone subscription or part of Adobe Creative Cloud. | **7-day free trial** with full access to standalone InCopy and Creative Cloud storage/features; no permanent free tier. |
| **[GatherContent](https://gathercontent.com/)** | Content operations platform for planning, creating, and publishing content at scale (Content Workflow by Bynder). | **~$130M+ ARR** (Parent company Bynder, backed by Thomas H. Lee Partners) | Starting from **$99/mo** (Starter tier for up to 500 items, ~10 active projects, unlimited users). | **14-day free trial** with full access to project authoring, workflows, and templates; no permanent free tier. |
| **[WoodWing Studio](https://www.woodwing.com/)** | Content creation and workflow platform for publishers, agencies, and marketing teams. | **~€70M+ Combined Revenue** (Omnidocs + WoodWing under Main Capital Partners) | Starting from **$99/user/month** (Starter package, custom enterprise quote required for scale). | **No permanent free tier and no self-service trial**; evaluations available via personalized guided product demos and proofs-of-concept. |
| **[QuarkCopyDesk](https://www.quark.com/)** | Standalone text editor compatible with QuarkXPress, designed for collaborative editorial workflows. | **~$65M–$70M Revenue** (Acquired by Zax.ai; formerly owned by Parallax Capital Partners) | Starting from **$313 one-time perpetual license** (QuarkCopyDesk standalone); enterprise Quark Publishing Platform (QPP) requires quote. | **7-day free trial** of QuarkCopyDesk (file export and save restrictions apply until license activation); no permanent free tier. |
| **[vjoon K4](https://www.vjoon.com/)** | Publishing system tightly integrated with Adobe InDesign/InCopy for magazine and corporate publishing. | **~$2.4M Revenue** (Privately held, vjoon GmbH) | Starting from **$99/user/month** (Directory benchmark; custom quote required based on deployment model and user seats). | **No permanent free tier and no public self-service trial**; evaluations provided via private consultation and tailored live vendor demos. |

## Open-Source GitHub Projects



- **[Etherpad](https://github.com/ether/etherpad)** [![GitHub Stars](https://img.shields.io/github/stars/ether/etherpad?style=social&color=white)](https://github.com/ether/etherpad/stargazers)  

  **The real-time collaborative editor standard.** ~18.5k stars. Web-based platform enabling multiple users to edit the same document simultaneously, with no login required and no account creation. **Strengths**: instant collaboration pads, plugin architecture for extensions, and a comprehensive API for document management. Best for quick collaborative writing sessions, meeting notes, and lightweight editorial coordination without infrastructure overhead.



- **[HedgeDoc](https://github.com/hedgedoc/hedgedoc)** [![GitHub Stars](https://img.shields.io/github/stars/hedgedoc/hedgedoc?style=social&color=white)](https://github.com/hedgedoc/hedgedoc/stargazers)  

  **The self-hosted Markdown collaboration platform.** Real-time collaborative Markdown editor for creating shared technical notes and knowledge bases. **Features**: LDAP/SAML/OAuth2 integration, export to GitHub Gists and multiple formats, and a private hosted environment for teams. Best for technical teams wanting a self-hosted wiki-style editorial workspace with Markdown-native authoring.



- **[TINO](https://github.com/confirm/tino)** [![GitHub Stars](https://img.shields.io/github/stars/confirm/tino?style=social&color=white)](https://github.com/confirm/tino/stargazers)  

  **The Typst-based self-hosted publishing platform.** Built for teams that want to author, review, and publish together. **Features**: bucket management, access control, and collaborative editing around Typst (a modern typesetting system). **License**: AGPL-3.0 for individuals and small teams; commercial licensing available for organizations requiring copyleft-free use. Best for teams wanting a modern, self-hosted alternative to proprietary editorial systems with structured typesetting output.



- **[Scribegate](https://explore.market.dev/ecosystems/git/projects/scribegate)**  

  **The Git-based editorial workflow system.** Markdown documents with immutable revisions cryptographically signed (ECDSA P-256) for tamper-evident history. **Workflow**: Proposal → Review → Approved → new Revision—analogous to pull requests but scoped to documents. **Features**: configurable approval thresholds, threaded comments anchored to specific lines, role-based access (Reader/Contributor/Reviewer/Admin), and API tokens for AI agents. Best for documentation teams and publishers wanting Git-native version control with editorial approval gates.



- **[PressForward](https://github.com/PressForward/pressforward)** [![GitHub Stars](https://img.shields.io/github/stars/PressForward/pressforward?style=social&color=white)](https://github.com/PressForward/pressforward/stargazers)  

  **The WordPress editorial aggregation plugin.** ~124 stars. Provides an editorial workflow for content aggregation and curation directly within the WordPress dashboard. **Features**: feed reader, group discussion of retrieved items, and integrated posting as the end of a smooth editorial process. AGPLv3 licensed. Best for bloggers and editorial teams curating content from the open web within WordPress.



### Additional Strong Open-Source Options



- **CryptPad** — End-to-end encrypted collaborative office suite with rich text, sheets, and presentations . Best for privacy-sensitive editorial teams requiring zero-knowledge encryption.

- **ONLYOFFICE Docs** — Full-featured online office suite with collaborative editing for text, spreadsheet, and presentation formats . Best for teams wanting a complete document editing experience.

- **XWiki** — Open-source knowledge management and collaboration platform with content management capabilities . Best as a broader collaboration layer alongside editorial workflows.

- **Pandoc** — Universal document converter that can transform Markdown to InCopy ICML format, enabling Markdown-based editorial pipelines feeding into InDesign layouts .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **True open-source replacements for InCopy/K4 workflows are scarce**: the commercial systems are deeply integrated with InDesign/InCopy for print production. Open-source alternatives like Etherpad and HedgeDoc serve collaborative writing but lack the print-layout integration that defines the category . TINO is the closest to a modern self-hosted publishing platform, but uses Typst rather than InDesign.

- **Pandoc bridges Markdown to InCopy**: teams can write in Markdown and convert to ICML for InDesign placement, enabling a hybrid open-source/commercial pipeline .

- **vjoon K4 has no free trial**: verify with vendor before committing to evaluation .

- **Self-hosted platforms require infrastructure**: Etherpad, HedgeDoc, and TINO all need servers and maintenance—free software is not free operations.



---



**Made for editorial teams, publishers, and documentation engineers building collaborative content workflows.**  

Let's make collaborative editorial software more open, version-controlled, and self-hostable.
