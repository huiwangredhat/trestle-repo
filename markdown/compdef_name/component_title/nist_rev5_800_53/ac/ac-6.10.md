---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ac-6.10
      description: Rule for ac-6.10
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ac-06.10
---

# ac-6.10 - \[Access Control\] Prohibit Non-privileged Users from Executing Privileged Functions

## Control Statement

Prevent non-privileged users from executing privileged functions.

## Control Assessment Objective

non-privileged users are prevented from executing privileged functions.

## Control guidance

Privileged functions include disabling, circumventing, or altering implemented security or privacy controls, establishing system accounts, performing system integrity checks, and administering cryptographic key management activities. Non-privileged users are individuals who do not possess appropriate authorizations. Privileged functions that require protection from non-privileged users include circumventing intrusion detection and prevention mechanisms or malicious code protection mechanisms. Preventing non-privileged users from executing privileged functions is enforced by [AC-3](#ac-3).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-6.10 -->

### Rules:

  - rule-ac-6.10

### Implementation Status: planned

______________________________________________________________________
