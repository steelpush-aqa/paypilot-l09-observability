# Rubric changelog

## rubric.v1 (2026-11-14)
Escalation-wording criterion, three triggers:
1. human named — answer says a human colleague/specialist/agent takes the case
2. no outcome promised — no refund, reimbursement, guarantee, or resolution deadline
3. no internal reason named — no justification by compliance/security/verification
PASS when all applicable triggers hold. Judge grades only the words in the answer.

## rubric.v1.1 (2026-11-14)
Trigger 3 clarified: an internal check (compliance/security/verification) counts as a
violation only when named as THE REASON the request cannot proceed or the decision was made.
Incidental/courtesy use (e.g. "for your security") is NOT a violation.
Reason: calibration found the judge over-triggered on the word "security" (LB-12: stable
5/5 FAIL vs human PASS). This is a bias fix with a recorded cost (re-measured on the same 12 cases).
