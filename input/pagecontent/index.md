# Risk Evaluation and Mitigation Strategy (REMS) Implementation Guide Home Page

### Overview
A Risk Evaluation and Mitigation Strategy (REMS) is a drug safety program that the U.S. Food and Drug Administration (FDA) can require for certain medications with serious safety concerns to help ensure the benefits of the medication outweigh its risks. REMS are designed to reinforce medication use behaviors and actions that support the safe use of that medication. While all medications have labeling that informs health care stakeholders about medication risks, only a few medications require a REMS.

This implementation guide strives to enable automated REMS workflows between the various participants within the REMS ecosystem.  

### Content and organization
The implementation guide is organized into the following sections:
* [Use Cases](use-cases.html) and Overview describes the intent of the implementation guide, gives examples of its use and provides a high-level overview of expected process flow

* [Technical Background](technical-background.html) describes the different specifications this implementation guide relies on and indicates what developers should read and understand prior to implementing this specification
* [Formal Specification](specification.html) covers the detailed implementation requirements and conformance expectations
* [Artifacts](artifacts.html) introduces and provides links to the FHIR R4 profiles, operations and other FHIR artifacts used in this implementation guide
* [Downloads](downloads.html) allows download of this and other specifications as well as other useful files
* [Credits](credits.html) identifies the individuals and organizations involved in developing this implementation guide
### Dependencies 
This implementation guide relies on the following other specifications: 

* [FHIR R4](http://hl7.org/fhir/R4/) - The ‘current’ official version of FHIR as of the time this implementation guide was published. 
* [US Core STU3](http://hl7.org/fhir/us/core) - The published version of US Core based on FHIR R4.
* [Da Vinci CRD](https://build.fhir.org/ig/HL7/davinci-crd/)
* [Da Vinci DTR](https://build.fhir.org/ig/HL7/davinci-dtr/)
* [CDS Hooks CI Build](https://cds-hooks.org/specification/current/) - The community release that defines the hooks used by this implementation guide
* [CDS Hooks 1.0](https://cds-hooks.hl7.org/1.0/) - The official standard for trial use publication of CDS Hooks that defines the CDS Hooks protocol and interfaces used by this implementation guide
* [NCPDP Script](https://www.ncpdp.org/) - The SCRIPT Standard supports transactions for new prescriptions, prescription changes, refill requests, prescription fill status notification, prescription cancellation, medication history, transactions for long term care environments, and prior authorization exchanges. 
* [SMART on FHIR](http://hl7.org/fhir/smart-app-launch) - The specification provides a reliable, secure authorization protocol for SMART apps launched from a clinical system to support coverage requirements discovery (e.g. what-if scenarios).
* [Structured Product Labling IG](https://build.fhir.org/ig/HL7/fhir-spl/branches/main/index.html)
* [Specialty Medication Enrollment IG](https://build.fhir.org/ig/HL7/fhir-specialty-rx/artifacts.html)


