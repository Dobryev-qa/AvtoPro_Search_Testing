# # AvtoPro – Search Functionality Testing

## Project Overview

This repository contains QA artifacts created as part of a **test assignment during a QA interview**.  
The goal was to analyze and test the **main search functionality** of the AvtoPro website.

---

## Application Under Test

- **Website:** https://avto.pro/
- **Test Object:** Main search functionality
- **Testing Date:** 15.12.2025

---

## Test Scope

The following search scenarios were analyzed and tested:
- Search by spare part name
- Search suggestions (autocomplete)
- Search by part code / article number
- Search by VIN
- Search by car brand and model
- Search with filters (brand, price)
- Search with typos
- Search with empty and invalid input
- Boundary testing (very long input)

---

## Test Artifacts

### 📘 User Stories
- [User Stories](./User_Stories.md)

### ☑️ Checklists
- [Positive Test Cases](./Checklist_Positive.md)
- [Negative Test Cases](./Checklist_Negative.md)

### 🐞 Bug Reports
- [Bug_001 – Search does not handle typos correctly](./Bug_Reports/Bug_001_Typo_Search.md)
- [Bug_002 – Search hangs on very long input (504 error)](./Bug_Reports/Bug_002_Long_Input_504.md)

---

## Testing Approach

During testing the following techniques were applied:
- Boundary Value Analysis
- Equivalence Partitioning
- Pairwise Testing (filters)
- Edge Case Testing

Browser DevTools were used to analyze network requests and server responses.  
During edge case testing, a server error (HTTP 504) was identified for very long search input.

