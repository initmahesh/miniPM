---
name: prd-review
description: Use this skill whenever a user wants to review a PRD, audit a product spec, run a PRD quality check, or get structured feedback on a product requirements document. Triggers include: "review this PRD", "check my PRD", "audit this spec", "is my PRD good", "PRD review checklist", "give feedback on my product doc", or when a user pastes a PRD and asks for critique.
version: 1.0.0
argument-hint: <PRD text or document>
---

# PRD Review Checklist
*Covers 2-pagers and 6-pagers. Mark each item ✅ (Yes) · ⚠️ (Partial) · ❌ (No)*

| Field | |
|---|---|
| Document Title | |
| Author / Reviewer | |
| Review Date | |

---

## 0. Opening & Framing
*Amazon PRFAQ principle: if the opening doesn't land, leadership stops reading. Check this first.*

| # | Check | Status | Notes |
|---|---|---|---|
| 0.1 | Headline / title is a customer benefit statement — not a feature description or internal project name | | |
| 0.2 | First paragraph names the customer, the problem, and the transformation delivered — an unfamiliar exec understands why this matters in under 30 seconds | | |
| 0.3 | Document is free of buzzwords and hype: "revolutionary", "game-changing", "AI-powered", "next-gen", "paradigm shift" | | |
| 0.4 | Narrative is written from the customer's perspective throughout — not the engineer's or the company's | | |

**Notes:**

---

## 1. Problem & Customer

| # | Check | Status | Notes |
|---|---|---|---|
| 1.1 | Problem is clearly articulated (job-to-be-done) and validated with real customer data or research — not internal assumptions | | |
| 1.2 | Problem statement is a pure pain statement — does NOT hint at or imply a solution | | |
| 1.3 | Negative impact is quantified: time lost, cost, frequency, or scale of affected users | | |
| 1.4 | Customer persona defined with specific roles, industries, and needs; buyer vs. user distinguished if different | | |
| 1.5 | Urgency is clear — explains why now and the cost of inaction | | |
| 1.6 | Existing alternatives called out as insufficient, with a specific reason why they fall short | | |
| 1.7 | MOAT is defined and defensible — data flywheel, workflow lock-in, proprietary training, or switching cost | | |
| 1.8 | Solution is differentiated from ChatGPT, copilots, and commodity AI wrappers | | |
| 1.9 | Validated demand signal present — customer quotes, paid pilots, waitlists, or demonstrated willingness to pay | | |

**Notes:**

---

## 2. Solution & AI Design

| # | Check | Status | Notes |
|---|---|---|---|
| 2.1 | Core value proposition is crisp (1–2 sentences) and directly addresses the stated problem | | |
| 2.2 | Solution addresses every problem raised in the Problem section — no orphaned pain points left unresolved | | |
| 2.3 | Solution is described in benefit language (what the customer experiences) — not feature lists or system architecture | | |
| 2.4 | Visual user flow included: input → processing → output | | |
| 2.5 | Core functional requirements listed in user story format | | |
| 2.6 | Use of Agentic AI / ML / LLMs justified over rule-based or simpler approaches; unstructured data types identified | | |
| 2.7 | AI drawbacks addressed: hallucination, attribution accuracy, agent failure modes, and explainability | | |

**Notes:**

---

## 3. Metrics & Success

| # | Check | Status | Notes |
|---|---|---|---|
| 3.1 | North Star metric defined — the single number that proves the product is working | | |
| 3.2 | Primary metric is customer-recognized — something the customer would care about, not an internal proxy | | |
| 3.3 | Every primary metric has a baseline (current state value) AND a SMART target (specific, time-bound) | | |
| 3.4 | Both leading indicators (early signals you can watch) and lagging indicators (ultimate business outcomes) are present | | |
| 3.5 | Secondary metrics included: adoption, time saved, cost reduction, or task completion rate | | |
| 3.6 | Anti-metrics / guardrails stated — what should NOT get worse (e.g. false attribution rate, user trust, latency) | | |
| 3.7 | Launch criteria clearly defined — what specific thresholds must be met to ship? | | |
| 3.8 | Metric ownership and tracking method defined — who owns each metric and how will it be measured? | | |

**Notes:**

---

## 4. Prioritization & Roadmap

| # | Check | Status | Notes |
|---|---|---|---|
| 4.1 | Agentic workflow broken into components (e.g. ingestion, extraction, summarization) with per-component risk assessment | | |
| 4.2 | ML feasibility, data availability, and accuracy expectations specified | | |
| 4.3 | Features prioritized by risk, cost, and value; MVP scope narrowed with rationale | | |
| 4.4 | Roadmap phases defined: MVP → MVP1 → Launch → Iteration, with feature sets and durations | | |
| 4.5 | Roadmap items linked back to priorities and risks | | |

**Notes:**

---

## 5. AI Evaluation & Prompt Strategy

| # | Check | Status | Notes |
|---|---|---|---|
| 5.1 | AI performance evaluation approach described (datasets, ground truth sources, benchmarking cadence) | | |
| 5.2 | Accuracy targets defined relative to a human or rule-based baseline — not just in absolute terms | | |
| 5.3 | Prompting strategy described — few-shot, CoT, or conditional prompting where applicable | | |
| 5.4 | Plan for prompt iteration and improvement based on user feedback | | |

**Notes:**

---

## 6. Responsible AI

| # | Check | Status | Notes |
|---|---|---|---|
| 6.1 | Risks assessed across Accountability, Transparency, Fairness, and Reliability | | |
| 6.2 | Human-in-the-loop and fallback paths planned | | |
| 6.3 | Sensitive use cases identified with mitigation strategies | | |

**Notes:**

---

## 7. Pricing & Business Case

| # | Check | Status | Notes |
|---|---|---|---|
| 7.1 | Development costs broken down (infra + manpower) and ongoing operational costs listed | | |
| 7.2 | Revenue scenarios defined and pricing model selected with rationale | | |
| 7.3 | Accuracy vs. cost tradeoffs explained | | |
| 7.4 | Directional pricing recommendation included | | |

**Notes:**

---

## Overall Verdict

| | |
|---|---|
| **Rating** | ⬜ Strong &nbsp; ⬜ Good — minor gaps &nbsp; ⬜ Needs Work &nbsp; ⬜ Not Ready |
| **Top Strengths** | 1. · 2. · 3. |
| **Top Gaps** | 1. · 2. · 3. |
| **Next Step** | |

---
*PRD Review Checklist v3.0 — Reviews Project · Updated 2026-04-01 based on Amazon PRFAQ best practices*

---

## ✦ Proposed Additions — v2 (2026-04-24)

*These items were added based on feedback patterns seen 5+ times across reviewed documents.*

| ✦ NEW | **Metrics & Success → 3.2** — Does each primary metric include a baseline (current state) and a SMART target? | | |
  *(Added v2 — seen in 5 docs. Example: "When a document scopes the product too narrowly (e.g. "back-office teams in CRE ...")* |
| ✦ NEW | **Problem & Customer → 1.1** — Is the problem backed by at least one concrete data point or direct customer evidence? | | |
  *(Added v2 — seen in 5 docs. Example: "When a document scopes the product too narrowly (e.g. "back-office teams in CRE ...")* |

---
*Checklist v2 — pending approval from Mahesh*