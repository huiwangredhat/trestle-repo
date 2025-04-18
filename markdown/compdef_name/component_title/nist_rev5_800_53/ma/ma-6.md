---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ma-6
      description: Rule for ma-6
x-trestle-param-values:
  ma-06_odp.01:
  ma-06_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ma-06
---

# ma-6 - \[Maintenance\] Timely Maintenance

## Control Statement

Obtain maintenance support and/or spare parts for {{ insert: param, ma-06_odp.01 }} within {{ insert: param, ma-06_odp.02 }} of failure.

## Control Assessment Objective

maintenance support and/or spare parts are obtained for {{ insert: param, ma-06_odp.01 }} within {{ insert: param, ma-06_odp.02 }} of failure.

## Control guidance

Organizations specify the system components that result in increased risk to organizational operations and assets, individuals, other organizations, or the Nation when the functionality provided by those components is not operational. Organizational actions to obtain maintenance support include having appropriate contracts in place.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ma-6 -->

### Rules:

  - rule-ma-6

### Implementation Status: planned

______________________________________________________________________
