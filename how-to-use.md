# How to Use This Repo

## The Thumbrule

> **hetexecs = "Should we?"**
> **hetops = "How do we?"**

If you're **deciding**, it's hetexecs. If you're **doing**, it's hetops.

| | **hetexecs** | **hetops** (this repo) |
|---|---|---|
| One question | "Is this the right thing to build?" | "Is this batch running correctly?" |
| Actor | CEO, alone or with one advisor | Program Manager + team |
| Cadence | Changes monthly | Changes weekly per batch |
| Content feels like | Hypotheses, reasoning, trade-offs, portfolio views | Checklists, artifacts, evidence, schedules |
| Failure mode | Built the wrong course | Ran the batch badly |

### Anecdotes to Ground This

**Example 1 — "The WMDG batch in Pune has 40% drop-off at Week 3"**
That's **this repo**. The course was already decided. Now you're asking: is the delivery working? You open the batch runbook, check QA checkpoint at Week 2, see what broke. Action happens here.

**Example 2 — "Should we do mushroom cultivation?"**
That's **hetexecs**. You're evaluating the idea — who's the learner, what changes, what NSQF level. No checklists involved. Pure reasoning.

**Example 3 — "Does this learner have valid Aadhaar and bank linkage?"**
That's **this repo**. You're qualifying a *person* for enrollment (BL-2 checklist). Not the course idea.

**Example 4 — "Should we target NSQF Level 3 or Level 4?"**
That's **hetexecs**. A scoping decision about the product, not about any batch.

**Example 5 — "What's in the Week 5 session plan?"**
That's **this repo** — curriculum content is manufacturing. hetexecs only holds the *spec* ("WhatsApp commerce + pricing at L4"). How that becomes weekly sessions is execution.

**Example 6 — "The Tranche-3 submission is due next week — do we have all evidence?"**
That's **this repo**. Livelihood checklist (BL-7), evidence spine, govt adapter — all here.

---

## What This Repo Is — And What It Isn't

### This repo is a **Field Manual**, not a **Live Dashboard**

Think of hetops as the **organization's operating manual** — the reusable playbook that tells the team *how to run any batch correctly*. It teaches behavior and enforces discipline. It's not where live data lives.

| What it IS | What it is NOT |
|------------|----------------|
| Checklists for every batch lifecycle stage | Live batch status ("Batch #47 is at Week 3") |
| Evidence spine definitions | Actual evidence files (photos, screenshots) |
| The batch runbook template | A filled-in runbook for a specific batch |
| Operational adapter checklists (Govt/CSR/Paid) | MOU documents or grant agreements |
| Roles and ownership matrix | HR records or trainer contracts |
| Ops decision records | Daily task lists or Slack messages |

### For a real organization, this repo answers:

**For the Program Manager:**
- "What must be true before I open a batch?" (Pre-Auth checklist)
- "What QA checkpoints do I enforce during delivery?"
- "What's the evidence spine for this course?"
- "What extra steps do I need for a govt-funded batch?"

**For the Center Coordinator:**
- "What does Day 1 kick-off look like?"
- "What do I check at Week 2?"

**For the Documentation Officer:**
- "What evidence do I need to capture at Day 30/60/90?"
- "What constitutes acceptable income proof?"
- "What's in the closure checklist?"

**For a Trainer:**
- "What artifacts should learners produce each week?"
- "What does the batch runbook say for this week?"

**For a new team member:**
- "How does this organization run batches?"
- "Who owns what at each stage?"

**It does NOT answer:**
- "What courses should we offer?" → That's **hetexecs** (product strategy)
- "How many learners passed assessment last month?" → That's **hetlms** (live data)
- "What does our website say about this course?" → That's **hetweb** (marketing)

---

## The Four Repos — How They Relate

```
┌─────────────────────────────────────────────────────────────┐
│                    THE SKILLING SYSTEM                       │
│                                                             │
│   hetexecs          hetops          hetlms         hetweb   │
│   ─────────         ──────          ──────         ──────   │
│   PLAYBOOK:         PLAYBOOK:       LIVE SYSTEM:   SHOPFRONT│
│   Strategy          Execution       Data + App     Marketing│
│                                                             │
│   "Should we?"      "How do we?"    "What's        "What    │
│                                     happening?"    does the │
│                                                    world    │
│                                                    see?"    │
├─────────────────────────────────────────────────────────────┤
│   Changes:          Changes:        Changes:       Changes: │
│   Monthly           Weekly          Daily/hourly   Quarterly│
│                                                             │
│   Actors:           Actors:         Actors:        Actors:  │
│   CEO, advisor      PM, trainer,    Developers,    CEO,     │
│                     doc officer     learners       designer │
│                                                             │
│   Content:          Content:        Content:       Content: │
│   Reasoning,        Checklists,     Attendance,    Courses, │
│   hypotheses,       templates,      enrollment,    outcomes, │
│   portfolio,        runbooks,       evidence,      stories, │
│   decisions         evidence spines assessments    branding │
└─────────────────────────────────────────────────────────────┘
```

### The simplest way to remember

| Repo | Analogy | Permanence |
|------|---------|-----------|
| **hetexecs** | The **constitution** — principles, product definitions, strategic decisions | Endures across batches |
| **hetops** | The **field manual** — SOPs, checklists, templates | Reused every batch |
| **hetlms** | The **factory floor** — live machines, real-time data, actual production | Changes constantly |
| **hetweb** | The **showroom** — what customers see | Updated periodically |

### How information flows

- **hetexecs → hetops:** "We're launching WMDG-v2 as a 6-week intensive. Here's the product spec. Go build the execution plan."
- **hetops → hetexecs:** "After 3 batches of WMDG-v1, we learned the 8-week format has 40% drop-off after Week 5. Consider a shorter version." (Feeds hetexecs pinboard)
- **hetops → hetlms:** "Here's the evidence spine definition. Build the forms and tracking for it."
- **hetlms → hetops:** "Batch #47 has 3 learners with incomplete Aadhaar linkage." (Live data surfaced to ops)
- **hetexecs → hetweb:** "We have 3 course families. Here's what the public should see."
- **hetlms → hetweb:** "Latest metrics — 240 women trained, 78% income increase."
