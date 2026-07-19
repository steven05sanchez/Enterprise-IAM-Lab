# Enterprise Identity & Access Management (IAM) Lab

## Overview

This project is a hands-on Microsoft Entra ID lab where I built a simulated Identity and Access Management (IAM) environment for a fictional company called **BroncoTech Solutions**.

The goal of this project was to better understand how organizations manage users, control access, and secure identities using Microsoft Entra ID. Throughout this project, I practiced many of the tasks that an IAM analyst would perform in an enterprise environment.

---

## Business Scenario

BroncoTech Solutions is a fictional technology company with approximately 200 employees.

For this project, I acted as the company's IAM analyst and was responsible for:

- Creating employee accounts
- Managing user identities
- Creating security groups
- Assigning users to groups
- Assigning administrative roles
- Reviewing authentication methods
- Creating a Conditional Access policy

---

## Technologies Used

- Microsoft Entra ID
- Microsoft Entra ID P2
- Microsoft Azure
- Conditional Access
- GitHub

---

## Project Roadmap

- [x] Phase 1 – Identity Foundation
- [x] Phase 2 – Security Groups
- [x] Phase 3 – User Group Assignments
- [x] Phase 4 – Administrative Roles
- [x] Phase 5 – Authentication Methods
- [x] Phase 6 – Conditional Access

---

## Skills Demonstrated

- Identity & Access Management (IAM)
- Microsoft Entra ID
- User Provisioning
- Security Groups
- Role-Based Access Control (RBAC)
- Administrative Role Management
- Conditional Access
- Authentication Methods
- Principle of Least Privilege

---

# Phase 1 – Identity Foundation

## Objective

Create the initial identity structure for BroncoTech Solutions.

## Tasks Completed

- Created enterprise user accounts
- Assigned Microsoft Entra ID P2 licenses
- Configured user profile information
- Used a consistent username naming convention
- Verified successful account creation

## What I Learned

This phase helped me understand how organizations provision user accounts and why identity management is the first step before assigning access or permissions.

---

# Phase 2 – Security Groups

## Objective

Create department-based security groups to organize users and simplify access management.

## Security Groups Created

- IT_Admins
- IT_Support
- HR_Users
- Finance_Users
- Sales_Users
- Marketing_Users
- Engineering_Users
- Executives

## Tasks Completed

- Created department security groups
- Used a consistent naming convention
- Designed the environment using Role-Based Access Control (RBAC)

## What I Learned

I learned that organizations manage permissions through groups instead of assigning permissions directly to individual users. This makes user management easier and more scalable.

---

# Phase 3 – User Group Assignments

## Objective

Assign users to the appropriate department security groups.

## Tasks Completed

- Assigned users to department groups
- Applied Role-Based Access Control (RBAC)
- Organized access based on job responsibilities

## What I Learned

I learned that assigning users to security groups makes onboarding, offboarding, and role changes much easier while following the Principle of Least Privilege.

---

# Phase 4 – Administrative Roles

## Objective

Assign administrative roles based on job responsibilities.

## Tasks Completed

- Assigned the Helpdesk Administrator role
- Assigned the User Administrator role
- Limited administrative access based on user responsibilities

## What I Learned

This phase helped me understand that not every IT employee should have full administrative privileges. Administrative roles should only be assigned when required.

---

# Phase 5 – Authentication Methods

## Objective

Review the authentication methods available in Microsoft Entra ID.

## Tasks Completed

- Reviewed available authentication methods
- Learned how organizations manage sign-in options for users

## What I Learned

I learned that organizations can control which authentication methods users are allowed to use in order to improve account security while still providing flexibility.

---

# Phase 6 – Conditional Access

## Objective

Create a Conditional Access policy to require Multi-Factor Authentication (MFA).

## Tasks Completed

- Created the policy **CA001 – Require MFA for Administrators**
- Configured the policy in Report-only mode
- Learned how organizations safely test security policies before enabling them

## What I Learned

This phase introduced me to Conditional Access and how organizations use it to enforce security policies without immediately impacting users. Using Report-only mode allows administrators to evaluate the policy before enforcing it.

---

# Screenshots

## Users

![Users](screenshots/01-users-created.png)

---

## Security Groups

![Security Groups](screenshots/02-security-groups.png)

---

## Administrative Role Assignment

![Administrative Role](screenshots/03-helpdesk-adminstrator-assignments.png)

---

## Authentication Methods

![Authentication Methods](screenshots/04-authentication-methods.png)

---

## Conditional Access

![Conditional Access](screenshots/05-conditional-access.png)

---

# Overall Takeaways

This project gave me hands-on experience with many of the core concepts used in Identity and Access Management. Before building this lab, I understood many of these topics from studying for Security+, but completing each phase helped me understand how they work together in a real enterprise environment.

Some of the biggest concepts I learned were user provisioning, Role-Based Access Control (RBAC), administrative role management, authentication methods, Conditional Access, and the Principle of Least Privilege.
