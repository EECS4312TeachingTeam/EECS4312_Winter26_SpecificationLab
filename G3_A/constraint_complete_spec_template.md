# Constraint‑Complete Specification Template

Complete all sections of the following document
## Goal
Describe in 1–2 sentences the objective of the meeting slot suggestion system.

## Inputs and Outputs
- **Inputs:** Describe each input parameter (`events`, `meeting_duration`, `day`). What type and format does each take? What values are valid?
- **Output:** Describe what the function returns.

## Functional Requirements
List as many as functional requirements as possible from the specification description. 


## Constraints.
List at least **six** constraints and assumptions relevant to the problem. 


Edge Cases. Boundary conditions and exceptional scenarios.
Tie-Breaking Rules. Explicit prioritization among valid out-
comes.
Rationale. Justification for constraints and rules.

## Invariants
List at least **three** invariants that must always hold. Examples: the returned slots are sorted. 

## Negative Requirements
List at least **two** negative requirements (situations that must **not** occur). 

## Tie‑Breaking Rules
Explain how the system should choose between multiple feasible slots. If two slots satisfy the same constraints, which should be returned first? If meeting durations differ, which duration should take precedence?

## Exceptions and Day‑Specific Rules
Document any special rules or exceptions, such as the Friday cutoff. Include any other day‑specific constraints you can think of.


