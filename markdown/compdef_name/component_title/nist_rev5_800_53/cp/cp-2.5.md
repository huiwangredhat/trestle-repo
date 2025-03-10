---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-cp-2.5
      description: Rule for cp-2.5
x-trestle-param-values:
  cp-02.05_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cp-02.05
---

# cp-2.5 - \[Contingency Planning\] Continue Mission and Business Functions

## Control Statement

Plan for the continuance of {{ insert: param, cp-02.05_odp }} mission and business functions with minimal or no loss of operational continuity and sustains that continuity until full system restoration at primary processing and/or storage sites.

## Control Assessment Objective

- \[CP-02(05)[01]\] the continuance of {{ insert: param, cp-02.05_odp }} mission and business functions with minimal or no loss of operational continuity is planned for;

- \[CP-02(05)[02]\] continuity is sustained until full system restoration at primary processing and/or storage sites.

## Control guidance

Organizations may choose to conduct the contingency planning activities to continue mission and business functions as part of business continuity planning or business impact analyses. Primary processing and/or storage sites defined by organizations as part of contingency planning may change depending on the circumstances associated with the contingency.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cp-2.5 -->

### Rules:

  - rule-cp-2.5

### Implementation Status: planned

______________________________________________________________________
