---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-9.4
      description: Rule for au-9.4
x-trestle-param-values:
  au-09.04_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-09.04
---

# au-9.4 - \[Audit and Accountability\] Access by Subset of Privileged Users

## Control Statement

Authorize access to management of audit logging functionality to only {{ insert: param, au-09.04_odp }}.

## Control Assessment Objective

access to management of audit logging functionality is authorized only to {{ insert: param, au-09.04_odp }}.

## Control guidance

Individuals or roles with privileged access to a system and who are also the subject of an audit by that system may affect the reliability of the audit information by inhibiting audit activities or modifying audit records. Requiring privileged access to be further defined between audit-related privileges and other privileges limits the number of users or roles with audit-related privileges.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-9.4 -->

### Rules:

  - rule-au-9.4

### Implementation Status: planned

______________________________________________________________________
