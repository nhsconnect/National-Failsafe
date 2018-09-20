---
title: Release Notes
keywords: development, versioning
tags: [development]
sidebar: overview_sidebar
permalink: overview_release_notes.html
summary: Summary release notes of the versions released in National Population Failsafe Management Implementation Guide
---

This site is under active development by NHS Digital and is intended to provide guidance and FHIR components for National Population Failsafe Management. This project is being developed using an agile methodology so iterative updates to content will be added on a regular basis, and remains subject to clinical review. Changes to this specification following the initial beta release will be documented here.

## Beta 1.1.0 ##

The EMS Event Message Bundle Structure page has been update to include clarification on the use of absolute URL references to Organization resources via the [FHIR ODS Lookup API](https://developer.nhs.uk/apis/ods).

Following stakeholder feedback this implementation guidance has been updated as follows:

- **National Failsafe Alert** - changes to data item requirements
	- GP Practice - changed to Required
	- Condition ID - changed to Mandatory
	- Condition Description - changed to Mandatory
	- Reason for alert - changed to Mandatory
	- Service needed to action - changed to Mandatory
	- Provider needed to action - new Mandatory item
	- Action Required - changed to Mandatory
	- Action required By Date - changed to Optional
	- Readable Format - changed to Mandatory

- **National Failsafe Alert Nullify Request** - Nullification Reason corrected to refer to EMS-FailsafeAlertNullify-Task-1


**Examples** 
- all relevant example instances updated to reflect all of the changes above.

Added page [Versioning](explore_event_versioning.html) to clarify versioning of event instances and event definitions.

## Beta 1.0.1 ##
This implementation guidance has been updated to include a guidance page for accessing example messages.
 
## Beta 1.0.0 ##
This Beta release includes National Population Failsafe Management implementation guidance to support the development of the National Failsafe Alert and Failsafe Nullify event messages.


