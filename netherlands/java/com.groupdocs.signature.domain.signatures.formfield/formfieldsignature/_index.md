---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor FormField-handtekeningen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Bevat eigenschappen voor FormField-handtekeningen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Specificeert unieke naam van formulierveld. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Specificeert unieke naam van formulierveld. |
|
|  | [getType()](#getType--) | Specificeert type van formulierveld. |
|
|  | [getValue()](#getValue--) | Specificeert gegevensobject van formulierveld. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Specificeert gegevensobject van formulierveld. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### getName() {#getName--}
```
public final String getName()
```


Specificeert unieke naam van formulierveld.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specificeert unieke naam van formulierveld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Specificeert type van formulierveld.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Specificeert gegevensobject van formulierveld.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specificeert gegevensobject van formulierveld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object |  |

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

