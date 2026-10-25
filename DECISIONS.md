# Design Principles

The human-centred design reasoning behind Geometry Reader. Each principle is condensed from the project's full decision log, which records who made each decision and why. That log is part of the Reviewer Pack. **Origin** says whether the author decided it or the AI coding assistant proposed it and the author accepted.

Every principle states a design intention. Whether it achieves its aim for learners is a research question (see [RESEARCH.md](RESEARCH.md)), not a claim.

## 1. Manipulate first, explain second
*Origin: author.* Every concept is taught by direct manipulation: learners drag points, lines and solids, and every angle, length, area and volume updates live. No value is hidden. Text-only geometry blocked the author's own understanding as a student; seeing and handling the figure unlocked it.

## 2. Watch why, not just that
*Origin: author.* Every theorem and formula is shown as an animation on the learner's own figure. Pieces fold, swing and slide until the reason becomes visible, with short plain captions. Proofs stay live: drag the figure and the same argument replays on the new shape. No exam board's written proof format is used as the main explanation.

## 3. Two kinds of language, side by side
*Origin: author.* Every formal term appears beside a plain-language translation, for example *Supplementary Angles ➔ (180° Flat Runway Pairs)*. Formal terms are where many learners freeze; the pairing lowers that wall while keeping the vocabulary examinations require.

## 4. Each colour has one job
*Origin: author.* Indigo marks what can be moved, mint marks proofs and truths, amber marks measurements and warnings, and cyan marks vocabulary. A learner never has to work out what a colour means twice. The interface never labels or diagnoses the learner.

## 5. A calm interface for every nervous system
*Origin: author, with AI proposals accepted.*
- **Calm mode** switches off flashes, glows and motion in one tap, and the app also respects the device's reduced-motion setting.
- Drag targets are large and snap to meaningful values, so precise motor control is not a precondition for success.
- Everything can be done from the keyboard.

## 6. Visual-first
*Origin: author.* The tool concentrates on what tutoring rarely provides at the margin: a manipulable picture. Audio is outside the current scope.

## 7. Built for shared, low-resource devices
*Origin: a property of the original build; the gendered-access rationale was stated by the author in October 2026.*
- The whole application runs in the browser, and the figures are drawn as lightweight vector graphics.
- After a single download of about 200 KB (compressed), it sends and receives nothing. A session costs no further data, and once the page has loaded it keeps working without a connection.
- An installable offline version is planned.

## 8. No accounts, nothing stored about the learner
*Origin: a property of the original build; the surveillance rationale was stated by the author in October 2026.* There is no login, no profile, no tracking and no analytics. On a shared household phone, a learning tool that keeps no record of the learner leaves nothing for anyone else to inspect. This matters most for learners whose device use is supervised (see RESEARCH.md, section 3).

## 9. Everyday anchors, drawn in-house
*Origin: author.* Each shape and property is linked to everyday objects, drawn as line illustrations that highlight the geometry inside the object: the right angle in a book corner, the apex of an ice-cream cone. Familiar objects from learners' own surroundings, such as a carrom board, a paper kite or a roti, are included deliberately.

## 10. Topics first, curriculum second
*Origin: author.* Each lab teaches its topic in depth regardless of syllabus. Mapping a lab to a particular examination system is a separate layer added on top.

## 11. Mathematically honest
*Origin: AI proposal, accepted, and extended by the author.* Where a simple rule has exceptions, the tool shows them rather than hiding them. Examples: a dented polygon breaks the "turns add to 360°" rule (an AI correction to the original brief); some textbooks disagree on how to count a cone's faces, and the author chose to teach that disagreement openly; and the trapezium has two competing definitions, of which the author chose the one learners are examined on.

## 12. Honest provenance and modest claims
*Origin: the privacy rules are the author's; disclosing AI use and keeping claims as hypotheses were AI proposals the author accepted.* AI involvement is disclosed (see [AI_USE.md](AI_USE.md)). Design aims stay hypotheses until they are measured. No learner, school, family or specific locality is identified.
