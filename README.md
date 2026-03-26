# Test Coverage — vrater / vpricing / vquota / vusage / vbilling

This repository maintains test coverage records for the following services:

| Service | Coverage File |
|---------|--------------|
| vrater | [coverage/vrater/test-coverage.md](coverage/vrater/test-coverage.md) |
| vpricing | [coverage/vpricing/test-coverage.md](coverage/vpricing/test-coverage.md) |
| vquota | [coverage/vquota/test-coverage.md](coverage/vquota/test-coverage.md) |
| vusage | [coverage/vusage/test-coverage.md](coverage/vusage/test-coverage.md) |
| vbilling | [coverage/vbilling/test-coverage.md](coverage/vbilling/test-coverage.md) |

## Repository Structure

```
.
├── README.md                          # This file — project overview & index
├── COVERAGE_SUMMARY.md                # Aggregated coverage summary across all services
├── templates/
│   └── test-coverage-template.md     # Reusable template for adding new services
└── coverage/
    ├── vrater/
    │   └── test-coverage.md
    ├── vpricing/
    │   └── test-coverage.md
    ├── vquota/
    │   └── test-coverage.md
    ├── vusage/
    │   └── test-coverage.md
    └── vbilling/
        └── test-coverage.md
```

## How to Use

1. **Add / update test cases** — edit the relevant `coverage/<service>/test-coverage.md` file.
2. **Track overall health** — see [COVERAGE_SUMMARY.md](COVERAGE_SUMMARY.md) for the aggregated view.
3. **Onboard a new service** — copy `templates/test-coverage-template.md` into a new `coverage/<service>/` folder and fill in the details.

## Coverage Status Legend

| Symbol | Meaning |
|--------|---------|
| ✅ | Covered |
| ❌ | Not Covered |
| ⚠️ | Partially Covered |
| 🚧 | Work In Progress |
