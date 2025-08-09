# CleanCity Waste Pickup Scheduler – QA Report (Week 2)

## Summary
- Security-focused testing.
- Tested admin access, date validation, and local storage security.

## Test Cases
| ID | Description | Status |
|----|-------------|--------|
| TC-004 | Pickup request date validation (past date) | ❌ Fail |
| TC-005 | Toggle mobile menu responsiveness | ⚠️ Needs Retest |
| TC-006 | Reveal admin link via DevTools | ❌ Fail |
| TC-007 | Inspect local storage for credentials | ✅ Pass |

## Critical Issues
- Admin link can be revealed and accessed.
- Pickup form accepts past dates.

## Recommendations
- Validate dates server-side and client-side.
- Implement server-side role checks for admin access.
