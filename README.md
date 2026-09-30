# Incident Lifecycle Automation in ServiceNow

## 📌 Project Overview

**Incident Lifecycle Automation in ServiceNow** is an end-to-end Incident Management implementation designed to manage incidents from creation to resolution.

The project demonstrates how ServiceNow modules such as Incident Management, Knowledge Management, Change Management, Configuration Management, and SLA tracking work together to support structured incident resolution.
# Incident Lifecycle Automation in ServiceNow

## 🔗 Project Demo

[▶️ View Project Demo](https://drive.google.com/drive/folders/1K1JnGiWLt0UAAvhPhd3OXPx8Q3WEXYNm)

## 📌 Project Overview

Incident Lifecycle Automation in ServiceNow is an end-to-end Incident Management implementation...

## 🎯 Project Objectives

* Create and classify incidents.
* Associate incidents with Services, Service Offerings, and Configuration Items.
* Use Knowledge articles for troubleshooting.
* Reassign incidents to appropriate support groups.
* Track incidents through Level 2 support.
* Handle emergency changes.
* Create and manage child incidents.
* Track SLAs.
* Resolve incidents with proper documentation.
* Create Knowledge articles from resolved incidents.

## 🛠️ ServiceNow Modules & Features

* Incident Management
* Service Management
* Configuration Management
* Knowledge Management
* Change Management
* SLA Tracking
* Service Operations Workspace
* Child Incident Management
* Emergency Change Management

## 🔄 End-to-End Workflow

```text
Service Creation
       ↓
Service Offering Creation
       ↓
Incident Creation
       ↓
Incident Classification
       ↓
Knowledge Integration
       ↓
Reassignment to Network Team
       ↓
Level 2 Support
       ↓
Configuration Item Update
       ↓
On Hold – Awaiting Change
       ↓
Child Incident Creation
       ↓
Cause Identification
       ↓
Emergency Change
       ↓
Incident Resolution
       ↓
Knowledge Creation
       ↓
Final Validation
```

## 📋 Key Implementation

### Service Hierarchy

```text
Service
   ↓
Service Offering
   ↓
Configuration Item (CI)
```

Example:

* **Service:** Remote Access
* **Service Offering:** Corporate VPN
* **Configuration Item:** ThinkStationS20 / PowerEdge

The service hierarchy is used to associate incidents with the appropriate business service and technical configuration item.

### Incident Management

The incident is created, classified, assigned to the appropriate support group, and tracked through its lifecycle.

The project includes:

* Incident classification
* Knowledge article integration
* Reassignment and escalation
* Level 2 support
* SLA tracking
* Incident hold and change handling
* Child incident creation
* Incident resolution

### Emergency Change

An emergency change is created when an urgent change is required to resolve a critical incident or prevent major service disruption.

### Knowledge Management

After resolving the incident, a Knowledge article is created from the resolution so that the documented solution can be reused for similar incidents.

## ✅ Final Validation

The project validates:

* Parent incident is Resolved
* Child incident is Resolved
* Change request is linked
* Knowledge article is created
* SLA tracking is visible
* Incident resolution is properly documented

## 🧪 Testing & Deployment Validation

The following areas were validated:

* Incident Lifecycle
* Escalation Process
* Change Integration
* Knowledge Creation
* Child Incident Management
* SLA Tracking
* Multi-Team Collaboration

## 🌟 Project Outcome

This project demonstrates how ServiceNow can be used to manage incidents from initial reporting through final resolution and knowledge reuse.

It provides practical experience in connecting Incident, Change, Knowledge, Configuration Management, Service Management, and SLA tracking for structured IT service delivery.

## 📸 Screenshots

Add screenshots of:

1. Service Creation
2. Service Offering
3. Incident Creation
4. Incident Classification
5. Knowledge Article
6. Assignment Group
7. SLA
8. Child Incident
9. Emergency Change
10. Incident Resolution
11. Knowledge Creation
12. Final Validation

## 👩‍💻 Author

**Laxmi Amitha Mutyala**

AI/ML Student | ServiceNow Enthusiast
