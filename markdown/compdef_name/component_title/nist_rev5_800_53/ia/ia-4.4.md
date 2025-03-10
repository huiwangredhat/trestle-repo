---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ia-4.4
      description: Rule for ia-4.4
x-trestle-param-values:
  ia-04.04_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ia-04.04
---

# ia-4.4 - \[Identification and Authentication\] Identify User Status

## Control Statement

Manage individual identifiers by uniquely identifying each individual as {{ insert: param, ia-04.04_odp }}.

## Control Assessment Objective

individual identifiers are managed by uniquely identifying each individual as {{ insert: param, ia-04.04_odp }}.

## Control guidance

Characteristics that identify the status of individuals include contractors, foreign nationals, and non-organizational users. Identifying the status of individuals by these characteristics provides additional information about the people with whom organizational personnel are communicating. For example, it might be useful for a government employee to know that one of the individuals on an email message is a contractor.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ia-4.4 -->

### Rules:

  - rule-ia-4.4

### Implementation Status: planned

______________________________________________________________________
