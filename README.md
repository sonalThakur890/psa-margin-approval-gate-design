# PSA Margin Approval Gate — design prototype

Interactive prototype for **FUL-10135** (margin approval gate) with **FUL-10045**
(provider vs customer contracted volume).

**Live:** https://sonalthakur890.github.io/psa-margin-approval-gate-design/

15 screens across the full lifecycle — the customer term sheet, the three build
screens, the queues, agreement details and schedules, the three approval buckets,
RFP / costing review, and threshold configuration.

| | Screen | What it adds |
|---|---|---|
| — | Overview & the rule | the gate and the deviation model |
| 0 | Customer term sheet | expected margin per property × service, on the Rates grid |
| 1a–1c | Draft template · Draft pricing · Ready for Negotiation | margin as it is set, plus **Compare to last season** |
| 2a | Queues | new approval tabs, margin and deviation filters |
| 2b | Active & Upcoming | expected and actual margin per agreement |
| 2c | Agreement details | expected visits, expected margin, actual to date, credits |
| 2d–2e | Schedules · Service schedule | per-visit invoice amounts and margin evidence |
| 3–5 | Awaiting Approval · Level 1 · Level 2 | the approval buckets and their blocks |
| 6 | RFP / costing review | per-line verdicts and the two return destinations |
| 7 | Threshold configuration | the levels and what they gate |

Rate change, alerts and post-signature margin drift are a separate prototype:
https://sonalthakur890.github.io/psa-rate-change-alerts-drift-design/

Behaviour is live, not static: row checkboxes drive every footer action and its
count, dialogs are built from the current selection and read the calling screen's
numbers, the margin and deviation filters compose, RFP verdicts re-split the two
return destinations, and the queue tab strip scrolls.

Not a visual design hand-off — this shows behaviour and information architecture.
