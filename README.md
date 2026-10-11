# pwg-ru-lod — static Linked-Open-Data surface for the PWG→RU graph

_Created: 11-10-2026 · Last updated: 11-10-2026_

**Machine translation — not yet human-reviewed — NOT CITABLE.** This site
publishes the graph *shape* of the Petersburg Dictionary → Russian LOD edition
as an explicitly non-citable technical preview (release-posture ruling (B),
MG 11-10-2026).

- Permanent namespace: `https://w3id.org/sanskrit-lexicon/repwg/` (w3id.org 303
  content negotiation: Turtle to machines, HTML to browsers; the PR to
  [perma-id/w3id.org](https://github.com/perma-id/w3id.org) registers it).
- Dataset descriptor: [void.ttl](https://sanskrit-lexicon.github.io/pwg-ru-lod/void.ttl)
  · build + safety + license provenance:
  [PROVENANCE.md](https://sanskrit-lexicon.github.io/pwg-ru-lod/PROVENANCE.md).
- Canonical standards surface (SHACL, acceptance query, runbook):
  [sanskrit-lexicon/csl-standards `standards/pwg-ru-lod/`](https://github.com/sanskrit-lexicon/csl-standards/tree/main/standards/pwg-ru-lod).
- Generator + renderer: [gasyoun/SanskritLexicography `RussianTranslation/src/`](https://github.com/gasyoun/SanskritLexicography/tree/master/RussianTranslation/src)
  (`export_lod.py`, `render_static_lod.py`).

Layout: `entry/<key>.ttl|html` (120,172 entries), `lemma/<key1>.ttl` (106,082),
`citation/<slug>.ttl` (35,778), `grades.ttl`, `vocab.ttl`, `dataset.ttl`, the two
full dumps, the SKOS small-class register (v1.6.1), `.nojekyll` (plain static —
GitHub Pages must not Jekyll-process this tree).

Wave-0 of [docs/PUBLISHING_LOD.md](https://github.com/sanskrit-lexicon/csl-standards/blob/main/docs/PUBLISHING_LOD.md),
executed under [H6484](https://github.com/gasyoun/Uprava/blob/main/handoffs/H6484-OxAlpha_csl-standards_publishing-lod-wave0-rulings-exec_11.10.26.md).

_Dr. Mārcis Gasūns_
