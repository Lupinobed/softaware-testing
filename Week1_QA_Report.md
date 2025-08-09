# CleanCity Waste Pickup Scheduler – QA Report (Week 1)

## Summary
- Initial functional and security testing for CleanCity app.
- Focus: Login, Registration, and Basic UI validation.

## Test Cases
| ID | Description | Status |
|----|-------------|--------|
| TC-001 | Login with demo user credentials | ❌ Fail |
| TC-002 | Register new user | ❌ Fail |
| TC-003 | Pickup request form validation (missing name) | ✅ Pass |

## Critical Issues
- No backend authentication implemented.
- Hardcoded demo credentials in HTML.
- Weak password policy.

## Recommendations
- Implement backend authentication.
- Remove hardcoded credentials.
- Enforce stronger password rules.
