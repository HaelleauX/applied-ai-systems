# Evidence-Driven AI Research System

## Case Study Overview

This project demonstrates a structured approach to AI-assisted research, evidence classification, source provenance, human verification, testing, and information architecture.

The system was developed while researching a legacy voice-interactive consumer robot with fragmented documentation, inconsistent community knowledge, undocumented behaviors, and information distributed across manuals, user reports, archived resources, and hands-on testing.

Rather than treating AI-generated synthesis as inherently reliable, the project introduced an evidence and verification architecture designed to distinguish documented facts from multi-source findings, community observations, hypotheses, and items requiring physical testing.

## The Problem

Researching legacy technology presents several challenges:

- official documentation may be incomplete or difficult to locate
- product behavior can differ from documented specifications
- community knowledge varies in reliability
- multiple sources may contradict one another
- AI systems can confidently merge fact, inference, and speculation
- undocumented behaviors may require physical verification
- large research collections quickly become difficult to navigate

The challenge was not simply collecting more information.

The challenge was building a system that could answer:

**What do we know, how do we know it, how confident are we, and what still needs to be tested?**

## System Design

The research workflow was organized into several connected components.

### Research Database

A structured research database was created to capture findings while preserving the relationship between claims and supporting evidence.

Research items could be categorized by verification status, including:

- Official documentation
- Multi-source confirmation
- Community-reported behavior
- Needs physical testing

This reduced the risk of treating every discovered claim as equally reliable.

### Interaction Database

A separate interaction database organized known and reported robot behaviors.

Separating interaction data from general research made it possible to compare:

- documented commands
- reported behaviors
- response patterns
- interaction conditions
- unresolved questions
- testing requirements

### Testing Protocol

Items that could not be confidently resolved through research were moved into a structured testing workflow.

The testing protocol supported repeatable verification by defining:

- the behavior or claim being tested
- required setup conditions
- test steps
- expected behavior
- observed behavior
- repeat attempts
- verification outcome
- notes and exceptions

This created a human-in-the-loop validation layer rather than allowing AI synthesis to become the final authority.

### Activity Mapping

Research findings were translated into structured user activities.

The activity map connected:

- discovered functionality
- required setup
- user instructions
- dependencies
- evidence status
- testing status
- documentation requirements

This helped transform raw research into usable product knowledge.

### Information Architecture

The research system ultimately supported a larger documentation structure.

A master outline and developmental-edit specification were used to organize information into a coherent hierarchy and reduce:

- duplication
- unsupported claims
- inconsistent terminology
- fragmented instructions
- missing prerequisites

## Research Workflow

The overall workflow followed this pattern:

```text
Source Discovery
      ↓
Claim Extraction
      ↓
Evidence Classification
      ↓
Cross-Source Comparison
      ↓
Research Database
      ↓
Unresolved Claim Detection
      ↓
Human / Physical Testing
      ↓
Verification Update
      ↓
Interaction Database
      ↓
Activity Mapping
      ↓
Information Architecture
      ↓
Final Documentation
