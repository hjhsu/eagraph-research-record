# Artifact disposition manifest

| Artifact class | Public representation | Restricted source |
|---|---|---|
| Paper and figures | Overleaf/arXiv source package | Draft history before author review |
| Testbed construction | Design, contracts, schemas, abstract layout | Executable oracle, study seeds, generated contents |
| Outcome analysis | Seven paper-world aggregate F1 values and exact-test code | Behavior-level truth and evaluator outputs |
| Preregistrations | Disclosure-safe records in `records/` | Frozen originals with private generator identifiers |
| Determinations | Disclosure-safe result records and incident register | Full session-level diagnostic reports |
| Generated worlds | Count and public labels only | Reference drops, ports, acceptance suites, ground truth |
| Practitioner case | Problem-level summary in the paper | Raw files and third-party/project-specific detail |
| Agent execution | Model IDs, dispatch date, aggregate design | Workspaces, transcripts, provider-side records |
| Access control | Public policy and blank request template | Requester identities, approvals, canary assignments |

`source_hashes.sha256` binds selected frozen internal records to this public
history without disclosing their contents. Low-entropy private metadata, such
as the source-to-paper world mapping, is deliberately not hashed publicly: a
public digest could otherwise confirm a guessed mapping. The hash file must be
regenerated immediately before an immutable release and checked after any
intentional source correction.
