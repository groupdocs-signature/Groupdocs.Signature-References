---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Spara alternativ för ordbehandlingsdokument."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Spara alternativ för ordbehandlingsdokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initierar en ny instans av WordProcessingSaveOptions-klass med standardvärden. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initierar en ny instans av WordProcessingSaveOptions-klass med angivet utdatafilformat. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initierar en ny instans av WordProcessingSaveOptions-klass med angiven utdata typ och överskrivningsflagga. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initierar en ny instans av WordProcessingSaveOptions-klass med angivet utdatafilformat och överskrivningsflagga. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Hämtar eller anger filformat för signerat dokument. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | Valfri OOXML-kompatibilitetsnivå för det signerade dokumentet. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | Valfri OOXML-kompatibilitetsnivå för det signerade dokumentet. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Initierar en ny instans av WordProcessingSaveOptions-klass med standardvärden.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Initierar en ny instans av WordProcessingSaveOptions-klass med angivet utdatafilformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initierar en ny instans av WordProcessingSaveOptions-klass med angiven utdata typ och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flagga som anger om den signerade filen ska skrivas över med samma fil. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initierar en ny instans av WordProcessingSaveOptions-klass med angivet utdatafilformat och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Utdatafiltyp [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


Valfri OOXML-kompatibilitetsnivå för det signerade dokumentet. När den är inställd, åsidosätter den
originaldokumentets kompatibilitet. När
null
(standard), den laddade dokumentets
kompatibilitet bevaras. Endast tillämpad för OOXML-format
(Docx, Docm, Dotx, Dotm, FlatOpc och FlatOpc-varianter).


Värdet är ett av [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


Valfri OOXML-kompatibilitetsnivå för det signerade dokumentet. När den är inställd, åsidosätter den
originaldokumentets kompatibilitet. När
null
(standard), den laddade dokumentets
kompatibilitet bevaras. Endast tillämpad för OOXML-format
(Docx, Docm, Dotx, Dotm, FlatOpc och FlatOpc-varianter).


Värdet är ett av [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering


**Returns:**
java.lang.String -
