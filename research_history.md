# Research history

## 1. Practitioner problem and method hypothesis

The project began from a migration case in which file-level change tracking
could not distinguish still-supported verification claims from claims whose
specific supporting data had drifted. The method hypothesis became an external
verification memory with artifact sub-path identity, explicit evidence, and
freshness tracked independently.

The practitioner materials motivate the problem but are not experimental data.
Raw case materials remain private because they contain project-specific and
third-party information.

## 2. Generated testbed

An existing repository could not provide complete behavior-level ground truth,
controlled withholding, multiple matched instances, or protection against
training-data recall. The study therefore generated a Python reference, a
TypeScript port, and a held-out acceptance suite from one intermediate
specification.

Successive harness revisions closed shortcuts found during development,
including history exposure, timestamp signals, scoring feedback, and ambiguity
in the requested reporting granularity. Shared scratch state and stale bytecode
were also identified; because they remained present in retained sessions, they
are validity threats rather than closed pilot issues. All are recorded in
`incident_register.md`.

## 3. Smaller-model round

The final smaller-model round used
`claude-haiku-4-5-20251001`, dispatched on 2026-08-01. The analysis retained
seven clean worlds and three memory conditions per world, for 21 sessions.

The hypothesis direction and `F1_notOK` outcome were frozen before dispatch.
The exact paired Wilcoxon form was selected after the runs and must therefore
be described as post hoc. ANCHOR exceeded both PROSE and NONE in all seven
worlds; each two-sided exact p-value was 0.015625. PROSE and NONE were not
detectably different.

One additional world was excluded in full after discovering base-template
contamination. No session from it appears in the paper's analyzed population.

## 4. Larger-model round

The larger-model round used the provider identifier `claude-sonnet-5`, also
dispatched on 2026-08-01, over the same seven paper worlds and three conditions,
for 21 sessions. The identifier has no date suffix, so the dispatch date is
required metadata and exact future resolution of that alias is a reproducibility
threat.

Its within-round hypotheses and exact paired test were preregistered. ANCHOR
scored 1.000 in every world, but control ceilings left only four and three
non-tied pairs. The preregistered contrasts were not supported (p=0.125 and
p=0.250).

## 5. Claim revision

The direct claim is model- and testbed-bounded: artifact-anchored verification
memory improved smaller-model provability judgment over prose and no persistent
memory in these seven generated worlds.

The cross-model observation is exploratory. Smaller-model ANCHOR scores were
descriptively close to larger-model conditions, while smaller-model controls
were not. This motivates the hypothesis that structured verification memory
may narrow an observed capability gap by externalizing re-derivation. The study
does not establish model equivalence or substitution.

## 6. Publication architecture

The project is reported as one paper. This separate record preserves the study
history so readers can inspect decisions and anomalies without forcing the
main narrative to reproduce every development episode. Testbed structure and
aggregate analysis are public; worlds and hidden answers are request-only; raw
practitioner-case materials are not released by default.
