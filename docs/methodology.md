# Ten Commandments Deep Dive Series — Methodology

*This file defines the methodology for ALL studies in the cmd-XX series (Ten Commandments Deep Dive). Every analysis agent MUST follow this methodology.*

## Central Question

**What does the Bible say about each of the Ten Commandments?**

This is an expository series, not a debate. Each study examines what the Bible teaches about one commandment — its origin, meaning, Hebrew/Greek word studies, OT application, prophetic expansion, NT treatment by Jesus and the apostles, and cross-references across Scripture from Genesis to Revelation.

There are no "positions" to investigate. The goal is to report what the text says.

---

## Investigative Methodology (include verbatim in every agent prompt)

```
INVESTIGATIVE METHODOLOGY:
- You are an investigator, not an advocate. Your job is to report what the evidence says.
- Gather evidence comprehensively. Trace the commandment from Genesis to Revelation.
- Do NOT state opinions. State what the text says.
- Do not use editorial characterizations like "genuine tension," "strongest argument,"
  "most significant challenge," "honestly acknowledge," or "non-intuitive reading."
  Simply state what each passage says.
- When presenting findings, state: "The text says X" (explicit). Then if needed:
  "From this, it follows that Y" (necessary implication) or
  "This has been interpreted to mean Z" (inference).
- Never use language like "irrefutable," "obviously," or "clearly proves."
  Use "the text states," "this is consistent with."
- The conclusion should emerge FROM the evidence, not be imposed ON it.
```

---

## Evidence Classification (REQUIRED in every CONCLUSION.md)

Every CONCLUSION.md MUST include a multi-tier evidence classification section. The tiers are **Explicit**, **Necessary Implication**, and **Inference** (with four inference subtypes: I-A, I-B, I-C, I-D).

**The classification is about what THE BIBLE says, not what individual verses say in isolation:**
- **Explicit:** "The Bible says X" — you can point to a verse that says X.
- **Necessary Implication:** "The Bible implies X" — you can point to verses that, when combined, force X with no alternative.
- **Inferred:** "Someone claims the Bible teaches X" — but no verse says it and no combination of verses forces X. Something must be added that the text does not contain. Inferences are further classified into four types (I-A, I-B, I-C, I-D) based on source and direction.

**Evidence Hierarchy:** E > N > I-A > I-B (resolved by SIS) > I-C > I-D

**CRITICAL RULE: Inferences cannot block explicit statements or necessary implications.** If explicit texts and necessary implications establish X, the existence of passages that *could be inferred* to teach not-X does not prevent X from being a necessary implication.

### 1. Explicit Statements Table

| # | Explicit Statement | Reference | Category |
|---|---|---|---|
| E1 | [What the text directly says — a quote or close paraphrase] | [Book Chapter:Verse] | [See categories below] |

Rules for explicit statements:
- The text must directly say this. Quote or closely paraphrase the actual words of Scripture.
- One explicit statement per verse or closely related verse cluster.
- A paraphrase of a single verse in different words is still explicit. "Thou shalt not kill" = "God forbids murder" → explicit (same verse, same meaning).
- **THE MEANING OF WORDS IS EXPLICIT.** If a single verse uses a word, what that word means is part of the explicit statement.

### 2. Necessary Implications Table

| # | Necessary Implication | Based on | Why it is unavoidable |
|---|---|---|---|
| N1 | [What unavoidably follows from explicit statements] | [Which E# statement(s)] | [Why no reader could deny this conclusion from those statements] |

Rules for necessary implications:
- A necessary implication follows unavoidably from one or more explicit statements.
- **No additional concept, framework, or interpretation is required** — only understanding what the words mean.
- **Every reader, regardless of theological position, must agree this follows.** If a reasonable reader could disagree, it is an inference, not a necessary implication.

**STRICTER N-TIER TEST:**

Ask these three questions for EACH N item:

1. **Universal agreement test:** Would a scholar from ANY theological tradition necessarily agree this follows from the cited E statements?
   - If NO → it's an inference, not a necessary implication

2. **No interpretation required test:** Does this require choosing between possible meanings, or is it the only possible meaning?
   - If it requires choosing → it's an inference (I-B)

3. **Zero added concepts test:** Does this add ANY concept, framework, or connection not present in the explicit statements themselves?
   - If YES → it's an inference

### 3. Inferences Table (4-Type Taxonomy)

| # | Claim | Type | What the Bible actually says | Why this is an inference | Criteria |
|---|-------|------|-----|------|----------|
| I1 | [The claim about what the Bible teaches] | [I-A/I-B/I-C/I-D] | [What the relevant verses actually say — cite E# and N# items AND include actual verse references] | [What must be added beyond what the text contains] | [Which criterion/criteria apply] |

#### The 4-Type Inference Taxonomy

|  | Aligns with E/N | Conflicts with E/N |
|--|--|--|
| **Derived from E/N** | **I-A** (Evidence-Extending) | **I-B** (Competing-Evidence) |
| **Not derived from E/N** | **I-C** (Compatible External) | **I-D** (Counter-Evidence External) |

**I-A (Evidence-Extending):** Uses ONLY vocabulary and concepts found in E/N statements. Only an inference because it systematizes multiple E/N items into a broader claim.

**I-B (Competing-Evidence):** Some E/N statements support it, but other E/N statements appear to contradict it. Genuine textual tension where both sides can cite Scripture. Resolved by the Scripture-Interprets-Scripture (SIS) protocol.

**I-C (Compatible External):** Reasoning from outside the text (theological tradition, philosophical framework, historical context) that does not contradict any E/N statements.

**I-D (Counter-Evidence External):** External concepts that require overriding, redefining, or qualifying E/N statements to be maintained.

#### Inference Criteria

An inference MUST require at least one of these:
1. **Adding a concept the text doesn't state**
2. **Choosing between two possible readings**
3. **Applying an external framework**
4. **Cross-referencing (4a: SIS with verified connection = not an inference trigger; 4b: without verified connection = inference trigger)**
5. **Systematizing into a doctrine**

---

## Category Classification (replaces Positional Classification)

Since this series is expository (not debate), items are classified by **category** instead of position:

- **Commandment Scope** — What the commandment prohibits or requires (its literal and expanded meaning)
- **Word Study** — Hebrew/Greek vocabulary analysis, definitions, semantic ranges
- **Biblical Application** — How the commandment is applied in OT narratives, laws, prophets
- **NT Treatment** — How Jesus, the apostles, and NT authors treat the commandment
- **Theological Significance** — What the commandment reveals about God's character, human nature, or the divine-human relationship
- **Cross-Commandment** — How this commandment connects to other commandments or broader biblical themes

These categories are used in the evidence database (`classification` field). The evidence_db.py `--classification` flag accepts these values for the cmd series.

---

## Scripture-Interprets-Scripture (SIS) Principle

When a passage about the commandment is unclear, use clearer passages to interpret it:

- **#4a** (SIS with verified textual connection) — NOT an inference trigger. Document the connection (shared vocabulary, OT quotation, tool-verified parallel).
- **#4b** (cross-referencing without verified textual connection) — IS an inference trigger.

### I-B Resolution Protocol

When an inference has competing textual support (I-B), apply this 5-step process:

**Step 1: Identify tension.** List E/N items FOR and AGAINST the claim.

**Step 2: Assess clarity** of each E/N item:
- **Plain**: Directly addresses the topic; no interpretation needed
- **Contextually Clear**: Addresses the topic but requires context awareness
- **Ambiguous**: Could plausibly be read either way

**Step 3: Count and weigh.** Plain statements outweigh Ambiguous ones.

**Step 4: Apply SIS.** Plain statements determine the reading of Ambiguous ones.

**Step 5: State resolution.** Strong / Moderate / Unresolved.

---

## Classification Decision Trees

### Tree 1 — Tier Classification

```
Q1: Does this directly quote or closely paraphrase the actual words
    of a specific verse or verse cluster?
    NO  -> go to N-CHECK
    YES -> go to E-CHECK

E-CHECK:
  E1: Is this the plain lexical meaning of those words —
      no concept, framework, or interpretation added?
      YES -> TIER: E (Explicit). Stop.
      NO  -> go to N-CHECK

N-CHECK:
  N1: Does this follow unavoidably from one or more E-items?
      NO  -> TIER: I (Inference). Stop. Go to Tree 2 (I-Type).
      YES -> go to N2

  N2: Would a scholar from ANY tradition necessarily agree this
      follows from the cited E-items, without any additional reasoning?
      NO  -> TIER: I. Stop. Go to Tree 2.
      YES -> go to N3

  N3: Does reaching this conclusion require choosing between
      two possible meanings?
      YES -> TIER: I. Stop. Go to Tree 2.
      NO  -> go to N4

  N4: Does this add ANY concept not present in the cited E-items?
      YES -> TIER: I. Stop. Go to Tree 2.
      NO  -> TIER: N (Necessary Implication). Stop.
```

### Tree 2 — I-Type Classification

```
SOURCE TEST:
  S1: Strip away systematization. Are ALL remaining components
      found in the E/N tables?
      YES -> text-derived -> go to DIRECTION TEST (text-derived)
      NO  -> external -> go to DIRECTION TEST (external)

DIRECTION TEST (text-derived):
  D1: Does this claim require any E/N statement to mean something
      other than its plain lexical value?
      NO  -> TYPE: I-A (Evidence-Extending). Stop.
      YES -> TYPE: I-B (Competing-Evidence). Stop.
            [I-B requires a full SIS Resolution subsection.]

DIRECTION TEST (external):
  D2: Does this claim override, redefine, or qualify any E/N statement?
      NO  -> TYPE: I-C (Compatible External). Stop.
      YES -> TYPE: I-D (Counter-Evidence External). Stop.
```

---

## Verification Phase (REQUIRED)

After completing all tables, run this verification check:

**Step A: Verify explicit statements:**
- Does each E-statement directly quote or closely paraphrase actual verse text?
- Is it actually just the plain meaning of the words in the verse?

**Step B: Verify necessary implications:**
- Does each N follow unavoidably from the cited E statements?
- Apply the three N-tier tests. If any test fails → move to Inferences.

**Step C: Verify inference classifications (source test):**
- Strip away systematization. All components in E/N tables? → text-derived (I-A or I-B). Otherwise → external (I-C or I-D).

**Step D: Verify inference classifications (direction test):**
- Does the claim require any E/N statement to mean something other than its lexical value? → conflicts (I-B or I-D). Otherwise → aligns (I-A or I-C).

**Step E: Run consistency checks:**
- Every I-A: Only requires criterion #5? If it requires #1, #2, or #3, reclassify.
- Every I-B: E/N items on BOTH sides? If only one side, reclassify.
- Every I-D: Overrides at least one E/N statement? If not, reclassify as I-C.

---

## Master Evidence Database (REQUIRED before writing Tally)

The evidence database (`D:/bible/bible-studies/cmd-evidence.db`, managed by `D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db`) holds all E/N/I items registered by every study.

### Standard Evidence DB Workflow

**Step 1 — Check for duplicates before adding:**

```bash
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db find E --ref "Exo 20:13" --text "thou shalt not kill"
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db search "thou shalt not kill murder"
```

**If match found:** Use the existing master ID. Record your study:
```bash
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db also-in E010 cmd-XX
```

**If no match:** Proceed to Step 2.

**Step 2 — Reserve the next available ID:**
```bash
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db next-id E
```

**Step 3 — Add the item:**
```bash
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db add E \
  --id E001 \
  --statement "Thou shalt not kill." \
  --ref "Exo 20:13" \
  --classification Neutral \
  --study cmd-07
```

**Step 4 — Note in CONCLUSION.md:**
```
Evidence items registered in D:/bible/bible-studies/cmd-evidence.db
```

### Verification
```bash
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db tally
python D:/bible/evidence_db.py --db D:/bible/bible-studies/cmd-evidence.db list --tier E
```

---

## Master Study Database

The study DB (`D:/bible/bible-studies/cmd-study.db`) indexes the full prose analysis from every completed study.

### Before starting — query prior analysis

```bash
python D:/bible/study_db.py --db D:/bible/bible-studies/cmd-study.db find-passage "Exo 20:13"
python D:/bible/study_db.py --db D:/bible/bible-studies/cmd-study.db find-word "ratsach"
python D:/bible/study_db.py --db D:/bible/bible-studies/cmd-study.db search "murder kill sixth commandment" --top 5
```

Also query the law series databases (read-only cross-reference):
```bash
python D:/bible/study_db.py --db D:/bible/bible-studies/law-study.db search "sixth commandment murder" --top 5
python D:/bible/evidence_db.py --db D:/bible/bible-studies/law-evidence.db search "thou shalt not kill"
```

### After completing — register the new study

```bash
python D:/bible/study_db.py --db D:/bible/bible-studies/cmd-study.db ingest D:/bible/bible-studies/cmd-XX-study-name
python D:/bible/study_db.py --db D:/bible/bible-studies/cmd-study.db embed --update
```

---

## Tally Summary Format

```
- Explicit statements: [count]
- Necessary implications: [count]
- Inferences: [count]
  - I-A (Evidence-Extending): [count]
  - I-B (Competing-Evidence): [count] ([N] resolved, [M] unresolved)
  - I-C (Compatible External): [count]
  - I-D (Counter-Evidence External): [count]
```

---

## What CAN Be Said / What CANNOT Be Said

**What CAN be said (Scripture explicitly states or necessarily implies):**
- [List — draw from both Explicit and Necessary Implication tables]

**What CANNOT be said (not explicitly stated or necessarily implied by Scripture):**
- [List of things the text does not directly say or necessarily imply — including things commonly assumed]

---

## Critical Rules Governing the Hierarchy

1. **E > N > I-A > I-B > I-C > I-D.** Higher-tier evidence governs the interpretation of lower-tier claims.

2. **Inferences cannot block explicit statements or necessary implications.**

3. **I-A inferences are the strongest inferences** because they use only the text's own vocabulary and concepts.

4. **I-B inferences require the SIS protocol.** Both sides have textual support. The resolution must be documented.

5. **I-D inferences bear the heaviest burden.** They require overriding what the text says with concepts the text does not contain.

6. **SIS connections (#4a) are not inference triggers.** Using clear passages to interpret unclear ones — when the connection is verified — is standard hermeneutics.
