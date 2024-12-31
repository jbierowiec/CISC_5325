# Assignment 4 - Transaction Management and Serializability

This repository contains the materials for Assignment 4 of Databases. The assignment focuses on transaction management concepts, including conflict and view serializability, isolation levels, two-phase locking protocols, and analyzing transaction schedules.

## Assignment Structure

```plaintext
├── Databases_Assignment_4.pdf
└── assignment4_settled.pdf
```

## Assignment Questions

1. **Conflict vs. View Serializability**
   - Discuss why conflict serializability is emphasized over view serializability.

2. **Lost Update Anomaly**
   - Provide examples and explanations regarding the lost update anomaly in different isolation levels:
     - Example of a schedule showing the anomaly.
     - Explanation of its possibility in the Read Committed isolation level.
     - Explanation of its impossibility in the Repeatable Read isolation level.

3. **Two-Phase Locking Protocol**
   - Augment two transactions (`T1` and `T2`) with lock and unlock instructions to follow the two-phase locking protocol.
   - Analyze whether the execution of these transactions can lead to a deadlock.

4. **Schedule Analysis**
   - Analyze a sequence of actions in schedule `S`:
     - Check for view-serializability and provide a view-equivalent serial schedule if applicable.
     - Check for conflict-serializability and describe conflict-equivalent serial schedules.
     - Determine if the schedule follows two-phase locking with exclusive locks.
     - Determine if the schedule follows two-phase locking with shared and exclusive locks.

## How to Use the File

1. Open `assignment4_settled.pdf` to review the assignment questions.
2. Solve the problems step-by-step, ensuring clarity in the explanations and correctness in examples.
3. Use diagrams or tables where necessary to illustrate transaction schedules and locking mechanisms.
