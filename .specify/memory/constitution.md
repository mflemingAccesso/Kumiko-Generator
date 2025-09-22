 # Kumiko-ifier App Constitution
 
 ## Core Principles
 
 ### I. Simplicity First
 Every feature should be as simple as possible. Avoid unnecessary complexity.
 
 ### II. Test-First Development
 All code must be covered by basic unit tests before merging. Red-Green-Refactor cycle is required.
 
 ### III. CLI and Web Interface
 All core functionality must be accessible via both CLI and web interface. Input/output should be text or JSON.
 
 ### IV. Self-Contained Modules
 Features should be implemented as independent modules with clear boundaries and minimal dependencies.
 
 ### V. Versioning
 Use semantic versioning (MAJOR.MINOR.PATCH) for all releases.
 
 ## Technology Stack
 - Node.js (latest LTS)
 - TypeScript or JavaScript (ES6+)
 - Express.js (or similar minimal web framework)
 - Jest (or similar test framework)
 - Git for version control
 
 ## Development Workflow
 - All code changes require a pull request and code review.
 - Tests must pass before merging.
 - Documentation for new features is mandatory.
 
 ## Governance
 - This constitution overrides all other practices.
 - Amendments require documentation and approval.
 
 **Version**: 1.0.0 | **Ratified**: 2025-09-21 | **Last Amended**: 2025-09-21

## Core Principles

### [PRINCIPLE_1_NAME]
<!-- Example: I. Library-First -->
[PRINCIPLE_1_DESCRIPTION]
<!-- Example: Every feature starts as a standalone library; Libraries must be self-contained, independently testable, documented; Clear purpose required - no organizational-only libraries -->

### [PRINCIPLE_2_NAME]
<!-- Example: II. CLI Interface -->
[PRINCIPLE_2_DESCRIPTION]
<!-- Example: Every library exposes functionality via CLI; Text in/out protocol: stdin/args → stdout, errors → stderr; Support JSON + human-readable formats -->

### [PRINCIPLE_3_NAME]
<!-- Example: III. Test-First (NON-NEGOTIABLE) -->
[PRINCIPLE_3_DESCRIPTION]
<!-- Example: TDD mandatory: Tests written → User approved → Tests fail → Then implement; Red-Green-Refactor cycle strictly enforced -->

### [PRINCIPLE_4_NAME]
<!-- Example: IV. Integration Testing -->
[PRINCIPLE_4_DESCRIPTION]
<!-- Example: Focus areas requiring integration tests: New library contract tests, Contract changes, Inter-service communication, Shared schemas -->

### [PRINCIPLE_5_NAME]
<!-- Example: V. Observability, VI. Versioning & Breaking Changes, VII. Simplicity -->
[PRINCIPLE_5_DESCRIPTION]
<!-- Example: Text I/O ensures debuggability; Structured logging required; Or: MAJOR.MINOR.BUILD format; Or: Start simple, YAGNI principles -->

## [SECTION_2_NAME]
<!-- Example: Additional Constraints, Security Requirements, Performance Standards, etc. -->

[SECTION_2_CONTENT]
<!-- Example: Technology stack requirements, compliance standards, deployment policies, etc. -->

## [SECTION_3_NAME]
<!-- Example: Development Workflow, Review Process, Quality Gates, etc. -->

[SECTION_3_CONTENT]
<!-- Example: Code review requirements, testing gates, deployment approval process, etc. -->

## Governance
<!-- Example: Constitution supersedes all other practices; Amendments require documentation, approval, migration plan -->

[GOVERNANCE_RULES]
<!-- Example: All PRs/reviews must verify compliance; Complexity must be justified; Use [GUIDANCE_FILE] for runtime development guidance -->

**Version**: [CONSTITUTION_VERSION] | **Ratified**: [RATIFICATION_DATE] | **Last Amended**: [LAST_AMENDED_DATE]
<!-- Example: Version: 2.1.1 | Ratified: 2025-06-13 | Last Amended: 2025-07-16 -->