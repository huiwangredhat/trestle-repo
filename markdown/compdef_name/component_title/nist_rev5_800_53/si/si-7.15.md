---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-si-7.15
      description: Rule for si-7.15
x-trestle-param-values:
  si-07.15_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-07.15
---

# si-7.15 - \[System and Information Integrity\] Code Authentication

## Control Statement

Implement cryptographic mechanisms to authenticate the following software or firmware components prior to installation: {{ insert: param, si-07.15_odp }}.

## Control Assessment Objective

cryptographic mechanisms are implemented to authenticate {{ insert: param, si-07.15_odp }} prior to installation.

## Control guidance

Cryptographic authentication includes verifying that software or firmware components have been digitally signed using certificates recognized and approved by organizations. Code signing is an effective method to protect against malicious code. Organizations that employ cryptographic mechanisms also consider cryptographic key management solutions.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-7.15 -->

### Rules:

  - rule-si-7.15

### Implementation Status: planned

______________________________________________________________________
