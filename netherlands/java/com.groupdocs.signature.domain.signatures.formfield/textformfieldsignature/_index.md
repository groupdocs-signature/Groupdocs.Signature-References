---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor een tekstinvoerveldhandtekening voor PDF-document."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Bevat eigenschappen voor een tekstinvoerveldhandtekening voor PDF-document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Maakt PdfTextFormFieldSignature met vooraf gedefinieerde naam. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Maakt PdfTextFormFieldSignature met vooraf gedefinieerde naam. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Haalt op of stelt de tekst van het tekstinvoerveld van het formulier in. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Haalt op of stelt de tekst van het tekstinvoerveld van het formulier in. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Maakt PdfTextFormFieldSignature met vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Maakt PdfTextFormFieldSignature met vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | tekst | java.lang.String | Tekst van formulierveldobject. |
|

### getText() {#getText--}
```
public final String getText()
```


Haalt op of stelt de tekst van het tekstinvoerveld van het formulier in.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Haalt op of stelt de tekst van het tekstinvoerveld van het formulier in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

