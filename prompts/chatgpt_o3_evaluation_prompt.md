# ChatGPT O3 IdeaSprint Evaluation Prompt

**Advanced AI-Assisted Startup Validation using ChatGPT's O3 Reasoning Model**

This prompt template leverages ChatGPT's advanced reasoning capabilities to perform comprehensive startup idea validation following the complete IdeaSprint Methodology.

## Overview

This prompt triggers a full validation workflow that includes:
- 10-factor scoring framework
- Stage-gate evaluation process
- 90-day validation planning
- Risk assessment with industry standards
- Automated deliverable generation

## The Prompt Template

Copy-paste this prompt into ChatGPT (O3 reasoning model) and replace the placeholders in **CAPS**:

---

**BEGIN PROMPT**

You are my venture‑studio analyst. Evaluate a prospective startup idea using our established *IdeaSprint Methodology* (Stage‑Gate flow, 10‑factor scorecard, 90‑day sprint, risk checklist, and deliverable templates).

**Idea name:** **[IDEA_NAME]**
**One‑sentence concept:** **[CONCEPT_BLURB]**
**Short description (2‑3 paragraphs):** **[DESCRIPTION]**
**Target persona (if known):** **[PERSONA]**

Tasks to complete:

1. **Problem & Opportunity Analysis** – Describe the current pain points and market tailwinds. Cite at least 10 high‑quality diverse sources (news, academic, industry).
2. **Solution Overview** – Explain how **[IDEA_NAME]** addresses the problem; highlight AI components, deployment model, guardrails.
3. **Ideal Target Persona** – Craft a detailed persona (background, KPIs, pains, buying triggers).
4. **Market Sizing & Growth** – Provide SAM/TAM estimates and CAGR with citations.
5. **Competitive Landscape** – Compare against 2‑3 closest alternatives in a table.
6. **Opportunities & Differentiation** – Summarize defensible wedge.
7. **Risk Map & Mitigations** – Technical, legal, operational; map to OWASP‑LLM, NIST AI‑RMF, EU AI Act.
8. **Stage‑Gate Evaluation** – Fill G0‑G4 with pass criteria and kill/pivot signals.
9. **10‑Factor Scorecard** – Weight, score (0‑5), and commentary.
10. **90‑Day Validation Plan** – Weeks 1‑9 tasks, KPIs, decision point.
11. **Deliverables** – Generate:
    a. A *Detailed Concept Document* (≈10 pages) in canvas.
    b. A concise *Investor Slide Deck* (≤10 slides) in canvas.

Rules:

* Use the *IdeaSprint Methodology* as framework.
* Use the web tool for up‑to‑date evidence; include citations citeturnXsearchY after each supporting sentence.
* Create each deliverable as a separate canvas textdoc via canmore.
* Summarize key findings in chat; do not duplicate full canvas content.
* If any Gate fails, recommend stopping early.
* Write clearly‑formatted markdown (## sections) in chat answers.

**END PROMPT**

---

## Instructions for Use

### Step 1: Prepare Your Idea Information
Before using the prompt, gather the following information:

- **[IDEA_NAME]**: Your startup name or concept name
- **[CONCEPT_BLURB]**: One sentence describing what your startup does
- **[DESCRIPTION]**: 2-3 paragraph detailed description of the problem, solution, and approach
- **[PERSONA]**: Initial target customer description (if known)

### Step 2: Execute the Prompt
1. Replace all placeholders with your specific information
2. Copy the complete prompt into ChatGPT (ensure you're using the O3 reasoning model)
3. Submit and wait for the comprehensive analysis

### Step 3: Review Outputs
The AI will generate:
- **Chat Summary**: Key findings and recommendations in the main chat
- **Canvas Document 1**: Detailed Concept Document (~10 pages)
- **Canvas Document 2**: Investor Slide Deck (~10 slides)

### Step 4: Decision Making
Based on the Stage-Gate evaluation:
- **Pass**: Proceed to validation execution
- **Pivot**: Modify based on recommendations and re-evaluate
- **Kill**: Archive idea and move to next concept

## Example Usage

Here's how to fill out the template:

```
**Idea name:** **AgentOS**
**One‑sentence concept:** **A governed, AI‑first "app‑on‑demand" platform that converts natural‑language specifications into production‑grade micro‑services and UIs.**
**Short description (2‑3 paragraphs):** **AgentOS targets enterprises whose backlogs, SaaS bloat, and new AI‑compliance requirements are colliding. 85% of organisations hold a backlog of 1‑20 internal apps, with many waiting >90 days. Meanwhile, 90% of IT leaders fear "shadow AI" risks, and GPU costs have doubled, squeezing Gen‑AI budgets.

AgentOS sits between low‑code/iPaaS and full‑stack engineering, providing: (1) Spec → Code generation via LLM chains, (2) Built‑in guardrails with RBAC, PII filters, and EU‑AI‑Act compliance, (3) Auto‑generated CI/CD with observability, and (4) SDK extensibility. The platform deploys in customer VPCs, ensuring code ownership and governance.**
**Target persona (if known):** **Maya Chen, Head of Platform & Automation - leads 25‑person platform team in $9B manufacturer, mandate to clear 12‑month backlog and cut SaaS spend 20%**
```

**Expected Output**: This should generate a comprehensive analysis following the AgentOS concept document format, including stage-gate evaluation, 10-factor scorecard, and detailed validation plan.

## What Makes This Prompt Powerful

### 1. **Comprehensive Framework Integration**
- Follows the complete IdeaSprint methodology
- Includes all 10 evaluation factors
- Implements stage-gate decision process

### 2. **Real-Time Market Intelligence**
- Uses web search for current market data
- Includes proper citation requirements
- Ensures evidence-based evaluation

### 3. **Industry Standard Risk Assessment**
- Maps to OWASP LLM Top 10
- Aligns with NIST AI Risk Management Framework
- Considers EU AI Act compliance

### 4. **Automated Deliverable Generation**
- Creates detailed concept documents
- Generates investor-ready slide decks
- Uses ChatGPT's canvas feature for structured outputs

### 5. **Decision-Oriented Structure**
- Clear pass/fail criteria for each gate
- Specific kill/pivot signals
- Actionable 90-day validation plan

## Advanced Usage Tips

### For Technical Startups
Add this context to the prompt:
```
Additional context: This is a technical B2B startup targeting enterprise customers. Focus extra attention on technical feasibility, integration challenges, and enterprise sales considerations.
```

### For Consumer Products
Add this context:
```
Additional context: This is a consumer-facing product. Emphasize user acquisition strategies, viral coefficients, and consumer behavior analysis.
```

### For AI/ML Startups
Add this context:
```
Additional context: This startup heavily involves AI/ML technology. Pay special attention to data requirements, model training costs, AI safety considerations, and regulatory compliance.
```

## Limitations and Considerations

### Prompt Limitations
- Relies on ChatGPT's knowledge cutoff and web search capabilities
- May not have access to proprietary market research
- Cannot replace real customer interviews and validation

### Best Practices
1. **Use as Starting Point**: Treat output as initial analysis, not final decision
2. **Validate Assumptions**: Independently verify key market and technical assumptions
3. **Update Regularly**: Re-run analysis as market conditions change
4. **Combine with Real Validation**: Use alongside actual customer interviews and market testing

## Integration with IdeaSprint Process

This prompt is designed to accelerate **Phase 1: Concept Definition** of the IdeaSprint methodology:

1. **Pre-Validation** (Days 1-7): Use this prompt for initial evaluation
2. **Deep Dive** (Days 8-21): Execute recommended research and validation tasks
3. **Gate Review** (Days 22-30): Make go/no-go decision based on combined AI analysis and real-world validation

## Version History

- **Version 1.0** (June 27, 2025): Initial release with O3 reasoning model support

## Citations and References

The prompt incorporates best practices from:
- Stage-Gate Process ([slidemodel.com](https://slidemodel.com/stage-gate-process-for-product-development/))
- Lean Validation ([bundl.com](https://www.bundl.com/guides/lean-validation-a-fundamental-guide))
- NIST AI Risk Management Framework ([nist.gov](https://www.nist.gov/itl/ai-risk-management-framework))
- EU AI Act ([digital-strategy.ec.europa.eu](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai))
- OWASP LLM Top 10 ([owasp.org](https://owasp.org/www-project-top-10-for-large-language-model-applications/))
- FinOps AI Costs ([finops.org](https://www.finops.org/wg/cost-estimation-of-ai-workloads/))
- Platform Engineering ([platformengineering.org](https://platformengineering.org/blog/platform-engineering-predictions-for-2025))
- Low-Code Growth ([kissflow.com](https://kissflow.com/low-code/low-code-trends-statistics/))

---

*This prompt template is part of the IdeaSprint framework for rapid startup validation. For the complete methodology, see [docs/methodology.md](../docs/methodology.md).*