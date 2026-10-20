---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för textinmatningsformulärsignatur för Pdf-dokument"
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Innehåller egenskaper för textinmatningsformulärsignatur för Pdf-dokument

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Skapar PdfTextFormFieldSignature med fördefinierat namn. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Skapar PdfTextFormFieldSignature med fördefinierat namn. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Hämtar eller anger text för formulärfältets textinmatning. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger text för formulärfältets textinmatning. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona FormField Signature-instans. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Skapar PdfTextFormFieldSignature med fördefinierat namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Skapar PdfTextFormFieldSignature med fördefinierat namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | text | java.lang.String | Text för formulärfältobjektet. |
|

### getText() {#getText--}
```
public final String getText()
```


Hämtar eller anger text för formulärfältets textinmatning.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Hämtar eller anger text för formulärfältets textinmatning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

