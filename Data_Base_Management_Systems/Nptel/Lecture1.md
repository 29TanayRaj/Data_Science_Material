# Lecture-1

## Course Overview
- **Total Modules**: 40
- **Duration per Module**: ~30 minutes
- **Lecture Goals**:
  - Discuss the importance of database management systems (DBMS).
  - Familiarize with course prerequisites, outline, textbook, and TAs.

---

## Why Do We Need Databases?

### Definition of DBMS
- A DBMS contains information about an enterprise.
- It deals with:
  - **Collection of interrelated data.**
  - **Set of programs** for data access and manipulation.
  - Provides an environment for **convenient and efficient** data usage.

### Applications of Databases
1. **Banking**:
   - Net banking for retail and corporate transactions.
2. **Reservation Systems**:
   - Railway, airline, and hotel reservations.
3. **University Systems**:
   - Managing students, courses, enrollments, and examinations.
4. **E-commerce**:
   - Platforms like Amazon, Flipkart for ordering, payments, and delivery tracking.
5. **Manufacturing**:
   - Inventory management and supply chain systems.
6. **Human Resources**:
   - Platforms like LinkedIn for recruitment and management.
7. **Social Media**:
   - Massive databases for user interactions and data storage.

### Key Characteristics
- **Large Scale Data**:
  - Small data can be managed with spreadsheets.
  - Beyond a threshold, DBMS is required.
- **Ubiquity**:
  - Databases are integral to all aspects of modern life.

---

## Transition from File Systems to Databases

### File Systems
- Early systems relied on sequential and random access files for data storage.
- Limitations:
  1. **Data Redundancy and Inconsistency**:
     - Data duplicated across files may lead to discrepancies.
  2. **Difficulty in Data Access**:
     - Sequential nature makes retrieval cumbersome.
  3. **Data Isolation**:
     - Different formats across files complicate integration.
  4. **Integrity Issues**:
     - Hard to enforce constraints, e.g., account balance checks, where balance needs to be positive to withdraw cash.
  5. **Atomicity Challenges**:
     - Operations must be all-or-nothing (e.g., fund transfers).
  6. **Concurrency**:
     - Multiple users accessing and updating data simultaneously can create conflicts.
  7. **Security**:
     - Hard to restrict access to specific users.

### Benefits of DBMS
- Solves the above problems with structured data management and advanced features.

---

## Course Plan

### Prerequisites
#### Essential Knowledge:
1. **Set Theory**:
   - Definitions: subsets, power sets, operations (union, intersection, etc.).
   - Reference: MOOC course on Set Theory.
2. **Relations and Functions**:
   - Binary relations, domain, range, reflexivity, symmetry, transitivity.
   - Functions (injective, surjective, bijective).
   - Reference: MOOC course on Discrete Mathematics.
3. **Propositional Logic**:
   - Truth values, operations (and, or, not), implication, equivalence.
4. **Predicate Logic**:
   - Existential and universal quantifiers.
5. **Data Structures**:
   - Arrays, lists, binary search trees (BSTs), B-trees, hash tables.
6. **Algorithms**:
   - Sorting and searching techniques.
   - Reference: MOOC courses on Algorithms.
7. **Programming**:
   - Proficiency in **C language** for application-level programming.

#### Recommended Knowledge:
- **Object-Oriented Design**:
  - Familiarity with languages like C++ or Java.

### Course Outline
1. **Modules**: 40, divided into 8 weeks.
2. **Focus Areas**:
   - **Week 1 to mid-week 5**:
     - Application programming: Query and data manipulation.
   - **Mid-week 5 onwards**:
     - Database analysis: Storage, file structures, performance tuning, indexing.
3. **Roles**:
   - Application Programmers: Basic database interaction.
   - Analysts: Advanced design and optimization.
  
| Week  | Topics                                                                 |
|-------|------------------------------------------------------------------------|
| Week 1 | Course Overview<br>Introduction to RDBMS                              |
| Week 2 | Structured Query Language (SQL)                                       |
| Week 3 | Relational Algebra<br>Entity-Relationship Model                       |
| Week 4 | Relational Database Design                                            |
| Week 5 | Application Development<br>Case Studies<br>Storage and File Structure |
| Week 6 | Indexing and Hashing<br>Query Processing                              |
| Week 7 | Query Optimization<br>Transactions (Serializability and Recoverability) |
| Week 8 | Concurrency Control<br>Recovery Systems<br>Course Summarization       |



---

## Key Topics Highlighted
1. **Atomicity**:
   - Ensures operations are completed fully or not at all.
   - Example: Fund transfers.
2. **Concurrency**:
   - Handles simultaneous access to prevent conflicts.
   - Example: Railway reservations.
3. **Security**:
   - Ensures controlled access based on user roles.

---

This concludes the notes for the first lecture. The subsequent modules will delve deeper into the concepts introduced here.
