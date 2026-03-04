# Test Coverage — vrater

**Owner:** <!-- team or individual responsible -->  
**Repository / Module:** <!-- link or path to vrater source -->  
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

### Rating Engine

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Validate basic rate calculation for standard plan | Unit | ✅ / ❌ / ⚠️ | |
| 2 | Validate rate calculation with discount applied | Unit | ✅ / ❌ / ⚠️ | |
| 3 | Rate lookup returns correct tier for given usage | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Invalid input returns appropriate error response | Unit | ✅ / ❌ / ⚠️ | |

### Rate Plan Management

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Create a new rate plan successfully | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Update an existing rate plan | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Delete a rate plan | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Fetch rate plan by ID | Unit | ✅ / ❌ / ⚠️ | |

### API Endpoints

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | GET /rate — returns correct rate for valid request | E2E | ✅ / ❌ / ⚠️ | |
| 2 | POST /rate-plan — creates rate plan | E2E | ✅ / ❌ / ⚠️ | |
| 3 | Unauthorized request returns 401 | E2E | ✅ / ❌ / ⚠️ | |

---

## Edge Cases & Negative Scenarios

| # | Scenario | Status | Notes |
|---|----------|--------|-------|
| 1 | Zero usage amount in rating request | ✅ / ❌ / ⚠️ | |
| 2 | Negative usage value | ✅ / ❌ / ⚠️ | |
| 3 | Rate plan with missing required fields | ✅ / ❌ / ⚠️ | |
| 4 | Concurrent rate requests for the same plan | ✅ / ❌ / ⚠️ | |

---

## Known Gaps

- <!-- List any known test coverage gaps for vrater -->

## References

- <!-- Links to vrater test files, test plans, or related tickets -->
