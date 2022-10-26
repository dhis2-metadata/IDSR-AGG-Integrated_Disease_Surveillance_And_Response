# Release Note

## 1.2.0

A new version (1.2.0) of the aggregate Integrated Disease Surveillance (IDS) package has been released with new content, configuration fixes and improvements. These are summarized below. 

### New Content

New **validation rules** , **validation rule groups** [IDS `OEfzRCqPEK`] and **validation notifications templates** have been been added. The validation notifications have been configured to send outbreak alerts to user groups according to validation rules that define the outbreak threshold. Validation notification templates have been configured for each outbreak alert with a customized message that can be further localized during implementation. 

New **dataset** for weekly population data [Population (weekly) `zTU6UZXtgwR`]. The 'Population (weekly) data set is used as part of the IDS package to provide population denominators for surveillance indicators that are monitored & analyzed on a weekly basis, such weekly incidence rates that can trigger outbreak alerts. While the dataset is generic and can be re-used to provide denominators for other programs conducting weekly data collection/monitoring, it is most typically used in the surveillance use case and therefore added to the package. By default, the dataset is assigned at Level 3 representing 'districts' in the package dev environment and can be modified. 

New **indicator** [IDS - Incidence rate of measles (confirmed cases), O3FS25ICj7i] used for analysis in triangulation dashboards comparing disease surveillance and immunization program data. 

Added **user group** for data capture [IDS data capture `tFbRg3v7QLB`]. This user group is assigned capture access to the IDS datasets.

### Fixes & Improvements

Object **names** and **codes** have been updated to fix spelling errors in the aggregate data entry form and align with standard recommended DHIS2 naming conventions and for consistency with internal metadata coding practices. Relevant object and code prefixes have been updated with 'IDS' to facilitate metadata management. 

**Data entry forms** and html code used for custom forms have been updated, cleaned code and made translatable for the following **data sets**

- IDS - Report: Suspected, Confirm, Death `ZyZmZTUwctj`
- IDS - Report: Suspected, Death `m9yPuQEqxmS`
- IDS - Aggregate Lab Weekly Report `OTvkNTijYQY`

Removed **data elements** for reporting Anthrax and Influenza-like illness which are not yet fully verified against WHO requirements and guidelines for incorporation into the weekly integrated disease surveillance module.

> **IMPORTANT**
>
> An older variation of this metadata package labeled 'with no disaggregation' has been discontinued. The current packages includes the WHO recommended age disaggregation variables according to disease. 
