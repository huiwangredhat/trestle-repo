---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-ir-6.1
      description: Rule for ir-6.1
x-trestle-param-values:
  ir-06.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-06.01
---

# ir-6.1 - \[Incident Response\] Automated Reporting

## Control Statement

Report incidents using {{ insert: param, ir-06.01_odp }}.

## Control Assessment Objective

incidents are reported using {{ insert: param, ir-06.01_odp }}.

## Control guidance

The recipients of incident reports are specified in [IR-6b](#ir-6_smt.b) . Automated reporting mechanisms include email, posting on websites (with automatic updates), and automated incident response tools and programs.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-6.1 -->

### Rules:

  - rule-ir-6.1

### Implementation Status: planned

______________________________________________________________________
