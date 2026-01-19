# Checklist – Main Search (Negative Scenarios)

| ID | Test Scenario | Expected Result | Status |
|----|---------------|-----------------|--------|
| N01 | Search for non-existing spare part | “No results found” message is displayed | Passed |
| N02 | Search with typo in spare part name | Relevant result is displayed | Failed |
| N03 | Search with empty input field | Search is not executed | Passed |
| N04 | Search with whitespace only | Search is not executed | Passed |
| N05 | Search with special characters | No errors, search handled correctly | Passed |
| N06 | Search with single character | No errors occur | Passed |
| N07 | Search with mixed languages (Ukrainian + Russian) | Search handles query correctly | Passed |
| N08 | Search with very long input (1000 characters) | No system errors occur | Failed |
