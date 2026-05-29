# Audit Finding — Privileged Access Review

## Finding Title

Excessive Privileged Access Retained Without Periodic Review

---

## Condition

During testing, a user account retained Domain Administrator privileges despite no longer requiring elevated access.

Sample testing identified that David Brown continued to hold Domain Administrator privileges two years after completing a special infrastructure project.

---

## Criteria

Company policy requires privileged accounts to be reviewed quarterly and restricted to personnel with a current business need.

---

## Cause

Periodic privileged access reviews were not performed.

Management had no documented process to recertify privileged access assignments.

---

## Effect

Users may retain excessive privileges beyond their job requirements.

Potential risks include:

- Unauthorized system changes
- Data loss
- Privilege abuse
- Security control circumvention
- Compliance violations

---

## Recommendation

Implement a formal privileged access review process.

Require quarterly recertification of privileged accounts by system owners and management.

Remove unnecessary administrative privileges promptly.

---

## Risk Rating

High
