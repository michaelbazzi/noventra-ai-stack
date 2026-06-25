# noventra-ai-stack
Production AI system design for a live Shopify e-commerce store selling 
premium outdoor furniture. Built and operated by a solo founder with zero 
engineering background — proof that AI architecture skills transfer directly 
to real business outcomes.

**Store:** shopnoventra.com  
**Platform:** Shopify Basic  
**Launched:** March 10, 2026  
**Catalog:** 980 SKUs across two premium suppliers

## AI Systems Built

### Noventra Sage — Customer Service Agent
A 5-layer system prompt architecture that handles customer inquiries across
damage claims, order status, product questions, and B2B requests.

- Layer 1: Identity and role definition
- Layer 2: Product knowledge and pricing rules
- Layer 3: Conversation routing logic
- Layer 4: Response formatting standards
- Layer 5: Escalation and edge case handling

### Email Triage Automation
Make.com webhook workflow connected to Claude API that:
- Classifies incoming emails by intent (support, sales, complaint, spam)
- Routes to appropriate response template
- Flags high-priority items for human review
- Logs all interactions to HubSpot CRM

### B2B Outreach System
Automated follow-up sequence for landscape architects and pool companies:
- Personalized outreach templates generated via Claude API
- HubSpot CRM integration for pipeline tracking
- Follow-up trigger logic based on response status

### Product Data Pipeline
- 980 SKUs imported and structured via Matrixify
- Custom CSV schema design for variant management
- Automated collection sort order logic
- SEO title format enforcement across entire catalog

## Tech Stack
Claude API · Make.com · HubSpot CRM · Shopify · Klaviyo · 
Matrixify · Judge.me · GoAffPro · JSON · Webhook Architecture

## Key Results
- Full 980-SKU catalog live with structured AI-assisted product descriptions
- Automated email triage system processing all inbound inquiries
- B2B outreach pipeline targeting 7 landscape and pool companies
- Affiliate program live at 10% commission via GoAffPro

## What This Demonstrates
End-to-end AI system design for a real business — not a tutorial project.
Covers prompt engineering, workflow automation, CRM integration, data 
architecture, and human-in-the-loop escalation design.
