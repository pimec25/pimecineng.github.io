# PIMEC Root Cause Studio

Public static tool served at https://www.pimecineng.com/tools/root-cause/. The homepage links here and the tool links back to the homepage. No DNS or client-portal authentication changes are required.

Cases save only in the visitor’s browser under pimec.causeway.cases.v1. Nothing is submitted to a consultant inbox. Users can export/import JSON case backups, download HTML reports, and print/save PDF reports. Cases on the separately hosted Causeway app are not automatically migrated; export and import a backup to move them.

The rule-based engine proposes editable hypotheses; clients supply causal evidence and verify the cause. The tool does not call an AI provider or certify causality. Client approval is a recorded judgment, not an electronic signature.

Run node tests/root-cause-check.mjs from the repository root. The checks verify workflow gates, report escaping, persistence, closure rules, and status regressions. No build dependencies are required.
