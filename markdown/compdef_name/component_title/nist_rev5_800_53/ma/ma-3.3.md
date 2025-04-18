---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ma-3.3
      description: Rule for ma-3.3
x-trestle-param-values:
  ma-03.03_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ma-03.03
---

# ma-3.3 - \[Maintenance\] Prevent Unauthorized Removal

## Control Statement

Prevent the removal of maintenance equipment containing organizational information by:

- \[(a)\] Verifying that there is no organizational information contained on the equipment;

- \[(b)\] Sanitizing or destroying the equipment;

- \[(c)\] Retaining the equipment within the facility; or

- \[(d)\] Obtaining an exemption from {{ insert: param, ma-03.03_odp }} explicitly authorizing removal of the equipment from the facility.

## Control Assessment Objective

- \[MA-03(03)(a)\] the removal of maintenance equipment containing organizational information is prevented by verifying that there is no organizational information contained on the equipment; or

- \[MA-03(03)(b)\] the removal of maintenance equipment containing organizational information is prevented by sanitizing or destroying the equipment; or

- \[MA-03(03)(c)\] the removal of maintenance equipment containing organizational information is prevented by retaining the equipment within the facility; or

- \[MA-03(03)(d)\] the removal of maintenance equipment containing organizational information is prevented by obtaining an exemption from {{ insert: param, ma-03.03_odp }} explicitly authorizing removal of the equipment from the facility.

## Control guidance

Organizational information includes all information owned by organizations and any information provided to organizations for which the organizations serve as information stewards.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ma-3.3 -->

### Rules:

  - rule-ma-3.3

### Implementation Status: planned

______________________________________________________________________
