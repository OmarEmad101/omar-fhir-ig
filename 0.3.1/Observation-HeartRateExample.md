# HeartRateExample - Omar Minimal FHIR Implementation Guide v0.3.1

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **HeartRateExample**

## Example Observation: HeartRateExample

Profile: [Device Observation](StructureDefinition-device-observation.md)

**status**: Final

**category**: Vital Signs

**code**: Heart Rate

**subject**: [Patient/example](Patient/example)

**value**: 72 beats/min

**device**: [Device/example](Device/example)



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "HeartRateExample",
  "meta" : {
    "profile" : [
      "https://omaremad101.github.io/omar-fhir-ig/StructureDefinition/device-observation"
    ]
  },
  "status" : "final",
  "category" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/observation-category",
          "code" : "vital-signs"
        }
      ]
    }
  ],
  "code" : {
    "text" : "Heart Rate"
  },
  "subject" : {
    "reference" : "Patient/example"
  },
  "valueQuantity" : {
    "value" : 72,
    "unit" : "beats/min"
  },
  "device" : {
    "reference" : "Device/example"
  }
}

```
