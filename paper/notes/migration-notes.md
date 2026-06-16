# Migration notes

**Created 2026-06-16** by spinning the form-meaning material out of the syntactic
umbrella paper, `papers/Linguistic_transparency/` (\enquote{Linguistic transparency
as mediated accessibility}).

## Why this paper exists

The umbrella paper committed to being the *syntactic* transparency paper: its
delivered results are the number-transparent quantificational-noun profile and
transparent free relatives, with Korean as the forthcoming cross-linguistic test.
The form-meaning material (constructional compositionality, compound transparency,
masked priming) was the most promissory part of that paper, three within-domain
profiles plus a *research hypothesis* (the cross-domain cluster), not a delivered
result. It was over-weighted there and is a genuinely separate project: different
relation R (interpretation/processing, not agreement), different methods (ratings,
masked priming), different literatures, and its own empirical test. So it was cut
to a single compressed section in the umbrella (which now points here) and moved
out whole as the seed of this paper.

## What was moved (verbatim, this repo `paper/sections/`)

- `03-constructional-transparency.tex` — CxG, compositionality gradient, the
  network-property hypothesis (Goldberg; Kay & Fillmore).
- `04-semantic-transparency.tex` — Bell & Schäfer compound transparency.
- `05-processing-transparency.tex` — Heyer & Kornishova masked priming; Feldman
  et al. rival parallel-processing position.
- `B1-appendix-b.tex` — Bell & Schäfer apparatus (Levi predicates, Reddy database).
- `C1-appendix-c.tex` — Heyer & Kornishova design and statistical detail.
- `D1-appendix-d.tex` — **the cross-modal probe design.** This is the intended
  empirical spine of the paper, not an appendix. Promote it into the body when
  developing the draft.

## To do before this compiles cleanly / reads as a standalone

1. **Dangling cross-references.** The moved files reference umbrella labels that
   don't exist here: `sec:1`, `sec:2`, `sec:2-1`, `sec:2-2`, `sec:2-3`, `sec:2-5`,
   `sec:2-6`, `sec:6`, `sec:7`. They print as `??`. Rewrite each as a one-line
   recap or a citation to the umbrella paper (add a bib entry for it once it has a
   preprint URL).
2. **Trim umbrella-only material.** `03` §3.4 (\enquote{Number-transparent NPs
   revisited}) and §3.5 (\enquote{TFRs revisited}) are cross-links back to the
   umbrella's syntactic cases; keep only what a form-meaning reader needs.
3. **Drop the referential boundary.** `04` §4.3 (\enquote{Referential transparency
   as boundary case}, the Lois/Superman *de re*/*de dicto* case) was **retained in
   the umbrella** as the schema's outer boundary. Delete it here; it isn't
   form-meaning-family material.
4. **Promote the probe (Appendix D) into the body** and build the paper around the
   four-window within-items study (corpus predictors, ratings, priming, interpretation
   accuracy on shared -ness/-ost' or NN-compound items). Running it is what turns
   this from a programmatic paper into a delivered empirical result.
5. **Write the intro and abstract** (currently TODO stubs).
6. **Prune `references-local.bib`** — copied wholesale from the umbrella; many
   entries (QN/TFR-specific) are unused here. Run `/validate-bib` after the body
   settles.

## Relationship to the umbrella paper

The umbrella's compressed §3 makes the R-relativity point (the schema reaches
form-meaning relations) and forward-references this paper. When this paper has a
preprint, add a reciprocal citation there.
