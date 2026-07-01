# Condition Severity Valueset - Template FHIR Implementation Guide - R5 v0.1.0

## ValueSet: Condition Severity Valueset 

 **References** 

* [MyCondition](StructureDefinition-MyCondition.md)

### Logical Definition (CLD)

 

### Expansion

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "severity-vs",
  "url" : "https://healthinfoservices.net/hello-fhir-ig/ValueSet/severity-vs",
  "version" : "0.1.0",
  "name" : "SeverityVS",
  "title" : "Condition Severity Valueset",
  "status" : "draft",
  "date" : "2026-07-01T02:13:59+00:00",
  "publisher" : "HealthInfoServices",
  "contact" : [{
    "name" : "HealthInfoServices",
    "telecom" : [{
      "system" : "url",
      "value" : "https://healthinfoservices.net"
    }]
  },
  {
    "name" : "Support",
    "telecom" : [{
      "system" : "url",
      "value" : "https://www.healthinfoservices.net"
    }]
  }],
  "jurisdiction" : [{
    "coding" : [{
      "system" : "http://unstats.un.org/unsd/methods/m49/m49.htm",
      "code" : "001",
      "display" : "World"
    }]
  }],
  "copyright" : "Daniel Foulkes (HealthInfoServices)",
  "compose" : {
    "include" : [{
      "system" : "http://snomed.info/sct",
      "concept" : [{
        "code" : "255604002",
        "display" : "Mild"
      },
      {
        "code" : "6736007",
        "display" : "Moderate"
      },
      {
        "code" : "24484000",
        "display" : "Severe"
      }]
    }]
  }
}

```
