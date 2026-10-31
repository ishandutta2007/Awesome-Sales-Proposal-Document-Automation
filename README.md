# Awesome-Sales-Proposal-Document-Automation

## Top Sales Proposal & Document Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Proposal Generation, RFP Response Automation & Self-Hosted Document Workflows*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Sales Proposal & Document Automation**. These tools enable sales teams to generate branded proposals, respond to RFPs, and automate document workflows—reducing manual drafting and ensuring every proposal is accurate, on-brand, and trackable.



**Examples** include HubSpot Proposal Software, PandaDoc, Proposify, Qwilr, Better Proposals, GetAccept, Nusii, Loopio, RFP360, and Responsive (RFPIO) (the category leaders).



**Open-source emphasis**: Sales Proposal & Document Automation is a domain where open-source tooling is **emerging but fragmented across distinct use cases**. The strongest active projects are **RFPilot** (a self-hosted AI-powered RFP response platform for IT pre-sales teams, with Claude API integration and Word proposal generation)  and **SmartPitch AI** (an AI-powered business proposal and pitch deck generator with multi-language support and PDF export) . For simpler template-driven generation, **GOTIHUB Proposal Engine** provides JSON-driven HTML/PDF proposals via Jinja2 and Playwright . For academic and NGO proposal drafting, **Project Proposal Generator** offers an agentic CrewAI workflow aligned with UN principles . The critical caveat: **no open-source project matches PandaDoc's integrated e-signature, CRM sync, and content library**—those remain commercial differentiators.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HubSpot Proposal Software](https://www.hubspot.com/)**  

  Proposal and quote tools within HubSpot's Sales Hub; connects deals, products, and e-signature for streamlined sales document workflows.



- **[PandaDoc](https://www.pandadoc.com/)**  

  Document automation platform combining proposal generation, e-signature, and CRM integrations; the benchmark for end-to-end sales document workflows.



- **[Proposify](https://www.proposify.com/)**  

  Proposal software with drag-and-drop editor, templates, and analytics; focused on streamlining the proposal creation and approval process.



- **[Qwilr](https://qwilr.com/)**  

  Interactive web-based proposal platform that replaces static PDFs with trackable, responsive pages; includes quotes, contracts, and analytics.



- **[Better Proposals](https://betterproposals.io/)**  

  Proposal creation platform with templates, e-signature, and tracking; positioned for freelancers and small agencies.



- **[GetAccept](https://www.getaccept.com/)**  

  Digital sales room platform combining proposals, e-signature, and video; tracks buyer engagement throughout the deal cycle.



- **[Nusii](https://nusii.com/)**  

  Proposal software for freelancers and agencies; focused on simplicity with templates, e-signature, and notifications.



- **[Loopio](https://www.loopio.com/)**  

  RFP response software with a content library and AI-assisted answering; positioned for enterprise bid teams.



- **[RFP360](https://www.rfp360.com/)**  

  RFP management platform covering the full response lifecycle, from intake to submission and analysis.



- **[Responsive (RFPIO)](https://www.responsive.io/)**  

  Strategic response management platform with AI-powered RFP response, content management, and collaboration for enterprise sales teams.



## Open-Source GitHub Projects



### AI-Powered RFP Response Platforms



- **[RFPilot](https://github.com/valinorintelligence/rfpilot)**  

  The most complete open-source **self-hosted RFP response platform** for IT pre-sales, cybersecurity, software development, and cloud teams (Docker single-command deploy) . Features two AI engines: **Engine A** uploads an RFP, extracts requirements, deadlines, evaluation criteria, and compliance needs, then generates a structured Word proposal; **Engine B** cross-matches your capability documents against the RFP to identify gaps, score sections, and write responses in your company's voice. Includes JWT auth with role-based access, document processing (PDF with OCR, DOCX, PPTX, TXT), a RFP repository with search/filter/tagging, analytics dashboard (win rates, pipeline value, gap frequency), and full audit log. Tech stack: FastAPI, React 18, PostgreSQL 15, Anthropic Claude API. **Best for IT pre-sales teams** wanting AI-assisted RFP response without commercial licensing—requires an Anthropic API key for AI features.



- **[AutoRFP (run-llama)](https://github.com/run-llama/auto_rfp)**  

  Open-source **AI-powered RFP response platform** from LlamaIndex (Next.js, Supabase, LlamaCloud integration) . Features question extraction from uploaded documents, AI response generation (single-step and multi-step), organization/project management, and LlamaCloud integration for document retrieval. Docker support with Next.js standalone output. **Best for teams already in the LlamaIndex ecosystem** wanting RFP automation—but requires OpenAI and LlamaCloud API keys for full functionality.



### AI-Powered Proposal Generation



- **[SmartPitch AI](https://github.com/Tapiwa128/SmartPitchAII)**  

  Open-source **AI-powered business proposal and pitch deck generator** for entrepreneurs, freelancers, and small businesses . Features AI-generated proposals from user inputs, smart pitch deck builder with structured slide decks, multi-language support (English, French, Spanish, German), professional templates (freelancers, NGOs, startups, agencies), PDF and slide export, and AI feedback on clarity, tone, and persuasion. Tech stack: React.js, Node.js/Flask, MongoDB/PostgreSQL, OpenAI/HuggingFace, DeepL/Google Translate. **Best for small businesses and freelancers** wanting quick AI-assisted proposal generation—but it is an early-stage project (June 2025) with limited production hardening.



- **[Project Proposal Generator (proposal_drafter)](https://github.com/Edouard-Legoupil/proposal_drafter)**  

  Open-source **agentic AI proposal drafting system** for UN agencies, NGOs, and mission-driven organizations (MIT, CrewAI framework) . Simulates a proposal team with specialized agents for research, budgeting, and drafting; aligns proposals with organizational priorities, donor guidelines, and thematic frameworks; exports to Word/Excel with validation tracking. **Best for humanitarian and development sector proposal writing**—but it is tailored to NGO/UN workflows and requires CrewAI and LLM configuration.



- **[GOTIHUB Proposal Engine](https://github.com/apurba-labs/gotihub-proposal)**  

  Open-source **JSON-driven proposal generator** (Python, Jinja2, Playwright) . Generates branded HTML and PDF business proposals from structured JSON data with reusable HTML components, inline CSS, base64 embedded assets, and professional A4 layout. Includes modular templates (cover, letter, requirements, scope, timeline, commercial, support). **Best for teams wanting template-driven, reproducible proposal generation** without AI dependencies—but it is a generation engine, not a full proposal management platform.



### Additional Strong Open-Source Options



- **mcp-sales (zavora-ai)** — Open-source **Sales MCP Server** with 29 tools across PandaDoc, Apollo.io, Calendly, and Stripe Billing; covers proposal lifecycle (draft → sent → viewed → signed → won), CPQ (configure-price-quote), sequences, and forecasting . **Not a proposal generator itself**—it is an integration layer for AI agents to orchestrate commercial sales tools, requiring API keys for each backend.

- **Orqafy** — Open-source **all-in-one business operations platform** for IT solutions companies with proposals & quotations, CRM, invoicing, and project management; multi-tenant SaaS architecture . **In development** (Phase 2 complete, Phase 3 scaffolding next as of April 2026)—not production-ready, but demonstrates the pattern for integrated proposal-to-invoice workflows.

- **ScopeSmith** — Open-source AI agent that transforms client assessment notes into presentation decks and Statement of Work documents (AWS Lambda, DynamoDB, Bedrock) . **Niche**—for professional services SOW generation rather than sales proposals, but demonstrates the AI-assisted document generation pattern.



**Frameworks for building custom systems**: For **RFP response automation**, RFPilot provides the most complete self-hosted platform with capability cross-matching and Word generation . For **AI-assisted proposal drafting**, SmartPitch AI offers a starting point for freelancers and small businesses . For **template-driven PDF generation**, GOTIHUB Proposal Engine provides a clean JSON-to-PDF pipeline . For **NGO/UN proposal writing**, Project Proposal Generator provides an agentic workflow . No open-source project matches PandaDoc's **integrated e-signature, CRM sync, and content library**—those remain commercial differentiators.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Sales proposal platforms handling client data and contracts must comply with applicable privacy regulations (GDPR, CCPA) and e-signature laws (ESIGN, eIDAS); **AI-generated proposal content should be reviewed by humans before sending**—RFPilot and SmartPitch generate drafts, not final legal documents.

- **Open-source proposal automation is emerging but fragmented**—RFPilot provides a strong RFP response platform , and SmartPitch AI provides a starting point for AI proposal generation . However, **no open-source project matches PandaDoc's integrated e-signature, CRM sync, and content library**—organizations requiring end-to-end proposal workflows should evaluate commercial platforms or plan for assembly.

- Verify license terms for commercial use; RFPilot is open-source (check repository) , SmartPitch AI is open-source , and GOTIHUB Proposal Engine uses MIT .



---



**Made for sales operations teams, proposal managers, and organizations building document automation workflows.**  

Let's make sales proposal automation more open, but with clear eyes about the e-signature and CRM integration gaps that commercial platforms still fill.
