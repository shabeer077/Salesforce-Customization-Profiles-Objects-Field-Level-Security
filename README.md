# Salesforce-Customization-Profiles-Objects-Field-Level-Security
This project demonstrates how I configured a Salesforce org to support a real-world business use case by customizing **profiles**, **objects**, and **field-level access** — all using Salesforce’s **point-and-click tools**.

# 🔧 Salesforce Customization: Profiles, Objects & Field-Level Security

## 📌 Overview

This project demonstrates how I configured a Salesforce org to support a real-world business use case by customizing **profiles**, **objects**, and **field-level access** — all using Salesforce’s **point-and-click tools**.

It was part of the hands-on Trailhead project:  
**“Work with Standard and Custom Fields”**  
from the **Admin Beginner** trail.

---

## 🚀 What I Built

### 👥 **Profiles**
- Cloned the **Standard User** profile to create:
  - ✅ Sales User
  - ✅ Support User

---

### 🏷️ **Renamed Standard Field**
- Renamed the **Rating** field on the **Account** object to:
  - **Prospect Rating**
- Added help text for clarity:
  > _"This indicates the likelihood of a sale being made to this account in the next six months..."_

---

### 📋 **Picklist Customization**
- Added a new value to the **Prospect Rating** picklist:
  - `Not Known`

---

### 🔐 **Field-Level Security**
- Made **Prospect Rating** read-only for all profiles **except** Sales User.

---

### ✅ **Custom Fields Created on Account Object**

#### 1. **Checkbox Field**
- **Field Label**: Has Support Plan  
- **Field Name**: `Has_Support_Plan`  
- **Purpose**: Used by Sales to indicate if a customer has an active support plan  
- **Access**: Editable by Sales & Support Users only

#### 2. **Date Field**
- **Field Label**: Support Plan Expiration Date  
- **Field Name**: `Support_Plan_Expiration_Date`  
- **Purpose**: Indicates when a support plan is due for renewal  
- **Access**: Editable by Sales & Support Users only

---

## 💼 Skills Demonstrated

- ✅ Custom Profile Management
- ✅ Standard Field Renaming
- ✅ Picklist Value Configuration
- ✅ Help Text & Descriptions
- ✅ Field-Level Security (FLS)
- ✅ Checkbox and Date Field Creation
- ✅ Business Process Simulation via Declarative Tools

---

## 🏁 Outcome

This project enhanced my understanding of how to configure Salesforce to meet specific business needs **without code**, by using standard admin features like:

- Profiles
- Field-Level Security
- Picklists & Field Metadata
- Object Manager
- UI Customization

---

## 📚 Reference

Trailhead Module: [Work with Standard and Custom Fields](https://trailhead.salesforce.com/)

---

## 🏷️ Tags

`#SalesforceAdmin` `#Trailhead` `#CustomFields` `#FieldSecurity` `#Profiles` `#NoCode` `#CRM` `#PointAndClick` `#LearningInPublic`

