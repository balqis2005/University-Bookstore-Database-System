# University Bookstore Database System

A comprehensive database engineering project focused on designing, optimizing, and implementing a relational database schema for a University Bookstore management system. This project covers the full lifecycle of database normalization and complex relational query building.

---

## 🛠️ Core Database Design & Phase Highlights

* **Functional Dependencies (FDs):** Analyzed and mapped core business logic dependencies (e.g., `BookISBN → BookTitle, Author, Publisher`, `CustomerPhone → CustomerID`).
* **Candidate Key Analysis:** Evaluated attribute closures mathematically to extract candidate keys systematically.
* **Schema Normalization (1NF to 3NF):** Elimination of data redundancies, update/delete anomalies, and optimization of relational tables up to the Third Normal Form (3NF).
* **Relational Algebra Expressions:** Structured mathematically precise query logic using selections ($\sigma$), projections ($\pi$), and complex Theta Joins ($\bowtie$) for inventory monitoring.

---

## 📊 Sample Queries Implemented

* **Union Operations ($\cup$):** Combining distinct author and publisher registries.
* **Set Difference ( $-$ ):** Isolating unregistered users versus active order accounts.
* **Theta Join & Projections:** Merging dynamic transaction tables to query global stock records where quantities exceed user thresholds.

---

## 📂 Project Materials

* 📄 [Download Full Technical Report (PDF)](DBMS%20Phase%201%2B2.pdf) - Contains the complete functional dependencies charts, candidate key proofs, relational trees, and normalized schemas.
