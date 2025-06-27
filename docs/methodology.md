# IdeaSprint Methodology

**Reusable Methodology for Validating AI-Era Startup Ideas**

A rapid, evidence-driven framework for validating AI-era startup ideas in 90 days, blending stage-gates, scorecards, risk checks, and pilot sprints. This playbook condenses proven analysis processes into a repeatable framework that moves any idea from *hunch* to *decision* in ~90 days.

## Overview

This methodology combines well-known product development techniques (Stage-Gate, Lean interviews), emerging AI governance guidance (NIST AI-RMF, EU AI Act), and modern FinOps controls to create a comprehensive validation framework optimized for AI-era startups.

**Key References:**
- [Stage-Gate Process](https://slidemodel.com/stage-gate-process-for-product-development/)
- [Lean Analytics](https://leananalyticsbook.com/scoring-problem-interviews/)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)

## 1. Stage-Gate Evaluation Flow

Each gate must be passed before proceeding to the next phase. **Stop at the first failed gate; otherwise proceed to pilot.**

| Gate | Purpose | Pass Criteria | Example Evidence |
|------|---------|---------------|------------------|
| **G0 — Problem Reality** | Confirm pain is top-3 for ICP | ≥10 structured interviews score ≥4/5 urgency | Lean-style interview scoresheets |
| **G1 — Market Momentum** | Size & growth validation | SAM ≥ $300M *and* >15% CAGR | Gartner/IDC TAM; market stats |
| **G2 — Solution Feasibility** | De-risk core technology | PoC delivers key job-to-be-done in ≤5 min | Demo video, success logs |
| **G3 — Unit Economics** | Profit potential | Gross margin ≥ 75%; volatile inputs <15% ARR | Cost model incl. GPU and token prices |
| **G4 — Regulatory Path** | Compliance readiness | Controls mapped to NIST AI-RMF & EU AI Act | Checklists, legal sign-off |

### Gate Evaluation Process
1. **Prepare Evidence**: Gather all required data and documentation
2. **Assess Criteria**: Evaluate against specific pass/fail criteria
3. **Document Decision**: Record rationale for pass/fail decision
4. **Kill/Pivot Signals**: If gate fails, determine if idea should be killed or pivoted

## 2. 10-Factor Scorecard

Weight each factor 1-5; **green-light if weighted score ≥ 70%**.

| Dimension | Weight | Data Source |
|-----------|--------|-------------|
| **Pain Urgency** | 20% | Interview scores (Lean methodology) |
| **Budget Availability** | 15% | CIO AI-budget surveys |
| **Market Growth** | 15% | Industry growth predictions |
| **Competitive Gap** | 15% | Competitive landscape mapping |
| **Technical Defensibility** | 10% | PoC benchmarking results |
| **Compliance Fit** | 10% | EU AI Act, NIST AI-RMF alignment |
| **Capital Attractiveness** | 10% | VC trend reports |
| **Founding Advantage** | 5% | Team and domain expertise |

### Scoring Process
1. **Rate Each Factor**: Score 1-5 for each dimension
2. **Apply Weights**: Multiply score by weight percentage
3. **Calculate Total**: Sum weighted scores
4. **Decision Threshold**: ≥70% = proceed, <70% = pivot or kill

## 3. 90-Day Validation Sprint

### Sprint Structure

**Weeks 1-2: Discovery & PoC**
- Conduct 15+ structured customer interviews
- Build razor-thin PoC addressing one core job-to-be-done
- Document pain points and solution fit

**Weeks 3-4: Design-Partner LOIs**
- Secure ≥3 Letters of Intent from potential customers
- Define specific KPI targets for pilot phase
- Establish pilot success criteria

**Weeks 5-8: Pilot Execution**
- Execute pilot with design partners
- Track KPI targets: ≥5× faster time-to-value, zero critical CVEs, controlled costs
- Collect quantitative and qualitative feedback

**Week 9: Retrospective & Go/No-Go**
- Re-run scorecard with real pilot data
- Conduct final gate evaluation
- Make final decision: Go/Pivot/Kill

### Success Metrics
- **Customer Validation**: 80%+ problem severity confirmation
- **Solution Validation**: 70%+ solution interest rate
- **Pilot Performance**: Meet all defined KPI targets
- **Business Validation**: Positive unit economics demonstrated

## 4. Risk & Compliance Checklist

| Category | Reference | Action Required |
|----------|-----------|-----------------|
| **LLM Security** | [OWASP Top-10 for LLM Apps](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Fuzz prompts; integrate guardrails |
| **AI Governance** | [NIST AI-RMF](https://www.nist.gov/itl/ai-risk-management-framework) | Document Govern-Map-Measure-Manage cycle |
| **Regulation** | [EU AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) | Apply conformity assessment plan |
| **FinOps** | AI Cost Management | Track GPU & token costs; flag >10% MoM spikes |

### AI-Specific Risk Categories

#### Technical Risks
- Model performance degradation
- Training data quality and bias
- Infrastructure scalability
- Security vulnerabilities (prompt injection, data poisoning)

#### Regulatory Risks
- EU AI Act compliance (high-risk AI systems)
- Data privacy regulations (GDPR, CCPA)
- Industry-specific compliance requirements
- Liability and accountability frameworks

#### Business Risks
- AI cost volatility (GPU prices, token costs)
- Vendor lock-in with AI providers
- Talent acquisition and retention
- Competitive response from Big Tech

## 5. Deliverable Templates

### 5.1 Detailed Concept Document (~10 pages)
1. **Executive Summary** - One-page overview
2. **Problem Landscape** - Market pain points and evidence
3. **Solution Overview** - Technical approach and AI components
4. **Target Persona** - Detailed customer profiles
5. **Market Opportunity** - TAM/SAM/SOM analysis
6. **Competitive Landscape** - Direct and indirect competitors
7. **Opportunities & Differentiation** - Unique value proposition
8. **Risks & Mitigations** - Comprehensive risk assessment
9. **Evaluation & Validation Plan** - 90-day sprint plan
10. **Next Steps** - Resource requirements and timeline

### 5.2 Investor Slide Deck (≤10 slides)
1. **Title** - Company name and tagline
2. **Problem** - Core pain point with evidence
3. **Market Tailwinds** - Growth drivers and timing
4. **Solution** - Technical approach and demo
5. **Target Persona** - Ideal customer profile
6. **Competitive Edge** - Defensible differentiation
7. **Market Size / Business Model** - Economics and scale
8. **Risks & Mitigation** - Key risks and responses
9. **Validation Roadmap** - Proof points and milestones
10. **Ask & Contact** - Funding needs and team info

## 6. How to Use This Framework

### Implementation Steps
1. **Copy** the scorecard and gates into a fresh workspace for each idea
2. **Run** discovery interviews and PoC work in two-week blocks; log evidence
3. **Update** the scorecard and stage-gate matrix; kill ideas early when a gate fails
4. **Export** a detailed doc + slide deck for any idea that clears G3; pitch partners or investors

### Decision Framework
- **Pass Gate**: All criteria met, proceed to next phase
- **Conditional Pass**: Most criteria met, address gaps before proceeding
- **Fail Gate**: Pivot the idea or kill and move to next concept

### Evidence Documentation
- Maintain detailed logs of all validation activities
- Record interview transcripts and insights
- Track all metrics and KPIs throughout the process
- Document decisions and rationale at each gate

## Tools and Templates

- [Detailed Concept Template](templates/detailed_concept_template.md) - Comprehensive idea documentation
- [Investor Deck Template](templates/investor_deck_template.pptx) - Presentation template
- [AI Evaluation Prompts](../prompts/) - AI-assisted validation tools
  - [Basic AI Evaluation](../prompts/idea_evaluation_prompt.md)
  - [ChatGPT O3 Advanced](../prompts/chatgpt_o3_evaluation_prompt.md)

## Success Metrics

Track these key metrics throughout the validation process:

- **Customer Interviews**: Minimum 15+ interviews per sprint
- **Problem Validation Rate**: Target 80%+ problem severity confirmation (≥4/5 urgency)
- **Solution Interest Rate**: Target 70%+ solution interest rate
- **Pilot Success Rate**: Meet all defined KPI targets
- **Gate Success Rate**: Pass all 5 gates (G0-G4)
- **Scorecard Performance**: Achieve ≥70% weighted score

## Decision Outcomes

After completing the 90-day IdeaSprint:

### Go Decision (≥70% scorecard + all gates passed)
- Proceed with full development and launch
- Secure funding based on validation evidence
- Scale team and operations

### Pivot Decision (50-69% scorecard or failed 1-2 gates)
- Modify the idea based on learnings
- Address specific gate failures
- Restart validation process

### No-Go Decision (<50% scorecard or failed 3+ gates)
- Archive the idea and document learnings
- Move to the next concept
- Apply learnings to future ideas

## Additional Resources

- [Case Studies](examples/) - Real-world applications including AgentOS
  - [AgentOS Journey](examples/agentos_case.md) - 90-day validation process
  - [AgentOS Concept Document](examples/agentos_concept_document.md) - **Gold standard output example**
  - [AgentOS Investor Deck](examples/agentos_investor_deck.md) - Professional presentation format
- [Validation Playbook](../playbooks/run_validation.sh) - Automated validation scripts
- [Documentation Generator](../scripts/generate_docs.sh) - Build and validation tools

---

*Version 1.0 — June 27, 2025*

This methodology is continuously updated based on real-world applications and emerging best practices in AI startup validation.