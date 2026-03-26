# Test Coverage — vpricing

**Owner:** <!-- team or individual responsible -->  
**Repository / Module:** <!-- link or path to vpricing source -->  
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

### Price Catalogue Management

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Create a new price catalogue entry | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Update price for an existing catalogue entry | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Delete a price catalogue entry | Integration | ✅ / ❌ / ⚠️ | |
| 4 | List all price catalogue entries | Unit | ✅ / ❌ / ⚠️ | |

### Pricing Rules

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Apply flat-rate pricing rule correctly | Unit | ✅ / ❌ / ⚠️ | |
| 2 | Apply tiered pricing rule correctly | Unit | ✅ / ❌ / ⚠️ | |
| 3 | Apply volume-based pricing rule correctly | Unit | ✅ / ❌ / ⚠️ | |
| 4 | Pricing rule precedence is respected | Unit | ✅ / ❌ / ⚠️ | |

### API Endpoints

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | GET /price — returns correct price for valid product | E2E | ✅ / ❌ / ⚠️ | |
| 2 | POST /price-catalogue — creates entry | E2E | ✅ / ❌ / ⚠️ | |
| 3 | PUT /price-catalogue/:id — updates entry | E2E | ✅ / ❌ / ⚠️ | |
| 4 | Unauthorized request returns 401 | E2E | ✅ / ❌ / ⚠️ | |

---

## Edge Cases & Negative Scenarios

| # | Scenario | Status | Notes |
|---|----------|--------|-------|
| 1 | Price lookup for non-existent product | ✅ / ❌ / ⚠️ | |
| 2 | Zero or negative price value | ✅ / ❌ / ⚠️ | |
| 3 | Overlapping pricing rules for the same product | ✅ / ❌ / ⚠️ | |
| 4 | Currency conversion edge cases | ✅ / ❌ / ⚠️ | |

---

## Known Gaps

- <!-- List any known test coverage gaps for vpricing -->

## References

- <!-- Links to vpricing test files, test plans, or related tickets -->
