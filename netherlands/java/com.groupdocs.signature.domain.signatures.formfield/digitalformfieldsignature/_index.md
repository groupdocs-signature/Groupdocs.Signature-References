---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor een digitale handtekening invoerveld voor PDF-documenten."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Bevat eigenschappen voor een digitale handtekening invoerveld voor PDF-documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Maakt PdfDigitalFormFieldSignature aan met een vooraf gedefinieerde naam. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSigned()](#getSigned--) | Alleen-lezen eigenschap die aangeeft of Form-field Signature is ondertekend met een digitaal certificaat. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Maakt PdfDigitalFormFieldSignature aan met een vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Alleen-lezen eigenschap die aangeeft of Form-field Signature is ondertekend met een digitaal certificaat.


**Returns:**
boolean
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon FormField Signature‑instantie.


**Returns:**
java.lang.Object - Retourneert gekloonde FormField Signature‑instantie.

