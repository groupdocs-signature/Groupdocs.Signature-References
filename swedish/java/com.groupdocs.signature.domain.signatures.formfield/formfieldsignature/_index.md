---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för Form-fältssignatur."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Innehåller egenskaper för Form-fältssignatur.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Anger unikt namn för formulärfält. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Anger unikt namn för formulärfält. |
|
|  | [getType()](#getType--) | Anger formulärfältstyp. |
|
|  | [getValue()](#getValue--) | Anger dataobjekt för formulärfält. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Anger dataobjekt för formulärfält. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona FormField Signature-instans. |
|
### getName() {#getName--}
```
public final String getName()
```


Anger unikt namn för formulärfält.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Anger unikt namn för formulärfält.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Anger formulärfältstyp.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Anger dataobjekt för formulärfält.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Anger dataobjekt för formulärfält.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona FormField Signature-instans.


**Returns:**
java.lang.Object – Returnerar klonad FormField Signature-instans.

