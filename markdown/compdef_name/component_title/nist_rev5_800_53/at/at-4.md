---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-at-4
      description: Rule for at-4
x-trestle-param-values:
  at-04_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: at-04
---

# at-4 - \[Awareness and Training\] Training Records

## Control Statement

- \[a.\] Document and monitor information security and privacy training activities, including security and privacy awareness training and specific role-based security and privacy training; and

- \[b.\] Retain individual training records for {{ insert: param, at-04_odp }}.

## Control Assessment Objective

- \[AT-04a.\]

  - \[AT-04a.[01]\] information security and privacy training activities, including security and privacy awareness training and specific role-based security and privacy training, are documented;
  - \[AT-04a.[02]\] information security and privacy training activities, including security and privacy awareness training and specific role-based security and privacy training, are monitored;

- \[AT-04b.\] individual training records are retained for {{ insert: param, at-04_odp }}.

## Control guidance

Documentation for specialized training may be maintained by individual supervisors at the discretion of the organization. The National Archives and Records Administration provides guidance on records retention for federal agencies.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: at-4 -->

### Rules:

  - rule-at-4

### Implementation Status: planned

______________________________________________________________________
