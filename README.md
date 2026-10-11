# CS2 Android Digital Forensics Case Study

## Project Overview

This repository documents the CS2 digital forensics case study involving an Android 10 Google Pixel 3 device dataset. It organises the examination methodology, evidence register, artefact findings, event chronology, validation notes, and appendices supporting the case report.

The purpose of this repository is to provide a clear and structured record of the forensic examination and to distinguish observed artefacts from interpretations and conclusions.

## Case Information

* **Module:** CS2
* **Case type:** Android mobile-device digital forensics
* **Device identified in the dataset:** Google Pixel 3 (`blueline`)
* **Operating system:** Android 10
* **Android SDK level:** 29
* **Build identifier:** `QQ1A.200105.003`
* **Security patch level:** 2020-01-01
* **Examination focus:** Device configuration, communications artefacts, application data, timestamps, and event chronology
* **Report author:** Asmau Danzaria
* **Student registration number:** 2617285

## Objectives

The objectives of the examination are to:

1. Document the available dataset and its integrity checks.
2. Identify relevant Android system and application artefacts.
3. Record observations from databases and configuration files.
4. Construct an event chronology using recorded timestamps.
5. Distinguish direct observations from interpretations.
6. Document limitations and identify findings that require further validation.


## Dataset and Evidence Handling

The examination notes identify the source archive as `Pixel 3 (2).zip`. The recorded SHA-256 value is:

`ca6918ef8b20486b6a5ded15609ac51318f377829480f93be3ba15364a8aa00a`

The recorded archive test reported: `Everything is Ok`.

These values are included as reported examination results and should be independently reproduced before being treated as independently verified. The original dataset is not included in this repository. Large forensic datasets, private communications, account identifiers, authentication codes, and other sensitive artefacts should not be committed to a public repository.

## Areas Examined

The examination notes identify artefacts associated with:

* Android device and system settings
* SMS and call-log databases
* Contacts and calendar databases
* Google Messages and Google Phone
* TextNow
* WhatsApp and other third-party messaging applications
* Google Maps and Google Photos application databases

The identification of an application database does not, by itself, establish that a particular activity occurred. Findings are documented according to the artefacts and records actually observed.

## Methodology

The case documentation covers dataset integrity checks, examination of extracted files, SQLite database inspection, review of Android system settings, timestamp conversion, and comparison of relevant records across artefact sources.

The acquisition context is documented as a logical copy following TWRP root access, rather than a bit-for-bit physical image. The report therefore considers the limitations of the available acquisition and the extent to which individual artefacts support a conclusion.

## Findings and Interpretation

The findings are separated into observed artefacts, their relevance to the investigation, and their limitations. Timestamps are interpreted with attention to the source format and timezone. Where a relationship between records has not been established, it is not presented as a confirmed link.

The chronology is a reconstruction from available records, not a complete record of all activity on the device.

## Limitations

* The available dataset may not contain every artefact originally present on the device.
* Database schemas or application presence alone do not prove a specific user action.
* A stored contact name does not independently establish the identity of the person using a number.
* A message or verification notification does not independently prove account ownership or control.
* A timestamp does not independently establish the physical location of the device or its user.
* Findings requiring independent validation are identified in the report and validation checklist.

## Repository Contents

* **Case report:** Main report and conclusions.
* **Findings log:** Artefact observations and their limitations.
* **Chronology:** Supported event sequence with timestamp information.
* **Methodology:** Examination approach and evidence-handling notes.
* **Appendices:** Supporting queries, timestamp conversions, and outstanding validation tasks.

## Academic Integrity

This repository is intended to support the submitted CS2 case study. All findings should be traceable to the examination material, and any limitations or unverified results should be stated explicitly. Any tools, procedures, or sources used in the final work should be acknowledged in accordance with the institution's academic integrity requirements.

## Author

**Asmau Danzaria**
CS2 Digital Forensics Case Study
