# Mathematics: Introductory Statistics — Field Atlas pack

`openstax-maths-introstats-0.1.0.fapack` — OpenStax *Introductory Statistics 2e*
as an offline Field Atlas collection, built with the Field Atlas pack tools
for POIDH bounty [Base #1554](https://poidh.xyz/base/bounty/1554).

- 82 documents: the 80 numbered sections of all 13 chapters (235 worked
  examples, 1,881 exercises, glossaries in 38 sections, 133 definitions),
  plus Appendix F (Mathematical Phrases, Symbols, and Formulas) and
  Appendix H (Tables) — the formula tables.
- 1,522 passages; pack 3,426,546 bytes, SHA-256
  `6684e28191584f9343c3a4e5c1178eba350c94d31bf68d8b31d128ddce938354`;
  installs to 3,425,706 bytes. Two builds from the pinned corpus are
  byte-identical; `verify_pack` (the app’s acceptance checks) passes.
- Source: openstax/osbooks-introductory-statistics-bundle at commit
  `50ec91749080bb040b57bb40c34337cacc994cba` (17 March 2026), the last
  revision under CC BY 4.0. Licence: CC BY 4.0 — see `ATTRIBUTION.txt`.

Build sources, corpus and evidence (answers run 5/5 with citations;
retrieval check 11/12 in top 3; 16 corpus tests pass, 34 tests in total
incl. the Prealgebra and stream-pack suites) are in the pull request
https://github.com/0x94t3z/fieldatlas/pull/30 that adds
`tools/packs/extract_openstax_introstats.py`,
`tools/packs/build_introstats_pack.py` and `tools/packs/introstats/`.

## Answers run — 5/5 with citations

Worked from the cited section’s stated formula; the teaching section is
the #1 retrieved passage for all five (detail in the PR,
`tools/packs/introstats/ANSWERS-SUMMARY.md`):

- Relative frequency 0.225 — §1.3 Frequency, Frequency Tables, and Levels of Measurement
- Binomial mean 6, SD √4.2 ≈ 2.049 — §4.3 Binomial Distribution
- Empirical Rule ≈ 95% — §6.1 The Standard Normal Distribution
- 95% confidence interval (78.08, 85.92) — §8.1 A Single Population Mean using the Normal Distribution
- Chi-square test of independence: expected 20/30/20/30, χ² = 16.67, df = 1 — §11.3 Test of Independence

## Retrieval check — 11/12 in top 3

12 ordinary statistics questions against the pack’s own FTS5 index
(`tools/packs/introstats/introstats-retrieval.json`): the teaching section
is in the top three hits for 11 of 12. The one miss is recorded honestly:
“regression equation” — §12.3 The Regression Equation’s first passage ranks 4th.

Import in Field Atlas: Library → Import, then pick this file.
