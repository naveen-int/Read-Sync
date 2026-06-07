# Read-Sync

## Project Title

Smart Library Management & Book Recommendation System

## Project Overview

Smart Library Management & Book Recommendation System is a web-based application that recommends books based on user interests and preferences. It also includes basic library management features such as displaying popular books, and managing book issue and return activities.

---

## Problem Statement

Library users often struggle to find books that match their interests, preferences, and reading requirements. At the same time, managing book issue and return records can become challenging. This can reduce the efficiency of library services and the overall user experience.

---

## Objectives

- Smart library management processes.
- Manage books, users, and transactions efficiently.
- Track book issue and return activities.
- Provide personalized book recommendations.
- Improve user experience and library efficiency.

---

## Features
- User Login & Registration
- Personalized Book Recommendations
- Display Popular Books
- Book Issue Management
- Book Return Management

---

## Modules & Workflow

```text
Home Page
│
├── User Module
│   ├── Login / Register
│   ├── Enter Book Preferences
│   ├── View Recommended Books
│   └── View Available & Popular Books
│
└── Library Module
    ├── Login / Register
    ├── View Available Books
    ├── Add Issue Record
    ├── View Active Records
    └── Delete Returned Records
```
---

## Database Requirement Analysis

### Database Tables

#### Users

| Field Name | Data Type |
|------------|------------|
| user_id | INT |
| name | VARCHAR(100) |
| email | VARCHAR(100) |
| password | VARCHAR(100) |
| role | VARCHAR(20) |

#### Books

| Field Name | Data Type |
|------------|------------|
| book_id | INT |
| book_name | VARCHAR(200) |
| genre | VARCHAR(50) |
| category | VARCHAR(50) |
| author_type | VARCHAR(20) |
| language | VARCHAR(20) |
| rating | VARCHAR(20) |
| availability | VARCHAR(20) |

#### Issue Records

| Field Name | Data Type |
|------------|------------|
| record_id | INT |
| user_no | VARCHAR(20) |
| book_id | INT |
| book_name | VARCHAR(200) |
| due_date | DATE |

---
