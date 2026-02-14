# IAM-Automation-Projects
This repository demonstrates hands-on Identity & Access Management (IAM) automation projects built using Microsoft Entra ID.
The focus of this repository is practical implementation of:

-Conditional Access engineering
-Privileged Identity Management (PIM)
-Identity governance automation
-Lifecycle-based access control
-Zero Trust enforcement

All configurations were implemented in a live tenant environment and include policy logic, enforcement design, and security impact analysis.



## Objectives
The goal of this repository is to demonstrate:
  -Automated enforcement of security policies
  -Reduction of standing privileged access
  -Time-bound access control
  -Automated onboarding and offboarding
  -Governance-driven identity management
  
This portfolio emphasizes real-world IAM engineering practices rather than theoretical labs.



## Project Structure

## Privileged Access Automation
Project: Just-in-Time (JIT) Administrative Access using PIM
  -Assigned eligible admin roles
  -Configured activation requirements (MFA + justification)
  -Enforced time-bound privilege elevation
  -Reviewed activation audit logs

Security Impact:
  -Eliminates permanent administrative access
  -Reduces attack surface
  -Supports compliance requirements


## Conditional Access Engineering
Project: Policy-Based Access Enforcement
  -Implemented MFA enforcement via Conditional Access
  -Configured device compliance requirements
  -Blocked legacy authentication
  -Tested and analyzed sign-in logs

Security Impact:
  -Enforces Zero Trust principles
  -Protects against credential compromise
  -Provides dynamic access evaluation


## Lifecycle Automation (Entitlement Management)

Project: Time-Bound Access Packages
  -Created access catalogs and packages
  -Configured automatic access expiration
  -Enforced automatic removal upon expiry
  -Tested access lifecycle end-to-end

Security Impact:
  -Prevents access creep
  -Automates onboarding/offboarding
  -Improves governance and audit readiness

## Automated Access Reviews

Project: Scheduled Access Governance
  -Configured recurring access reviews
  -Enabled automatic removal upon no response
  -Applied review results automatically

Security Impact:
  -Enforces least privilege
  -Reduces stale permissions
  -Supports regulatory compliance



## Key IAM Concepts Demonstrated

-Least Privilege
-Role-Based Access Control (RBAC)
-Conditional Access policy evaluation
-Just-in-Time privilege elevation
-Identity risk-based enforcement
-Access lifecycle automation
-Governance-driven access control

## Zero Trust Alignment

All projects align with Zero Trust principles:
  -Verify explicitly
  -Use least privilege access
  -Assume breach
  
Access decisions are enforced dynamically at sign-in and privilege elevation is time-bound.


## Career Focus

These projects support roles such as:
  -IAM Analyst
  -Identity Engineer
  -Cloud Security Engineer (IAM-focused)
  -Zero Trust Security Engineer

