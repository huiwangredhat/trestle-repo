---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-sc-7.18
      description: Rule for sc-7.18
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: sc-07.18
---

# sc-7.18 - \[System and Communications Protection\] Fail Secure

## Control Statement

Prevent systems from entering unsecure states in the event of an operational failure of a boundary protection device.

## Control Assessment Objective

systems are prevented from entering unsecure states in the event of an operational failure of a boundary protection device.

## Control guidance

Fail secure is a condition achieved by employing mechanisms to ensure that in the event of operational failures of boundary protection devices at managed interfaces, systems do not enter into unsecure states where intended security properties no longer hold. Managed interfaces include routers, firewalls, and application gateways that reside on protected subnetworks (commonly referred to as demilitarized zones). Failures of boundary protection devices cannot lead to or cause information external to the devices to enter the devices nor can failures permit unauthorized information releases.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sc-7.18 -->

### Rules:

  - rule-sc-7.18

### Implementation Status: planned

______________________________________________________________________
