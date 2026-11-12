# Markdown for Faculty: The Force Multiplier
**A Curriculum Architect's Guide to Institutional Agility (S-A-R Standard v2.2)**

Markdown is a plain-text formatting syntax that allows you to focus on **Content Engineering** rather than document formatting. It is the **Single Source of Truth (`SSoT`)** that powers everything from your Syllabus to your born-accessible Canvas LMS pages.

---

## The Clinical Framing Protocol (`Pattern / Rule / Solve`)

- **Pattern (Context):** Traditional document editors (Word / static PDF) create format friction. They are hard to version-control, frequently inaccessible to screen readers, and drift across LMS shells.
- **Rule (Constraint):** Every piece of curriculum must be **Scalable, Auditable, and Repeatable (`S-A-R Standard`)**. Enforcing a strict Markdown heading and contrast hierarchy guarantees **ADA Title II & WCAG 2.2 AA (`9:1` Double-Contrast Guard)** compliance by default.
- **Solve (Intervention):** Author once in clean Markdown and compile deterministically across Canvas LMS (`GraphQL`), Open Educational Resource (`OER`) archives, and semantic HTML.

---

## Essential Syntax for Educators

### 1. Structural Hierarchy (Headings)
Always follow a sequential heading hierarchy without skipping levels. **Note:** Start at `##` in Canvas body pages, as `#` (`<h1>`) is reserved exclusively for the Canvas Page Title.
- `## Heading 2` (Main Module Sections)
- `### Heading 3` (Lab Instructions & Sub-Topics)
- `#### Heading 4` (Specific Clinical Data)

### 2. Emphasis & Semantic Lists
- **Bold:** `**Important Text**`
- *Italics:* `*Emphasized Text*`
- **Unordered List:** Use `-` or `*` for real semantic `<ul>` bullet points (never fake typed bullets inside paragraphs).
- **Ordered List:** Use `1.`, `2.`, `3.` for sequential `<ol>` laboratory procedures.

### 3. Accessible Links & Alt Text
- **Descriptive Hyperlink:** `[Arizona Western College Exercise Science](https://www.azwestern.edu/)`
- **Informative Image (`<= 120` chars):** `![Anatomical diagram of sagittal plane knee flexion](image-url.png)`

### 4. Callouts & Blockquotes
Use `>` for *In Plain English* / *En palabras sencillas* callouts and instructor safety gates:
> **Safety Gate:** Verify all clinical outputs against the primary Academic Single Source of Truth (`PAGA 2018 2nd Ed.`, `DGA 2025–2030`, `ACSM 12th Ed.`, `NASM OPT`).

### 5. Delimiter Isolation Protocol
Wrap all clinical case data, client profiles, and biometric inputs inside triple-hash (`###`) code blocks:
```text
###CASE_DATA_START###
Client biometrics and regional Yuma heat-stress presentation
###CASE_DATA_END###
```

---

## The Architect's Advantage
By mastering Markdown SSoT, faculty draft once in Git, pass automated **POUR / WCAG 2.2 AA (`9:1`)** pre-commit gates, and publish across Canvas LMS with zero accessibility debt.

---
*Developed by [Alan Pruitt (Coach Alan)](https://alanpruitt.com/) — Founder & Principal, [Webcognita LLC](https://www.webcognita.com/) | Arizona Western College & The University of Arizona (Yuma)*
