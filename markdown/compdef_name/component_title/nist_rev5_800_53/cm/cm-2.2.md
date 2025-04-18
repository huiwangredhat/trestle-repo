---
x-trestle-comp-def-rules:
  component_title:
    - name: rule-cm-2.2
      description: Rule for cm-2.2
x-trestle-param-values:
  cm-02.02_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cm-02.02
---

# cm-2.2 - \[Configuration Management\] Automation Support for Accuracy and Currency

## Control Statement

Maintain the currency, completeness, accuracy, and availability of the baseline configuration of the system using {{ insert: param, cm-02.02_odp }}.

## Control Assessment Objective

- \[CM-02(02)[01]\] the currency of the baseline configuration of the system is maintained using {{ insert: param, cm-02.02_odp }};

- \[CM-02(02)[02]\] the completeness of the baseline configuration of the system is maintained using {{ insert: param, cm-02.02_odp }};

- \[CM-02(02)[03]\] the accuracy of the baseline configuration of the system is maintained using {{ insert: param, cm-02.02_odp }};

- \[CM-02(02)[04]\] the availability of the baseline configuration of the system is maintained using {{ insert: param, cm-02.02_odp }}.

## Control guidance

Automated mechanisms that help organizations maintain consistent baseline configurations for systems include configuration management tools, hardware, software, firmware inventory tools, and network management tools. Automated tools can be used at the organization level, mission and business process level, or system level on workstations, servers, notebook computers, network components, or mobile devices. Tools can be used to track version numbers on operating systems, applications, types of software installed, and current patch levels. Automation support for accuracy and currency can be satisfied by the implementation of [CM-8(2)](#cm-8.2) for organizations that combine system component inventory and baseline configuration activities.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cm-2.2 -->

### Rules:

  - rule-cm-2.2

### Implementation Status: planned

______________________________________________________________________
