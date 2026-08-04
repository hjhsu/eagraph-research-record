# Incident and design-change register

| Incident | Detected | Scope | Disposition |
|---|---|---|---|
| Base-template contamination in one additional Haiku world | Post-run audit | Three sessions from that world | Excluded the entire world from every analysis and figure; seven retained worlds renumbered 1--7 only for publication. |
| File timestamps could reveal changed artifacts | Harness development | Earlier pilot revisions | Normalized timestamps before the retained rounds; timestamp procedure still differed across four cross-model worlds, so only three are fully aligned for that factor. |
| Version-control history could reveal the previous drop | Harness development | Early testbed design | Delivered the reference as an unversioned directory and prohibited repository history in the session workspace. |
| Shared scratch state could transmit information across conditions | Sonnet-round audit | Three retained sessions reported seeing and ignoring other sessions' intermediate scripts or diffs | No ground truth leaked, but session independence was compromised and is disclosed as a validity threat. |
| Python bytecode/cache retained pre-drift reference behavior | Final audit | Retained workspaces; two controls used it | The older state produced the lower scores predicted by that state, so this is a protocol defect that depresses those controls rather than an answer oracle. It remains disclosed rather than treated as repaired data. |
| Task wording originally allowed file-level status interpretation | Harness development | Earlier rounds | Required exactly one status classification per behavior and made behavior-level F1 the primary outcome. |
| Evaluator feedback could turn the episode into iterative test repair | Testbed design | All retained rounds | Acceptance suite remained outside the workspace and no score was returned during a session. |
| One Haiku ANCHOR repair destroyed the executable port despite perfect status classification | Result audit | One retained session | Preserved the session; reported repair completion as secondary and separated it from epistemic classification. |
| Exact Haiku test form selected after observations | Analysis audit | Two confirmatory-direction contrasts | Retained exact p-values but explicitly labels the test form post hoc. |
| Undated Sonnet model alias | Model identity audit | 21 Sonnet sessions | Reports both `claude-sonnet-5` and dispatch date 2026-08-01; acknowledges future alias-resolution risk. |

This register is disclosure-safe. Private incident evidence, session archives,
and source identifiers remain in the controlled study archive and are tracked
by hashes rather than copied here.
