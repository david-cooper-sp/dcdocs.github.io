---
marp: true
theme: gaia

---
<!-- this is a "This was worked on by Dave and Gentjan" -->

![bg left:40% 80%](https://www.sailpoint.com/images/SailPoint-logo-cropped.svg)

# Identity Security Cloud
## Mock Project

David Cooper and Gentjan Kocaqi

---

# Requirements

Defined in a high-level as:

## Phase 1

- Create accounts and Identity Profile within ISC
- Configure Lifecycle States based on startDate attribute

---

# Requirements

Defined in a high-level as:

## Phase 2

- Create Accounts on Active Directory and assign Group Membership
- Configure logic for adjusting Lifecycle state based on endDate attribute
- Modify Active Directory attributes based on XYZ source data change

---

# Requirements

Defined in a high-level as:

## Phase 3

- Create Certification Campaigns based on:
1. Change of employment type
2. Quarterly review mandate
3. Privileged Active Directory group assignment

---

# Requirements

Defined in a high-level as:

## Phase 3

- Create Access Requests for:
1. Elevation of Active Directory privileges
2. Access to Treasury data

---

# Requirements

Defined in a high-level as:

## Phase 3

- Create Reporting for:
1. Weekly review of Contractors with elevated privileges
2. Weekly review of New Hires and Terminations
3. Daily review of failed Provisioning and Aggregation

---

# Phase 1 Design

Identities created in ISC will be imported from a CSV file with the required fields, in addition to some further useful fields.

**Useful Additions**
- Company
- Name
- Username
- Company

These will be used for calculating attributesin Provisioning Policy

---

# Phase 2

---

# Phase 3
