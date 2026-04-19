# Labels — Violation Tracking

## Severity Labels

| Label | Color | Definition |
|-------|-------|------------|
| `severity:high` | Red | Safety failures, attachment creation, authority replacement, mature theme engagement |
| `severity:medium` | Yellow | Answer-giving, authority undermining without replacement, gaslighting without apology |
| `severity:low` | Blue | Minor infractions, boundary-adjacent but not clearly violating |

## Status Labels

| Label | Color | Definition |
|-------|-------|------------|
| `status:open` | Gray | Reported. Awaiting investigation. |
| `status:confirmed` | Orange | Investigated. Violation confirmed. Fix in progress. |
| `status:fixed` | Green | Fix implemented. Awaiting verification or closure. |
| `status:closed` | Dark Green | Verified as resolved. Permanent record. |
| `status:invalid` | Purple | Investigated. Not a violation per rubric. Explanation provided. |
| `status:duplicate` | Silver | Duplicate of existing issue. Link provided. |
| `status:needs-info` | Pink | Incomplete report. Awaiting more information from reporter. |

## Response Time Labels

| Label | Color | When Applied |
|-------|-------|--------------|
| `response:acknowledged` | Light Blue | Within severity commitment window |
| `response:late` | Red | Acknowledgment or fix missed commitment window |

## How to Apply Labels

Maintainers assign labels when:
1. A new issue is opened (severity + status:open)
2. Investigation begins (status:needs-info or status:confirmed)
3. Fix is deployed (status:fixed)
4. Issue is closed (status:closed)
5. Issue is invalid (status:invalid + explanation comment)

## No Label Deletion Without Replacement

Labels track state changes. Do not delete a label without adding the next state label.
