# AI Use & Code Provenance Statement

Geometry Reader was built with substantial help from an AI coding assistant (Claude Code, by Anthropic). This statement sets out who did what, so that the work can be judged accurately.

## Authorship and accountability
- **Wasema Farzana is the author of Geometry Reader** and is accountable for all of it, including the parts the assistant produced.
- **The assistant was a tool the author directed.** Following the position of the Committee on Publication Ethics, an AI tool cannot be an author, because it cannot take responsibility for the work (COPE, 2023).
- **The `Co-Authored-By` line on commits is a disclosure, not a claim of authorship.** It is the convention software projects use to record which commits an assistant wrote.

## The author's contribution
Listed by the contributor roles of the CRediT taxonomy (Brand et al., 2015):
- **Conceptualisation.** Conceived the product, named it and the planned series of "Readers", and set its scope: the whole of school geometry, from first ideas to O-Level. Identified measurement and unit conversion, which many learners find confusing, as the next module.
- **Methodology (pedagogy).** Designed the teaching approach the tool embodies:
  - manipulation before explanation;
  - proofs that are watched, not recited;
  - formal terms paired with plain language;
  - one meaning for each colour, and large, forgiving controls, without ever labelling the learner;
  - everyday objects as anchors;
  - topics first, curriculum second.
- **Subject expertise.** Set the mathematical definitions and conventions the tool teaches, including where textbooks disagree: the definition of a trapezium, the kite family, and how to count faces on curved solids, with the disagreement taught openly.
- **Investigation.** Uses the tool in the author's own teaching and revises it from what is observed, as the first phase of design-based research (see [RESEARCH.md](RESEARCH.md)).
- **Supervision.** Wrote the briefs, reviewed the results, resolved open questions, and accepted or rejected the assistant's proposals.
- **Project administration.** Set the licence, the rollout plan, the privacy rules, and the split between this public showcase and the private materials.
- **Research framing.** Owns the research agenda, the field observations and the educational and anthropological reasoning behind them.
- **Writing.** Wrote the first draft of the project's story, and reviewed every document.

## The assistant's contribution
- **Software.** Wrote all of the application code, from the author's briefs.
- **Visualisation.** Drew the everyday-object illustrations, after the author chose in-house drawings.
- **Validation.** Ran the automated checks: lint, build, numerical tests and scripted browser walk-throughs.
- **Mathematical review.** At the author's request, checked the visual proofs for gaps in logic, and fixed the ones found.
- **Writing.** Drafted most of the documentation from the author's own statements, and checked the references against published records.
- **Proposals.** Suggested some design decisions, which the author accepted on their merits. These include Calm mode and keyboard control, the policy of disclosing AI use, keeping design claims as hypotheses, correcting a mathematical over-generalisation in the original brief, and building the measurement lab as a foundation module shared across subjects. The full decision log, part of the Reviewer Pack, records the origin of every decision.

## Provenance
- Commits written by the assistant carry a `Co-Authored-By` trailer.
- No learning, anxiety or accessibility outcome has been measured. Design aims are stated as hypotheses.

## References
- Brand, A., Allen, L., Altman, M., Hlava, M., & Scott, J. (2015). Beyond authorship: Attribution, contribution, collaboration, and credit. *Learned Publishing*, 28(2), 151–155. https://doi.org/10.1087/20150211
- COPE (Committee on Publication Ethics). (2023, 13 February). *Authorship and AI tools* [Position statement]. https://publicationethics.org/cope-position-statements/ai-author
