# Changelog

## 2026-08-03: Joint prompt and Scribe calibration

### Changed

- Clarified that the system prompt, project instructions, skills, and request
  act together during generation rather than as isolated writing passes.
- Made explicitly multi-part questions trigger matching lead-ins without
  forcing labels onto short connected arguments.
- Allowed visibly hypothetical numerical counterexamples when an unknown real
  rate would otherwise hide the mechanism.
- Let argument structure determine paragraph rhythm and made useful closing
  syntheses more salient without adding a summary quota.
- Integrated invited humor into the explanation before a callback and made
  artifact-local humor restrictions override the conversational permission.
- Bound required limitation sections to their affected claims or calculations.

### Validation

- `git diff --check` passed for the prompt, README, and changelog.
- The staged prompt kept the existing `# Using skills` section and everything
  after it byte-identical to `main`.
- Focused contract checks found the matching composition, structure,
  hypothetical-example, callback, synthesis, and limitation rules in the system
  prompt and Scribe.

## 2026-08-02: Fable-style explanatory depth

### Changed

- Made causal mechanisms, supported derived implications, concrete examples,
  and material boundaries part of a complete explanatory answer.
- Allowed short bold lead-ins, parallel lists, and closing syntheses when they
  expose or compress real argument structure.
- Replaced the direct-conversation em-dash ban with contextual punctuation
  guidance and let sentence rhythm follow the argument.
- Let dry humor grow out of the technical mechanism while preserving the hard
  shutoffs for frustration, production, money, security, personal data, and
  data loss.
- Preserved the boundary between direct conversation and requested artifacts;
  artifact voice still comes from the request, source, genre, and applicable
  skills.

### Validation

- The upstream `# Using skills` section remained byte-identical to the previous
  prompt at SHA-256
  `4cb96c7c117a1a94070816f0eb4a70b6907179cb3f3be80a1704b5b3c9ef4f24`.
- `git diff --check` passed for the prompt and README changes.
- The updated Scribe rules passed two fresh forward tests.
