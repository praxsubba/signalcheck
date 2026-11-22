# SignalCheck: intended use

## Purpose
SignalCheck helps a quality reviewer spot unusual changes in public FDA device
reports (MAUDE) for one product family. It counts reports by month, charts the
share of each failure type, flags patterns with standard control chart rules,
and runs a standard disproportionality test (PRR).

## Users
A quality or post-market reviewer who decides what each flag means.

## Data
Public openFDA device adverse event data only. Phase 1 covers product code GAM
(absorbable synthetic PGA suture), reports received October 1, 2021 to
September 30, 2026.

## Out of scope
- Deciding whether an event must be reported to FDA
- Opening or closing investigations, CAPAs, or complaints
- Any product quality or release decision
- Estimating failure rates (report counts are not rates)

## Human oversight
The tool flags; a person decides. Every flag is reviewed and the decision is
recorded with the reviewer's name, the date, and the reasoning.
