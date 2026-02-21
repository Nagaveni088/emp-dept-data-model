# emp-dept-data-model

Spring Boot data model implementation of an EMPLOYEE–DEPARTMENT ERD using JPA annotations and entity relationships. This project demonstrates database modeling, entity mapping, and repository structure for backend development tasks.

---

## 📌 Project Overview
This project implements a simple relational data model based on an ER diagram consisting of:
- Employee entity
- Department entity
- One-to-Many relationship (Department → Employees)

Built as part of a data modeling task submission using Spring Boot and JPA.

---

## 🛠️ Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- GitHub

---

## 🧱 Data Model
### Entities:
**Employee**
- id (Primary Key)
- ssn
- name
- salary
- department (Many-to-One)

**Department**
- id (Primary Key)
- name
- employees (One-to-Many)

---

## 🔗 Relationships
- One Department can have multiple Employees
- Each Employee belongs to one Department
- Implemented using:
  - `@OneToMany`
  - `@ManyToOne`
  - `@JoinColumn`

---

## 📁 Project Structure
