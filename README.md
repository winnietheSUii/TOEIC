# 📘 TOEIC Study Plan — 40 Days
> **Daily Commitment:** 3 Hours · **Tools:** Memmoread · NotebookLM · iPad Error Log
> **Level:** B1 → B2 · **Parts:** 1–4 (Listening) · 5–7 (Reading & Grammar)

---

## 📂 Repository Structure

```
TOEIC/
├── README.md                     ← You are here
├── Dashboard/
│   ├── index.html                ← 📊 Score Monitor (open in browser, drop CSVs)
│   ├── LC/                       ← 🎧 Listening CSVs (Part 1–4)
│   │   └── *.csv
│   └── RC/                       ← 📖 Reading CSVs (Part 5–7)
│       └── *.csv
└── Grammar/                      ← 📝 Study Notes (Markdown)
    ├── PART5_6_MASTER_TRICKS.md
    ├── 01 Nouns/
    ├── 02 Pronouns/
    ├── 03 Adjectives/
    ├── 04 Adverbs/
    ├── 05 Word Forms/
    ├── 06 Objects, Complements/
    ├── 07 Subject, Verbs/
    ├── 08 Forms and Types of English Verbs/
    ├── 09 Subject-Verb Agreement/
    ├── 10 Tenses/
    ├── 11 Active Voice, Passive Voice/
    └── 12 Prepositions/
```

### CSV Format (Memmoread Export)

```csv
Exam Title,ETS ชมพู ขาว Listening Test 2
Timestamp(ms),1777180453926
DateTime,2026-04-26 12:14

Question,Selected,Correct
Question 1,A,✓
Question 2,B,✗
...
```

**Naming:** Place Listening CSVs in `LC/` and Reading CSVs in `RC/`.

### Question → Part Mapping

| Section | Part | CSV Questions | Exam Questions |
|---------|------|---------------|----------------|
| LC | Part 1 — Photos | Q1–6 | Q1–6 |
| LC | Part 2 — Q&A | Q7–31 | Q7–31 |
| LC | Part 3 — Conversations | Q32–70 | Q32–70 |
| LC | Part 4 — Talks | Q71–100 | Q71–100 |
| RC | Part 5 — Incomplete Sentences | Q1–30 | Q101–130 |
| RC | Part 6 — Text Completion | Q31–46 | Q131–146 |
| RC | Part 7 — Single Passage | Q47–75 | Q147–175 |
| RC | Part 7 — Double Passage | Q76–85 | Q176–185 |
| RC | Part 7 — Triple Passage | Q86–100 | Q186–200 |

---

## 📊 Dashboard

Open `Dashboard/index.html` in any browser → drag & drop your CSV files → done.

- Per-part accuracy bars (P1–P7 with Single/Double/Triple breakdown)
- Bar chart comparison across all parts
- Auto-detected weakest part with focus recommendation
- Test list with scores

> No server needed. Pure client-side — runs via File API.

---

## 📊 Progress Dashboard

| Phase | Days | Focus | Status |
|-------|------|-------|--------|
| 🧱 Phase 1 | Day 1–10 | Grammar Foundations + Problem Drilling | 🔄 In Progress |
| 🏋️ Phase 2 | Day 11–25 | Listening Intensive + Part 7 Stamina | ⬜ Pending |
| 🚀 Phase 3 | Day 26–40 | ETS Full Simulation + Error Mastery | ⬜ Pending |

---

## 🗺️ Grammar Module Roadmap

```
✅ Module 1 ──► ✅ Module 2 ──► Module 3 ──► Module 4 ──► Module 5
(Parts of Speech)  (Sentence Core)  (Connectors)  (Non-Finite)  (Clauses)
   COMPLETE          COMPLETE         Week 3         Week 4        Week 5
```

| Module | Priority | Status |
|--------|----------|--------|
| 🔴 Module 1 — High-Yield Fundamentals | HIGH | ✅ **Complete** |
| 🔴 Module 2 — Core Sentence Mechanics | HIGH | ✅ **Complete** |
| 🟡 Module 3 — Syntactical Connectors | MEDIUM-HIGH | 🔄 In Progress |
| 🟡 Module 4 — Non-Finite Verbs & Modifiers | MEDIUM | ⬜ Pending |
| 🔵 Module 5 — Complex Clauses | MEDIUM-LOW | ⬜ Pending |
| ⚪ Module 6 — Edge Cases | — | ✂️ **Skipped** |

---

## ✅ Module 1 — High-Yield Fundamentals *(Complete)*
> "10-second kill" questions — solvable by identifying word class without reading the full sentence.

<details>
<summary><b>1.1 · Nouns ✅</b> — 6 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 1.1.1 | Position of Nouns | Subject · Object · Complement positions |
| 1.1.2 | Count vs. Non-Count Nouns | Article rules · Confusing pairs (advertising vs. advertisement) |
| 1.1.3 | Determiners and Nouns | Articles (a/an/the) · Quantifier matching table |
| 1.1.4 | Concrete vs. Abstract Nouns | Person noun (-or/-ist) vs. concept noun (-tion/-ment) |
| 1.1.5 | Compound Nouns | Noun + Noun structure · Pluralization rule · TOEIC vocab list |
| 1.1.6 | Common Nouns in TOEIC | Similar-looking nouns with different meanings (permit vs. permission) |

</details>

<details>
<summary><b>1.2 · Pronouns ✅</b> — 6 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 1.2.1 | Personal · Possessive Pronouns · Possessive Adjectives | Subject/Object/Possessive forms · Pronoun before noun vs. standalone |
| 1.2.2 | Reflexive Pronouns | Same subject/object rule · Emphasis use · `by oneself` expressions |
| 1.2.3 | Demonstrative Pronouns & Adjectives | `that/those` in comparisons · `those` = "people who" |
| 1.2.4 | Indefinite Pronouns (1) — One, Another, Other | Specific vs. unspecified · `another` = singular · `others` = standalone |
| 1.2.5 | Indefinite Pronouns (2) — Some, Any, No, None, Most | Sentence type matching · `no` vs. `none` · `most` vs. `almost` |
| 1.2.6 | Pronoun / Possessive Adjective Agreement | Number · Gender · Person · Organization = `its` (not `their`) |

</details>

<details>
<summary><b>1.3 · Adjectives ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 1.3.1 | Positions of Adjectives | Pre-nominal · Predicative · Only adj can modify noun |
| 1.3.2 | Quantifiers as Adjectives & Indefinite Pronouns | Count/non-count quantifier table · `of the` pronoun structure |
| 1.3.3 | Confusing Adjectives | Same-root pairs: `satisfactory` vs `satisfying` · `economic` vs `economical` |
| 1.3.4 | Expressions with Be + Adjective | Fixed collocations: `be subject to` · `be eligible for` · `be aware of` |

</details>

<details>
<summary><b>1.4 · Adverbs ✅</b> — 8 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 1.4.1 | Functions & Positions of Adverbs | 3 positions · Adjective ≠ adverb trap |
| 1.4.2 | Confusing Adverbs | hard/hardly · late/lately · near/nearly · high/highly |
| 1.4.3 | Adverbs of Time | already/still/yet · ever since · ago · once |
| 1.4.4 | Adverbs of Frequency | Frequency scale · Double negative trap (hardly ever) |
| 1.4.5 | Connecting Adverbs | however/therefore/furthermore · Semicolon rule · No redundancy |
| 1.4.6 | Emphasizing Adverbs (1) | just/right/well/even/quite · Comparison emphasisers |
| 1.4.7 | Emphasizing Adverbs (2) | so vs. such · very vs. too · much too |
| 1.4.8 | Other Adverbs | also/too/as well/either · later/thereafter/since · ahead/forward |

</details>

<details>
<summary><b>1.5 · Word Forms ✅</b> — 5 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 1.5.1 | Word Family & Suffix System | All 4 suffix groups · Signal word detection · 4-step strategy |
| 1.5.2 | Noun ↔ Verb Forms | 35 core pairs · Nominalization · Verb after modal |
| 1.5.3 | Adjective Forms | Suffix groups · `-ed` vs `-ing` (cause vs. receive) |
| 1.5.4 | Adverb Forms | `-ly` patterns · Flat adverbs · Tricky `-ly` adjectives |
| 1.5.5 | Word Families Master Reference | 30 essential families · Mixed practice · Speed strategy |

</details>

---

## ✅ Module 2 — Core Sentence Mechanics *(Complete)*
> Highest ROI after Module 1. The structural core of English sentences.

| # | Subtopic | Key Focus | Status |
|---|----------|-----------|--------|
| 2.1 | Subjects & Verbs | See breakdown below | ✅ Done |
| 2.2 | Objects & Complements | See breakdown below | ✅ Done |
| 2.3 | Forms & Types of Verbs | See breakdown below | ✅ Done |
| 2.4 | Subject-Verb Agreement | See breakdown below | ✅ Done |
| 2.5 | Tenses | See breakdown below | ✅ Done |
| 2.6 | Active & Passive Voice | See breakdown below | ✅ Done |

<details>
<summary><b>2.1 · Subjects & Verbs ✅</b> — 6 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.1.1 | Subjects | Valid subject forms · No verb/adj in subject slot · Nouns that look like adj/verb |
| 2.1.2 | Dummy Subject `It` | `It is adj + to/that` · Only `it` works — not `that` or `there` |
| 2.1.3 | Dummy Subject `There` | `There + linking verb + noun` · Existence · `It` vs `There` decision rule |
| 2.1.4 | Verbs | Only conjugated verbs · Verbals cannot be main verbs · No noun/adj in verb slot |
| 2.1.5 | Number, Tense & Voice | Subject-verb number · Time expression = tense signal · Active vs. passive |
| 2.1.6 | Verbs in the Imperative | Bare infinitive after `When/If/Whatever` · `Please` + bare infinitive |

</details>

<details>
<summary><b>2.2 · Objects & Complements ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.2.1 | Objects | Valid object forms · No verb/adj in object slot · Noun conversion required |
| 2.2.2 | Dummy Object `It` | `Verb + it + adj + to/that` · `make it possible to` → to-infinitive |
| 2.2.3 | Complements | Subject complement vs. object complement · No verb/adverb in complement slot |
| 2.2.4 | Noun vs. Adjective Complements | Identify (noun) vs. describe (adj) · Signal: `a/an` → noun, `quite/very` → adj |

</details>

<details>
<summary><b>2.3 · Forms & Types of English Verbs ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.3.1 | Modal & Auxiliary Verbs + Bare Infinitive | `will/can/must/should/did` → bare form · No `to`, no `-s`, no past |
| 2.3.2 | Transitive vs. Intransitive Verbs | Direct object vs. preposition + object · `discuss` ≠ `discuss about` |
| 2.3.3 | Ditransitive Verbs | Two-object verbs: `tell/inform/advise` vs. `explain/suggest to` |
| 2.3.4 | Verbs in That-Clauses | Mandative subjunctive: `suggest/require/essential that` → bare infinitive |

</details>

<details>
<summary><b>2.4 · Subject-Verb Agreement ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.4.1 | SVA in Number | `every/each` → singular · `many/a variety of` → plural · `of the` partitive rule |
| 2.4.2 | Conjunctions & Modifiers | `and` → plural · `or` → nearest · correlative → match B · `along with` → ignore |
| 2.4.3 | SVA in Relative Clauses | Antecedent controls verb · Distractor trap · `the number of` (singular) vs `a number of` (plural) |
| 2.4.4 | Mixed Practice & Special Cases | Gerund subject → singular · Collective nouns → singular · Error identification drill |

</details>

<details>
<summary><b>2.5 · Tenses ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.5.1 | Present/Past/Future Simple | Progressive tenses · Stative verbs cannot use `-ing` · Signal word matching |
| 2.5.2 | Progressive Tenses | Present/Past/Future Perfect · `since/for` → present perfect · `had` for earlier past event |
| 2.5.3 | Perfect Tenses | Tense-signal matching table · Sequence of tenses · `as soon as` + present simple |
| 2.5.4 | Agreement in Tense | Mixed drill · Signal word ↔ tense matching · Master reference table |

</details>

<details>
<summary><b>2.6 · Active & Passive Voice ✅</b> — 4 subtopics</summary>

| # | Subtopic | Key Focus |
|---|----------|-----------|
| 2.6.1 | Identifying Active/Passive | Object present → active · Object absent → passive · Works in main clause, to-inf, relative clause |
| 2.6.2 | Passive in Sentence Structures | Ditransitive (2-object) passive · Object complement stays after passive verb |
| 2.6.3 | Perception Verbs | Subject causes feeling → active · Subject receives feeling → passive · `-ed` vs `-ing` |
| 2.6.4 | Passive Form Expressions | `be + p.p. + preposition` collocations · `be + p.p. + to-infinitive` fixed structures |

</details>

---

## 🟡 Module 3 — Syntactical Connectors
> Always read both clauses before choosing. These test logic as much as grammar.

| # | Subtopic | Key Focus | Status |
|---|----------|-----------|--------|
| 3.1 | Prepositions | Time · Place · Direction · Fixed collocations | 🔄 In Progress |
| 3.2 | Coordinating Conjunctions | FANBOYS: for / and / nor / but / or / yet / so | — |
| 3.3 | Correlative Conjunctions | both…and · either…or · neither…nor · not only…but also | — |

> 🗒️ Transition words already covered in **Module 1.4 — Connecting Adverbs**. No re-study needed.

---

## 🟡 Module 4 — Non-Finite Verbs & Modifiers
> Pattern recognition over rule memorization.

| # | Subtopic | Key Focus | Status |
|---|----------|-----------|--------|
| 4.1 | Participles | V-ing / V-ed as modifiers · Cause vs. receive recap | — |
| 4.2 | Gerunds | Verb + gerund vs. verb + infinitive · Common pairs | — |
| 4.3 | To-infinitives | Purpose · Adjective complement · Noun role | — |
| 4.4 | Modifiers | Misplaced modifier trap only — 1 session | — |

---

## 🔵 Module 5 — Complex Clauses *(Light Coverage)*
> These appear more in Part 6 & 7 than Part 5. Don't over-invest.

| # | Subtopic | Key Focus | Status |
|---|----------|-----------|--------|
| 5.1 | Relative Clauses | who / which / that / whose · Defining vs. non-defining | — |
| 5.2 | Adverb Clauses | because / although / when / if — the 4 essential types | — |
| 5.3 | Comparison | Comparative + superlative with much / even / far / by far | — |
| 5.4 | Parallelism | Concept overview — 30 min max | — |

---

## 📅 40-Day Schedule

### 🧱 Phase 1 · Days 1–10 · Grammar + Problem Drilling

**Daily 3-Hour Block:**
- **Hour 1 — Theory** (Memmoread `Learn Grammar` + NotebookLM notes)
- **Hour 2 — Problem Diving** (Part 5 drill → Part 6 drill, same topic as Hour 1)
- **Hour 3 — Error Log** (iPad screenshots + 1-sentence fix per wrong answer)

| Day | Grammar Topic | Module |
|-----|---------------|--------|
| Day 1–2 | Subjects & Verbs + Objects & Complements | 2.1 / 2.2 |
| Day 3–4 | Forms & Types of Verbs | 2.3 |
| Day 5–6 | Subject-Verb Agreement | 2.4 |
| Day 7–8 | Tenses (3 only) | 2.5 |
| Day 9–10 | Active & Passive Voice | 2.6 |

---

### 🏋️ Phase 2 · Days 11–25 · Listening + Reading Stamina

**Daily 3-Hour Block:**
- **Hour 1 — Listening** (Parts 1–4 · Read questions before audio starts)
- **Hour 2 — Part 7** (Questions first → keywords → scan · Single then double passages)
- **Hour 3 — Grammar + Vocab** (Part 5/6 drill · Business flashcards from Parts 4 & 7)

| Day | Grammar Topic | Module |
|-----|---------------|--------|
| Day 11–13 | Prepositions | 3.1 |
| Day 14–16 | Coordinating + Correlative Conjunctions | 3.2 / 3.3 |
| Day 17–18 | Participles | 4.1 |
| Day 19–20 | Gerunds | 4.2 |
| Day 21–22 | To-infinitives | 4.3 |
| Day 23 | Modifiers | 4.4 |
| Day 24–25 | Relative Clauses | 5.1 |

---

### 🚀 Phase 3 · Days 26–40 · ETS Simulation
> **Materials:** ETS Official Books (เล่มเทาเทา · เขียวฟ้า · ส้มฟ้า)

**Alternating Pattern:**
- **Listening Days** (26, 28, 30, 32, 34, 36): 1 Full Listening Test — no pausing (45 min) + error review
- **Reading Days** (27, 29, 31, 33, 35): 1 Full Reading Test — 75-min timer · Part 5+6 ≤ 20 min → 55 min for Part 7
- **Sundays** (33, 40): No new tests · Swipe through iPad error screenshots · Self-quiz

| Day | Grammar Topic | Module |
|-----|---------------|--------|
| Day 26–27 | Adverb Clauses | 5.2 |
| Day 28–29 | Comparison | 5.3 |
| Day 30 | Parallelism | 5.4 |
| Day 31–36 | No new grammar — simulation + error review only | — |
| Day 37 | Module 1+2 — revisit 3 weakest topics from error log | Review |
| Day 38 | Module 3+4 — revisit 3 weakest topics from error log | Review |
| Day 39 | Full timed Part 5 drill (40 Qs · 15 min max) | Review |
| Day 40 | Light review only — rest | — |

---

## 🧠 Exam Strategy — Quick Reference

| Part | Questions | Time Budget | Key Tactic |
|------|-----------|-------------|------------|
| **Part 5** | 40 Qs | ≤ 20 min | Signal word → suffix scan → eliminate → decide by meaning |
| **Part 6** | 16 Qs | Within 20 min | Read full paragraph first · Tense + connector consistency |
| **Part 7** | 54 Qs | 55 min | Questions → keywords → scan · Never read whole text first |
| **Parts 1–4** | — | 45 min | Read next set's questions while audio plays · Never chase missed answers |

> 💡 **Score Bottleneck Check:** After each simulation, track your **time left** at end of Part 7.
> Running out of time for Part 7 → your **Part 5 speed** is the problem, not your vocabulary.

---

## ✂️ What Was Cut & Why

| Topic | Reason |
|-------|--------|
| Subjunctives | < 2 questions per exam — not worth it |
| Inversion | Extremely rare · Basic concept in Adverbs of Frequency |
| Noun Clauses *(standalone)* | Low Part 5 frequency · Implicit in Part 7 reading |
| Transition Words *(Module 3)* | Fully covered in Adverbs — Connecting Adverbs |
| Parallelism | 30-minute concept only — no deep study |

---

**Total grammar notes:** 55 files · All in Notion-importable Markdown format

*Import any `.md` file into Notion: **+ New Page → Import → Markdown & CSV***
