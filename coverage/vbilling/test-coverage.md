# Test Coverage — vbilling

**Owner:** <!-- team or individual responsible -->  
**Repository / Module:** <!-- link or path to vbilling source -->  
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

### Invoice Generation

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Generate invoice for a standard billing cycle | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Invoice includes all line items from vusage | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Invoice applies correct prices from vpricing | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Invoice applies discounts and credits correctly | Unit | ✅ / ❌ / ⚠️ | |
| 5 | Invoice PDF is generated and stored | Integration | ✅ / ❌ / ⚠️ | |

### Payment Processing

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Process a successful payment | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Handle payment failure gracefully | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Retry failed payment according to retry policy | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Refund an invoice | Integration | ✅ / ❌ / ⚠️ | |

### Billing Account Management

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | Create a new billing account | Integration | ✅ / ❌ / ⚠️ | |
| 2 | Update billing account details | Integration | ✅ / ❌ / ⚠️ | |
| 3 | Close / deactivate a billing account | Integration | ✅ / ❌ / ⚠️ | |
| 4 | Fetch billing history for an account | Unit | ✅ / ❌ / ⚠️ | |

### API Endpoints

| # | Test Case Description | Type | Status | Notes |
|---|-----------------------|------|--------|-------|
| 1 | POST /invoice — triggers invoice generation | E2E | ✅ / ❌ / ⚠️ | |
| 2 | GET /invoice/:id — fetches invoice details | E2E | ✅ / ❌ / ⚠️ | |
| 3 | POST /payment — processes a payment | E2E | ✅ / ❌ / ⚠️ | |
| 4 | Unauthorized request returns 401 | E2E | ✅ / ❌ / ⚠️ | |

---

## Edge Cases & Negative Scenarios

| # | Scenario | Status | Notes |
|---|----------|--------|-------|
| 1 | Invoice with zero total amount | ✅ / ❌ / ⚠️ | |
| 2 | Payment gateway timeout | ✅ / ❌ / ⚠️ | |
| 3 | Billing period with no usage events | ✅ / ❌ / ⚠️ | |
| 4 | Duplicate invoice generation for the same period | ✅ / ❌ / ⚠️ | |
| 5 | Invoice generated with late usage data | ✅ / ❌ / ⚠️ | |

---

## Known Gaps

- <!-- List any known test coverage gaps for vbilling -->

## References

- <!-- Links to vbilling test files, test plans, or related tickets -->
