---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-7.1
      description: Rule for au-7.1
x-trestle-param-values:
  au-07.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-07.01
---

# au-7.1 - \[Audit and Accountability\] Automatic Processing

## Control Statement

Provide and implement the capability to process, sort, and search audit records for events of interest based on the following content: {{ insert: param, au-07.01_odp }}.

## Control Assessment Objective

- \[AU-07(01)[01]\] the capability to process, sort, and search audit records for events of interest based on {{ insert: param, au-07.01_odp }} are provided;

- \[AU-07(01)[02]\] the capability to process, sort, and search audit records for events of interest based on {{ insert: param, au-07.01_odp }} are implemented.

## Control guidance

Events of interest can be identified by the content of audit records, including system resources involved, information objects accessed, identities of individuals, event types, event locations, event dates and times, Internet Protocol addresses involved, or event success or failure. Organizations may define event criteria to any degree of granularity required, such as locations selectable by a general networking location or by specific system component.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-7.1 -->

### Rules:

  - rule-au-7.1

### Implementation Status: planned

______________________________________________________________________
