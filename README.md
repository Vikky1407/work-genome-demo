# Work Genome

**The Autonomous Enterprise · tool 02 of 05**

When an expert leaves, or a process moves to another delivery centre, most of what they know leaves with them. Work Genome captures how the work is really done from task-mining data, checks what the expert says against what the logs show, and hands it over with evidence, in weeks.

**Try it:** https://vikky1407.github.io/work-genome-demo/

Download one demo file, upload it in the app, and follow the steps:

| Process | Demo file | Departing expert |
|---|---|---|
| AP invoice exceptions (procure to pay) | [AP-invoice-exceptions.xlsx](data/AP-invoice-exceptions.xlsx) | U01 |
| Month-end account reconciliations (record to report) | [Account-reconciliations.xlsx](data/Account-reconciliations.xlsx) | R21 |
| Customer deduction disputes (order to cash) | [Customer-deduction-disputes.xlsx](data/Customer-deduction-disputes.xlsx) | C11 |

**New: calibrate the ruler first.** One expert is a ruler of one: a consistent habit of theirs would look like the truth. The demo files now carry labels from a panel of four people, twice. Before the AI labeller is measured, Work Genome checks the panel itself:
- agreement within the panel;
- titles with no majority, set aside until they are settled;
- every person and the AI on one difficulty-adjusted ruler (a simple Rasch model);
- anyone who drifted between rounds (exact McNemar test).

Everything runs in your browser; no data is uploaded anywhere. Demo data is synthetic.

This repository holds the published demo only. © 2026 Vikas Choudhary. All rights reserved. See [LICENSE](LICENSE).
