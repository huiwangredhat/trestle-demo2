---
x-trestle-set-params:
  pm-01_odp.01:
    values:
  pm-01_odp.02:
    values:
x-trestle-global:
  sort-id: pm-01
---

# pm-1 - \[Program Management\] Information Security Program Plan

## Control Statement

- \[a.\] Develop and disseminate an organization-wide information security program plan that:

  - \[1.\] Provides an overview of the requirements for the security program and a description of the security program management controls and common controls in place or planned for meeting those requirements;
  - \[2.\] Includes the identification and assignment of roles, responsibilities, management commitment, coordination among organizational entities, and compliance;
  - \[3.\] Reflects the coordination among organizational entities responsible for information security; and
  - \[4.\] Is approved by a senior official with responsibility and accountability for the risk being incurred to organizational operations (including mission, functions, image, and reputation), organizational assets, individuals, other organizations, and the Nation;

- \[b.\] Review and update the organization-wide information security program plan {{ insert: param, pm-01_odp.01 }} and following {{ insert: param, pm-01_odp.02 }} ; and

- \[c.\] Protect the information security program plan from unauthorized disclosure and modification.

## Control Assessment Objective

- \[PM-01a.\]

  - \[PM-01a.[01]\] an organization-wide information security program plan is developed;
  - \[PM-01a.[02]\] the information security program plan is disseminated;
  - \[PM-01a.01\]

    - \[PM-01a.01[01]\] the information security program plan provides an overview of the requirements for the security program;
    - \[PM-01a.01[02]\] the information security program plan provides a description of the security program management controls in place or planned for meeting those requirements;
    - \[PM-01a.01[03]\] the information security program plan provides a description of the common controls in place or planned for meeting those requirements;

  - \[PM-01a.02\]

    - \[PM-01a.02[01]\] the information security program plan includes the identification and assignment of roles;
    - \[PM-01a.02[02]\] the information security program plan includes the identification and assignment of responsibilities;
    - \[PM-01a.02[03]\] the information security program plan addresses management commitment;
    - \[PM-01a.02[04]\] the information security program plan addresses coordination among organizational entities;
    - \[PM-01a.02[05]\] the information security program plan addresses compliance;

  - \[PM-01a.03\] the information security program plan reflects the coordination among the organizational entities responsible for information security;
  - \[PM-01a.04\] the information security program plan is approved by a senior official with responsibility and accountability for the risk being incurred to organizational operations (including mission, functions, image, and reputation), organizational assets, individuals, other organizations, and the Nation;

- \[PM-01b.\]

  - \[PM-01b.[01]\] the information security program plan is reviewed and updated {{ insert: param, pm-01_odp.01 }};
  - \[PM-01b.[02]\] the information security program plan is reviewed and updated following {{ insert: param, pm-01_odp.02 }};

- \[PM-01c.\]

  - \[PM-01c.[01]\] the information security program plan is protected from unauthorized disclosure;
  - \[PM-01c.[02]\] the information security program plan is protected from unauthorized modification.

## Control guidance

An information security program plan is a formal document that provides an overview of the security requirements for an organization-wide information security program and describes the program management controls and common controls in place or planned for meeting those requirements. An information security program plan can be represented in a single document or compilations of documents. Privacy program plans and supply chain risk management plans are addressed separately in [PM-18](#pm-18) and [SR-2](#sr-2) , respectively.

An information security program plan documents implementation details about program management and common controls. The plan provides sufficient information about the controls (including specification of parameters for assignment and selection operations, explicitly or by reference) to enable implementations that are unambiguously compliant with the intent of the plan and a determination of the risk to be incurred if the plan is implemented as intended. Updates to information security program plans include organizational changes and problems identified during plan implementation or control assessments.

Program management controls may be implemented at the organization level or the mission or business process level, and are essential for managing the organization’s information security program. Program management controls are distinct from common, system-specific, and hybrid controls because program management controls are independent of any particular system. Together, the individual system security plans and the organization-wide information security program plan provide complete coverage for the security controls employed within the organization.

Common controls available for inheritance by organizational systems are documented in an appendix to the organization’s information security program plan unless the controls are included in a separate security plan for a system. The organization-wide information security program plan indicates which separate security plans contain descriptions of common controls.

Events that may precipitate an update to the information security program plan include, but are not limited to, organization-wide assessment or audit findings, security incidents or breaches, or changes in laws, executive orders, directives, regulations, policies, standards, and guidelines.
