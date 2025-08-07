# Final QA Report - CleanCity Web Application

## Executive Summary
The QA team conducted comprehensive manual testing for CleanCity. Major bugs were identified in the dashboard filtering, form validation, and password security. Many functional areas worked as expected. Recommendations are given for improvements.

## Strategy Recap
Manual testing was used to validate user flows. Tests were based on `functional-requirements.md`. Jira was used for issue tracking.

## Findings
- Total test cases: 3
- Passed: 1
- Failed: 2

## Bugs
- BUG-001: Location filter incorrect
- BUG-002: Passwords not encrypted
- BUG-003: Missing validation on feedback form

## Recommendations
- Add secure hashing to passwords
- Improve UI filter logic
- Enforce strict validation rules on all forms

## Risk Assessment
- Unfixed password storage may expose user data
- Filtering bugs may mislead admin actions

## Conclusion
With the identified fixes implemented, CleanCity can be significantly improved in terms of user trust and data reliability.
