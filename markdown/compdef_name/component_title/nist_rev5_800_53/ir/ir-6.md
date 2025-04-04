---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ir-6
      description: Rule for ir-6
x-trestle-param-values:
  ir-06_odp.01:
  ir-06_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-06
---

# ir-6 - \[Incident Response\] Incident Reporting

## Control Statement

- \[a.\] Require personnel to report suspected incidents to the organizational incident response capability within {{ insert: param, ir-06_odp.01 }} ; and

- \[b.\] Report incident information to {{ insert: param, ir-06_odp.02 }}.

## Control Assessment Objective

- \[IR-06a.\] personnel is/are required to report suspected incidents to the organizational incident response capability within {{ insert: param, ir-06_odp.01 }};

- \[IR-06b.\] incident information is reported to {{ insert: param, ir-06_odp.02 }}.

## Control guidance

The types of incidents reported, the content and timeliness of the reports, and the designated reporting authorities reflect applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Incident information can inform risk assessments, control effectiveness assessments, security requirements for acquisitions, and selection criteria for technology products.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-6 -->

### Rules:

  - rule-ir-6

### Implementation Status: planned

______________________________________________________________________
