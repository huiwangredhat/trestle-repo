---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-5.2
      description: Rule for au-5.2
x-trestle-param-values:
  au-05.02_odp.01:
  au-05.02_odp.02:
  au-05.02_odp.03:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-05.02
---

# au-5.2 - \[Audit and Accountability\] Real-time Alerts

## Control Statement

Provide an alert within {{ insert: param, au-05.02_odp.01 }} to {{ insert: param, au-05.02_odp.02 }} when the following audit failure events occur: {{ insert: param, au-05.02_odp.03 }}.

## Control Assessment Objective

an alert is provided within {{ insert: param, au-05.02_odp.01 }} to {{ insert: param, au-05.02_odp.02 }} when {{ insert: param, au-05.02_odp.03 }} occur.

## Control guidance

Alerts provide organizations with urgent messages. Real-time alerts provide these messages at information technology speed (i.e., the time from event detection to alert occurs in seconds or less).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-5.2 -->

### Rules:

  - rule-au-5.2

### Implementation Status: planned

______________________________________________________________________
