# PSA Margin Approval Gate — design prototype

Interactive prototype for **FUL-10135** (margin approval gate) with **FUL-10045**
(provider vs customer contracted volume).

**Live:** https://sonalthakur890.github.io/psa-margin-approval-gate-design/

14 screens across the agreement lifecycle — Draft, Ready for Negotiation, the three
approval buckets (Awaiting Approval, Level 1, Level 2), RFP / costing review, rate
change, threshold configuration, alerts, and post-signature margin drift.

Behaviour is live, not static: row checkboxes drive every footer action and its count,
dialogs are built from the current selection, RFP verdicts re-split the two return
destinations, and the queue tab strip scrolls.

Not a visual design hand-off — this shows behaviour and information architecture.
