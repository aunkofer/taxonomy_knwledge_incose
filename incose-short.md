# INCOSE Guide to Writing Requirements v3.1
A need set is a structured set of agreed-to need expressions for the entity (enterprise/business unit/system/subsystem/system element/process) and its external interfaces.
A requirement set is a structured set of agreed-to requirement expressions for the entity (enterprise/business unit/system/subsystem/system element/process) and its external interfaces.
## Characteristics of well-formed sets of needs requirements.
### Formal Transformation
Given the set of needs and
requirements is the result of a formal transformation, the
following characteristics of the need and requirement set
have been derived:
- C10 - Complete: The need or requirement set for a given
SOI should stand alone such that it sufficiently describes
the necessary capabilities, characteristics, functionality,
performance, drivers, constraints, interactions,
standards, regulations, and/or quality factors without
requiring other sets of needs or requirements at the
appropriate level of abstraction.
- C11 - Consistent: The sets of needs and requirements
contains individual needs or requirements that are
unique, do not conflict with or overlap with others in the
set, and the units and measurement systems they use
are homogeneous. The language used within the sets is
consistent (i.e., the same words are used throughout the
set to mean the same thing). All terms used within the
needs and requirements statements are consistent with
the architectural model, project glossary, and project
data dictionary.

### Agreed-to Obligation.
Since the set of need and requirements
is to be a result of a fair agreement to meet an obligation, the
following characteristics of the set have been derived:
- C12 - Feasible: Sets of needs and requirements can be
realized within entity constraints (for example, cost, schedule,
technical) with acceptable risk.
- C13 - Comprehensible: The set of needs and set of resulting
requirements must be written such that it is clear as to what is
expected of the entity and its relation to the macro system of
which it is a part.
- C14 - Able to be validated: It must be able to be validated that
the integrated set of needs will lead to the achievement of the
product goals and objectives, stakeholder expectations, risks,
and lifecycle concepts within the constraints (such as cost,
schedule, technical, legal and regulatory compliance) with
acceptable risk.
It must be able to be validated that the set of requirements will
lead to the achievement of the integrated set of needs and
higher-level requirements within the constraints (such as cost,
schedule, technical, and regulatory compliance) with
acceptable risk.

# Attributes of Need and Requirement Statements (defined in the NRM)
An attribute is additional information associated with an entity which is used to aid in its definition and management.
A need expression includes a need statement and a set of associated attributes.
A requirement expression includes a requirement statement and a set of associated attributes.
A minimum set of attributes that should be defined for each requirement are annotated with an asterisk (“*”)

### Attributes to Help Define Needs & Requirement and Their Intent
- A1 - Rationale*
- A2 - Trace to Parent*
- A3 - Trace to Source*
- A4 - States and Modes
- A5 - Allocation/Budgeting*
### Attributes Associated with System Verification & System Validation
- A6 - System Verification or System Validation Success Criteria*
- A7 - System Verification or System Validation Strategy*
- A8 - System Verification or System Validation Method*
- A9 - System Verification or System Validation Responsible
### Organization*
- A10 - System Verification or System Validation Level
- A11 - System Verification or System Validation Phase
- A12 - Condition of Use
- A13 -System Verification or System Validation Results
- A14 -System Verification or System Validation Status
### Attributes to Help Maintain the Requirements
- A15 - Unique Identifier*
- A16- Unique Name
- A17 - Originator/Author*
- A18 - Date Requirement Entered
- A19- Owner*
- A20 – Stakeholders
- A21 - Change Board
- A22 - Change Proposed
- A23 - Version Number
- A24 - Approval Date
- A25 - Date of Last Change
- A26 - Stability/Volatility
- A27 - Responsible Person
- A28 - Need or Requirement Verification Status*
- A29 - Need or Requirement Validation Status*
- A30 - Status of the Need or Requirement
- A31 - Status (of Implementation)
- A32 - Trace to Interface Definition
- A33 - Trace to Dependent Peer Requirements
- A34 - Priority*
- A35 - Criticality or Essentiality*
- A36 - Risk (of Implementation) *
- A37 - Risk (Mitigation)
- A38 - Key Driving Need or Requirement (KDN/KDR)
- A39 - Additional Comments
- A40 - Type/Category
### Attributes to Show Applicability and Allow Reuse
- A41- Applicability
- A42 - Region
- A43 - Country
- A44 - State/Province
- A45 - Market Segment
- A46 - Business Unit
### Attributes to Aid in Product Line Management
- A47 – Product Line
- A48 - Product Line Common Needs and Requirements
- A49 - Product Line Variant Needs and Requirements

# Rules for Need and Requirement Statements and Sets of Needs and Requirements

## Accuracy
- R1: Use a structured, complete sentence: subject, verb, object.
- R2: Use the active voice in the main sentence structure of the need or requirement statement with the responsible entity clearly identified as the subject of the sentence.
- R3: Ensure the subject and verb of the need or requirement statement are appropriate to the entity to which the need
or requirement refers.
- R4: Define terms in a glossary, data dictionary, etc.
- R5: Use definite article “the” rather than the indefinite article “a.”
- R6: Use appropriate units when stating quantities. All numbers should have units of measure explicitly stated.
- R7: Avoid the use of vague terms such as “some”, “any”, “allowable”, “several”, “many”, “a lot of”, “a few”, “almost always”, “very nearly”, “nearly”, “about”, “close to”, “almost”, and “approximate”.
- R8: Avoid escape clauses such as such as “so far as is possible”, “as little as possible”, “where possible”, “as much as possible”, “if it should prove necessary”, “if necessary”, “to the extent necessary”, “as appropriate”, “as required”, “to the extent practical”, and “if practicable".
- R9: Avoid open-ended clauses such as “including but not limited to”, “etc.” and “and so on.”.
## Concision
- R10: Avoid superfluous infinitives such as “ .. be designed to… ”, “…be able to … ..”, “…be capable of…”.
- R11: Use a separate clause for each condition or qualification.
## Non-ambiguity
- R12: Use correct grammar.
- R13: Use correct spelling.
- R14: Use correct punctuation.
- R15: Use a defined convention to express logical expressions such as “[X AND Y]”, “[X OR Y]”, [X XOR Y]”, “NOT[X OR Y]”.
- R16: Avoid the use of “not.”
- R17: Avoid the use of the oblique ("/") symbol except in units, i.e. Km/hr
## Singularity
- R18: Write a single sentence that contains a single thought conditioned and qualified by relevant sub-clauses.
- R19: Avoid combinators that join clauses, such as “and”, “or”, ”then”, ”unless”, ”but”, ”as well as”, ”but also”, ”however”, ”whether”, "meanwhile”, ”whereas”, ”on the other hand”, or ”otherwise.”
- R20: Avoid phrases that indicate the purpose of the need or requirement.
- R21: Avoid parentheses and brackets containing subordinate text.
- R22: Enumerate sets explicitly instead of using a group noun to name the set.
- R23: When a need or requirement is related to complex behavior, refer to the supporting diagram or model.
## Completeness
- R24: Avoid the use of pronouns and indefinite pronouns.
- R25: Avoid relying on headings to support explanation or understanding of the requirement.
## Realism
- R26: Avoid using unachievable absolutes such as 100% reliability, 100% availability, all, every, always, never, etc.
## Conditions
- R27: State applicability conditions explicitly.
- R28: Express the propositional nature of a condition explicitly for a single action instead of giving lists of actions for a specific condition.
## Uniqueness
- R29: Classify the needs and requirements according to the aspects of the problem or system it addresses.
- R30: Express each need and requirement once and only once.
## Abstraction
- R31 When defining design inputs avoid stating a solution unless there is rationale for constraining the design. Focus on the problem “what” rather than the solution “how.”
## Quantifiers
- R32: Use “each” instead of “all” , “any" or “both" when universal quantification is intended
## Tolerance
- R33: Define quantities with a range of values appropriate to the entity to which the apply and to which the entity will be verified or validated against.
## Quantification
- R34: Provide specific measurable performance targets appropriate to the entity to which the need or requirement is stated and against which the entity will be verified to meet.
- R35: Define temporal dependencies explicitly instead of using indefinite temporal keywords such as “eventually”, “until”, “before”, “after”, “as”, “once”, “earliest”, “latest”, “instantaneous”, “simultaneous”, “at last” .
## Uniformity of Language
- R36: Use each term consistently throughout need and requirement sets.
- R37: Use a consistent set of acronyms.
- R38: Avoid the use of abbreviations.
- R39: Use a project-wide style guide for individual needs and requirements and for sets of needs and requirements statements.
## Modularity
- R40: Group related requirements together.
- R41: Conform to a defined structure or template for sets of needs and requirements