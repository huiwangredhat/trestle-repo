---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-sc-7.5
      description: Rule for sc-7.5
x-trestle-param-values:
  sc-07.05_odp.01:
  sc-07.05_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: sc-07.05
---

# sc-7.5 - \[System and Communications Protection\] Deny by Default — Allow by Exception

## Control Statement

Deny network communications traffic by default and allow network communications traffic by exception {{ insert: param, sc-07.05_odp.01 }}.

## Control Assessment Objective

- \[SC-07(05)[01]\] network communications traffic is denied by default {{ insert: param, sc-07.05_odp.01 }};

- \[SC-07(05)[02]\] network communications traffic is allowed by exception {{ insert: param, sc-07.05_odp.01 }}.

## Control guidance

Denying by default and allowing by exception applies to inbound and outbound network communications traffic. A deny-all, permit-by-exception network communications traffic policy ensures that only those system connections that are essential and approved are allowed. Deny by default, allow by exception also applies to a system that is connected to an external system.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sc-7.5 -->

### Rules:

  - rule-sc-7.5

### Implementation Status: planned

______________________________________________________________________
