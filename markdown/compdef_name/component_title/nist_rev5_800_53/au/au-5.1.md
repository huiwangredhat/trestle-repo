---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-5.1
      description: Rule for au-5.1
x-trestle-param-values:
  au-05.01_odp.01:
  au-05.01_odp.02:
  au-05.01_odp.03:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-05.01
---

# au-5.1 - \[Audit and Accountability\] Storage Capacity Warning

## Control Statement

Provide a warning to {{ insert: param, au-05.01_odp.01 }} within {{ insert: param, au-05.01_odp.02 }} when allocated audit log storage volume reaches {{ insert: param, au-05.01_odp.03 }} of repository maximum audit log storage capacity.

## Control Assessment Objective

a warning is provided to {{ insert: param, au-05.01_odp.01 }} within {{ insert: param, au-05.01_odp.02 }} when allocated audit log storage volume reaches {{ insert: param, au-05.01_odp.03 }} of repository maximum audit log storage capacity.

## Control guidance

Organizations may have multiple audit log storage repositories distributed across multiple system components with each repository having different storage volume capacities.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-5.1 -->

### Rules:

  - rule-au-5.1

### Implementation Status: planned

______________________________________________________________________
