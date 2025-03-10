---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-4
      description: Rule for au-4
x-trestle-param-values:
  au-04_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-04
---

# au-4 - \[Audit and Accountability\] Audit Log Storage Capacity

## Control Statement

Allocate audit log storage capacity to accommodate {{ insert: param, au-04_odp }}.

## Control Assessment Objective

audit log storage capacity is allocated to accommodate {{ insert: param, au-04_odp }}.

## Control guidance

Organizations consider the types of audit logging to be performed and the audit log processing requirements when allocating audit log storage capacity. Allocating sufficient audit log storage capacity reduces the likelihood of such capacity being exceeded and resulting in the potential loss or reduction of audit logging capability.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-4 -->

### Rules:

  - rule-au-4

### Implementation Status: planned

______________________________________________________________________
