# Enterprise Account Executive for SaaS — Claude Skill

A strategic copilot for experienced Enterprise Account Executives selling SaaS to large enterprise accounts. Built to operate as a peer-level advisor across the full sales cycle — from first outbound touch to signed contract.

---

## What It Does

This skill turns Claude into an expert Enterprise AE coach and execution partner. It covers every major stage of a complex, multi-stakeholder SaaS deal:

| Option | Capability |
|--------|-----------|
| A | **Deal Qualification** — MEDDIC/MEDDPICC scorecard with color-coded ratings, gap analysis, and prioritized next actions |
| B | **Prospecting & Account Planning** — ICP definition, trigger events, outbound sequences, org mapping, hypothesis of value |
| C | **Discovery Call Prep** — SPIN question banks, 60-min call structure, post-call follow-up templates |
| D | **Executive Presentations & Business Cases** — 30-min exec meeting structure, ROI models, QBR frameworks |
| E | **Proposals & RFP Responses** — winning proposal structure, decision document principles, RFP strategy |
| F | **Negotiation Strategy** — concession tiers, procurement counter-tactics, price protection plays |
| G | **Contract & Commercial Terms** — MSA risk areas, SLA implications, deal desk justification |
| H | **Closing Strategy** — mutual close plans, stall diagnosis, urgency creation, champion testing |

---

## How It Works

When you invoke the skill, it:

1. **Asks your experience level** — so it can calibrate. A 2-year AE gets frameworks explained; a 15-year veteran gets peer-level, no-preamble execution.
2. **Presents a menu** — you pick the area you need help with, or describe your situation freely.
3. **Digs in** — using MEDDIC/MEDDPICC, Challenger Sale, SPIN Selling, and Command of the Message as its underlying frameworks, it produces scorecards, scripts, templates, and action plans tailored to your specific deal.

---

## Frameworks Covered

- **MEDDIC / MEDDPICC** — deal qualification and forecast accuracy
- **Challenger Sale** — insight-led selling and commercial teaching
- **SPIN Selling** — Situation, Problem, Implication, Need-Payoff discovery
- **Command of the Message** — value-based positioning and business outcome framing
- **Mutual Action Plans (MAP)** — close plan discipline and deal control

---

## Installation

### In Claude Code
1. Download or clone this repo
2. Copy the `enterprise-ae-saas/` folder (containing `SKILL.md` and `references/`) into your Claude skills directory:
   ```bash
   cp -r enterprise-ae-claude-skill ~/.claude/skills/enterprise-ae-saas
   ```
3. The skill will appear automatically in your next Claude Code session

### Via `.skill` file
If you have a packaged `.skill` file, install it through the Claude Code skill manager.

---

## Example Prompts That Trigger This Skill

- *"Help me build a MEDDPICC scorecard for a $1.2M deal at a Fortune 500 retailer"*
- *"I have a meeting with the CFO next Tuesday — help me structure it"*
- *"My deal has been stuck for 3 weeks. The champion says the EB is busy. What do I do?"*
- *"Write me a cold outbound sequence for VP of RevOps at mid-market SaaS companies"*
- *"Procurement just asked for a 30% discount. How do I respond?"*
- *"Help me prep for a discovery call with a CTO at a fintech company"*
- *"Build a business case I can send to the CFO"*

---

## File Structure

```
enterprise-ae-claude-skill/
├── SKILL.md                          # Main skill — loaded on every invocation
└── references/
    ├── meddic.md                     # Full MEDDPICC framework with probing questions
    ├── discovery.md                  # SPIN question banks and call structure
    ├── exec-presentation.md          # Executive meeting structure and ROI models
    ├── negotiation.md                # Concession tiers and procurement counters
    └── prospecting.md                # ICP, trigger events, outbound sequences
```

---

## Benchmark Results

Tested against 3 real-world enterprise sales scenarios:

| Test Case | With Skill | Without Skill |
|-----------|-----------|---------------|
| Stalled $1.8M deal rescue (Fortune 500, CFO gone dark) | ✅ 5/5 | ⚠️ 4/5 |
| MEDDPICC scorecard ($650K manufacturing deal) | ✅ 5/5 | ⚠️ 4/5 |
| 30-min CRO executive presentation prep | ✅ 5/5 | ⚠️ 3/5 |
| **Overall pass rate** | **100%** | **73%** |

Key differentiators vs. Claude without the skill:
- Produces full color-coded MEDDPICC scorecards (not just general advice)
- Provides week-level action plans tied to specific close windows
- Quantifies pilot/proof data into actual $ business impact
- Ends every session with a specific, calendar-ready next step
- Calibrates depth and tone to the AE's experience level

---

## Target User

Strategic Enterprise AEs selling SaaS with:
- Deal sizes of **$250K–$10M+ ARR**
- Multi-stakeholder, multi-threaded sales cycles
- 3–12 month average sales cycles
- Fortune 500 / large enterprise accounts

Works across all SaaS verticals — security, data, HR tech, fintech, RevOps, infrastructure, and more.

---

## Contributing

Pull requests welcome. If you have additional frameworks, reference materials, or vertical-specific playbooks you'd like to add, open a PR or issue.

---

