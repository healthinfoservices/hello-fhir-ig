# Observation ValueSet - Template FHIR Implementation Guide - R5 v0.1.0

## ValueSet: Observation ValueSet 

 
Use all LOINC codes for observations 

 **References** 

This value set is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

### Logical Definition (CLD)

 

### Expansion

-------

 [Description of the above table(s)](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#terminology). 



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "obs-vs",
  "url" : "https://healthinfoservices.net/hello-fhir-ig/ValueSet/obs-vs",
  "version" : "0.1.0",
  "name" : "ObsVS",
  "title" : "Observation ValueSet",
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
  "description" : "Use all LOINC codes for observations",
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
      "system" : "http://loinc.org"
    }]
  }
}

```
