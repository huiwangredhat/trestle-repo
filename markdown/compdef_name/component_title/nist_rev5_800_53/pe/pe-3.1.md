---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-pe-3.1
      description: Rule for pe-3.1
x-trestle-param-values:
  pe-03.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: pe-03.01
---

# pe-3.1 - \[Physical and Environmental Protection\] System Access

## Control Statement

Enforce physical access authorizations to the system in addition to the physical access controls for the facility at {{ insert: param, pe-03.01_odp }}.

## Control Assessment Objective

- \[PE-03(01)[01]\] physical access authorizations to the system are enforced;

- \[PE-03(01)02]\] physical access controls are enforced for the facility at {{ insert: param, pe-03.01_odp }}.

## Control guidance

Control of physical access to the system provides additional physical security for those areas within facilities where there is a concentration of system components.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pe-3.1 -->

### Rules:

  - rule-pe-3.1

### Implementation Status: planned

______________________________________________________________________
