# Atlas Information Model

> **A standardized metadata framework for identifying, organizing,
> tracking, and managing every artifact within Project Atlas.**

------------------------------------------------------------------------

# Purpose

The Atlas Information Model establishes a common metadata standard for
every artifact within Project Atlas.

By assigning each artifact a consistent identity and descriptive
metadata, Atlas becomes searchable, traceable, maintainable, and ready
for future automation and analytics.

Metadata is not documentation for its own sake---it is the information
architecture that connects the entire Atlas ecosystem.

------------------------------------------------------------------------

# Design Principles

The Atlas Information Model is built upon four guiding principles:

-   **Consistency** --- Every artifact follows the same metadata
    structure.
-   **Readability** --- Metadata should be understandable by humans.
-   **Maintainability** --- Metadata should be easy to update.
-   **Automation Ready** --- Metadata should support future tooling
    without increasing contributor burden.

------------------------------------------------------------------------

# Standard Metadata Block

Every major artifact should begin with the following metadata block.

``` text
Atlas ID:
Title:
Artifact Type:
Version:
Status:

Owner:
Contributors:
Reviewer:
Approver:

Course:
Module:
Learning Outcomes:
Prerequisites:
Dependencies:
Related Artifacts:

Created:
Last Updated:
Review Cycle:

Tags:
```

This metadata should appear near the beginning of every document,
immediately following the document title.

------------------------------------------------------------------------

# Metadata Categories

## 1. Identity

  Field           Description
  --------------- ------------------------------
  Atlas ID        Permanent unique identifier
  Title           Human-readable artifact name
  Artifact Type   Category of artifact

The Atlas ID should never change after publication.

## 2. Ownership

  Field          Description
  -------------- --------------------------
  Owner          Primary maintainer
  Contributors   Additional authors
  Reviewer       Quality reviewer
  Approver       Final approval authority

Ownership promotes accountability and simplifies maintenance.

## 3. Lifecycle

  Field          Description
  -------------- ---------------------------------------------------------
  Version        Semantic version
  Status         Draft, Review, Approved, Released, Deprecated, Archived
  Created        Initial publication date
  Last Updated   Most recent revision
  Review Cycle   Expected review frequency

## 4. Educational Context

  Field               Description
  ------------------- ------------------------------
  Course              Associated course
  Module              Associated module
  Learning Outcomes   Supported learning outcomes
  Prerequisites       Required prior knowledge
  Dependencies        Related supporting artifacts
  Related Artifacts   Connected Atlas resources
  Tags                Search keywords

------------------------------------------------------------------------

# Atlas ID Standard

Examples:

``` text
ATLAS-STD-001
ATLAS-POLICY-001
ATLAS-TEMPLATE-001

ATLAS-COURSE-CPT244
ATLAS-MODULE-CPT244-01
ATLAS-LESSON-CPT244-01-01
ATLAS-LAB-CPT244-01-01
ATLAS-PROJECT-CPT244-01
ATLAS-QUIZ-CPT244-01
ATLAS-RUBRIC-CPT244-01
```

Identifiers should remain stable throughout the artifact lifecycle.

------------------------------------------------------------------------

# Artifact Types

-   Standard
-   Policy
-   Template
-   Course
-   Module
-   Lesson
-   Laboratory
-   Project
-   Assessment
-   Quiz
-   Examination
-   Rubric
-   Presentation
-   Announcement
-   Study Guide
-   Instructor Guide

------------------------------------------------------------------------

# Versioning

Atlas follows Semantic Versioning.

  -----------------------------------------------------------------------
  Version                               Meaning
  ------------------------------------- ---------------------------------
  Major                                 Significant structural or
                                        instructional changes

  Minor                                 New features or substantial
                                        additions

  Patch                                 Corrections, clarifications,
                                        formatting, or minor improvements
  -----------------------------------------------------------------------

Example:

``` text
Version: 2.3.1
```

------------------------------------------------------------------------

# Benefits

A standardized information model enables Atlas to:

-   Search artifacts efficiently
-   Track curriculum evolution
-   Support dependency analysis
-   Generate release notes
-   Produce curriculum analytics
-   Simplify maintenance
-   Enable future automation and AI-assisted workflows

Metadata transforms documentation into an interconnected knowledge
system.

------------------------------------------------------------------------

# Governance

All newly created artifacts shall implement the Atlas Information Model.

Existing artifacts should adopt the standard during normal revision
cycles.

Exceptions should be documented and approved through the Atlas review
process.

------------------------------------------------------------------------

# Closing Statement

The Atlas Information Model establishes the common language that
connects every artifact within Project Atlas.

By standardizing metadata, Atlas becomes more than a repository of
educational resources---it becomes a structured curriculum engineering
platform capable of continuous growth, analysis, and improvement.

A shared information model creates consistency.

Consistency enables automation.

Automation strengthens sustainability.

------------------------------------------------------------------------

> **Engineering Better Learning**

# **LET'S BUILD.**
