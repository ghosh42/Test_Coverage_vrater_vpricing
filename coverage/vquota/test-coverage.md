# Test Coverage — vquota

**Owner:** <!-- team or individual responsible -->  
**Repository / Module:** <!-- link or path to vquota source -->  
**Last Updated:** <!-- YYYY-MM-DD -->

---

## Summary

| Metric | Value |
|--------|-------|
| Total Test Cases | — |
| ✅ Covered | — |
| ❌ Not Covered | — |
| ⚠️ Partially Covered | — |
| Coverage % | — |

---

## Test Cases

### Quota Allocation

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Allocate quota to a new account | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Update quota limit for an existing account | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Revoke quota from an account | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Fetch current quota for a given account | Unit | ✅ / ❌ / ⚠️ | |

### Quota Enforcement

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Request is allowed when quota is available | Unit | ✅ / ❌ / ⚠️ | |
| 2 | Request is rejected when quota is exhausted | Unit | ✅ / ❌ / ⚠️ | |
| 3 | Quota resets on schedule (e.g., monthly) | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Quota reset notification is sent | Integration | ✅ / ❌ / ⚠️ | |

### API Endpoints

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | GET /quota/:accountId — returns quota details | E2E | ✅ / ❌ / ⚠️ | |
| 2 | POST /quota — allocates quota | E2E | ✅ / ❌ / ⚠️ | |
| 3 | PUT /quota/:accountId — updates quota | E2E | ✅ / ❌ / ⚠️ | |
| 4 | Unauthorized request returns 401 | E2E | ✅ / ❌ / ⚠️ | |

---

## Edge Cases & Negative Scenarios

| # | Scenario | Status | Notes |
|---|----------|--------|-------|
| 1 | Quota check for unknown account | ✅ / ❌ / ⚠️ | |
| 2 | Setting quota to zero | ✅ / ❌ / ⚠️ | |
| 3 | Concurrent quota updates for the same account | ✅ / ❌ / ⚠️ | |
| 4 | Quota reset while request is in-flight | ✅ / ❌ / ⚠️ | |

---

## Known Gaps

- <!-- List any known test coverage gaps for vquota -->

## References

- <!-- Links to vquota test files, test plans, or related tickets -->
