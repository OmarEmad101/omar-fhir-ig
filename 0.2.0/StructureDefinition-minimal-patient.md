# Minimal Patient Profile - Omar Minimal FHIR Implementation Guide v0.2.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Minimal Patient Profile**

## Resource Profile: Minimal Patient Profile 

| | |
| :--- | :--- |
| *Official URL*:https://omaremad101.github.io/omar-fhir-ig/StructureDefinition/minimal-patient | *Version*:0.2.0 |
| Draft as of 2026-01-08 | *Computable Name*:MinimalPatient |

 
A minimal Patient profile for demo purposes 

**Usages:**

* Examples for this Profile: [Patient/ExamplePatient](Patient-ExamplePatient.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/omar.minimal.ig|current/StructureDefinition/minimal-patient)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-minimal-patient.csv), [Excel](StructureDefinition-minimal-patient.xlsx), [Schematron](StructureDefinition-minimal-patient.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "minimal-patient",
  "url" : "https://omaremad101.github.io/omar-fhir-ig/StructureDefinition/minimal-patient",
  "version" : "0.2.0",
  "name" : "MinimalPatient",
  "title" : "Minimal Patient Profile",
  "status" : "draft",
  "date" : "2026-01-08T02:13:22+01:00",
  "publisher" : "Omar Emad",
  "contact" : [
    {
      "name" : "Omar Emad",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://omaremad101.github.io"
        },
        {
          "system" : "email",
          "value" : "your.email@example.com"
        }
      ]
    },
    {
      "name" : "Omar Emad",
      "telecom" : [
        {
          "system" : "email",
          "value" : "your.email@example.com"
        }
      ]
    }
  ],
  "description" : "A minimal Patient profile for demo purposes",
  "jurisdiction" : [
    {
      "coding" : [
        {
          "system" : "urn:iso:std:iso:3166",
          "code" : "US",
          "display" : "United States of America"
        }
      ]
    }
  ],
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "loinc",
      "uri" : "http://loinc.org",
      "name" : "LOINC code for the element"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Patient",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Patient",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Patient",
        "path" : "Patient"
      }
    ]
  }
}

```
