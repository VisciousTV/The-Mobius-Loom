# Mobius Loom — Comprehensive Overview
_Last updated: 2026-01-30_

This packet is the **single most comprehensive outline** of Mobius Loom: the vision, mechanics, schemas, safety, incentives, governance, and a concrete MVP build plan. It is written to be usable by:
- builders/engineers,
- potential collaborators,
- advisors/investors,
- domain experts and researchers,
- community organizers.

---

## 0) Executive summary

### 0.1 One sentence
**Mobius Loom is a human+AI collaborative intelligence network that routes work to the right mix of experts and AI agents, producing both (1) a concrete deliverable (“Particle Output”) and (2) a structured reusable learning update (“Wave Delta”) that compounds cross-domain problem-solving over time.**

### 0.2 The core thesis
- **AI is a force multiplier** for iteration, drafting, synthesis, and decomposition.
- **Humans remain the coherence and alignment substrate**, especially for high-stakes or truth-claims.
- The platform captures **verified collaboration traces** (not just final answers) and extracts **structured learnings** (Wave Deltas) into a public memory (**Rosetta Stone**).
- Over time, Rosetta + traces improve routing, clarification, and reliability—**without turning the platform into “just a forum”**.

### 0.3 What makes Loom different
Most systems capture the “forward pass” (answers). Loom also captures the “backward pass” (learning updates) explicitly:
- **Particle Output** = deliverable (what the user wanted)
- **Wave Delta** = structured update (how the system got better)

This is the **Wave/Particle duality** requirement that keeps Loom compounding.

---

## 1) The “Bridge” principle (what Loom connects)

Mobius Loom is a bridge system. It bridges:

### 1.1 Access + capability bridges
1) **Access to experts** for people who don’t have networks, credentials, or funds.
2) **Novice ↔ expert** by clarifying intent into executable specs and translating jargon.
3) **AI novices ↔ AI veterans** by standardizing “how to ask” and “how to verify.”
4) **AI atrophy ↔ skill growth** by embedding tutoring, review, and feedback into normal use.

### 1.2 Trust + correctness bridges
5) **Scale ↔ coherence**: where model scaling alone cannot ensure correctness, humans + verification do.
6) **Consensus ↔ truth**: voting is fine for taste; verification is required for truth.
7) **Safety ↔ usefulness**: low-friction for low risk; quarantines/committees for high risk.

### 1.3 Societal + economic bridges
8) **Capitalism ↔ post-scarcity**: not a rejection of capitalism—uses incentives now to gradually reduce scarcity dynamics (“dissolves by replacement, not by fight”).
9) **Job displacement ↔ job replacement**: creates paid work paths as automation replaces jobs.

### 1.4 Knowledge + research bridges
10) **Research output ↔ accessibility**: makes progress traces and methods reusable, searchable, and visible.
11) **Funding ↔ autonomy**: bounties/campaigns fund work researchers believe in, not only what institutions dictate.
12) **Discipline ↔ discipline**: cross-domain translation uncovers shared structure across fields.

### 1.5 Perspective bridges
13) **Perspective ↔ perspective**: translation + reframing reduce unnecessary conflict and tribal loops.

> **Design intention:** The product experience should make these bridges *obvious*, not hidden.

---

## 2) Neurons ↔ myelin (human/AI alternation)

Loom is not “AI replaces humans.” It is **alternation**:

- **AI (myelin-like)**: speeds iteration, drafts, decomposes, searches, proposes.
- **Humans (neurons)**: ground truth, judge taste, enforce coherence, align to human values.

The system is explicitly built to switch back and forth:
- AI drafts ↔ human reviews ↔ AI revises ↔ human verifies ↔ promote.

This is the “Mobius” twist: multiple viewpoints become one continuous loop rather than competing fragments.

---

## 3) Wave/Particle duality + the Uplift rule

### 3.1 Particle output (forward pass)
The user’s concrete deliverable: code, plan, doc, design, analysis, prototype, etc.

### 3.2 Wave delta (backward pass)
A **structured** generalizable learning update (Rosetta/Method/Rule/Confusion/Negative result).

**Non‑negotiable:** Wave Delta cannot be “just notes.” It must be machine-readable.

### 3.3 Uplift rule (hierarchical compounding)
Every lower-level contribution must uplift the level above:

- **Artifact** uplifts a **Thread**
- **Thread** uplifts the **Route Card**
- **Route Card** uplifts **Rosetta** + community memory

This prevents “task completion without compounding progress.”

---

## 4) Product primitives (the minimal architecture)

Loom is built on 5 primitives:

1) **Route Card** (refined intention spec)
2) **Threads** (atomic work units)
3) **Artifacts** (deliverables + wave deltas + proofs)
4) **Event Log** (trace capture / “spikes”)
5) **Rosetta Stone** (external weights memory)

Everything else is an iteration built on these.

---

## 5) Workflow (how Loom operates)

### Step 1 — Wizard (guided intention filtering)
Turns vague intent into an executable spec:
- goal, constraints, success criteria, non-goals
- stakes/risk, lane suggestion
- definition of done

### Step 2 — Orchestrator (thread decomposition)
Splits the Route Card into **reviewable**, **routable**, **independently solvable** Threads.

### Step 3 — Router (matchmaking + translation)
Assigns:
- AI agent roles + human expert roles
- lane (fast/standard/rigorous)
- review depth (none/compressed/single/committee/layered)

**Router role can be “jack-of-all-trades bridge”**: translate between dialects and people.

### Step 4 — Work loop (AI ↔ human)
AI drafts ↔ human reviews ↔ revisions ↔ verification ↔ promotion.

### Step 5 — Provenance + verification
Every promoted artifact includes:
- who/what produced it
- what checks ran
- what remains uncertain

### Step 6 — Consolidation (“sleep cycle”)
Daily/weekly consolidation extracts:
- **Method Cards** (reusable workflows)
- **Rule Packs** (style compression and defaults)
- **Rosetta updates** (cross-domain mappings + evidence)
- system prompt improvements (“wake up smarter tomorrow”)

---

## 6) Lanes (evidence burden + friction control)

Lanes are a single concept: **minimum evidence burden**.

### Fast lane
- default for low-risk
- AI-first; quick gating
- must include uncertainty notes and provenance

### Standard lane
- typical tasks
- requires human review for medium stakes or when flagged

### Rigorous lane
- high-stakes truth work
- requires verification:
  - tests / execution traces
  - citations
  - reproducibility
  - formal proof where feasible
- often layered expert passes

Rule: the system can **escalate up** based on risk; user can request less friction but cannot force unsafe delivery.

---

## 7) Safety + trust (immune response)

### 7.1 Detectors + quarantine
- Automated detectors flag risk (suggestion layer).
- Quarantine routes outputs to committee review when thresholds trip.

### 7.2 Reason-coded veto (mandatory)
A veto must include:
- reason category (medical/legal/financial/security/privacy/other)
- short evidence note

### 7.3 Consensus vs truth (mandatory distinction)
- **Consensus** is acceptable for taste/preference
- **Truth** requires evidence and verification

### 7.4 Supervisor AI
A “supervisor” AI can:
- propose committee composition
- propose mitigations
- flag suspicious patterns

But humans remain final authority for high stakes.

---

## 8) Incentives, credits, leveling, and fairness

### 8.1 Credits model (high level)
- Users earn credits by contributing value.
- Credits purchase:
  - speed (skip line)
  - depth (committee/layered review)
  - expert time

Credits can be redeemed for money (later stage; compliance required).

### 8.2 Expert access guarantee
To prevent a paywall world:
- Experts complete **1 free assignment for every 4 paid** (configurable).
- Free users get limited expert assists; can earn more via contributions.

### 8.3 Semi-experts and learners have a place
- low-tier contributions earn credits first
- performance and verified results unlock higher tiers
- onboarding assessment helps route users to fitting tasks

### 8.4 Difficulty-as-pass-count (restored mechanic)
- Problems passed/declined many times get higher “difficulty weight.”
- Solver reward increases with pass_count (log-scaled recommended).
- Attempting but failing does not automatically punish (encourage learning).
- Low-effort spam is handled via separate reputation flags.

---

## 9) Community co-design + governance

### 9.1 Community-driven evolution
The collective should feel empowered to shape Loom:
- feature proposals
- protocol changes
- experiments
- governance participation

A “healthy anarchist” community style is a goal: bottom-up improvement with clear protocols.

### 9.2 Large community events
- week/month campaigns where many people co-build
- output can become shared IP or shared profit pools (optional structure)

### 9.3 Consensus meetings for science
Structured convergence:
- each side states what evidence would change their mind
- peer-reviewable reasoning
- bounty paid if consensus protocol is completed

---

## 10) Cross-domain translation and the “Rosetta protocol”

### 10.1 Rosetta is not a glossary
Rosetta is an evidence-backed memory that supports:
- **vector search** (embeddings)
- **knowledge graph relations** (extends/contradicts/similar_to)
- evidence counts and tiering
- conflict tracking (no silent overwrites)

### 10.2 Dual-lane correlation experiment
To test domain transfer:
- Domain A expert solves in native language
- Domain B expert solves translated equivalent
- translation layer back-translates
- both vote “felt native?” + list confusion points
- verifier decides if mapping update is valid

### 10.3 Communication auditors
Separate role to tag breakdown points:
- where translation fails
- where jargon hides assumptions
- where clarifications are missing

---

## 11) Style compression: Rule Packs + divide-and-review

People review fastest in their own style:
- Rule Packs: “defaults I always use” (coding, design, reasoning)
- diff-first review
- chunk the project so many reviewers can validate small segments quickly
- reduce “one person reviewing thousands of lines”

This is a scalability mechanism.

---

## 12) Definition of Done (non-negotiable)

A unit of work is “done” only if it includes **all four**:

1) **Particle output** (deliverable)
2) **Wave delta** (structured Rosetta/method/rule update, or `none + reason`)
3) **Roadmap** (next actions + roles + acceptance criteria)
4) **Integration explanation**:
   - how it advances the refined user goal
   - how it strengthens Rosetta (even small)

---

## 13) Canonical schemas (high-level)

### 13.1 Route Card (intent embedding)
Key fields:
- goal, success criteria, constraints, non-goals
- stakes/risk/evidence burden
- lane + routing plan + counterfactuals
- definition of done
- north star: user outcome + rosetta contribution goal

### 13.2 Thread
Key fields:
- task, DoD
- lane + enforcement rules
- goal echo:
  - user goal echo
  - rosetta echo
- pass_count + attempts
- assigned roles

### 13.3 Artifact
Key fields:
- type (particle, wave delta, method card, rule pack, etc.)
- provenance + checks + uncertainty
- traceability links to route card/thread
- promotion status

### 13.4 Event Log
Key fields:
- who/what did what when
- loop phase (draft/review/revise/verify/promote)
- risk flags
- payload

---

## 14) Wave Delta schema (Rosetta Update) — REQUIRED

Rosetta updates must be machine-readable, queryable, and evidence-backed.

### 14.1 Practical JSON shape
```json
{
  "delta_id": "wd_...",
  "delta_type": "mapping|rule|method|confusion_point|negative_result",
  "source_context": {
    "domain": "string",
    "concept": "string",
    "tags": ["string"],
    "embedding_ref": "optional_vector_id"
  },
  "target_context": {
    "domain": "string",
    "concept": "string",
    "tags": ["string"],
    "embedding_ref": "optional_vector_id"
  },
  "claim": "string",
  "mechanism": "string",
  "applicability": {
    "conditions": ["string"],
    "exceptions": ["string"]
  },
  "machine_logic": {
    "kind": "rewrite_rule|routing_hint|template_patch|checklist|other",
    "payload": {}
  },
  "evidence": {
    "success_count": 0,
    "failure_count": 0,
    "examples": [
      {
        "input_summary": "string",
        "output_summary": "string",
        "artifact_ids": ["art_..."],
        "thread_id": "th_..."
      }
    ]
  },
  "confidence_tier": "experimental|promising|established|canonical",
  "uncertainty": 0.0,
  "relations": [
    {
      "related_delta_id": "wd_...",
      "relation_type": "extends|contradicts|similar_to"
    }
  ],
  "provenance": {
    "route_card_id": "rc_...",
    "thread_id": "th_...",
    "creator": {"kind": "human|ai|system", "id": "string"},
    "verifiers": ["u_..."],
    "created_at": "ISO-8601"
  }
}
```

### 14.2 Why machine_logic matters
- prevents Rosetta from becoming “notes”
- enables automation:
  - routing hints
  - rewrite rules
  - checklist generation
  - template patches

---

## 15) MVP build plan (the fastest path to reality)

### 15.1 MVP = trace engine
Build only:
1) Route Cards (Wizard)
2) Threads (decomposition)
3) Artifacts + provenance
4) Event log
5) Rosetta entries + attempts + wave delta validation

### 15.2 14-day roadmap (high-level)
- Days 1–3: DB + events + CRUD
- Days 4–6: Wizard v1
- Days 7–9: Router v1 + lanes
- Days 10–12: Rosetta v1 + wave delta ingest
- Days 13–14: UI pages (route card/thread/rosetta)

### 15.3 Cold start strategy
- seed Rosetta with 25–100 starter deltas
- private alpha with strict DoD
- track reuse metrics (how often wave deltas are reused)

---

## 16) How to contribute (roles)
- builders/engineers
- routers (bridge people)
- verifiers (truth lanes)
- domain experts
- communication auditors
- governance/ops
- campaign leads

---

## 17) Appendix: Templates (copy/paste)

### 17.1 Task Card template (for builders/AI coders)
- Goal (Particle):
- Wave Delta:
- Integration (Uplift):
  - User Goal Echo:
  - Rosetta Echo:
- Scope:
- Acceptance criteria:
- APIs/DB touched:
- Events logged:
- Risks:
- Roadmap next actions:

### 17.2 Wave Delta quality checklist
A good wave delta includes:
- clear claim + mechanism
- applicability conditions + exceptions
- machine logic payload that is actually reusable
- evidence counts + links
- uncertainty score

---

## 18) Included companion docs
This packet is paired with builder-friendly documents:
- Builder Playbook v2
- AI Coder Prompt Pack v2
- MVP Issue Tracker v2
- Comprehensive Outline v1 (older consolidation)
- Shareable Outline v2
- Wave Delta Schema (shareable v1)

