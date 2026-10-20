---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslaanopties voor PDF‑documenten."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Opslaanopties voor PDF‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met standaardwaarden. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met de overschrijfvlag. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat en overschrijfvlag. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Een machtigingswachtwoord (het primaire wachtwoord) vereist een wachtwoord om de machtigingsinstellingen te wijzigen. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Een machtigingswachtwoord (het primaire wachtwoord) vereist een wachtwoord om de machtigingsinstellingen te wijzigen. |
|
|  | [getPermissions()](#getPermissions--) | De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met standaardwaarden.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoertype bestand [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met de overschrijfvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Vlag of een ondertekend bestand moet worden overschreven met hetzelfde bestand. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de PdfSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat en overschrijfvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoertype bestand [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | Vlag of een ondertekend bestand moet worden overschreven met hetzelfde bestand. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Haalt of stelt het bestandsformaat van het ondertekende document in.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Haalt of stelt het bestandsformaat van het ondertekende document in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Een machtigingswachtwoord (het primaire wachtwoord) vereist een wachtwoord om de machtigingsinstellingen te wijzigen.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Een machtigingswachtwoord (het primaire wachtwoord) vereist een wachtwoord om de machtigingsinstellingen te wijzigen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie.


Om deze rechten te wijzigen, de
PermissionsPassword
moet worden ingesteld.
De waarde is een combinatie van vlaggen uit [Permissions](../../com.groupdocs.signature.options/permissions).
Een
null
waarde betekent dat er geen expliciete rechten worden toegepast.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
