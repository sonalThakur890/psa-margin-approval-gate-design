# Margin guidance and gate — design prototype

Interactive prototype for epic **FUL-11893** (stories FUL-11894 to FUL-11899). It matches
the screens pack sent to business on 23 Nov 2026 (PSA_Margin_Screens_V1_doc).

**Live:** https://sonalthakur890.github.io/psa-margin-approval-gate-design/

| | Screen | What it shows |
|---|---|---|
| — | Overview & the rule | the routing rule, and where each ticket shows |
| 1a | Draft — template | over-servicing check against the customer term sheet, reason required |
| 1b | Draft — pricing | property margin at both ends of the price range |
| 1c | Ready for Negotiation | one margin per property, the approval it needs, Recalculate |
| 2a | Queue | Awaiting Level 1, Level 2 and RFP Review tabs |
| 3 · 4 | Level 1 · Level 2 | approve, Send back (reason + comment), Move to Level 2, RFP review |
| 5 | RFP review | verdict returned to Level 2 |
| 6 · 6b | No approval · Healthy site | straight to signature; one losing line on a healthy site |
| 7 | Thresholds | Level 1 and Level 2 limits per trade, change log |

On every PSA: a comment icon (people talk it through) and an Activity log icon beside the
PSA number (read-only record of everything done, with who and when).

Behaviour is live: selections drive the footer actions, Send back posts its comment to the
PSA's comments and the Activity log, and comments appear in the log.

The previous version is kept in `archive/`.
