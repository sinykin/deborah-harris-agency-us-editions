# Deborah Harris Agency titles in US editions, 2000–2026

Books represented by the **Deborah Harris Agency** (DHA) that appeared in US editions, 2000–2026, compiled and quality-checked title by title. Each row carries the evidence for including it.

## Files

| File | Rows | Contents |
|---|---|---|
| `Harris_Agency_US_fiction_2000-2026_ALL_QC.csv` | 108 | All fiction: literary, commercial/genre, children's and YA |
| `Harris_Agency_US_LITERARY_2000-2026_QC.csv` | 50 | The literary subset — every `ISRAELI-LITERARY` (45) and `ENGLISH-LITERARY` (5) row |

The LITERARY file is a strict subset of the ALL file; the two share the same columns, and it can be reproduced by filtering `Category`.

## Columns

| Column | Notes |
|---|---|
| `Year` | Year of the US edition, 2000–2026 |
| `Author` | 67 distinct authors across the ALL file |
| `Title` | US edition title |
| `US Publisher` | 71 distinct publishers |
| `Category` | `ISRAELI-LITERARY` 45 · `COMMERCIAL/GENRE` 24 · `CHILDRENS` 19 · `YA` 15 · `ENGLISH-LITERARY` 5 |
| `Source language` | Hebrew 56 · English 52 |
| `Harris evidence` | Prose note recording *why* the row is included: agency roster page, publisher or Publishers Weekly page, ISBN, translator, and any judgement calls, usually with URLs |

## Judgement calls

Four rows carry a `FLAG` in the evidence column, marking a decision a reader might make differently:

- **Yael Hedaya, *Housebroken* (2001)** — a collection of three novellas, not a single novel.
- **Amir Gutfreund, *Our Holocaust* (2006) and *The World a Moment Later* (2008)** — Toby Press has both Connecticut and London offices; counted as US on its New Milford, CT imprint.
- **Michal Govrin, *Hold on to the Sun* (2010)** — a mixed-genre collection (stories, essays, legends, poetry), borderline for a literary-fiction list.

## Caveats

- **One row is not confirmed as DHA-represented.** Shifra Horn, *The Fairest Among Women* (2001) is kept and its
  `Harris evidence` says why: she is not on the DHA client roster, and her site credits the Institute for the Translation
  of Hebrew Literature for her books. Every other row's evidence cites the agency roster, a QC-verified deal, or a
  Publishers Marketplace deal record.
- **Coverage depends on what could be documented.** Agency rosters change, and titles whose representation left no public trace may be missing. Treat yearly counts as a lower bound.
- **2026 is a part-year** (7 rows), so it is not comparable with full years.
- **`Category` is an editorial judgement**, not a label taken from the publisher.
- **Roster pages are live sites that change.** Some evidence notes cite Wayback Machine captures with their capture dates.
