---
x-trestle-global:
  sort-id: cm-04.01
---

# cm-4.1 - \[Configuration Management\] Separate Test Environments

## Control Statement

Analyze changes to the system in a separate test environment before implementation in an operational environment, looking for security and privacy impacts due to flaws, weaknesses, incompatibility, or intentional malice.

## Control Assessment Objective

- \[CM-04(01)[01]\] changes to the system are analyzed in a separate test environment before implementation in an operational environment;

- \[CM-04(01)[02]\] changes to the system are analyzed for security impacts due to flaws;

- \[CM-04(01)[03]\] changes to the system are analyzed for privacy impacts due to flaws;

- \[CM-04(01)[04]\] changes to the system are analyzed for security impacts due to weaknesses;

- \[CM-04(01)[05]\] changes to the system are analyzed for privacy impacts due to weaknesses;

- \[CM-04(01)[06]\] changes to the system are analyzed for security impacts due to incompatibility;

- \[CM-04(01)[07]\] changes to the system are analyzed for privacy impacts due to incompatibility;

- \[CM-04(01)[08]\] changes to the system are analyzed for security impacts due to intentional malice;

- \[CM-04(01)[09]\] changes to the system are analyzed for privacy impacts due to intentional malice.

## Control guidance

A separate test environment requires an environment that is physically or logically separate and distinct from the operational environment. The separation is sufficient to ensure that activities in the test environment do not impact activities in the operational environment and that information in the operational environment is not inadvertently transmitted to the test environment. Separate environments can be achieved by physical or logical means. If physically separate test environments are not implemented, organizations determine the strength of mechanism required when implementing logical separation.
