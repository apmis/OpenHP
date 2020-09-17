# OpenHP
Open Health Platform is a digital health platform for regional health authorities in developing countries to fast track adoption of digital health within (public/private) facilities in their jurisdiction. The platform allows for one unique longitudinal healthcare record for each citizen and sharing of healthcare data among the stakeholders easily as well as providing aggregate healthcare data for their region in a simple and secure manner.
The platform is patient centric and we expect the citizens would be able to interact with healthcare through a mobile app and be able to view their healthcare data.
The goal is to provide real time analytics that regional health governments can act on and respond to using current technology stack.

# Backend Infrastructure
1. OpenHP would be a fhir-first and fhir-native aplication (https://www.hl7.org/fhir/). 
1. It is a cloud-hybrid solution with offline-first capability. This implies that it can work where internet connectivty is not constant. As a cloud hybrid solution, it would have a local application server within the facility or organization that is able to synch data  with the cloud SaaS solution based on internet availability as well as synch with webapp or andriod apps on a mobile client device. The mobile client device (via webapp or andriod app) would be able to synch data with the Cloud SaaS solution and/or the local organization application server. Effectively you have a three-way sync.
1. OpenHP would be reactive or realtime event driven enabling secure chat messaging and event driven updates and notification.
1. Security via OAuth 2.0 and HIPAA /GDPR compliance (with possible Meaningful use certification : is ths still a thing!)
1. Ability to deploy backend as a microsoervice, docker /kubernetes implementation.
1. Ability to deploy Smart on FHIR apps would be an added advantage.
1. Utilization of terminologies such as ICD10, SNOMED, RXNORM, LOINC and other codeset would be important.
1. We expect to be able to implement realtime analytics and potential data pipeline for machine learning.
1. We expect to be able to share verify managed care clients, claims information and implement contracts between providers and insurers.
1. OpenHP would enable facilities offer telemedicine services to clients as well as intergrate with LIS and DICOM modalities (PACS/RIS) within a facility.
1. OpenHP SaaS Cloud would be a multi-tenanted solution.
1. OpenHP would offer CLinical Decision support
1. OpenHP would be able to push data to DHIS2 and generate the NHMIS Monthly summary report.
1. Possible extension of data storage to meet ISO 3606 spec (OpenEHR) down the line.

**MODULES**
1. User Management
1. Facility Management Module
1. Patient Manager Module.
1. Appointment manager
1. Clinic Management Module // Patient-Location Manager
1. Clinical Documentation Manager
1. Ward Manager Module.
1. Inventory Management
1. Pharmacy.
1. Laboratory.
1. Radiology.
1. Immunization
1. Payment Module.
1. Billing Manager.
1. Managed Care
1. Analytics
1. Audit
1. Admin module
