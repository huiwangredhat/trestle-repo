---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-cm-3.4
      description: Rule for cm-3.4
x-trestle-param-values:
  cm-3.4_prm_1:
  cm-03.04_odp.01:
  cm-03.04_odp.02:
  cm-03.04_odp.03:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cm-03.04
---

# cm-3.4 - \[Configuration Management\] Security and Privacy Representatives

## Control Statement

Require {{ insert: param, cm-3.4_prm_1 }} to be members of the {{ insert: param, cm-03.04_odp.03 }}.

## Control Assessment Objective

- \[CM-03(04)[01]\] {{ insert: param, cm-03.04_odp.01 }} are required to be members of the {{ insert: param, cm-03.04_odp.03 }};

- \[CM-03(04)[02]\] {{ insert: param, cm-03.04_odp.02 }} are required to be members of the {{ insert: param, cm-03.04_odp.03 }}.

## Control guidance

Information security and privacy representatives include system security officers, senior agency information security officers, senior agency officials for privacy, or system privacy officers. Representation by personnel with information security and privacy expertise is important because changes to system configurations can have unintended side effects, some of which may be security- or privacy-relevant. Detecting such changes early in the process can help avoid unintended, negative consequences that could ultimately affect the security and privacy posture of systems. The configuration change control element referred to in the second organization-defined parameter reflects the change control elements defined by organizations in [CM-3g](#cm-3_smt.g).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cm-3.4 -->

### Rules:

  - rule-cm-3.4

### Implementation Status: planned

______________________________________________________________________
