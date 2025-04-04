---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ra-3.1
      description: Rule for ra-3.1
x-trestle-param-values:
  ra-03.01_odp.01:
  ra-03.01_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ra-03.01
---

# ra-3.1 - \[Risk Assessment\] Supply Chain Risk Assessment

## Control Statement

- \[(a)\] Assess supply chain risks associated with {{ insert: param, ra-03.01_odp.01 }} ; and

- \[(b)\] Update the supply chain risk assessment {{ insert: param, ra-03.01_odp.02 }} , when there are significant changes to the relevant supply chain, or when changes to the system, environments of operation, or other conditions may necessitate a change in the supply chain.

## Control Assessment Objective

- \[RA-03(01)(a)\] supply chain risks associated with {{ insert: param, ra-03.01_odp.01 }} are assessed;

- \[RA-03(01)(b)\] the supply chain risk assessment is updated {{ insert: param, ra-03.01_odp.02 }} , when there are significant changes to the relevant supply chain, or when changes to the system, environments of operation, or other conditions may necessitate a change in the supply chain.

## Control guidance

Supply chain-related events include disruption, use of defective components, insertion of counterfeits, theft, malicious development practices, improper delivery practices, and insertion of malicious code. These events can have a significant impact on the confidentiality, integrity, or availability of a system and its information and, therefore, can also adversely impact organizational operations (including mission, functions, image, or reputation), organizational assets, individuals, other organizations, and the Nation. The supply chain-related events may be unintentional or malicious and can occur at any point during the system life cycle. An analysis of supply chain risk can help an organization identify systems or components for which additional supply chain risk mitigations are required.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ra-3.1 -->

### Rules:

  - rule-ra-3.1

### Implementation Status: planned

______________________________________________________________________
