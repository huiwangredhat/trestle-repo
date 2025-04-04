---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ac-2.11
      description: Rule for ac-2.11
x-trestle-param-values:
  ac-02.11_odp.01:
  ac-02.11_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ac-02.11
---

# ac-2.11 - \[Access Control\] Usage Conditions

## Control Statement

Enforce {{ insert: param, ac-02.11_odp.01 }} for {{ insert: param, ac-02.11_odp.02 }}.

## Control Assessment Objective

{{ insert: param, ac-02.11_odp.01 }} for {{ insert: param, ac-02.11_odp.02 }} are enforced.

## Control guidance

Specifying and enforcing usage conditions helps to enforce the principle of least privilege, increase user accountability, and enable effective account monitoring. Account monitoring includes alerts generated if the account is used in violation of organizational parameters. Organizations can describe specific conditions or circumstances under which system accounts can be used, such as by restricting usage to certain days of the week, time of day, or specific durations of time.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2.11 -->

### Rules:

  - rule-ac-2.11

### Implementation Status: planned

______________________________________________________________________
