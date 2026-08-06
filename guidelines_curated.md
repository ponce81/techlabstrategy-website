# TechStrategyLab — Curated Business Guidelines

This document refines the original `guidelines.md` into a structured foundation for building the company website.

## 1. Company & Founder

- **Company:** TechStrategyLab
- **Founder:** Carlos Ponce
- **Type:** IT Consulting boutique
- **Market focus:** Europe-wide, remote-friendly (not limited to a single country)
- **Industry focus:** Industry-agnostic by positioning. Founder's deepest track record is in Utilities/Energy (Germany & Switzerland), but the company should not brand itself as industry-specific — this experience is used as credibility proof, not as a niche limitation.

## 2. Founder Background (for About/credibility sections, kept generic — no named clients)

18 years of experience in the SAP consulting world, with progressive responsibility across roles:

- Developer
- Developer + Functional Consultant
- Integration Expert — 8 years
- Integration Architect — 4 years
- Solution Architect — 5 years
- Enterprise Architect — 2 years

Note: some of these roles overlapped (e.g., worked in parallel as Integration Architect and Enterprise Architect on different projects). Primary industries: Utilities and Energy companies in Germany and Switzerland.

**Positioning takeaway:** deep, hands-on technical grounding (started as a developer) that grew into architecture and strategic leadership — not a "pure strategy" consultant without technical depth. This is a credibility differentiator: technical credibility + business/strategy fluency.

### Education & Certifications

- **Master's in Informatics** (Germany)
- **MBA** (Germany)
- **TOGAF** certification (reinforces Enterprise Architecture credibility)
- Multiple **SAP** certifications (technical depth across the 18-year SAP career)
- **AWS** and **Azure** cloud certifications
- **Terraform** (infrastructure-as-code)
- Currently attending: **AI and Machine Learning professional certification, MIT (Boston)** — technical AI depth
- Currently attending: **"AI-Driven Leadership – Strategies for the Future," Stanford University** — a less technical, more business/leadership/culture-focused program

**Positioning takeaway:** this combination — hands-on cloud/infra certifications, formal enterprise-architecture credentialing (TOGAF), an academic business foundation (MBA), and active, ongoing investment in AI from both a technical and leadership angle — supports the "technical depth + strategic/business fluency" narrative and directly backs the AI Strategy and AI-Leadership service lines. Framing as "currently attending" (not yet completed) should stay accurate on the site and be updated once certifications are awarded.

## 3. Services

1. **Enterprise Architecture** — Consulting services to introduce Enterprise Architecture practices, assessments, and services.
2. **AI Strategy** — Readiness checks, AI assessments, and business use case development (e.g., using Design Thinking techniques).
3. **CTO Consulting** — Acting as a sparring partner for CTOs, or supporting strategy development for existing tech leadership.
4. **Fractional CTO** — Taking on CTO responsibilities part-time/on-demand, structured via the Fractional CTO Framework (see below).
5. **AI-Leadership & Innovation Mindset** — Best practices for team leaders and innovation teams to build an innovation-ready culture.

## 4. Fractional CTO Framework: Audit → Strategy → Scale

*(Framework is a work in progress — structure below is the current draft.)*

### Phase 1 — Audit (4 weeks)
- Meet the team
- Assess company culture
- Assess the current tech stack
- Review documented processes
- **Deliverable:** findings report highlighting results and possible quick wins

### Phase 2 — Strategy (4 weeks)
- Build a roadmap with specific, actionable steps
- Determine team needs: hiring gaps or upskilling requirements
- **Deliverable:** actionable roadmap

### Phase 3 — Scale (4 weeks)
- Establish KPIs and metrics
- Define steps to improve company culture
- Mentor and train internal tech leads so key players can operate independently
- **Deliverable:** executive reporting pack for C-Level and board

Total framework duration: ~12 weeks, structured in three clear, time-boxed stages — reinforces the "pragmatic, no-fluff" positioning by giving clients visible structure and defined checkpoints.

## 5. Target Audience

- Startup founders/CEOs needing CTO-level guidance without a full-time hire
- Mid-size company executives (CTOs, CIOs, VPs) needing strategy or enterprise architecture support
- Enterprise leadership needing formal enterprise architecture or AI assessments

Website content should speak to all three segments without forcing a single persona — likely via distinct service pages or messaging tracks rather than one generic pitch.

## 6. Brand Voice & Positioning

- **Tone:** Approachable & conversational — first-person, feels like talking to a trusted advisor, not a stiff corporate consultancy.
- **Mindset/Values (from original guidelines):**
  - Pragmatic, no unnecessary paperwork or meetings without a plan
  - Direct communication with key stakeholders
  - Listen first: take notes, gather requirements and ideas
  - Transform business ideas into technology assets
  - Problem solvers, not theorists

### Key differentiators to emphasize
- **Pragmatic, no-fluff approach** — action over process theater
- **Structured frameworks** — Audit/Strategy/Scale gives clients clarity on process and expected outcomes
- **AI-specific expertise** — not a generalist IT consultancy; AI strategy and readiness is a core pillar
- **Flexibility** — fractional/part-time engagement lowers cost and risk vs. a full-time hire

## 7. Engagement Models

The site should acknowledge multiple ways of working together (without publishing exact rates):

- **Project-based** — fixed scope/fee (e.g., an AI readiness assessment as a defined package)
- **Retainer/ongoing** — for Fractional CTO engagements
- **Hourly/day-rate advisory** — for ad-hoc sparring-partner style consulting

Pricing itself stays undisclosed on the site — framed as "let's discuss what fits your situation."

## 8. Primary Call-to-Action

- **Soft CTA** — the site is primarily a credibility/expertise showcase, not a hard-sell funnel. Encourage exploration and low-pressure contact rather than pushing visitors into an immediate booking or form.

## 9. Languages

The website should support three languages:
- English
- German
- Spanish

## 10. Visual Identity

- **Style direction:** Bold, innovative, tech-savvy — dark-mode UI with an electric accent, moving away from the earlier "clean & corporate" direction.
- **Color palette:** Near-black navy background (`#090c14`), light text, electric cyan accent (`#00e5ff`) paired with a violet secondary (`#7c5cff`) used in gradients (buttons, borders, footer accent line, logo mark).
- **Typography accents:** Monospace font used for eyebrows/labels, phase numbers, and role years to reinforce the tech feel; bold/tight-tracked headings.
- **Logo:** simple wordmark + abstract mark icon (SVG), styled in the new dark/gradient palette — not a final designed logo, but a placeholder in the new visual direction.

## 11. Sitemap (Launch Scope)

- **Home**
- **Services** (overview, likely linking out to more detail per service as content grows)
- **Fractional CTO Framework** — dedicated page for Audit → Strategy → Scale, since it's a key differentiator
- **About** — founder background, credentials, mindset/values
- **Blog/Insights** — thought leadership, SEO content, space to publish on AI strategy, enterprise architecture, leadership topics
- **Contact** — soft CTA, low-pressure inquiry

## 12. Domain

- **techstrategylab.io** (already registered)

## 13. Hosting & Deployment

- **Hosting:** AWS S3 bucket, static website hosting.
- Implication: the site should be built as a **static site** (e.g., static HTML/CSS/JS output, or a static-site generator/framework that exports fully static assets — no server-side rendering or backend runtime). Any contact form or dynamic behavior will need a static-friendly approach (e.g., a third-party form service, or a separate Lambda/API Gateway endpoint if custom backend logic is ever needed).
- Multi-language (EN/DE/ES) routing needs to work within a static-hosting setup (e.g., static paths per language such as `/en/`, `/de/`, `/es/`).

## 14. Open Items for Later

- Final logo design.
- Specific static-site framework/generator choice (e.g., plain static HTML, or a static-export frontend framework) and build/deploy pipeline (e.g., CI to sync build output to S3, CloudFront in front of the bucket for HTTPS/CDN — not yet decided).
- Fractional CTO Framework is explicitly "work in progress" — content should be written in a way that's easy to refine later without a full rewrite.
