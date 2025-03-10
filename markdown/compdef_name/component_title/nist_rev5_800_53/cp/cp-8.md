---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-cp-8
      description: Rule for cp-8
x-trestle-param-values:
  cp-08_odp.01:
  cp-08_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cp-08
---

# cp-8 - \[Contingency Planning\] Telecommunications Services

## Control Statement

Establish alternate telecommunications services, including necessary agreements to permit the resumption of {{ insert: param, cp-08_odp.01 }} for essential mission and business functions within {{ insert: param, cp-08_odp.02 }} when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.

## Control Assessment Objective

alternate telecommunications services, including necessary agreements to permit the resumption of {{ insert: param, cp-08_odp.01 }} , are established for essential mission and business functions within {{ insert: param, cp-08_odp.02 }} when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.

## Control guidance

Telecommunications services (for data and voice) for primary and alternate processing and storage sites are in scope for [CP-8](#cp-8) . Alternate telecommunications services reflect the continuity requirements in contingency plans to maintain essential mission and business functions despite the loss of primary telecommunications services. Organizations may specify different time periods for primary or alternate sites. Alternate telecommunications services include additional organizational or commercial ground-based circuits or lines, network-based approaches to telecommunications, or the use of satellites. Organizations consider factors such as availability, quality of service, and access when entering into alternate telecommunications agreements.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cp-8 -->

### Rules:

  - rule-cp-8

### Implementation Status: planned

______________________________________________________________________
