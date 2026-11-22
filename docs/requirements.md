# SignalCheck Phase 1: requirements and acceptance criteria

| ID | Requirement | Acceptance criterion | Risk | How checked |
| --- | --- | --- | --- | --- |
| R1 | Use only public openFDA reports for product code GAM in the stated window | 100% of rows carry product code GAM | Medium | Notebook check G |
| R2 | Download every report openFDA holds for the query | Rows = openFDA total = sum of monthly totals | High | Notebook check G |
| R3 | Save each pull with its date and exact queries | Dated data file and pull log exist | High | Notebook check G |
| R4 | Count each report once | 0 duplicate report keys | High | Notebook check G |
| R5 | Monthly counts add up to the total | Sum of months = total rows | Medium | Notebook check G |
| R6 | p-chart center line and limits follow the standard formulas | Hand calculation for 2 months matches within 0.001 | High | Hand check |
| R7 | Run rules flag: beyond limits, 8 in a row on one side, 6 in a row rising or falling | Flags exactly the planted points in a known test series | High | Notebook check G |
| R8 | PRR uses the standard 2 x 2 formula; signal = PRR at least 2, chi-square at least 4, at least 3 reports | Matches a hand-worked example (PRR = 20.00) | High | Notebook check G |
| R9 | Every chart says counts are reports, not failure rates | Footnote on every chart | Medium | Visual check |
| R10 | The tool flags; a person decides | Every flag has reviewer, date, decision, and reasoning | High | Review log check |

Acceptance criteria were written on [22 November 2026], before any analysis was run.
