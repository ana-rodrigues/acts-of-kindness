# Context Rules

## Overview
This document establishes the requirement to use specific context files for all development tasks in this repository.

## Context Files Location
All context files are located in the `/context` directory and must be referenced for every task, current and future, related to this repository.

### Required Context Files:
- `context/prd.md` - Product Requirements Document

## Rules for Development Tasks

### 1. Mandatory Context Review
Before starting any development task, bug fix, feature implementation, or code modification:
- Review all documents in /context
- Ensure understanding of the project's security requirements
- Align implementation with the phase one product requirements
- Consider technical constraints and considerations outlined in the documents

### 2. Decision Making
All technical decisions must be made with reference to:
- Security guidelines from the security extension whitepaper
- Product requirements from the PRD phase one document
- Technical constraints from the technical considerations document

### 3. Code Quality Standards
- All code must meet the security standards outlined in the context documents
- Implementation must align with the architectural decisions documented
- Features must fulfill the requirements specified in the PRD

### 4. Documentation Updates
When making changes:
- Update relevant documentation to reflect changes
- Ensure consistency with the context documents
- Document any deviations from the original specifications with justification

### 5. Tutoring
When taking on any task:
- Explain the context documents to the user
- Explain the decision making process
- Explain the code quality standards
- Explain the documentation updates process
- Explain the tutoring process

## Enforcement
This rule applies to:
- All current development tasks
- All future development tasks
- Bug fixes and maintenance
- Feature additions and modifications
- Code reviews and quality assurance

## Note
The context directory is gitignored to protect sensitive information, but these documents remain the authoritative source for project requirements and constraints.

---
*Created: 2025-11-02*
*Purpose: Ensure consistent use of project context across all development activities*
