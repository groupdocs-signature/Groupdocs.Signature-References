---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Spara alternativ för PDF-dokument."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Spara alternativ för PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Initierar en ny instans av PdfSaveOptions-klassen med standardvärden. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Initierar en ny instans av PdfSaveOptions-klassen med angivet utdatafilformat. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Initierar en ny instans av PdfSaveOptions-klassen med överskrivningsflagga. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Initierar en ny instans av PdfSaveOptions-klassen med angivet utdatafilformat och överskrivningsflagga. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Ett behörighetslösenord (huvudlösenordet) kräver ett lösenord för att ändra behörighetsinställningar. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Ett behörighetslösenord (huvudlösenordet) kräver ett lösenord för att ändra behörighetsinställningar. |
|
|  | [getPermissions()](#getPermissions--) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initierar en ny instans av PdfSaveOptions-klassen med standardvärden.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Initierar en ny instans av PdfSaveOptions-klassen med angivet utdatafilformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Initierar en ny instans av PdfSaveOptions-klassen med överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flagga som anger om den signerade filen ska skrivas över med samma fil. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initierar en ny instans av PdfSaveOptions-klassen med angivet utdatafilformat och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | Flagga som anger om den signerade filen ska skrivas över med samma fil. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Hämtar eller anger filformat för signerat dokument.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Hämtar eller anger filformat för signerat dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Ett behörighetslösenord (huvudlösenordet) kräver ett lösenord för att ändra behörighetsinställningar.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Ett behörighetslösenord (huvudlösenordet) kräver ett lösenord för att ändra behörighetsinställningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion.


För att ändra dessa behörigheter, 
PermissionsPassword
måste anges.
Värdet är en flaggkombination från [Permissions](../../com.groupdocs.signature.options/permissions).
En
null
värde betyder att inga explicita behörigheter tillämpas.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
