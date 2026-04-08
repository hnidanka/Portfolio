# Test Checklist - Trello API Training

Legend:
- ⬜ Not Executed
- 🟢 Pass
- 🔴 Fail
- 🟡 Blocked

---

## 🔐 Authentication

| Test Scenario | Status | Comments |
|---|---|---|
| Verify authorization with valid API key and token | 🟢 | |
| Verify authorization fails with invalid API key | 🟢 | |
| Verify authorization fails with invalid token | 🟢 | |
| Verify authorization fails when API key is missing | ⬜ | |
| Verify authorization fails when token is missing | ⬜ | |

---

## 📌 Board Management

### Create

| Test Scenario | Status | Comments |
|---|---|---|
| Verify board can be created with valid name | 🟢 | |
| Verify board cannot be created with empty name | 🟢 | |
| Verify board cannot be created with wrong name value type | 🟢 | |
| Verify board cannot be created with missing name parametr | 🟢 | |
| Verify board creation with very long name | ⬜ | |
| Verify board creation with special characters | ⬜ | |

### Read

| Test Scenario | Status | Comments |
|---|---|---|
| Verify board retrieval by valid ID | 🟢 | |
| Verify error for invalid board ID | 🟢 | |
| Verify error for missing board ID | ⬜ | |

### Update

| Test Scenario | Status | Comments |
|---|---|---|
| Verify board description update | 🟢 | |
| Verify board update on non-existing board | 🟢 | |
| Verify board update with missing board ID | 🟢 | |
| Verify board update with description wrong value type  | 🟢 | |

### Delete

| Test Scenario | Status | Comments |
|---|---|---|
| Verify board deletion | 🟢 | |
| Verify deleted board is not accessible | 🟢 | |
| Verify deleting non-existing board | 🟢 | | 
| Verify board deleting with missing board ID | 🟢 | | 

---

## 📋 List Management

### Create

| Test Scenario | Status | Comments |
|---|---|---|
| Verify list creation on existing board | 🟢 | |
| Verify list creation with missing board ID and name | 🟢 | |
| Verify list creation with missing board ID | 🟢 | |
| Verify list creation on non-existing board | ⬜ | |
| Verify list creation with missing board name parameter | 🟢 | |
| Verify list creation with empty name value type | 🟢 | |
| Verify list creation with empty name | ⬜ | |

### Read

| Test Scenario | Status | Comments |
|---|---|---|
| Verify lists retrieval for valid board | 🟢 | |
| Verify error for non-existing board ID | 🟢 | |
| Verify error with missing board ID | ⬜ | |


### Update

| Test Scenario | Status | Comments |
|---|---|---|
| Verify list position update | 🟢 | |
| Verify invalid position handling | ⬜ | |
| Verify update on non-existing list | ⬜ | |
| Verify list update with missing list ID | 🟢 | |

### Archive

| Test Scenario | Status | Comments |
|---|---|---|
| Verify list archiving | 🟢 | |
| Verify archived list is inactive | 🟢 | |
| Verify archiving non-existing list | 🟢 | |

---

## 🧾 Card Management

### Create

| Test Scenario | Status | Comments |
|---|---|---|
| Verify card creation with required parameters | 🟢 | |
| Verify card creation with optional parameters | 🟢 | |
| Verify card creation without list ID | ⬜ | |
| Verify card creation with non-existing list ID| 🟢 | |
| Verify card creation with wrong list ID value type| 🟢 | |
| Verify card creation with empty name | ⬜ | |
| Verify card creation with invalid name value type | 🟢 | |
| Verify boundary values of due date format | 🔴 | |


### Read

| Test Scenario | Status | Comments |
|---|---|---|
| Verify cards retrieval for valid list | 🟢 | |
| Verify cards retrieval error for invalid list | ⬜ | |
| Verify card retrieval by valid ID | 🟢 | |
| Verify card retrieval by invalid ID | 🟢 | |


### Update

| Test Scenario | Status | Comments |
|---|---|---|
| Verify card name update | 🟢 | |
| Verify update on non-existing card | 🟢 | |
| Verify update with empty name | ⬜ | |
| Verify update with wrong name value type | ⬜ | |

### Delete

| Test Scenario | Status | Comments |
|---|---|---|
| Verify card deletion | 🟢 | |
| Verify deleted card is not accessible | 🟢 | |
| Verify deleting non-existing card | 🟢 | |
| Verify deleting card with missing card ID | 🟢 | |

---

## ☑️ Checklist Management

### Create

| Test Scenario | Status | Comments |
|---|---|---|
| Verify checklist creation on existing card | 🟢 | |
| Verify checklist creation with missing card ID | 🟢 | |
| Verify checklist creation on non-existing card | 🟢 | |

### Read

| Test Scenario | Status | Comments |
|---|---|---|
| Verify checklists retrieval for valid card | 🟢 | |
| Verify checklists retrieval error for non-existing card | ⬜ | |
| Verify checklists retrieval for valid checklists ID | 🟢 | |
| Verify error for non-existing checklist | 🟢 | |


### Delete

| Test Scenario | Status | Comments |
|---|---|---|
| Verify checklist deletion | 🟢 | |
| Verify deleted checklist is not accessible | 🟢 | |
| Verify deleting non-existing checklist | 🟢 | |