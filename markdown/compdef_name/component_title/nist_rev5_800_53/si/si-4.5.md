---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-si-4.5
      description: Rule for si-4.5
x-trestle-param-values:
  si-04.05_odp.01:
  si-04.05_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-04.05
---

# si-4.5 - \[System and Information Integrity\] System-generated Alerts

## Control Statement

Alert {{ insert: param, si-04.05_odp.01 }} when the following system-generated indications of compromise or potential compromise occur: {{ insert: param, si-04.05_odp.02 }}.

## Control Assessment Objective

{{ insert: param, si-04.05_odp.01 }} are alerted when system-generated {{ insert: param, si-04.05_odp.02 }} occur.

## Control guidance

Alerts may be generated from a variety of sources, including audit records or inputs from malicious code protection mechanisms, intrusion detection or prevention mechanisms, or boundary protection devices such as firewalls, gateways, and routers. Alerts can be automated and may be transmitted telephonically, by electronic mail messages, or by text messaging. Organizational personnel on the alert notification list can include system administrators, mission or business owners, system owners, information owners/stewards, senior agency information security officers, senior agency officials for privacy, system security officers, or privacy officers. In contrast to alerts generated by the system, alerts generated by organizations in [SI-4(12)](#si-4.12) focus on information sources external to the system, such as suspicious activity reports and reports on potential insider threats.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-4.5 -->

### Rules:

  - rule-si-4.5

### Implementation Status: planned

______________________________________________________________________
