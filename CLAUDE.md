# CLAUDE.md — Project Briefing for Riley's 5th Grade Math Materials

Read this file before touching anything in this project.

---

## Who this is for

Riley — 5th grade math teacher at KIPP DC (Key Academy), Room 323.
Four math classes: NCAT, BAMA, SHAWU, FAMU.
Standards: Common Core, Grade 5 (5.NBT, 5.NF, 5.MD, 5.OA).

---

## What this project is

A set of HTML-based student worksheets that open in a browser and print cleanly to PDF.
HTML is used instead of Word or Google Docs because it holds its formatting permanently —
no drift between sessions, no reformatting, no starting over.

---

## Folder structure



CLAUDE.md                          ← this file (read first, always)
Morning Work Template.html         ← master template for daily morning work
I Do You Do Template.html          ← master template for I Do / You Do lessons
README.md                          ← project notes
index.html                         ← navigation page
daily/                             ← one file per day, organized by week
week-of-04-20/                 ← first week (Mon April 20 = Day 1)
2026-04-20 Day 1.html
problems/                          ← reusable scaffold snippets
area-model.html
bar-model.html
number-line.html
blank.html
archive/                           ← version snapshots of templates (do not edit)
uploads/                           ← scanned PDFs for reference (do not edit)


## How to make a new daily file

1. Copy Morning Work Template.html into daily/week-of-[monday-date]/
2. Name it: YYYY-MM-DD Day N.html (e.g. 2026-04-21 Day 2.html)
   Day numbering starts at 1 = Monday April 20, 2026. Count up from there.
3. Update the masthead: date, day number, standard code, topic name
4. Fill in: math joke, fluency facts, and each problem prompt
5. For scaffolds: paste the relevant snippet from problems/ or remove the scaffold block entirely
6. Never edit the master template unless Riley explicitly says to update it

---

## Design rules — never change these without being told

- Fonts: Caveat (display/handwritten), Kalam (body handwritten), Inter (UI/labels)
- Page size: 816px wide × 1056px tall (letter at 96dpi)
- Colors: --ink #111, --muted #666, --line #222, --paper #fff, --soft #f5f3ec
- Print: always include @media print styles, @page size: letter, margin: 0
- Style: clean, teacher-made feel — slightly rotated stamps/badges, dashed lines, hand-lettered look
- No external frameworks (no Bootstrap, no Tailwind) — plain CSS only

---

## What Riley will tell you each morning

When Riley asks for a new daily file, he will provide some or all of:
- Date and day number (e.g. "April 21, Day 2") — Day 1 = April 20, 2026
- Standard (e.g. "5.NF.B.4")
- Topic / skill name (e.g. "Multiplying a fraction by a whole number")
- Math joke (optional — Riley may ask you to suggest one)
- Fluency facts (Riley will provide or ask you to generate)
- Problem prompts (Riley will provide or ask you to write them)
- Which scaffold to use, if any

If Riley doesn't provide something, ask before inventing it — especially problem numbers.

---

## Tone and communication style

- Riley is learning to code while building. Explain what you're doing in plain English.
- Keep explanations short — one concept at a time.
- When you make a file, say exactly where you saved it and what Riley should do next.
- Never silently change the master template. Always confirm first.
