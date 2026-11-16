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
  byte-identical; `verify_pack` (the app's acceptance checks) passes.
- Source: openstax/osbooks-introductory-statistics-bundle at commit
  `50ec91749080bb040b57bb40c34337cacc994cba` (17 March 2026), the last
  revision under CC BY 4.0. Licence: CC BY 4.0 — see `ATTRIBUTION.txt`.

Build sources, corpus and evidence (answers run 5/5 with citations;
retrieval check 11/12 in top 3) are in the pull request to
https://github.com/0x94t3z/fieldatlas that adds
`tools/packs/extract_openstax_introstats.py`,
`tools/packs/build_introstats_pack.py` and `tools/packs/introstats/`.

Import in Field Atlas: Library → Import, then pick this file.
