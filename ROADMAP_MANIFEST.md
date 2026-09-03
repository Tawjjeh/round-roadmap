# Tawjjeh Educational Roadmap - Manifest

> **For AI Assistants**: This document provides a comprehensive overview of the entire Tawjjeh Educational Roadmap curriculum. Use this to understand the full context before assisting with any roadmap-related tasks.

---

## Project Overview

**Project Name**: Tawjjeh Educational Roadmap ("Tawjjeh" means "graduation" or "completion" in Arabic)

**Purpose**: An 8-sprint (4-month) intensive program designed to transform contributors into effective open source maintainers.

**Target Audience**: Developers who want to transition from open source contributors to maintainers, or those seeking to deepen their understanding of open source development practices.

**Technical Stack Focus**: Primarily Microsoft/.NET ecosystem (C#, xUnit, FluentValidation, AutoMapper, Entity Framework Core, Roslyn Analyzers, GitHub Actions)

---

## Curriculum Breakdown

### Month 1: Setup & Standards

#### Sprint 1: Setup & Foundations

**Technical Topic**: Git Branches & Pointers Under the Hood

- **Learning Objectives**:
  - Understand how Git truly works under the hood (objects, refs, pointers)
  - Master branch management strategies for open source contributions
  - Learn effective workflows for working with remote repositories

- **Key Concepts**:
  - Git objects: blobs, trees, commits
  - HEAD, branches, and remote tracking
  - Merge vs Rebase strategies
  - Detached HEAD state and its implications

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Open Source Culture & CONTRIBUTING.md Etiquette

- **Learning Objectives**:
  - Understand the values and norms of open source communities
  - Learn to read and follow CONTRIBUTING.md guidelines
  - Make effective contributions that get accepted

- **Key Concepts**:
  - Open source ethos and community dynamics
  - Reading and interpreting CONTRIBUTING.md
  - Fork and branch workflow for external contributions
  - Code of conduct and interaction guidelines

- **Documentation Status**: Partially documented (structure exists, content pending)

---

#### Sprint 2: Code Standards & Issue Triage

**Technical Topic**: Code Formatting, EditorConfig, and Roslyn Analyzers

- **Learning Objectives**:
  - Master consistent code formatting across teams
  - Configure EditorConfig for project-wide style enforcement
  - Implement Roslyn analyzers for real-time code quality

- **Key Concepts**:
  - EditorConfig syntax and precedence rules
  - Roslyn analyzer architecture and rule sets
  - StyleCop, SonarLint, and other analyzer integrations
  - Suppressing warnings appropriately

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Triage and Choosing the Right Issue

- **Learning Objectives**:
  - Learn to evaluate issues for complexity and suitability
  - Develop skills to ask clarifying questions
  - Understand issue priority and timing considerations

- **Key Concepts**:
  - Good first issue vs. help wanted labels
  - Issue complexity assessment
  - Asking effective clarifying questions
  - Time estimation for contributions

- **Documentation Status**: Partially documented (structure exists, content pending)

---

### Month 2: Quality & Validation

#### Sprint 3: Validation & Open Source Licenses

**Technical Topic**: Validation in Open Source Using FluentValidation

- **Learning Objectives**:
  - Implement robust validation patterns in library code
  - Create validators that are extensible and testable
  - Learn FluentValidation best practices for OSS projects

- **Key Concepts**:
  - Rule-based validation chains
  - Custom validators and predicates
  - Async validation patterns
  - Integration with ASP.NET Core

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Open Source Licenses: MIT, GPL, Apache

- **Learning Objectives**:
  - Understand the implications of different open source licenses
  - Learn how to properly license your own projects
  - Navigate license compliance in OSS contributions

- **Key Concepts**:
  - MIT License: simplicity and permissiveness
  - GPL: copyleft and its implications
  - Apache 2.0: patent protection and attribution
  - License compatibility and stacking
  - Adding licenses to projects

- **Documentation Status**: Partially documented (structure exists, content pending)

---

#### Sprint 4: Unit Testing & Code Review Culture

**Technical Topic**: Unit Testing Basics with xUnit

- **Learning Objectives**:
  - Master xUnit framework fundamentals
  - Write effective unit tests for open source projects
  - Understand test organization and naming conventions

- **Key Concepts**:
  - xUnit facts and theories
  - Test fixtures and class fixtures
  - Assert libraries and custom assertions
  - Mocking with Moq or similar libraries
  - Test coverage considerations

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Code Review Culture and Accepting Feedback

- **Learning Objectives**:
  - Develop a healthy attitude toward code reviews
  - Learn to give constructive feedback
  - Navigate the back-and-forth of review discussions

- **Key Concepts**:
  - Blending ego with code
  - Writing clear, actionable review comments
  - Responding to critique professionally
  - When to push back and when to concede

- **Documentation Status**: Partially documented (structure exists, content pending)

---

### Month 3: Data & Errors

#### Sprint 5: Object Mapping & Documentation

**Technical Topic**: Object Mapping with AutoMapper

- **Learning Objectives**:
  - Implement efficient object-to-object mapping patterns
  - Configure type maps and custom resolvers
  - Handle complex mapping scenarios in OSS libraries

- **Key Concepts**:
  - Profile-based mapping configuration
  - Custom value resolvers and type converters
  - Null handling and conditional mapping
  - Performance considerations for large-scale mapping

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Writing Selling Documentation and READMEs

- **Learning Objectives**:
  - Create compelling documentation that attracts users
  - Structure READMEs for maximum impact
  - Document features, installation, and usage effectively

- **Key Concepts**:
  - README structure and essential sections
  - Badges, demos, and visual polish
  - Contributing guidelines in documentation
  - Updating docs alongside code changes

- **Documentation Status**: Partially documented (structure exists, content pending)

---

#### Sprint 6: Error Handling & Personal Branding

**Technical Topic**: Global Error Handling & Middlewares

- **Learning Objectives**:
  - Implement robust exception handling in libraries
  - Design user-friendly error messages for OSS consumers
  - Create middleware pipelines for cross-cutting concerns

- **Key Concepts**:
  - Exception filters and middleware
  - Problem details and error response standards
  - Logging integration for diagnostics
  - Graceful degradation patterns

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Building a Personal Brand in the Open Source Community

- **Learning Objectives**:
  - Establish credibility through meaningful contributions
  - Leverage open source work for career growth
  - Network effectively within communities

- **Key Concepts**:
  - Consistent contribution strategies
  - Blog posts, talks, and community presence
  - GitHub profile as a portfolio
  - Balancing multiple OSS commitments

- **Documentation Status**: Partially documented (structure exists, content pending)

---

### Month 4: Database & Automation

#### Sprint 7: EF Core Migrations & Burnout Management

**Technical Topic**: Managing EF Core Migrations in Teams

- **Learning Objectives**:
  - Coordinate database schema changes across distributed teams
  - Handle migration conflicts and resolution strategies
  - Implement migration best practices for OSS libraries

- **Key Concepts**:
  - Migration file organization and naming
  - Merge conflicts in migration files
  - Idempotent migrations and deployment strategies
  - Keeping migrations lean and reversible

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Dealing with Burnout in Open Source

- **Learning Objectives**:
  - Recognize signs of contributor burnout
  - Establish sustainable open source involvement
  - Set boundaries while maintaining community relationships

- **Key Concepts**:
  - Warning signs of burnout
  - Time management for OSS commitments
  - Saying no gracefully
  - Finding renewal through community support

- **Documentation Status**: Partially documented (structure exists, content pending)

---

#### Sprint 8: CI/CD Automation & Maintainership

**Technical Topic**: CI/CD Automations with GitHub Actions

- **Learning Objectives**:
  - Build comprehensive CI/CD pipelines for OSS projects
  - Automate testing, building, and deployment workflows
  - Implement quality gates and automated checks

- **Key Concepts**:
  - Workflow syntax and job configuration
  - Matrix builds for multiple platforms
  - Secrets management and environment variables
  - Artifact publishing and release automation

- **Documentation Status**: Partially documented (structure exists, content pending)

---

**Knowledge Topic**: Maintainership and Merging PRs

- **Learning Objectives**:
  - Develop criteria for accepting and merging contributions
  - Manage contributor relationships long-term
  - Handle difficult PRs and community conflicts

- **Key Concepts**:
  - PR evaluation checklist
  - Communicating decisions to contributors
  - Squash merge vs. merge commit strategies
  - Sunset projects gracefully

- **Documentation Status**: Partially documented (structure exists, content pending)

---

## Technical Prerequisites

Participants should have:
- Basic familiarity with C# and the .NET ecosystem
- Understanding of Git fundamentals (commits, pushes, pulls)
- A GitHub account
- Visual Studio or VS Code installed

## Documentation Status Summary

| Status | Count | Description |
|--------|-------|-------------|
| **Fully Documented** | 0 | No sprint has complete content |
| **Partially Documented** | 8 | All sprints have structure but lack detailed content |
| **Planned/Pending** | 0 | All planned topics are outlined |

### Content Gaps

- All sprints contain placeholder sections for "Preparation Notes & Code Snippets" that are currently empty
- No actual code snippets, technical deep-dives, or knowledge articles have been written
- Each sprint file has empty sections for Technical Notes, Knowledge Notes, and Code Snippets

## File Inventory

| File | Purpose | Documentation Status |
|------|---------|---------------------|
| `LICENSE` | MIT License file | Complete |
| `README.md` | Project introduction and contribution guide | Complete |
| `ROADMAP_MANIFEST.md` | This manifest | Complete |
| `00_OVERVIEW.md` | High-level program overview | Complete |
| `01_Sprint_Setup.md` | Sprint 1 content | Partial |
| `02_Sprint_Standards.md` | Sprint 2 content | Partial |
| `03_Sprint_Validation.md` | Sprint 3 content | Partial |
| `04_Sprint_Testing.md` | Sprint 4 content | Partial |
| `05_Sprint_Mapping.md` | Sprint 5 content | Partial |
| `06_Sprint_ErrorHandling.md` | Sprint 6 content | Partial |
| `07_Sprint_Migrations.md` | Sprint 7 content | Partial |
| `08_Sprint_Automation.md` | Sprint 8 content | Partial |

---

> **Note for AI Assistants**: When assisting with this roadmap, please reference this manifest to understand the full curriculum context. If asked to generate content for any sprint, ensure alignment with the stated learning objectives and key concepts outlined above.
