---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-pe-5
      description: Rule for pe-5
x-trestle-param-values:
  pe-05_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: pe-05
---

# pe-5 - \[Physical and Environmental Protection\] Access Control for Output Devices

## Control Statement

Control physical access to output from {{ insert: param, pe-05_odp }} to prevent unauthorized individuals from obtaining the output.

## Control Assessment Objective

physical access to output from {{ insert: param, pe-05_odp }} is controlled to prevent unauthorized individuals from obtaining the output.

## Control guidance

Controlling physical access to output devices includes placing output devices in locked rooms or other secured areas with keypad or card reader access controls and allowing access to authorized individuals only, placing output devices in locations that can be monitored by personnel, installing monitor or screen filters, and using headphones. Examples of output devices include monitors, printers, scanners, audio devices, facsimile machines, and copiers.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pe-5 -->

### Rules:

  - rule-pe-5

### Implementation Status: planned

______________________________________________________________________
