# ATLAS-STD-009

## Program Specification Standard

**Document ID:** ATLAS-STD-009\
**Version:** 1.0 Draft\
**Status:** Working Draft\
**Classification:** Engineering Standard\
**Owner:** Atlas Curriculum Engineering Body of Knowledge (CEBoK)\
**Effective Date:** TBD\
**Last Modified:** TBD

------------------------------------------------------------------------

# Revision History

  Version     Date   Author                Description
  ----------- ------ --------------------- ---------------
  1.0 Draft   TBD    Atlas Working Group   Initial Draft

------------------------------------------------------------------------

# Table of Contents

-   Executive Summary

1.  Purpose
2.  Scope
3.  Normative References
4.  Terms and Definitions
5.  Guiding Principles
6.  Program Specification Artifact
7.  Required Components
8.  Engineering Requirements
9.  Relationships and Traceability
10. Quality Requirements
11. Verification and Validation
12. Lifecycle Management
13. Conformance

-   Appendix A -- Program Specification Template (Normative)
-   Appendix B -- Example Program Specification (Informative)
-   Appendix C -- Traceability Matrix (Normative)
-   Appendix D -- Conformance Checklist (Normative)
-   Bibliography

------------------------------------------------------------------------

# Executive Summary

The Atlas Program Specification Standard establishes the engineering
requirements for defining, documenting, governing, and maintaining
academic programs within the Atlas Curriculum Engineering System (CES).

A Program Specification is the authoritative engineering artifact
describing an academic program. It defines the program's purpose,
educational objectives, graduate competencies, curriculum architecture,
learning progression, assessment strategy, governance, and continuous
improvement processes.

The Program Specification serves as the parent artifact for all
subordinate curriculum engineering artifacts, including Course
Specifications, Curriculum Maps, Assessment Blueprints, Weekly Modules,
Lesson Plans, and associated instructional resources.

This standard establishes the minimum engineering requirements for
Program Specifications to ensure consistency, traceability, quality,
interoperability, and long-term maintainability across institutions
implementing the Atlas Curriculum Engineering System.

------------------------------------------------------------------------

# 1. Purpose

## 1.1 General

The purpose of this standard is to establish uniform engineering
requirements for the development, maintenance, governance, and
continuous improvement of Program Specifications.

Program Specifications shall serve as the primary engineering artifact
from which curriculum is designed, implemented, evaluated, and
maintained.

## 1.2 Objectives

This standard establishes requirements for:

-   Defining academic programs as engineered systems.
-   Documenting graduate competencies and educational outcomes.
-   Establishing curriculum architecture.
-   Defining curriculum sequencing and prerequisite relationships.
-   Supporting curriculum traceability.
-   Supporting accreditation activities.
-   Enabling continuous improvement.
-   Providing standardized program documentation.
-   Supporting software automation within Atlas Studio.

------------------------------------------------------------------------

# 2. Scope

## 2.1 Applicability

This standard applies to all academic programs managed under the Atlas
Curriculum Engineering System, including but not limited to:

-   Associate Degree Programs
-   Bachelor's Degree Programs
-   Graduate Programs
-   Technical Certificates
-   Diplomas
-   Continuing Education Programs
-   Workforce Development Programs
-   Apprenticeship Programs
-   Corporate Training Programs

## 2.2 Exclusions

This standard does not prescribe:

-   Instructional methodologies
-   Pedagogical philosophies
-   Discipline-specific content
-   Institutional governance policies
-   Accreditation requirements specific to any single accrediting body

------------------------------------------------------------------------

# 3. Normative References

The following documents are indispensable for the application of this
standard.

-   ATLAS-GOV-001 --- Governance Framework
-   ATLAS-REF-000 --- Atlas Glossary
-   ATLAS-REF-001 --- Bibliography
-   ATLAS-STD-001 --- Course Specification Standard
-   ATLAS-STD-002 --- Learning Outcome Standard
-   ATLAS-STD-003 --- Competency Standard
-   ATLAS-STD-004 --- Assessment Engineering Standard
-   ATLAS-STD-005 --- Curriculum Mapping Standard

Where conflicts exist, the Governance Framework shall take precedence.

------------------------------------------------------------------------

# 4. Terms and Definitions

Terms used within this standard shall conform to the definitions
established in **ATLAS-REF-000 -- Atlas Glossary**.

No additional terminology is defined within this document.

------------------------------------------------------------------------

# 5. Guiding Principles

Program Specifications shall be engineered according to the following
principles.

-   Student-Centered
-   Outcome-Driven
-   Competency-Based
-   Systems-Oriented
-   Evidence-Informed
-   Industry-Aligned
-   Traceable
-   Measurable
-   Governed
-   Continuously Improved
-   Accessible
-   Maintainable

These principles shall guide all engineering decisions associated with
Program Specification development and maintenance.

------------------------------------------------------------------------

# 6. Program Specification Artifact

## 6.1 General

A Program Specification is the authoritative engineering artifact describing the structure, purpose, behavior, governance, and quality expectations of an academic program.

The Program Specification serves as the parent engineering artifact from which all subordinate curriculum artifacts are derived.

Every academic program governed under the Atlas Curriculum Engineering System shall possess one and only one active Program Specification.

The Program Specification shall define the engineering characteristics of the program independently of instructional delivery methods, academic calendar structures, or institutional implementation practices.

---

## 6.2 Purpose

The Program Specification exists to:

- Define the educational mission of the program.
- Describe the graduate profile.
- Establish program learning outcomes.
- Define graduate competencies.
- Establish curriculum architecture.
- Describe competency progression.
- Define prerequisite relationships.
- Establish assessment philosophy.
- Support accreditation.
- Support curriculum governance.
- Support continuous improvement.
- Provide complete traceability throughout the curriculum lifecycle.

---

## 6.3 Engineering Role

Within Atlas, the Program Specification functions as the system architecture document for an academic program.

All subordinate curriculum artifacts derive authority from the Program Specification.

The Program Specification establishes:

- System objectives
- Functional requirements
- Educational constraints
- Component relationships
- Verification strategy
- Quality expectations

The Program Specification shall remain technology-neutral and delivery-neutral.

---

## 6.4 Parent Relationships

### Program Artifact Hierarchy

```text
Institution
        │
        ▼
Program Specification
        │
        ▼
Course Specifications
        │
        ▼
Weekly Modules
        │
        ▼
Lessons
        │
        ▼
Assessments
        │
        ▼
Evidence
```

The Program Specification shall serve as the parent artifact for:

- Course Specifications
- Curriculum Maps
- Competency Models
- Assessment Blueprints
- Resource Plans
- Improvement Plans

All subordinate artifacts shall maintain traceability to the Program Specification.

---

## 6.5 Artifact Characteristics

| Characteristic | Requirement |
|----------------|-------------|
| Authoritative | Yes |
| Version Controlled | Yes |
| Traceable | Yes |
| Governed | Yes |
| Reviewable | Yes |
| Verifiable | Yes |
| Testable | Yes |
| Maintainable | Yes |
| Auditable | Yes |
| Reusable | Yes |

---

## 6.6 Required Metadata

Every Program Specification shall contain the following metadata.

| Metadata Field | Required |
|----------------|:--------:|
| Program Name | ✔ |
| Program Identifier | ✔ |
| Degree Type | ✔ |
| Academic Level | ✔ |
| Department | ✔ |
| Version | ✔ |
| Status | ✔ |
| Owner | ✔ |
| Effective Date | ✔ |
| Review Date | ✔ |
| Approver | ✔ |

---

## 6.7 Artifact Composition

A Program Specification shall consist of the following engineering components.

```text
Program Specification

├── Metadata
├── Mission
├── Vision
├── Graduate Profile
├── Program Outcomes
├── Graduate Competencies
├── Program Architecture
├── Curriculum Architecture
├── Course Architecture
├── Learning Progression
├── Competency Progression
├── Assessment Strategy
├── Industry Alignment
├── Accreditation Alignment
├── Governance
├── Quality Assurance
├── Continuous Improvement
└── Revision History
```

---

## 6.8 Artifact Interfaces

The Program Specification interfaces with multiple internal and external engineering artifacts.

### Consumes

- Institutional Mission
- Strategic Plan
- Industry Requirements
- Workforce Needs
- Accreditation Standards
- Regulatory Requirements

### Produces

- Course Specifications
- Curriculum Maps
- Assessment Plans
- Competency Models
- Learning Progressions
- Improvement Plans

---

## 6.9 Engineering Constraints

Every Program Specification shall:

- Support version control.
- Support traceability.
- Support competency mapping.
- Support curriculum mapping.
- Support assessment mapping.
- Support change management.
- Support governance review.
- Support continuous improvement.
- Remain implementation-neutral.
- Remain technology-neutral.

---

## 6.10 Design Philosophy

The Program Specification shall describe the academic program as an integrated educational system rather than a collection of independent courses.

All program components shall contribute to a coherent learning progression supporting the development of graduate competencies.

---

# 6.11 Program Architecture

## 6.11.1 General

Program Architecture is the engineered structural model describing how an academic program is organized, governed, implemented, assessed, and continuously improved.

The Program Architecture provides the blueprint from which all curriculum engineering artifacts are derived.

Every Program Specification shall contain one Program Architecture describing the relationships among educational objectives, competencies, curriculum, assessments, governance, and quality assurance processes.

---

## 6.11.2 Objectives

The Program Architecture shall:

- Define the educational system.
- Organize all curriculum engineering artifacts.
- Establish relationships among program components.
- Support traceability.
- Support governance.
- Support verification.
- Support continuous improvement.
- Support future evolution.

---

## 6.11.3 Program Architecture Components

```text
Program Architecture

├── Program Identity
│
├── Mission and Vision
│
├── Graduate Profile
│
├── Educational Objectives
│
├── Graduate Competencies
│
├── Curriculum Architecture
│
├── Learning Progression
│
├── Assessment Architecture
│
├── Resource Architecture
│
├── Governance Architecture
│
├── Quality Architecture
│
├── Continuous Improvement Architecture
│
└── Version History
```

---

## 6.11.4 Curriculum Architecture

Curriculum Architecture defines the structural organization of learning experiences within an academic program.

Curriculum Architecture identifies:

- Courses
- Prerequisite relationships
- Co-requisite relationships
- Competency progression
- Learning progression
- Assessment distribution
- Curriculum sequencing
- Curriculum pathways

Curriculum Architecture shall demonstrate how graduate competencies are progressively developed throughout the academic program.

---

## 6.11.5 Learning Progression

Learning Progression describes the intentional sequence through which learners develop knowledge, skills, behaviors, and professional competencies.

Learning Progression shall identify where competencies are:

- Introduced
- Reinforced
- Applied
- Mastered

Every competency shall demonstrate an identifiable progression throughout the curriculum.

---

## 6.11.6 Competency Architecture

Competency Architecture defines the complete set of graduate competencies together with their relationships, dependencies, progression, and assessment strategy.

Each competency shall map to:

- Program Outcomes
- Course Specifications
- Learning Activities
- Assessments
- Graduate Profile

Competencies shall not exist independently but as integrated elements of the Program Architecture.

---

## 6.11.7 Assessment Architecture

Assessment Architecture defines how evidence of student learning is collected throughout the curriculum.

Assessment Architecture shall identify:

- Formative assessments
- Summative assessments
- Competency assessments
- Capstone assessments
- External assessments
- Program evaluation measures

---

## 6.11.8 Governance Architecture

Governance Architecture defines the organizational structures responsible for the development, approval, maintenance, review, and continuous improvement of the academic program.

Governance Architecture shall maintain alignment with **ATLAS-GOV-001 – Governance Framework**.

---

## 6.11.9 Quality Architecture

Quality Architecture defines the mechanisms used to ensure curriculum quality.

Quality Architecture shall include:

- Review cycles
- Performance indicators
- Assessment evidence
- Stakeholder feedback
- Industry validation
- Continuous improvement activities

---

## 6.11.10 Continuous Improvement Architecture

Continuous Improvement Architecture defines the processes through which assessment evidence is analyzed, engineering decisions are made, and curriculum revisions are implemented.

Continuous Improvement shall be evidence-based and governed under **ATLAS-GOV-001**.

---

## 6.11.11 Program Architecture Overview

```text
Institution
        │
        ▼
Program Architecture
        │
 ┌──────┼──────────────┐
 │      │              │
 ▼      ▼              ▼
Graduate Curriculum Assessment
Profile Architecture Architecture
 │      │              │
 └──────┼──────────────┘
        ▼
Learning Progression
        ▼
Course Specifications
        ▼
Weekly Modules
        ▼
Lessons
        ▼
Assessments
        ▼
Evidence
        ▼
Continuous Improvement

```
## 6.12 Program Architecture Principles

Every Program Architecture shall adhere to the following principles.

### Alignment

The Program Architecture shall align with the institution's mission, strategic objectives, and applicable accreditation requirements.

### Cohesion

All architectural components shall contribute directly to the educational purpose of the program.

### Traceability

Every curriculum artifact shall be traceable to one or more Program Outcomes and Graduate Competencies.

### Modularity

Program components shall be organized to support modification without unnecessary impact on unrelated components.

### Scalability

The architecture shall support future curriculum expansion while preserving structural integrity.

### Maintainability

The architecture shall facilitate systematic review, revision, and continuous improvement.

### Verifiability

The architecture shall define measurable outcomes that permit evaluation of program effectiveness.

### Governance

All architectural modifications shall comply with ATLAS-GOV-001.

## 6.13 Conformance Requirements

A Program Specification conforms to this section when it:

- contains all required architectural components;
- defines one complete Program Architecture;
- establishes traceable relationships among subordinate artifacts;
- supports governance and lifecycle management;
- satisfies all mandatory requirements identified within this standard.
------------------------------------------------------------------------

# 7. Required Components

## 7.1 General

Every Program Specification shall contain the components defined in this section.

The required components establish the minimum information necessary to describe, implement, govern, evaluate, and continuously improve an academic program.

Institutions may include additional components provided they do not conflict with the requirements of this standard.

Each required component shall:

- Serve a distinct engineering purpose.
- Contain all required information.
- Maintain traceability to related engineering artifacts.
- Support governance and quality assurance.
- Remain current throughout the program lifecycle.

Every required component defined within this standard shall conform to the standardized engineering structure defined in Section 7.1.1.

---

## 7.1.1 Standard Component Structure

All required components within a Program Specification shall follow the standardized engineering structure defined below.

### Purpose

Describes the engineering purpose of the component and its role within the Program Specification.

### Required Information

Defines the minimum information that shall be included within the component.

### Requirements

Contains the normative engineering requirements governing the component.

Requirements shall:

- use mandatory language ("shall");
- be uniquely identified;
- be independently verifiable;
- be individually traceable;
- remain stable across document revisions.

### Quality Requirements

Defines the measurable characteristics used to evaluate component quality.

### Traceability

Identifies upstream and downstream engineering artifacts that depend upon or support the component.

---

## 7.2 Program Metadata

### Purpose

Program Metadata uniquely identifies the Program Specification and provides the administrative information required for governance, configuration management, version control, lifecycle management, and traceability.

---

### Required Information

Every Program Specification shall include the following metadata.

| Field | Requirement |
|--------|-------------|
| Program Name | Required |
| Program Identifier | Required |
| Degree Type | Required |
| Credential Awarded | Required |
| CIP Code | Required |
| Academic Level | Required |
| Department | Required |
| Institution | Required |
| Version | Required |
| Status | Required |
| Owner | Required |
| Approver | Required |
| Effective Date | Required |
| Review Date | Required |
| Revision Number | Required |

---

### Requirements

**REQ-STD009-7.2-001**

A Program Specification shall contain a unique Program Identifier.

---

**REQ-STD009-7.2-002**

A Program Specification shall identify exactly one document owner responsible for governance and maintenance.

---

**REQ-STD009-7.2-003**

A Program Specification shall contain a version identifier conforming to the Atlas Versioning Standard.

---

**REQ-STD009-7.2-004**

A Program Specification shall identify its current lifecycle status.

---

**REQ-STD009-7.2-005**

A Program Specification shall record the effective date of the current approved version.

---

**REQ-STD009-7.2-006**

A Program Specification shall identify the approving authority.

---

**REQ-STD009-7.2-007**

A Program Specification shall include a scheduled review date.

---

### Quality Requirements

Program Metadata shall:

- uniquely identify the Program Specification;
- support configuration management;
- support version control;
- support lifecycle management;
- support governance;
- support traceability.

---

### Traceability

Program Metadata shall maintain traceability to:

- Governance Records
- Revision History
- Institutional Program Inventory
- Program Approval Records

---

## 7.3 Program Identity

### Purpose

Program Identity defines the official identity of the academic program and establishes its organizational position within the institution.

---

### Required Information

Program Identity shall include:

- Official program title
- Program abbreviation
- Credential awarded
- Academic discipline
- Department
- Academic division
- Instructional delivery options
- Program length
- Total required credits
- Catalog designation

---

### Requirements

**REQ-STD009-7.3-001**

The Program Specification shall identify the official program title approved by the institution.

---

**REQ-STD009-7.3-002**

The Program Specification shall identify the credential awarded upon successful completion.

---

**REQ-STD009-7.3-003**

The Program Specification shall identify the total credit hours required for completion.

---

**REQ-STD009-7.3-004**

The Program Specification shall identify the department responsible for academic oversight.

---

**REQ-STD009-7.3-005**

The Program Specification shall identify all approved instructional delivery methods.

---

### Quality Requirements

Program Identity shall:

- be unique;
- remain consistent across institutional publications;
- accurately identify the academic program;
- remain stable across curriculum revisions unless formally approved.

---

### Traceability

Program Identity shall trace to:

- Institutional Catalog
- Program Inventory
- Academic Governance Records

---

## 7.4 Mission Statement

### Purpose

The Mission Statement defines the educational purpose of the academic program.

---

### Required Information

The Mission Statement shall describe:

- the purpose of the program;
- the students the program serves;
- the knowledge domains addressed;
- the professional fields supported;
- the value delivered to graduates, employers, and society.

---

### Requirements

**REQ-STD009-7.4-001**

The Program Specification shall contain one Mission Statement.

---

**REQ-STD009-7.4-002**

The Mission Statement shall align with the institutional mission.

---

**REQ-STD009-7.4-003**

The Mission Statement shall support the Graduate Profile.

---

**REQ-STD009-7.4-004**

The Mission Statement shall support the Educational Objectives.

---

### Quality Requirements

The Mission Statement shall:

- be concise;
- be measurable through Program Outcomes;
- support strategic planning;
- support curriculum development;
- remain consistent with institutional priorities.

---

### Traceability

The Mission Statement shall trace to:

- Institutional Mission
- Strategic Plan
- Graduate Profile
- Educational Objectives

---

## 7.5 Vision Statement

### Purpose

The Vision Statement describes the desired future state of the academic program.

---

### Required Information

The Vision Statement shall identify:

- long-term aspirations;
- expected program evolution;
- workforce needs;
- innovation objectives;
- future program direction.

---

### Requirements

**REQ-STD009-7.5-001**

The Program Specification shall contain one Vision Statement.

---

**REQ-STD009-7.5-002**

The Vision Statement shall support long-term program planning.

---

**REQ-STD009-7.5-003**

The Vision Statement shall align with institutional strategic priorities.

---

### Quality Requirements

The Vision Statement shall:

- be forward-looking;
- encourage innovation;
- support continuous improvement;
- remain consistent with institutional strategy.

---

### Traceability

The Vision Statement shall trace to:

- Strategic Plan
- Program Improvement Plan
- Institutional Vision
- Long-Term Program Objectives

---

## 7.6 Graduate Profile

### Purpose

The Graduate Profile defines the characteristics, capabilities, knowledge, skills, behaviors, and professional attributes expected of graduates upon successful completion of the academic program.

The Graduate Profile establishes the desired characteristics of program graduates and serves as the foundation for Educational Objectives, Program Learning Outcomes, Graduate Competencies, and Curriculum Architecture.

---

### Required Information

Every Program Specification shall contain one Graduate Profile.

The Graduate Profile shall describe:

- expected professional roles;
- technical knowledge;
- technical skills;
- professional competencies;
- ethical responsibilities;
- communication abilities;
- collaboration skills;
- problem-solving capabilities;
- lifelong learning expectations;
- career readiness.

---

### Requirements

**REQ-STD009-7.6-001**

The Program Specification shall contain exactly one Graduate Profile.

---

**REQ-STD009-7.6-002**

The Graduate Profile shall describe the expected capabilities of graduates rather than the curriculum used to develop those capabilities.

---

**REQ-STD009-7.6-003**

The Graduate Profile shall support all Educational Objectives.

---

**REQ-STD009-7.6-004**

The Graduate Profile shall support all Program Learning Outcomes.

---

**REQ-STD009-7.6-005**

The Graduate Profile shall remain independent of individual courses.

---

### Quality Requirements

The Graduate Profile shall:

- represent graduate capabilities;
- be measurable through Program Outcomes;
- support workforce readiness;
- support continuous improvement;
- remain technology-neutral.

---

### Traceability

The Graduate Profile shall trace to:

- Program Mission
- Vision Statement
- Educational Objectives
- Program Learning Outcomes
- Graduate Competencies

## 7.7 Educational Objectives

### Purpose

Educational Objectives define the broad accomplishments graduates are expected to achieve several years after completing the academic program.

Educational Objectives describe long-term professional performance rather than immediate learning achievements.

---

### Required Information

Educational Objectives shall describe expected graduate achievement in areas including:

- professional practice;
- career advancement;
- leadership;
- ethical conduct;
- lifelong learning;
- community engagement;
- innovation;
- continued education.

---

### Requirements

**REQ-STD009-7.7-001**

Every Program Specification shall define one or more Educational Objectives.

---

**REQ-STD009-7.7-002**

Educational Objectives shall align with the Program Mission.

---

**REQ-STD009-7.7-003**

Educational Objectives shall support the Graduate Profile.

---

**REQ-STD009-7.7-004**

Educational Objectives shall be measurable through Program Assessment.

---

**REQ-STD009-7.7-005**

Educational Objectives shall be reviewed during each program review cycle.

---

### Quality Requirements

Educational Objectives shall:

- be realistic;
- be measurable;
- remain stable over time;
- support workforce expectations;
- support institutional strategic priorities.

---

### Traceability

Educational Objectives shall trace to:

- Program Mission
- Graduate Profile
- Program Learning Outcomes
- Assessment Strategy

## 7.8 Program Learning Outcomes

### Purpose

Program Learning Outcomes (PLOs) define the measurable knowledge, skills, abilities, and professional behaviors that students shall demonstrate upon successful completion of the academic program.

Program Learning Outcomes establish the educational achievements required for graduation and serve as the primary mechanism for curriculum design, competency development, assessment planning, and continuous improvement.

Program Learning Outcomes provide the measurable foundation from which Graduate Competencies, Course Learning Outcomes, Learning Activities, and Assessment Strategies are derived.

---

### Required Information

Every Program Specification shall define one or more Program Learning Outcomes.

Each Program Learning Outcome shall include:

- Unique outcome identifier
- Outcome statement
- Outcome description
- Performance expectation
- Associated graduate competencies
- Assessment strategy
- Evidence sources
- Curriculum mapping references
- Bloom's Taxonomy level
- Revision history

The detailed engineering specification for Learning Outcomes shall conform to **ATLAS-STD-002 – Learning Outcome Standard**.

---

### Requirements

**REQ-STD009-7.8-001**

Every Program Specification shall define one or more Program Learning Outcomes.

---

**REQ-STD009-7.8-002**

Each Program Learning Outcome shall possess a unique identifier.

---

**REQ-STD009-7.8-003**

Each Program Learning Outcome shall be measurable.

---

**REQ-STD009-7.8-004**

Each Program Learning Outcome shall support one or more Educational Objectives.

---

**REQ-STD009-7.8-005**

Each Program Learning Outcome shall support one or more Graduate Competencies.

---

**REQ-STD009-7.8-006**

Each Program Learning Outcome shall be assessed through one or more assessment methods.

---

**REQ-STD009-7.8-007**

Each Program Learning Outcome shall be mapped throughout the Curriculum Architecture.

---

**REQ-STD009-7.8-008**

Program Learning Outcomes shall conform to the requirements defined in **ATLAS-STD-002 – Learning Outcome Standard**.

---

### Quality Requirements

Program Learning Outcomes shall:

- be measurable;
- be observable;
- be assessable;
- use action-oriented language;
- support graduate competencies;
- support curriculum mapping;
- support assessment planning;
- support continuous improvement.

Program Learning Outcomes shall avoid ambiguous or non-measurable terminology.

---

### Traceability

Program Learning Outcomes shall maintain traceability to:

**Upstream Artifacts**

- Program Mission
- Vision Statement
- Graduate Profile
- Educational Objectives

**Downstream Artifacts**

- Graduate Competencies
- Curriculum Architecture
- Course Specifications
- Course Learning Outcomes
- Assessment Strategy
- Curriculum Maps
- Continuous Improvement Plan

---

## 7.8.1 Engineering Role

Within the Atlas Curriculum Engineering System, Program Learning Outcomes function as the primary educational requirements governing the curriculum.

Program Learning Outcomes translate institutional and program goals into measurable educational achievements.

All curriculum engineering artifacts shall demonstrate traceability to one or more Program Learning Outcomes.

---

## 7.8.2 Engineering Relationships

Program Learning Outcomes establish the relationship between strategic educational goals and instructional implementation.

```text
Program Mission
        │
        ▼
Graduate Profile
        │
        ▼
Educational Objectives
        │
        ▼
Program Learning Outcomes
        │
        ▼
Graduate Competencies
        │
        ▼
Course Learning Outcomes
        │
        ▼
Weekly Learning Outcomes
        │
        ▼
Lesson Learning Outcomes
        │
        ▼
Learning Activities
        │
        ▼
Assessments
        │
        ▼
Evidence
```

---

## 7.8.3 Conformance

A Program Specification conforms to this section when:

- one or more Program Learning Outcomes are defined;
- every Program Learning Outcome is uniquely identified;
- every Program Learning Outcome satisfies **ATLAS-STD-002**;
- every Program Learning Outcome is measurable;
- every Program Learning Outcome is traceable to Educational Objectives and Graduate Competencies;
- every Program Learning Outcome is supported by one or more assessment methods.

## 7.9 Graduate Competencies

### Purpose

Graduate Competencies define the integrated knowledge, skills, abilities, behaviors, and professional attributes that graduates are expected to demonstrate in academic, professional, and workforce environments.

Graduate Competencies represent the professional capabilities developed through successful achievement of the Program Learning Outcomes.

The engineering specification for competencies shall conform to **ATLAS-STD-003 – Competency Standard**.

---

### Required Information

Every Program Specification shall define one or more Graduate Competencies.

Each Graduate Competency shall include:

- Competency identifier
- Competency title
- Competency description
- Competency category
- Associated Program Learning Outcomes
- Curriculum mapping references
- Assessment methods
- Evidence sources
- Performance expectations
- Revision history

---

### Requirements

**REQ-STD009-7.9-001**

Every Program Specification shall define one or more Graduate Competencies.

---

**REQ-STD009-7.9-002**

Each Graduate Competency shall possess a unique identifier.

---

**REQ-STD009-7.9-003**

Each Graduate Competency shall map to one or more Program Learning Outcomes.

---

**REQ-STD009-7.9-004**

Each Graduate Competency shall be supported by one or more Course Learning Outcomes.

---

**REQ-STD009-7.9-005**

Each Graduate Competency shall be evaluated using one or more assessment methods.

---

**REQ-STD009-7.9-006**

Each Graduate Competency shall conform to the requirements defined in **ATLAS-STD-003 – Competency Standard**.

---

### Quality Requirements

Graduate Competencies shall:

- support workforce readiness;
- be measurable through assessment evidence;
- remain technology-neutral where appropriate;
- support lifelong learning;
- align with industry expectations;
- support curriculum engineering;
- support continuous improvement.

---

### Traceability

Graduate Competencies shall maintain traceability to:

**Upstream Artifacts**

- Graduate Profile
- Educational Objectives
- Program Learning Outcomes

**Downstream Artifacts**

- Course Specifications
- Course Learning Outcomes
- Curriculum Architecture
- Assessment Strategy
- Competency Maps
- Continuous Improvement Plan

---

## 7.9.1 Engineering Role

Graduate Competencies function as the professional capability model for the academic program.

Graduate Competencies organize the Program Learning Outcomes into meaningful professional capabilities that prepare graduates for employment, continued education, certification, and lifelong professional growth.

Graduate Competencies provide the framework used to engineer curriculum architecture, assessment strategies, and competency progression throughout the program.

---

## 7.9.2 Competency Categories

Graduate Competencies shall be organized into one or more competency categories appropriate for the academic discipline.

Examples include:

- Technical Competencies
- Analytical Competencies
- Professional Competencies
- Communication Competencies
- Collaboration Competencies
- Ethical Competencies
- Leadership Competencies
- Innovation Competencies
- Digital Literacy Competencies
- Lifelong Learning Competencies

Institutions may define additional competency categories as appropriate.

---

## 7.9.3 Engineering Relationships

Graduate Competencies establish the connection between educational achievement and professional capability.

```text
Educational Objectives
        │
        ▼
Program Learning Outcomes
        │
        ▼
Graduate Competencies
        │
        ▼
Course Learning Outcomes
        │
        ▼
Learning Activities
        │
        ▼
Assessments
        │
        ▼
Evidence
```

---

## 7.9.4 Conformance

A Program Specification conforms to this section when:

- one or more Graduate Competencies are defined;
- each Graduate Competency possesses a unique identifier;
- each Graduate Competency satisfies **ATLAS-STD-003**;
- each Graduate Competency is traceable to one or more Program Learning Outcomes;
- each Graduate Competency is supported by curriculum, assessment, and evidence.

## 7.10 Curriculum Architecture

### Purpose

Curriculum Architecture defines the structural organization of the academic program and describes how learning experiences are intentionally arranged to support the development of Program Learning Outcomes and Graduate Competencies.

Curriculum Architecture establishes the relationships among courses, learning progressions, prerequisite structures, assessment strategies, and competency development.

The Curriculum Architecture provides the blueprint from which Course Specifications, Curriculum Maps, Learning Progressions, and Assessment Plans are derived.

---

### Required Information

Every Program Specification shall contain one Curriculum Architecture.

The Curriculum Architecture shall include:

- Curriculum structure
- Course inventory
- Program sequence
- Prerequisite relationships
- Co-requisite relationships
- Recommended course pathways
- Credit hour distribution
- Competency progression
- Program Learning Outcome mapping
- Assessment distribution
- Capstone integration
- Elective structure (if applicable)
- Graduation requirements

---

### Requirements

**REQ-STD009-7.10-001**

Every Program Specification shall define one Curriculum Architecture.

---

**REQ-STD009-7.10-002**

The Curriculum Architecture shall identify every course required for program completion.

---

**REQ-STD009-7.10-003**

The Curriculum Architecture shall define prerequisite and co-requisite relationships among courses.

---

**REQ-STD009-7.10-004**

Every required course shall support one or more Program Learning Outcomes.

---

**REQ-STD009-7.10-005**

Every required course shall support one or more Graduate Competencies.

---

**REQ-STD009-7.10-006**

The Curriculum Architecture shall demonstrate a logical learning progression from introductory to advanced concepts.

---

**REQ-STD009-7.10-007**

The Curriculum Architecture shall identify the distribution of assessments throughout the curriculum.

---

**REQ-STD009-7.10-008**

The Curriculum Architecture shall identify the location and purpose of any capstone or culminating learning experiences.

---

### Quality Requirements

The Curriculum Architecture shall:

- support student success;
- promote progressive competency development;
- minimize unnecessary prerequisite complexity;
- align with workforce expectations;
- support curriculum flexibility where appropriate;
- support continuous improvement;
- remain internally consistent.

---

### Traceability

Curriculum Architecture shall maintain traceability to:

**Upstream Artifacts**

- Graduate Profile
- Educational Objectives
- Program Learning Outcomes
- Graduate Competencies

**Downstream Artifacts**

- Course Specifications
- Curriculum Maps
- Learning Progressions
- Assessment Strategy
- Capstone Experience
- Continuous Improvement Plan

---

## 7.10.1 Curriculum Structure

The Curriculum Structure defines the overall organization of courses within the academic program.

Curriculum Structure shall identify:

- required courses;
- elective courses;
- general education requirements;
- major requirements;
- supporting coursework;
- sequencing;
- academic milestones.

---

## 7.10.2 Course Sequencing

Course Sequencing defines the recommended order in which students complete the curriculum.

Course Sequencing shall support:

- progressive learning;
- prerequisite fulfillment;
- competency development;
- timely graduation.

---

## 7.10.3 Prerequisite Architecture

Prerequisite Architecture defines the dependency relationships among courses.

Prerequisite relationships shall:

- support learning progression;
- minimize unnecessary dependencies;
- prevent curriculum bottlenecks;
- clearly identify prerequisite and co-requisite requirements.

---

## 7.10.4 Competency Progression

Curriculum Architecture shall demonstrate where each Graduate Competency is:

- Introduced
- Reinforced
- Applied
- Mastered

Competency progression shall span the entire academic program.

---

## 7.10.5 Program Learning Outcome Mapping

Every Program Learning Outcome shall be mapped throughout the curriculum.

Each Program Learning Outcome shall identify:

- introductory experiences;
- reinforcement opportunities;
- mastery opportunities;
- assessment locations.

No Program Learning Outcome shall exist without curriculum support.

---

## 7.10.6 Assessment Distribution

Curriculum Architecture shall describe how assessment evidence is collected throughout the curriculum.

Assessment distribution shall identify:

- formative assessments;
- summative assessments;
- competency assessments;
- authentic assessments;
- capstone assessments.

Assessment activities shall collectively provide sufficient evidence to evaluate achievement of all Program Learning Outcomes.

---

## 7.10.7 Curriculum Pathways

Where multiple completion pathways exist, the Curriculum Architecture shall define each approved pathway.

Examples include:

- Full-time pathway
- Part-time pathway
- Transfer pathway
- Online pathway
- Accelerated pathway

All pathways shall satisfy identical Program Learning Outcomes and Graduate Competencies.

---

## 7.10.8 Engineering Relationships

Curriculum Architecture serves as the structural bridge between program design and instructional implementation.

```text
Program Learning Outcomes
            │
            ▼
Graduate Competencies
            │
            ▼
Curriculum Architecture
            │
    ┌───────┼────────┐
    ▼       ▼        ▼
Course   Curriculum  Learning
Specs      Maps     Progressions
    │
    ▼
Weekly Modules
    │
    ▼
Lessons
    │
    ▼
Assessments
```

---

## 7.10.9 Conformance

A Program Specification conforms to this section when:

- one Curriculum Architecture is defined;
- every required course is represented;
- prerequisite and co-requisite relationships are documented;
- every Program Learning Outcome is mapped within the curriculum;
- every Graduate Competency demonstrates a complete progression through the curriculum;
- assessment distribution provides evidence supporting all Program Learning Outcomes and Graduate Competencies.

  ## 7.11 Course Architecture

### Purpose

Course Architecture defines the structural organization of courses within the Curriculum Architecture and establishes the role, relationships, responsibilities, and educational purpose of each course in achieving the Program Learning Outcomes and Graduate Competencies.

Course Architecture provides the engineering framework from which individual Course Specifications are derived.

The detailed engineering specification for individual courses shall conform to **ATLAS-STD-001 – Course Specification Standard**.

---

### Required Information

Every Program Specification shall define the Course Architecture for the academic program.

The Course Architecture shall include:

- Course inventory
- Course identifiers
- Course titles
- Credit hours
- Course descriptions
- Prerequisite relationships
- Co-requisite relationships
- Program Learning Outcome mappings
- Graduate Competency mappings
- Recommended sequencing
- Major course categories
- Capstone designation (where applicable)

---

### Requirements

**REQ-STD009-7.11-001**

Every Program Specification shall define one Course Architecture.

---

**REQ-STD009-7.11-002**

Every required course shall possess a unique course identifier.

---

**REQ-STD009-7.11-003**

Every required course shall support one or more Program Learning Outcomes.

---

**REQ-STD009-7.11-004**

Every required course shall support one or more Graduate Competencies.

---

**REQ-STD009-7.11-005**

Every required course shall conform to **ATLAS-STD-001 – Course Specification Standard**.

---

**REQ-STD009-7.11-006**

Every required course shall identify prerequisite and co-requisite relationships where applicable.

---

**REQ-STD009-7.11-007**

The Course Architecture shall demonstrate complete coverage of all Program Learning Outcomes.

---

### Quality Requirements

Course Architecture shall:

- support curriculum coherence;
- eliminate unnecessary duplication;
- promote progressive learning;
- support efficient program completion;
- maintain alignment with industry expectations;
- support curriculum evolution.

---

### Traceability

Course Architecture shall maintain traceability to:

**Upstream Artifacts**

- Curriculum Architecture
- Program Learning Outcomes
- Graduate Competencies

**Downstream Artifacts**

- Course Specifications
- Weekly Modules
- Lesson Plans
- Assessment Strategy
- Curriculum Maps

---

## 7.11.1 Course Classification

Every course shall be assigned to one or more classifications appropriate to the academic program.

Examples include:

- General Education
- Core Program Course
- Major Requirement
- Technical Elective
- Supporting Course
- Capstone Course
- Internship
- Independent Study

Institutions may define additional classifications as appropriate.

---

## 7.11.2 Course Relationships

Course relationships define the educational dependencies among courses.

Relationships may include:

- Prerequisite
- Co-requisite
- Recommended Preparation
- Concurrent Enrollment
- Equivalent Course
- Replacement Course

Course relationships shall support logical learning progression and competency development.

---

## 7.11.3 Course Responsibilities

Each course shall contribute to one or more aspects of the academic program.

Course responsibilities may include:

- Introducing Program Learning Outcomes
- Reinforcing Program Learning Outcomes
- Applying Program Learning Outcomes
- Supporting mastery of Program Learning Outcomes
- Developing Graduate Competencies
- Collecting assessment evidence

Every required course shall have clearly defined educational responsibilities.

---

## 7.11.4 Course Interfaces

Courses do not function independently.

Each course interfaces with other curriculum components through:

- prerequisite knowledge;
- subsequent coursework;
- competency development;
- assessment evidence;
- curriculum mapping.

Course interfaces shall minimize redundancy while supporting progressive learning.

---

## 7.11.5 Course Coverage

The Course Architecture shall demonstrate that all Program Learning Outcomes and Graduate Competencies are supported by one or more required courses.

No required Program Learning Outcome or Graduate Competency shall exist without course-level implementation.

---

## 7.11.6 Engineering Relationships

Course Architecture establishes the connection between curriculum design and instructional implementation.

```text
Curriculum Architecture
            │
            ▼
Course Architecture
            │
     ┌──────┼──────┐
     ▼      ▼      ▼
Course  Course  Course
 Spec     Spec    Spec
     │      │      │
     └──────┼──────┘
            ▼
Weekly Modules
            ▼
Lessons
            ▼
Assessments
```

---

## 7.11.7 Conformance

A Program Specification conforms to this section when:

- one Course Architecture is defined;
- every required course is represented;
- every required course satisfies **ATLAS-STD-001**;
- every Program Learning Outcome is supported by one or more courses;
- every Graduate Competency is supported by one or more courses;
- prerequisite relationships are documented and justified;
- course sequencing supports progressive competency development.

## 7.12 Learning Progression

### Purpose

Learning Progression defines the intentional developmental pathway through which students acquire, reinforce, apply, and ultimately master the knowledge, skills, abilities, and professional competencies required for successful completion of the academic program.

Learning Progression ensures that learning experiences are organized to support continuous intellectual, technical, and professional growth throughout the curriculum.

Learning Progression provides the engineering framework for sequencing courses, learning activities, assessments, and competency development.

---

### Required Information

Every Program Specification shall define one Learning Progression.

The Learning Progression shall identify:

- developmental stages;
- competency progression;
- Program Learning Outcome progression;
- prerequisite dependencies;
- major learning milestones;
- capstone preparation;
- expected graduate achievement.

---

### Requirements

**REQ-STD009-7.12-001**

Every Program Specification shall define one Learning Progression.

---

**REQ-STD009-7.12-002**

Every Program Learning Outcome shall demonstrate progression throughout the curriculum.

---

**REQ-STD009-7.12-003**

Every Graduate Competency shall demonstrate progressive development.

---

**REQ-STD009-7.12-004**

Learning Progression shall align with the Curriculum Architecture.

---

**REQ-STD009-7.12-005**

Learning Progression shall support logical prerequisite relationships.

---

**REQ-STD009-7.12-006**

Learning Progression shall culminate in demonstrated graduate competency.

---

### Quality Requirements

Learning Progression shall:

- promote continuous student development;
- minimize unnecessary repetition;
- support increasing levels of complexity;
- encourage authentic application;
- support independent learning;
- prepare students for professional practice.

---

### Traceability

Learning Progression shall maintain traceability to:

**Upstream Artifacts**

- Curriculum Architecture
- Program Learning Outcomes
- Graduate Competencies

**Downstream Artifacts**

- Course Specifications
- Weekly Modules
- Lesson Plans
- Assessment Strategy
- Curriculum Maps
- Capstone Experience

---

## 7.12.1 Developmental Stages

Learning Progression shall organize student development through defined stages of competency acquisition.

The Atlas Curriculum Engineering System defines four standard developmental stages:

| Stage | Abbreviation | Description |
|---------|--------------|-------------|
| Introduced | I | Students encounter new concepts, skills, or competencies for the first time. |
| Reinforced | R | Students strengthen understanding and increase proficiency through guided practice and repeated application. |
| Applied | A | Students independently apply competencies to authentic, increasingly complex problems and contexts. |
| Mastered | M | Students consistently demonstrate competency at the expected graduate level with minimal guidance. |

The I-R-A-M progression shall serve as the default competency progression model unless an approved alternative progression model is documented.

---

## 7.12.2 Competency Progression

Every Graduate Competency shall demonstrate progression through one or more developmental stages.

Competency progression shall:

- begin with introduction;
- include opportunities for reinforcement;
- provide authentic application experiences;
- culminate in demonstrated mastery.

No competency shall be expected to achieve mastery without prior developmental stages.

---

## 7.12.3 Program Learning Outcome Progression

Program Learning Outcomes shall be intentionally developed throughout the curriculum.

Each Program Learning Outcome shall identify where it is:

- Introduced;
- Reinforced;
- Applied;
- Mastered.

Program Learning Outcomes shall demonstrate sufficient instructional support prior to assessment of mastery.

---

## 7.12.4 Learning Milestones

Learning Progression shall define significant educational milestones within the curriculum.

Examples include:

- foundational knowledge;
- core technical skills;
- professional communication;
- collaborative practice;
- systems integration;
- capstone readiness;
- graduate readiness.

Milestones shall support continuous monitoring of student development.

---

## 7.12.5 Progression Mapping

Learning Progression shall be documented using one or more progression maps.

Progression maps shall identify:

- courses;
- Program Learning Outcomes;
- Graduate Competencies;
- developmental stages;
- major assessments;
- curriculum milestones.

Progression maps shall support curriculum review and continuous improvement.

---

## 7.12.6 Engineering Relationships

Learning Progression connects curriculum design with student development.

```text
Curriculum Architecture
            │
            ▼
Learning Progression
            │
      ┌─────┼─────┐
      ▼     ▼     ▼
 Program  Graduate Course
Learning Competencies Learning
Outcomes              Outcomes
      │
      ▼
Learning Activities
      │
      ▼
Assessments
      │
      ▼
Evidence
```

---

## 7.12.7 Conformance

A Program Specification conforms to this section when:

- one Learning Progression is defined;
- every Program Learning Outcome demonstrates progression;
- every Graduate Competency demonstrates progression;
- progression aligns with Curriculum Architecture;
- progression culminates in graduate readiness;
- progression is supported by documented evidence throughout the curriculum.

## 7.13 Assessment Strategy

### Purpose

Assessment Strategy defines the systematic approach used to evaluate student achievement of Program Learning Outcomes and Graduate Competencies throughout the academic program.

Assessment Strategy establishes the framework for collecting, analyzing, and interpreting evidence of student learning to support instructional effectiveness, program quality, and continuous improvement.

---

### Required Information

Every Program Specification shall define one Assessment Strategy.

The Assessment Strategy shall identify:

- assessment philosophy;
- assessment methods;
- formative assessment practices;
- summative assessment practices;
- assessment schedule;
- Program Learning Outcome assessment;
- Graduate Competency assessment;
- performance criteria;
- assessment responsibilities;
- evidence collection methods.

---

### Requirements

**REQ-STD009-7.13-001**

Every Program Specification shall define one Assessment Strategy.

---

**REQ-STD009-7.13-002**

Every Program Learning Outcome shall be assessed using one or more documented assessment methods.

---

**REQ-STD009-7.13-003**

Every Graduate Competency shall be assessed using one or more documented assessment methods.

---

**REQ-STD009-7.13-004**

The Assessment Strategy shall include both formative and summative assessment methods.

---

**REQ-STD009-7.13-005**

Assessment methods shall align with the intended learning outcomes and competency expectations.

---

**REQ-STD009-7.13-006**

Assessment shall occur throughout the curriculum to support continuous measurement of student progress.

---

**REQ-STD009-7.13-007**

Assessment results shall provide evidence suitable for program evaluation and continuous improvement.

---

### Quality Requirements

Assessment Strategy shall:

- support valid measurement of learning;
- promote reliable evaluation practices;
- ensure fairness and consistency;
- encourage authentic demonstration of competency;
- provide meaningful feedback to students and faculty;
- generate evidence suitable for program evaluation.

---

### Traceability

Assessment Strategy shall maintain traceability to:

**Upstream Artifacts**

- Program Learning Outcomes
- Graduate Competencies
- Learning Progression
- Curriculum Architecture

**Downstream Artifacts**

- Course Specifications
- Assessment Plans
- Rubrics
- Assessment Evidence
- Program Evaluation
- Continuous Improvement Plans

---

## 7.13.1 Assessment Philosophy

Assessment shall support student learning while providing objective evidence of educational effectiveness.

Assessment activities shall be:

- aligned with intended learning outcomes;
- appropriate to the level of instruction;
- transparent to students;
- consistently administered;
- based on documented performance expectations.

---

## 7.13.2 Formative Assessment

Formative assessment provides ongoing feedback to support student learning during instruction.

Examples include:

- quizzes;
- practice exercises;
- laboratory activities;
- draft submissions;
- peer review;
- instructor feedback;
- classroom discussions.

Formative assessment should be used to guide instructional adjustments and improve student performance prior to summative evaluation.

---

## 7.13.3 Summative Assessment

Summative assessment evaluates achievement following completion of significant instructional activities.

Examples include:

- examinations;
- major projects;
- portfolios;
- presentations;
- capstone experiences;
- performance demonstrations;
- certification examinations.

Summative assessment shall provide evidence of student achievement relative to Program Learning Outcomes and Graduate Competencies.

---

## 7.13.4 Assessment Alignment

Every assessment activity shall align with one or more:

- Program Learning Outcomes;
- Course Learning Outcomes;
- Graduate Competencies.

Assessment activities shall measure the intended knowledge, skills, or competencies identified by the associated learning outcomes.

---

## 7.13.5 Assessment Responsibilities

The Assessment Strategy shall identify responsibilities for:

- assessment design;
- assessment administration;
- scoring and evaluation;
- evidence collection;
- results analysis;
- reporting;
- continuous improvement activities.

Responsibilities shall be clearly documented and consistently applied.

---

## 7.13.6 Engineering Relationships

Assessment Strategy connects learning with measurable evidence.

```text
Learning Progression
          │
          ▼
Program Learning Outcomes
          │
          ▼
Graduate Competencies
          │
          ▼
Assessment Strategy
          │
     ┌────┼────┐
     ▼    ▼    ▼
Formative
Assessment

Summative
Assessment

Rubrics
     │
     ▼
Assessment Evidence
     │
     ▼
Program Evaluation
```

---

## 7.13.7 Conformance

A Program Specification conforms to this section when:

- one Assessment Strategy is defined;
- every Program Learning Outcome is assessed;
- every Graduate Competency is assessed;
- formative and summative assessment methods are documented;
- assessment methods align with intended learning outcomes;
- assessment responsibilities are documented;
- assessment results support program evaluation and continuous improvement.

## 7.14 Evidence Collection

### Purpose

Evidence Collection defines the systematic process for identifying, collecting, organizing, storing, and maintaining evidence that demonstrates student achievement of Program Learning Outcomes and Graduate Competencies.

Evidence Collection provides the factual basis for program evaluation, accreditation activities, curriculum review, and continuous improvement.

---

### Required Information

Every Program Specification shall define one Evidence Collection strategy.

The Evidence Collection strategy shall identify:

- evidence sources;
- evidence types;
- collection methods;
- collection frequency;
- responsible parties;
- storage requirements;
- retention requirements;
- evidence accessibility;
- evidence security;
- evidence usage.

---

### Requirements

**REQ-STD009-7.14-001**

Every Program Specification shall define one Evidence Collection strategy.

---

**REQ-STD009-7.14-002**

Evidence shall be collected for every Program Learning Outcome.

---

**REQ-STD009-7.14-003**

Evidence shall be collected for every Graduate Competency.

---

**REQ-STD009-7.14-004**

Evidence collection methods shall be documented.

---

**REQ-STD009-7.14-005**

Evidence shall be maintained in a manner that supports program evaluation and continuous improvement.

---

**REQ-STD009-7.14-006**

Evidence shall be retained according to institutional policies and applicable regulatory requirements.

---

**REQ-STD009-7.14-007**

Evidence shall be protected to ensure confidentiality, integrity, and appropriate accessibility.

---

### Quality Requirements

Evidence Collection shall:

- support objective evaluation;
- provide sufficient evidence for decision making;
- ensure data integrity;
- maintain consistency of collection practices;
- support long-term analysis;
- protect confidential student information.

---

### Traceability

Evidence Collection shall maintain traceability to:

**Upstream Artifacts**

- Assessment Strategy
- Program Learning Outcomes
- Graduate Competencies
- Learning Progression

**Downstream Artifacts**

- Program Evaluation
- Quality Assurance
- Accreditation Reports
- Continuous Improvement Plans

---

## 7.14.1 Evidence Sources

Evidence may be obtained from multiple sources, including:

- examinations;
- projects;
- laboratory activities;
- portfolios;
- presentations;
- capstone projects;
- internships;
- certification examinations;
- clinical or field experiences;
- student reflections.

Evidence sources shall align with the associated assessment methods.

---

## 7.14.2 Evidence Types

Evidence may include:

- quantitative data;
- qualitative observations;
- performance artifacts;
- assessment scores;
- rubric evaluations;
- competency demonstrations;
- employer feedback;
- student feedback;
- graduate outcomes.

Evidence types shall be appropriate for the intended evaluation purpose.

---

## 7.14.3 Collection Methods

Evidence shall be collected using documented procedures.

Collection methods shall identify:

- what evidence is collected;
- when evidence is collected;
- who collects the evidence;
- where evidence is stored;
- how evidence is verified.

Collection procedures shall promote consistency across the academic program.

---

## 7.14.4 Evidence Management

The Evidence Collection strategy shall define procedures for:

- evidence organization;
- storage;
- access control;
- retention;
- archival;
- disposal, when appropriate.

Evidence management practices shall support institutional governance and applicable legal requirements.

---

## 7.14.5 Evidence Utilization

Collected evidence shall support:

- assessment of Program Learning Outcomes;
- assessment of Graduate Competencies;
- curriculum evaluation;
- faculty review;
- accreditation activities;
- program improvement;
- strategic planning.

Evidence shall be used to support documented, evidence-based decision making.

---

## 7.14.6 Engineering Relationships

Evidence Collection provides measurable proof of educational effectiveness.

```text
Assessment Strategy
          │
          ▼
Assessment Activities
          │
          ▼
Assessment Results
          │
          ▼
Evidence Collection
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Storage Analysis Reporting
          │
          ▼
Program Evaluation
          │
          ▼
Continuous Improvement
```

---

## 7.14.7 Conformance

A Program Specification conforms to this section when:

- one Evidence Collection strategy is defined;
- evidence is collected for every Program Learning Outcome;
- evidence is collected for every Graduate Competency;
- collection procedures are documented;
- evidence management practices are established;
- evidence supports program evaluation and continuous improvement;
- evidence is protected in accordance with institutional policies and applicable regulations.

## 7.15 Program Evaluation

### Purpose

Program Evaluation defines the systematic process for analyzing assessment evidence to determine the effectiveness of the academic program in achieving its mission, educational objectives, Program Learning Outcomes, and Graduate Competencies.

Program Evaluation supports informed decision-making by identifying program strengths, improvement opportunities, and the effectiveness of curriculum design and instructional practices.

---

### Required Information

Every Program Specification shall define one Program Evaluation process.

The Program Evaluation process shall identify:

- evaluation objectives;
- evaluation criteria;
- evaluation frequency;
- performance indicators;
- evidence sources;
- responsible parties;
- reporting requirements;
- decision-making procedures;
- improvement planning.

---

### Requirements

**REQ-STD009-7.15-001**

Every Program Specification shall define one Program Evaluation process.

---

**REQ-STD009-7.15-002**

Program Evaluation shall utilize evidence collected through the Assessment Strategy and Evidence Collection process.

---

**REQ-STD009-7.15-003**

Program Evaluation shall determine the extent to which Program Learning Outcomes are achieved.

---

**REQ-STD009-7.15-004**

Program Evaluation shall determine the extent to which Graduate Competencies are achieved.

---

**REQ-STD009-7.15-005**

Program Evaluation shall identify program strengths, deficiencies, risks, and opportunities for improvement.

---

**REQ-STD009-7.15-006**

Program Evaluation results shall be documented and communicated to appropriate stakeholders.

---

**REQ-STD009-7.15-007**

Program Evaluation results shall support Continuous Improvement activities.

---

### Quality Requirements

Program Evaluation shall:

- be evidence-based;
- be objective and repeatable;
- support data-informed decision making;
- evaluate the program as an integrated educational system;
- identify measurable improvement opportunities;
- support long-term program quality.

---

### Traceability

Program Evaluation shall maintain traceability to:

**Upstream Artifacts**

- Assessment Strategy
- Evidence Collection
- Program Learning Outcomes
- Graduate Competencies
- Educational Objectives

**Downstream Artifacts**

- Continuous Improvement Plans
- Curriculum Revisions
- Resource Planning
- Accreditation Reports
- Strategic Planning

---

## 7.15.1 Evaluation Objectives

Program Evaluation shall determine the effectiveness of the academic program in achieving its intended educational outcomes.

Evaluation objectives shall include:

- achievement of Program Learning Outcomes;
- development of Graduate Competencies;
- alignment with Educational Objectives;
- curriculum effectiveness;
- instructional effectiveness;
- student success;
- graduate readiness.

---

## 7.15.2 Evaluation Criteria

Evaluation criteria shall establish measurable standards for determining program effectiveness.

Criteria may include:

- student achievement data;
- assessment performance;
- competency attainment;
- completion rates;
- graduation rates;
- certification results;
- employment outcomes;
- employer feedback;
- student satisfaction;
- graduate satisfaction.

Evaluation criteria shall be appropriate for the academic discipline and institutional mission.

---

## 7.15.3 Evaluation Process

The Program Evaluation process shall define procedures for:

- collecting evaluation data;
- analyzing evidence;
- identifying trends;
- comparing performance against established criteria;
- documenting findings;
- recommending corrective actions.

The evaluation process shall be documented and consistently applied.

---

## 7.15.4 Evaluation Reporting

Program Evaluation results shall be documented in formal evaluation reports.

Evaluation reports shall summarize:

- findings;
- supporting evidence;
- conclusions;
- identified risks;
- recommended improvements;
- planned corrective actions.

Reports shall be available to authorized stakeholders.

---

## 7.15.5 Stakeholder Participation

Program Evaluation shall include participation from appropriate stakeholders, which may include:

- program faculty;
- academic administrators;
- advisory committees;
- industry representatives;
- students;
- graduates;
- institutional assessment personnel.

Stakeholder participation shall support comprehensive program evaluation and informed decision making.

---

## 7.15.6 Engineering Relationships

Program Evaluation transforms assessment evidence into actionable program improvements.

```text
Assessment Strategy
          │
          ▼
Evidence Collection
          │
          ▼
Program Evaluation
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Analysis Findings Recommendations
          │
          ▼
Continuous Improvement
          │
          ▼
Program Revision
```

---

## 7.15.7 Conformance

A Program Specification conforms to this section when:

- one Program Evaluation process is defined;
- evaluation is based on documented evidence;
- Program Learning Outcomes are evaluated;
- Graduate Competencies are evaluated;
- evaluation findings are documented;
- stakeholders participate as appropriate;
- evaluation results support continuous improvement and program quality enhancement.

## 7.16 Industry Alignment

### Purpose

Industry Alignment defines the systematic process for ensuring that the academic program remains relevant to current and emerging workforce needs, professional practices, industry standards, and technological advancements.

Industry Alignment supports the continuous relevance of Program Learning Outcomes, Graduate Competencies, Curriculum Architecture, and instructional content through collaboration with industry stakeholders.

---

### Required Information

Every Program Specification shall define one Industry Alignment strategy.

The Industry Alignment strategy shall identify:

- industry sectors served;
- workforce needs;
- industry standards;
- advisory committee participation;
- employer engagement;
- technology trends;
- professional certifications;
- external partnerships;
- review frequency;
- improvement processes.

---

### Requirements

**REQ-STD009-7.16-001**

Every Program Specification shall define one Industry Alignment strategy.

---

**REQ-STD009-7.16-002**

The academic program shall identify the industries and professional disciplines it is intended to serve.

---

**REQ-STD009-7.16-003**

Program Learning Outcomes shall be periodically reviewed for alignment with current industry expectations.

---

**REQ-STD009-7.16-004**

Graduate Competencies shall be periodically reviewed for alignment with current professional practice.

---

**REQ-STD009-7.16-005**

Industry stakeholders shall have opportunities to provide input into program evaluation and improvement.

---

**REQ-STD009-7.16-006**

The Industry Alignment strategy shall identify mechanisms for monitoring changes in technology, workforce demands, and professional standards.

---

**REQ-STD009-7.16-007**

Findings from Industry Alignment activities shall support curriculum review and continuous improvement.

---

### Quality Requirements

Industry Alignment shall:

- maintain workforce relevance;
- support graduate employability;
- promote professional readiness;
- encourage engagement with industry partners;
- identify emerging technologies and practices;
- support long-term program sustainability.

---

### Traceability

Industry Alignment shall maintain traceability to:

**Upstream Artifacts**

- Program Mission
- Educational Objectives
- Program Learning Outcomes
- Graduate Competencies
- Program Evaluation

**Downstream Artifacts**

- Curriculum Revisions
- Course Specifications
- Continuous Improvement Plans
- Advisory Committee Reports
- Strategic Planning

---

## 7.16.1 Workforce Needs

The Industry Alignment strategy shall identify the workforce needs addressed by the academic program.

Workforce needs may include:

- occupational competencies;
- technical skills;
- professional skills;
- emerging technologies;
- regional workforce priorities;
- national workforce trends.

Workforce needs shall be periodically reviewed and documented.

---

## 7.16.2 Industry Engagement

The academic program shall establish mechanisms for engagement with industry stakeholders.

Engagement activities may include:

- advisory committees;
- employer surveys;
- internship partnerships;
- cooperative education;
- guest speakers;
- industry-sponsored projects;
- professional association participation;
- workforce development initiatives.

Industry engagement shall provide meaningful input into curriculum planning and evaluation.

---

## 7.16.3 Professional Standards

The Industry Alignment strategy shall identify applicable professional standards, certifications, regulations, or best practices relevant to the academic discipline.

Where applicable, the academic program shall consider alignment with:

- professional certification objectives;
- industry frameworks;
- occupational standards;
- licensing requirements;
- employer expectations.

---

## 7.16.4 Technology Monitoring

The academic program shall establish procedures for monitoring significant technological developments relevant to the discipline.

Technology monitoring may include:

- software and hardware advancements;
- industry tools and platforms;
- development methodologies;
- regulatory changes;
- research trends;
- automation and artificial intelligence.

Technology monitoring shall inform curriculum planning and program improvement.

---

## 7.16.5 Industry Feedback

Industry feedback shall be collected and analyzed as part of the Program Evaluation process.

Feedback may include:

- employer evaluations;
- internship supervisor feedback;
- advisory committee recommendations;
- graduate employment outcomes;
- workforce trend analysis.

Documented feedback shall support evidence-based curriculum improvement.

---

## 7.16.6 Engineering Relationships

Industry Alignment ensures that the academic program remains connected to professional practice.

```text
Industry Trends
          │
          ▼
Industry Alignment
          │
     ┌────┼────┐
     ▼    ▼    ▼
Workforce Professional Technology
Needs      Standards    Trends
          │
          ▼
Program Evaluation
          │
          ▼
Curriculum Revision
          │
          ▼
Continuous Improvement
```

---

## 7.16.7 Conformance

A Program Specification conforms to this section when:

- one Industry Alignment strategy is defined;
- workforce needs are identified;
- Program Learning Outcomes are periodically reviewed;
- Graduate Competencies are periodically reviewed;
- industry stakeholders participate in program improvement;
- technology and professional trends are monitored;
- findings support curriculum review and continuous improvement.

## 7.17 Accreditation Alignment

### Purpose

Accreditation Alignment defines the systematic process for ensuring that the academic program maintains alignment with applicable institutional, regional, national, professional, and specialized accreditation standards.

Accreditation Alignment supports educational quality, regulatory compliance, accountability, and continuous program improvement through the integration of accreditation requirements into program planning, evaluation, and governance.

---

### Required Information

Every Program Specification shall define one Accreditation Alignment strategy.

The Accreditation Alignment strategy shall identify:

- applicable accrediting organizations;
- accreditation standards;
- compliance responsibilities;
- evidence requirements;
- reporting requirements;
- review cycles;
- accreditation risks;
- corrective action procedures;
- continuous compliance activities.

---

### Requirements

**REQ-STD009-7.17-001**

Every Program Specification shall define one Accreditation Alignment strategy.

---

**REQ-STD009-7.17-002**

The academic program shall identify all applicable accreditation and regulatory requirements.

---

**REQ-STD009-7.17-003**

Program Learning Outcomes shall demonstrate alignment with applicable accreditation requirements, where required.

---

**REQ-STD009-7.17-004**

Evidence supporting accreditation compliance shall be identified and maintained.

---

**REQ-STD009-7.17-005**

The Accreditation Alignment strategy shall define responsibilities for maintaining compliance with applicable accreditation requirements.

---

**REQ-STD009-7.17-006**

Accreditation requirements shall be periodically reviewed for changes that may affect the academic program.

---

**REQ-STD009-7.17-007**

Accreditation findings shall support Program Evaluation and Continuous Improvement activities.

---

### Quality Requirements

Accreditation Alignment shall:

- support continuous compliance;
- promote educational quality;
- reduce accreditation risk;
- ensure documentation consistency;
- support evidence-based accreditation reporting;
- facilitate continuous program improvement.

---

### Traceability

Accreditation Alignment shall maintain traceability to:

**Upstream Artifacts**

- Program Mission
- Educational Objectives
- Program Learning Outcomes
- Program Evaluation
- Industry Alignment

**Downstream Artifacts**

- Accreditation Reports
- Compliance Documentation
- Continuous Improvement Plans
- Program Revisions
- Institutional Reporting

---

## 7.17.1 Applicable Standards

The Accreditation Alignment strategy shall identify all accreditation, regulatory, and institutional standards applicable to the academic program.

Applicable standards may include:

- institutional policies;
- regional accreditation requirements;
- programmatic accreditation requirements;
- governmental regulations;
- licensing requirements;
- professional education standards.

Applicable standards shall be documented and periodically reviewed.

---

## 7.17.2 Compliance Management

The academic program shall establish procedures for maintaining compliance with applicable accreditation requirements.

Compliance management shall include:

- requirement identification;
- evidence collection;
- documentation maintenance;
- compliance monitoring;
- corrective action management;
- reporting.

Compliance activities shall be documented and consistently performed.

---

## 7.17.3 Accreditation Evidence

The Accreditation Alignment strategy shall identify evidence used to demonstrate compliance.

Evidence may include:

- assessment results;
- curriculum maps;
- Program Learning Outcome evaluations;
- Graduate Competency assessments;
- faculty qualifications;
- advisory committee documentation;
- program evaluation reports;
- continuous improvement records.

Evidence shall be maintained in accordance with institutional policies.

---

## 7.17.4 Accreditation Review

The academic program shall establish procedures for preparing for accreditation reviews.

Preparation activities may include:

- self-study development;
- internal audits;
- evidence verification;
- documentation review;
- corrective action implementation;
- stakeholder preparation.

Accreditation preparation shall support timely and accurate reporting.

---

## 7.17.5 Accreditation Findings

Accreditation findings shall be analyzed to identify:

- strengths;
- deficiencies;
- recommendations;
- compliance risks;
- opportunities for improvement.

Findings shall be incorporated into the Program Evaluation and Continuous Improvement processes.

---

## 7.17.6 Engineering Relationships

Accreditation Alignment connects external quality standards with internal program governance.

```text
Accreditation Standards
          │
          ▼
Accreditation Alignment
          │
     ┌────┼────┐
     ▼    ▼    ▼
Compliance Evidence Reviews
          │
          ▼
Program Evaluation
          │
          ▼
Continuous Improvement
          │
          ▼
Program Revision
```

---

## 7.17.7 Conformance

A Program Specification conforms to this section when:

- one Accreditation Alignment strategy is defined;
- applicable accreditation requirements are identified;
- compliance responsibilities are documented;
- accreditation evidence is maintained;
- accreditation reviews are supported by documented procedures;
- accreditation findings inform Program Evaluation and Continuous Improvement activities.

## 7.18 Resource Requirements

### Purpose

Resource Requirements defines the personnel, facilities, technology, equipment, instructional materials, financial resources, and support services necessary to effectively implement, deliver, maintain, and continuously improve the academic program.

Resource Requirements ensure that the academic program possesses the operational capability required to achieve its mission, Educational Objectives, Program Learning Outcomes, and Graduate Competencies.

---

### Required Information

Every Program Specification shall define one Resource Requirements specification.

The Resource Requirements specification shall identify:

- personnel requirements;
- faculty qualifications;
- instructional facilities;
- laboratory and equipment requirements;
- technology requirements;
- instructional materials;
- financial resource considerations;
- student support services;
- administrative support;
- resource review frequency.

---

### Requirements

**REQ-STD009-7.18-001**

Every Program Specification shall define one Resource Requirements specification.

---

**REQ-STD009-7.18-002**

The academic program shall identify the personnel necessary to support program delivery.

---

**REQ-STD009-7.18-003**

Faculty qualifications shall be appropriate for the academic discipline and institutional requirements.

---

**REQ-STD009-7.18-004**

Facilities, laboratories, equipment, and technology shall support achievement of Program Learning Outcomes and Graduate Competencies.

---

**REQ-STD009-7.18-005**

Instructional materials shall support the Curriculum Architecture and Learning Progression.

---

**REQ-STD009-7.18-006**

Resource needs shall be periodically reviewed to ensure continued program effectiveness.

---

**REQ-STD009-7.18-007**

Resource planning shall support Continuous Improvement activities.

---

### Quality Requirements

Resource Requirements shall:

- support effective instruction;
- provide appropriate learning environments;
- ensure access to required technologies;
- support student success;
- enable faculty effectiveness;
- promote sustainable program operation.

---

### Traceability

Resource Requirements shall maintain traceability to:

**Upstream Artifacts**

- Program Mission
- Curriculum Architecture
- Learning Progression
- Program Evaluation
- Industry Alignment

**Downstream Artifacts**

- Budget Planning
- Equipment Planning
- Faculty Development Plans
- Technology Refresh Plans
- Continuous Improvement Plans

---

## 7.18.1 Personnel Requirements

The academic program shall identify the personnel necessary to support successful program delivery.

Personnel may include:

- faculty;
- laboratory instructors;
- instructional designers;
- academic advisors;
- technical support personnel;
- program coordinators;
- administrative staff.

Personnel requirements shall be periodically reviewed.

---

## 7.18.2 Faculty Qualifications

Faculty qualifications shall support achievement of the academic program's Educational Objectives.

Qualifications may include:

- academic credentials;
- professional certifications;
- industry experience;
- teaching experience;
- continuing professional development;
- disciplinary expertise.

Qualification expectations shall align with institutional policies and applicable accreditation requirements.

---

## 7.18.3 Facilities and Technology

The academic program shall identify facilities and technology necessary to support learning.

Resources may include:

- classrooms;
- laboratories;
- specialized instructional spaces;
- computer systems;
- software platforms;
- networking infrastructure;
- simulation environments;
- online learning technologies.

Facilities and technology shall support both current instructional needs and anticipated program growth.

---

## 7.18.4 Instructional Resources

The academic program shall identify instructional resources required to support student learning.

Instructional resources may include:

- textbooks;
- reference materials;
- digital learning resources;
- software licenses;
- laboratory supplies;
- instructional media;
- open educational resources.

Instructional resources shall be reviewed periodically for relevance and effectiveness.

---

## 7.18.5 Student Support Resources

The academic program shall identify student support resources necessary to promote academic success.

Support resources may include:

- tutoring;
- advising;
- career services;
- library services;
- accessibility services;
- technical support;
- internship coordination.

Support services shall align with institutional policies and student needs.

---

## 7.18.6 Engineering Relationships

Resource Requirements provide the operational capability necessary to implement the academic program.

```text
Program Architecture
          │
          ▼
Resource Requirements
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Personnel Facilities Technology
          │
          ▼
Instructional Delivery
          │
          ▼
Assessment & Learning
          │
          ▼
Program Evaluation
          │
          ▼
Continuous Improvement
```

---

## 7.18.7 Conformance

A Program Specification conforms to this section when:

- one Resource Requirements specification is defined;
- personnel requirements are documented;
- faculty qualification expectations are identified;
- facilities and technology support the Curriculum Architecture;
- instructional and student support resources are documented;
- resource needs are periodically reviewed;
- resource planning supports Continuous Improvement.

## 7.19 Governance

### Purpose

Governance defines the organizational structure, roles, responsibilities, decision-making processes, and oversight mechanisms necessary to effectively manage, maintain, and continuously improve the academic program.

Governance ensures accountability, transparency, consistency, and effective stewardship of the academic program throughout its lifecycle.

---

### Required Information

Every Program Specification shall define one Governance structure.

The Governance structure shall identify:

- governance objectives;
- governance roles;
- governance responsibilities;
- decision-making authority;
- reporting relationships;
- stakeholder participation;
- review responsibilities;
- approval processes;
- governance review frequency.

---

### Requirements

**REQ-STD009-7.19-001**

Every Program Specification shall define one Governance structure.

---

**REQ-STD009-7.19-002**

Governance roles and responsibilities shall be documented.

---

**REQ-STD009-7.19-003**

Decision-making authority shall be clearly defined.

---

**REQ-STD009-7.19-004**

The Governance structure shall identify responsibilities for Program Evaluation, Quality Assurance, and Continuous Improvement.

---

**REQ-STD009-7.19-005**

Stakeholders shall have opportunities to participate in governance activities appropriate to their roles.

---

**REQ-STD009-7.19-006**

Governance activities shall be documented and periodically reviewed.

---

**REQ-STD009-7.19-007**

Governance decisions affecting the academic program shall support achievement of the Program Mission, Educational Objectives, Program Learning Outcomes, and Graduate Competencies.

---

### Quality Requirements

Governance shall:

- promote accountability;
- support transparent decision making;
- encourage stakeholder participation;
- support consistent program management;
- facilitate timely decision making;
- ensure effective oversight of program quality.

---

### Traceability

Governance shall maintain traceability to:

**Upstream Artifacts**

- Program Mission
- Educational Objectives
- Program Evaluation
- Industry Alignment
- Accreditation Alignment

**Downstream Artifacts**

- Quality Assurance
- Continuous Improvement Plans
- Program Revisions
- Resource Planning
- Annual Program Reports

---

## 7.19.1 Governance Roles

The Governance structure shall identify the roles responsible for oversight and management of the academic program.

Governance roles may include:

- program coordinator;
- department chair;
- faculty;
- curriculum committee;
- advisory committee;
- academic administration;
- institutional assessment personnel.

Governance roles shall include clearly defined responsibilities and decision-making authority.

---

## 7.19.2 Responsibilities

Governance responsibilities may include:

- curriculum oversight;
- assessment oversight;
- Program Evaluation;
- resource planning;
- accreditation coordination;
- policy implementation;
- risk management;
- Continuous Improvement.

Responsibilities shall be assigned to one or more governance roles.

---

## 7.19.3 Decision-Making

The Governance structure shall define procedures for program-level decision making.

Decision-making activities may include:

- curriculum revisions;
- program approval recommendations;
- assessment improvements;
- resource allocation recommendations;
- technology adoption;
- policy updates.

Decision-making processes shall be documented and consistently applied.

---

## 7.19.4 Stakeholder Participation

Governance shall provide opportunities for participation by appropriate stakeholders.

Stakeholders may include:

- faculty;
- administrators;
- students;
- graduates;
- employers;
- advisory committee members;
- institutional support personnel.

Stakeholder participation shall support informed, evidence-based decision making.

---

## 7.19.5 Governance Review

The Governance structure shall be periodically reviewed to ensure continued effectiveness.

Governance reviews shall evaluate:

- role effectiveness;
- decision-making efficiency;
- stakeholder participation;
- governance documentation;
- governance outcomes.

Review findings shall support Quality Assurance and Continuous Improvement.

---

## 7.19.6 Engineering Relationships

Governance provides organizational oversight for the academic program.

```text
Program Mission
          │
          ▼
Governance
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Oversight Decisions Accountability
          │
          ▼
Program Evaluation
          │
          ▼
Quality Assurance
          │
          ▼
Continuous Improvement
```

---

## 7.19.7 Conformance

A Program Specification conforms to this section when:

- one Governance structure is defined;
- governance roles and responsibilities are documented;
- decision-making authority is identified;
- stakeholder participation is supported;
- governance activities are periodically reviewed;
- governance supports Program Evaluation, Quality Assurance, and Continuous Improvement.

## 7.20 Quality Assurance

### Purpose

Quality Assurance defines the systematic processes used to verify that the academic program consistently meets its established requirements, Educational Objectives, Program Learning Outcomes, Graduate Competencies, institutional expectations, and applicable external standards.

Quality Assurance provides confidence that the academic program is operating effectively and in accordance with its approved Program Specification.

---

### Required Information

Every Program Specification shall define one Quality Assurance process.

The Quality Assurance process shall identify:

- quality objectives;
- quality standards;
- quality indicators;
- monitoring activities;
- review procedures;
- audit activities;
- performance measures;
- reporting requirements;
- corrective action procedures.

---

### Requirements

**REQ-STD009-7.20-001**

Every Program Specification shall define one Quality Assurance process.

---

**REQ-STD009-7.20-002**

Quality Assurance shall monitor achievement of Program Learning Outcomes and Graduate Competencies.

---

**REQ-STD009-7.20-003**

Quality Assurance shall verify conformance with this Program Specification.

---

**REQ-STD009-7.20-004**

Quality Assurance activities shall utilize evidence generated through Program Evaluation and Evidence Collection.

---

**REQ-STD009-7.20-005**

Quality Assurance findings shall identify strengths, deficiencies, risks, and opportunities for corrective action.

---

**REQ-STD009-7.20-006**

Quality Assurance activities shall be performed on a documented and periodic basis.

---

**REQ-STD009-7.20-007**

Quality Assurance findings shall support Continuous Improvement planning.

---

### Quality Requirements

Quality Assurance shall:

- be systematic and repeatable;
- utilize objective evidence;
- support consistent program performance;
- identify nonconformities;
- verify implementation of approved processes;
- promote a culture of quality and accountability.

---

### Traceability

Quality Assurance shall maintain traceability to:

**Upstream Artifacts**

- Program Evaluation
- Assessment Strategy
- Evidence Collection
- Governance
- Accreditation Alignment

**Downstream Artifacts**

- Continuous Improvement Plans
- Corrective Actions
- Program Revisions
- Annual Program Reports
- Accreditation Documentation

---

## 7.20.1 Quality Objectives

The Quality Assurance process shall establish measurable objectives for evaluating program performance.

Quality objectives may include:

- achievement of Program Learning Outcomes;
- Graduate Competency attainment;
- instructional effectiveness;
- curriculum effectiveness;
- student success;
- stakeholder satisfaction;
- compliance with institutional standards.

Quality objectives shall support continuous monitoring of program quality.

---

## 7.20.2 Monitoring Activities

The Quality Assurance process shall define procedures for monitoring program performance.

Monitoring activities may include:

- assessment reviews;
- curriculum reviews;
- internal audits;
- faculty reviews;
- student performance analysis;
- graduate outcome analysis;
- employer feedback analysis.

Monitoring activities shall be conducted according to documented procedures.

---

## 7.20.3 Audits and Reviews

Quality Assurance shall include periodic reviews of the academic program.

Reviews may evaluate:

- Program Specification conformance;
- assessment practices;
- evidence quality;
- curriculum implementation;
- governance effectiveness;
- resource adequacy.

Review findings shall be documented and communicated to appropriate stakeholders.

---

## 7.20.4 Corrective Actions

The Quality Assurance process shall define procedures for addressing identified deficiencies.

Corrective actions shall include:

- issue identification;
- root cause analysis;
- corrective action planning;
- implementation;
- verification of effectiveness.

Corrective actions shall be documented and monitored until completion.

---

## 7.20.5 Quality Reporting

Quality Assurance findings shall be documented in periodic quality reports.

Quality reports shall summarize:

- monitoring results;
- audit findings;
- identified risks;
- corrective actions;
- recommendations;
- overall program quality status.

Reports shall support Program Evaluation and Governance activities.

---

## 7.20.6 Engineering Relationships

Quality Assurance verifies that the academic program operates in accordance with its approved design.

```text
Program Specification
          │
          ▼
Quality Assurance
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Monitoring Reviews Audits
          │
          ▼
Findings
          │
          ▼
Corrective Actions
          │
          ▼
Continuous Improvement
```

---

## 7.20.7 Conformance

A Program Specification conforms to this section when:

- one Quality Assurance process is defined;
- quality objectives are documented;
- monitoring and review activities are established;
- conformance with the Program Specification is verified;
- corrective action procedures are documented;
- Quality Assurance findings support Continuous Improvement.

## 7.21 Continuous Improvement

### Purpose

Continuous Improvement defines the systematic process for identifying, planning, implementing, monitoring, and evaluating improvements to the academic program based on evidence obtained through Program Evaluation, Quality Assurance, Industry Alignment, Accreditation Alignment, and stakeholder feedback.

Continuous Improvement ensures that the academic program remains effective, relevant, sustainable, and responsive to changing educational, professional, and institutional needs.

---

### Required Information

Every Program Specification shall define one Continuous Improvement process.

The Continuous Improvement process shall identify:

- improvement objectives;
- improvement priorities;
- evidence sources;
- stakeholder participation;
- improvement planning procedures;
- implementation responsibilities;
- monitoring activities;
- effectiveness evaluation;
- documentation requirements.

---

### Requirements

**REQ-STD009-7.21-001**

Every Program Specification shall define one Continuous Improvement process.

---

**REQ-STD009-7.21-002**

Continuous Improvement activities shall be based on documented evidence obtained through Program Evaluation and Quality Assurance.

---

**REQ-STD009-7.21-003**

Improvement opportunities shall be identified, prioritized, and documented.

---

**REQ-STD009-7.21-004**

Improvement actions shall identify responsible parties, implementation timelines, and expected outcomes.

---

**REQ-STD009-7.21-005**

Completed improvement actions shall be evaluated to determine their effectiveness.

---

**REQ-STD009-7.21-006**

Continuous Improvement activities shall be documented and periodically reviewed.

---

**REQ-STD009-7.21-007**

Continuous Improvement shall support achievement of the Program Mission, Educational Objectives, Program Learning Outcomes, and Graduate Competencies.

---

### Quality Requirements

Continuous Improvement shall:

- be systematic and evidence-based;
- promote measurable enhancement of program quality;
- encourage stakeholder participation;
- support timely implementation of improvements;
- evaluate the effectiveness of implemented changes;
- foster a culture of continuous learning and innovation.

---

### Traceability

Continuous Improvement shall maintain traceability to:

**Upstream Artifacts**

- Program Evaluation
- Quality Assurance
- Industry Alignment
- Accreditation Alignment
- Governance

**Downstream Artifacts**

- Program Revisions
- Curriculum Revisions
- Resource Planning
- Strategic Planning
- Future Program Evaluations

---

## 7.21.1 Improvement Planning

The Continuous Improvement process shall establish procedures for planning program improvements.

Improvement planning shall include:

- identification of improvement opportunities;
- prioritization of actions;
- assignment of responsibilities;
- implementation schedules;
- expected outcomes;
- success criteria.

Improvement plans shall be documented and approved through the Governance structure.

---

## 7.21.2 Implementation

The Continuous Improvement process shall define procedures for implementing approved improvement actions.

Implementation activities may include:

- curriculum revisions;
- assessment improvements;
- technology enhancements;
- faculty development;
- resource enhancements;
- policy revisions;
- process improvements.

Implementation activities shall be documented and monitored.

---

## 7.21.3 Effectiveness Evaluation

Completed improvement actions shall be evaluated to determine whether intended outcomes have been achieved.

Effectiveness evaluation shall consider:

- updated assessment evidence;
- Program Learning Outcome performance;
- Graduate Competency attainment;
- stakeholder feedback;
- quality indicators;
- program performance measures.

Evaluation findings shall be documented.

---

## 7.21.4 Stakeholder Participation

Continuous Improvement shall encourage participation by appropriate stakeholders.

Stakeholders may include:

- faculty;
- academic administrators;
- advisory committee members;
- employers;
- students;
- graduates;
- institutional assessment personnel.

Stakeholder participation shall support informed and collaborative improvement planning.

---

## 7.21.5 Improvement Documentation

Continuous Improvement activities shall be documented to provide evidence of program evolution.

Documentation may include:

- improvement plans;
- implementation records;
- meeting minutes;
- action item tracking;
- effectiveness evaluations;
- lessons learned.

Documentation shall support future Program Evaluation and accreditation activities.

---

## 7.21.6 Engineering Relationships

Continuous Improvement completes the program engineering lifecycle by transforming evaluation findings into planned enhancements.

```text
Program Evaluation
          │
          ▼
Quality Assurance
          │
          ▼
Continuous Improvement
          │
     ┌────┼─────┐
     ▼    ▼     ▼
Planning Implementation Evaluation
          │
          ▼
Program Revision
          │
          ▼
Updated Program Specification
          │
          ▼
Next Evaluation Cycle
```

---

## 7.21.7 Conformance

A Program Specification conforms to this section when:

- one Continuous Improvement process is defined;
- improvement activities are evidence-based;
- improvement opportunities are documented and prioritized;
- implementation responsibilities are assigned;
- completed improvements are evaluated for effectiveness;
- improvement activities are documented;
- Continuous Improvement supports ongoing enhancement of the academic program.

## 7.22 Revision History

### Purpose

Revision History defines the requirements for documenting changes made to the Program Specification throughout its lifecycle.

Revision History provides configuration management, traceability, accountability, and historical context for all approved revisions to the Program Specification.

---

### Required Information

Every Program Specification shall maintain one Revision History.

The Revision History shall identify:

- revision identifier;
- revision date;
- revision summary;
- reason for the revision;
- approval authority;
- approval date;
- affected sections.

---

### Requirements

**REQ-STD009-7.22-001**

Every Program Specification shall maintain a Revision History.

---

**REQ-STD009-7.22-002**

Each approved revision shall receive a unique revision identifier.

---

**REQ-STD009-7.22-003**

Each revision shall identify the date on which the revision became effective.

---

**REQ-STD009-7.22-004**

Each revision shall include a concise description of the changes made.

---

**REQ-STD009-7.22-005**

Each revision shall identify the reason for the revision.

---

**REQ-STD009-7.22-006**

Each revision shall identify the approving authority.

---

**REQ-STD009-7.22-007**

Revision History entries shall be retained for the life of the Program Specification.

---

### Quality Requirements

Revision History shall:

- provide complete traceability of approved revisions;
- accurately document the evolution of the Program Specification;
- support accountability for approved changes;
- facilitate audits and accreditation activities;
- preserve historical records;
- promote effective configuration management.

---

### Traceability

Revision History shall maintain traceability to:

**Upstream Artifacts**

- Governance
- Quality Assurance
- Continuous Improvement

**Downstream Artifacts**

- Current Program Specification
- Historical Program Specifications
- Program Evaluation Reports
- Accreditation Documentation
- Institutional Records

---

## 7.22.1 Revision Identification

Each revision shall be uniquely identified using the institution's or organization's approved version identification method.

Version identifiers shall distinguish between major and minor revisions where applicable.

---

## 7.22.2 Revision Documentation

Each Revision History entry shall document:

- revision identifier;
- revision date;
- affected sections;
- summary of modifications;
- rationale for the revision;
- approval information.

Revision summaries shall be sufficiently detailed to understand the scope of the change.

---

## 7.22.3 Approval

Program Specification revisions shall be approved in accordance with the Governance structure.

Approval records shall identify:

- approving authority;
- approval date;
- approval method.

Only approved revisions shall become effective.

---

## 7.22.4 Record Retention

Revision History records shall be retained throughout the lifecycle of the Program Specification in accordance with institutional records management policies.

Historical revision information shall remain available for audit, accreditation, and program evaluation purposes.

---

## 7.22.5 Configuration Management

Revision History shall support configuration management by ensuring that:

- approved versions are uniquely identifiable;
- obsolete versions are retained but clearly identified;
- current versions are readily distinguishable;
- revision records remain complete and accurate.

Configuration management practices shall support document integrity and traceability.

---

## 7.22.6 Engineering Relationships

Revision History provides configuration control for the Program Specification throughout its lifecycle.

```text
Governance
      │
      ▼
Approved Changes
      │
      ▼
Revision History
      │
 ┌────┼─────┐
 ▼    ▼     ▼
Version Traceability Records
      │
      ▼
Current Program Specification
      │
      ▼
Future Revisions
```

---

## 7.22.7 Conformance

A Program Specification conforms to this section when:

- one Revision History is maintained;
- each approved revision has a unique identifier;
- revisions document the effective date, affected sections, rationale, and approval information;
- historical revision records are retained;
- configuration management practices support traceability and document integrity.
------------------------------------------------------------------------

# 8. Engineering Requirements

*Reserved for future development.*

------------------------------------------------------------------------

# 9. Relationships and Traceability

*Reserved for future development.*

------------------------------------------------------------------------

# 10. Quality Requirements

*Reserved for future development.*

------------------------------------------------------------------------

# 11. Verification and Validation

*Reserved for future development.*

------------------------------------------------------------------------

# 12. Lifecycle Management

*Reserved for future development.*

------------------------------------------------------------------------

# 13. Conformance

*Reserved for future development.*

------------------------------------------------------------------------

# Appendix A --- Program Specification Template (Normative)

*Reserved for future development.*

------------------------------------------------------------------------

# Appendix B --- Example Program Specification (Informative)

*Reserved for future development.*

------------------------------------------------------------------------

# Appendix C --- Traceability Matrix (Normative)

*Reserved for future development.*

------------------------------------------------------------------------

# Appendix D --- Conformance Checklist (Normative)

*Reserved for future development.*

------------------------------------------------------------------------

# Bibliography

*Reserved for future development.*
