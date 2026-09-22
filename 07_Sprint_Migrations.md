# Sprint 7: EF Core Migrations, Seed Data, and Versioning

---

## Technical Topic: Managing EF Core Migrations in Teams

### Learning Objectives

- Coordinate database schema changes across distributed teams
- Handle migration conflicts and resolution strategies
- Add small, repeatable seed data for local development
- Implement migration best practices for OSS libraries

### Key Concepts

| Concept | Description |
|---------|-------------|
| **Migration Organization** | Naming conventions and file structure for migrations |
| **Migration Conflicts** | When two team members create overlapping migrations |
| **Idempotent Migrations** | Migrations that can run safely multiple times |
| **Lean Migrations** | Keeping migrations small and focused |
| **Reversible Changes** | Writing migrations that can be rolled back if needed |
| **Seed Data** | Initial data used to run and test the application locally |

> **Practice**: Do not edit an applied migration. Create a new migration for the next database change.

---

## Knowledge Topic: Changelogs and Versioning

### Learning Objectives

- Record user-visible changes in a changelog
- Understand major, minor, and patch versions
- Write a short release note

### Key Concepts

| Concept | Description |
|---------|-------------|
| **Changelog** | A list of important changes between releases |
| **Semantic Versioning** | A version format based on breaking changes and features |
| **Breaking Change** | A change that requires users to update their code |

> **Practice**: Add one entry to a changelog and label it as a fix, feature, or breaking change.

---

## Preparation Notes & Code Snippets

### Technical Notes:



### Knowledge Notes:



### Code Snippets:

