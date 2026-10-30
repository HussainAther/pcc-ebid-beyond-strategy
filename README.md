# Beyond Strategy v8 - editorial readiness package

The v8 manuscript is 10 IEEEtran-formatted pages, including references. Its PDF Author metadata field is blank. This revision makes only the final editorial adjustments: references Table II, changes overstated 'frozen', 'exploitability', and 'strong' wording, identifies the historical workflow, and clarifies that the Leduc variant permits three bets/raises total per round.

The statistical test values, archived evidence, and research conclusions are unchanged from v7. No new experiments were run.

## Evidence inventory
- supplement/empirical_evidence_manifest.json: preserved archived evidence manifest with checksums
- supplement/measurement_overlap.json: measurement comparison
- supplement/predictions_frozen.json and supplement/transfer_results.csv: held-out results
- supplement/experiment_report.json: experiment report
- reproducibility/*.py: selected source modules, NOT a complete runnable environment

An obvious-identifier text scan found no personal paths, usernames, emails, or GitHub URLs in supplemental JSON/CSV/Python, but this does not guarantee all metadata or indirect identifiers are absent.

## Remaining research and submission checks
- This selection of files is not a complete replication archive for all four historical games. Complete repository, dependencies, seeds, raw histories, and dated threshold provenance remain incomplete in this package. Do not describe it as fully reproducible.
- Confirm target journal's current policies and whether a previously rejected manuscript may be submitted there again, or choose another venue.
- Verify author assurances and customize the separate cover-letter draft. The cover letter should not be included with anonymized reviewer files.
- Do not publish the supplement without a further comprehensive anonymity and license check.
