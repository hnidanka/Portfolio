# Trello API Testing Collection (Postman)

## Overview
Postman collection for testing Trello REST API using workflow-based scenarios.

Covers authentication, boards, lists, cards, and checklists, including both positive and negative cases.

---

## Scope

**Positive scenarios:**
- authentication with valid credentials
- board creation, retrieval, and description update
- verification of updated board data
- retrieving board lists and validating board ownership
- list creation and verification that the list appears on the board
- retrieving a list by ID
- updating list position and verifying the new order
- creating a card with required parameters only
- creating a card with additional parameters
- verifying that the created card appears in the list
- validating card data such as name, description, due date, board ID, and list ID
- checklist creation and retrieval for a card
- validating relationships between board, list, card, and checklist
- archiving a list
- cleanup flow: deleting checklist, card, and board, then verifying resource removal

**Negative scenarios:**
- invalid API key / token → 401
- invalid board ID → 400
- invalid card/checklist-related IDs → 400
- access to deleted resource → 404
- invalid data types (e.g. boolean instead of string where string is expected)
- negative attempts to update/archive selected resources with incorrect input

---

## What is tested
- status codes
- JSON schema
- response data consistency
- relationships between board, list, card, and checklist
- resource lifecycle (create → update → delete → verify)
- API validation against incorrect input types

---

## Key Features
- dynamic test data (random values)
- collection variables (`boardId`, `listId`, `cardId`)
- chained requests (stateful testing)
- positive and negative testing

---

## Tech Stack
- Postman
- JavaScript (Postman scripts)
- Trello REST API
- 
---

## How to Run
1. Import collection to Postman  
2. Set variables: `url`, `apiKey`, `token`  
3. Run via Collection Runner
