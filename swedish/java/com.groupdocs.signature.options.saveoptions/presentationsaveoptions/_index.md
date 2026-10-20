---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Spara alternativ för presentationsdokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Spara alternativ för presentationsdokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Initierar en ny instans av PresentationSaveOptions-klassen med standardvärden. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Initierar en ny instans av PresentationSaveOptions-klassen med angivet utdatafilformat. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Initierar en ny instans av PresentationSaveOptions-klassen med angiven utdata typ och överskrivningsflagga. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Initierar en ny instans av PresentationSaveOptions-klass med angivet utdatafilformat och överskrivningsflagga. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Initierar en ny instans av PresentationSaveOptions-klassen med standardvärden.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Initierar en ny instans av PresentationSaveOptions-klassen med angivet utdatafilformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Initierar en ny instans av PresentationSaveOptions-klassen med angiven utdata typ och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flagga som anger om den signerade filen ska skrivas över med samma fil. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initierar en ny instans av PresentationSaveOptions-klass med angivet utdatafilformat och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
