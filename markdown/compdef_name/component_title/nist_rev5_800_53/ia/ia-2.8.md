---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ia-2.8
      description: Rule for ia-2.8
x-trestle-param-values:
  ia-02.08_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ia-02.08
---

# ia-2.8 - \[Identification and Authentication\] Access to Accounts — Replay Resistant

## Control Statement

Implement replay-resistant authentication mechanisms for access to {{ insert: param, ia-02.08_odp }}.

## Control Assessment Objective

replay-resistant authentication mechanisms for access to {{ insert: param, ia-02.08_odp }} are implemented.

## Control guidance

Authentication processes resist replay attacks if it is impractical to achieve successful authentications by replaying previous authentication messages. Replay-resistant techniques include protocols that use nonces or challenges such as time synchronous or cryptographic authenticators.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ia-2.8 -->

### Rules:

  - rule-ia-2.8

### Implementation Status: planned

______________________________________________________________________
