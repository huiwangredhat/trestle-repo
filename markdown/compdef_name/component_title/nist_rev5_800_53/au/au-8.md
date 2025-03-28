---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-au-8
      description: Rule for au-8
x-trestle-param-values:
  au-08_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-08
---

# au-8 - \[Audit and Accountability\] Time Stamps

## Control Statement

- \[a.\] Use internal system clocks to generate time stamps for audit records; and

- \[b.\] Record time stamps for audit records that meet {{ insert: param, au-08_odp }} and that use Coordinated Universal Time, have a fixed local time offset from Coordinated Universal Time, or that include the local time offset as part of the time stamp.

## Control Assessment Objective

- \[AU-08a.\] internal system clocks are used to generate timestamps for audit records;

- \[AU-08b.\] timestamps are recorded for audit records that meet {{ insert: param, au-08_odp }} and that use Coordinated Universal Time, have a fixed local time offset from Coordinated Universal Time, or include the local time offset as part of the timestamp.

## Control guidance

Time stamps generated by the system include date and time. Time is commonly expressed in Coordinated Universal Time (UTC), a modern continuation of Greenwich Mean Time (GMT), or local time with an offset from UTC. Granularity of time measurements refers to the degree of synchronization between system clocks and reference clocks (e.g., clocks synchronizing within hundreds of milliseconds or tens of milliseconds). Organizations may define different time granularities for different system components. Time service can be critical to other security capabilities such as access control and identification and authentication, depending on the nature of the mechanisms used to support those capabilities.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-8 -->

### Rules:

  - rule-au-8

### Implementation Status: planned

______________________________________________________________________
