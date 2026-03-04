# Test Coverage — vusage

**Owner:** <!-- team or individual responsible -->  
**Repository / Module:** <!-- link or path to vusage source -->  
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

### Usage Ingestion

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Ingest valid usage event successfully | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Reject usage event with missing required fields | Unit | ✅ / ❌ / ⚠️ | |
| 3 | Deduplicate duplicate usage events | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Batch ingestion of multiple usage events | Integration | ✅ / ❌ / ⚠️ | |

### Usage Aggregation

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Aggregate daily usage for an account | Unit | ✅ / ❌ / ⚠️ | |
| 2 | Aggregate monthly usage for an account | Unit | ✅ / ❌ / ⚠️ | |
| 3 | Aggregate usage by resource type | Unit | ✅ / ❌ / ⚠️ | |
| 4 | Usage aggregation handles timezone correctly | Unit | ✅ / ❌ / ⚠️ | |

### Usage Reporting

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Generate usage report for a billing period | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Export usage data in CSV format | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Usage report is accurate after late-arriving events | Integration | ✅ / ❌ / ⚠️ | |

### API Endpoints

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | POST /usage — ingests a usage event | E2E | ✅ / ❌ / ⚠️ | |
| 2 | GET /usage/:accountId — returns usage summary | E2E | ✅ / ❌ / ⚠️ | |
| 3 | Unauthorized request returns 401 | E2E | ✅ / ❌ / ⚠️ | |

---

## Edge Cases & Negative Scenarios

| # | Scenario | Status | Notes |
|---|----------|--------|-------|
| 1 | Usage event with future timestamp | ✅ / ❌ / ⚠️ | |
| 2 | Usage event with very large quantity value | ✅ / ❌ / ⚠️ | |
| 3 | Usage query for account with no events | ✅ / ❌ / ⚠️ | |
| 4 | Late-arriving usage event after billing period closed | ✅ / ❌ / ⚠️ | |

---

## Known Gaps

- <!-- List any known test coverage gaps for vusage -->

## References

- <!-- Links to vusage test files, test plans, or related tickets -->
