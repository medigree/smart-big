# PatientExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **PatientExample**

## Example Patient: PatientExample

-------

**English**

-------

Profile: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (no stated gender), DoB Unknown

-------

-------

**French**

-------

Profil: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (sexe non précisé), Date de Naissance inconnue

-------

-------

**German**

-------

Profile: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (no stated gender), DoB Unknown

-------

-------

**Portuguese**

-------

Perfil: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (sem género declarado), DN Desconhecida

-------

-------

**Spanish**

-------

Profile: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (no stated gender), DoB Unknown

-------

-------

**Lithuanian**

-------

Profile: [MyPatient](StructureDefinition-MyPatient.md)

James Pond (no stated gender), DoB Unknown

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "PatientExample",
  "meta" : {
    "profile" : ["http://smart.who.int/big/StructureDefinition/MyPatient"]
  },
  "name" : [{
    "family" : "Pond",
    "given" : ["James"]
  }]
}

```
