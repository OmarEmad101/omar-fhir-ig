# Minimal Patient Instance - Omar Minimal FHIR Implementation Guide v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Minimal Patient Instance**

## Example Patient: Minimal Patient Instance

Profile: [Minimal Patient Profile](StructureDefinition-minimal-patient.md)

Omar Abdelbar (no stated gender), DoB: 2002-05-08

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "ExamplePatient",
  "meta" : {
    "profile" : [
      "https://omaremad101.github.io/omar-fhir-ig/StructureDefinition/minimal-patient"
    ]
  },
  "name" : [
    {
      "family" : "Abdelbar",
      "given" : ["Omar"]
    }
  ],
  "birthDate" : "2002-05-08"
}

```
