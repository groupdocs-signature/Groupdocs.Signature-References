---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Spara alternativ för kalkylbladsdokument."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Spara alternativ för kalkylbladsdokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Initierar en ny instans av SpreadsheetSaveOptions-klass med standardvärden. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Initierar en ny instans av SpreadsheetSaveOptions-klass med fördefinierat utdatafilformat. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Initierar en ny instans av SpreadsheetSaveOptions-klass med angiven utdata typ och överskrivningsflagga. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Initierar en ny instans av SpreadsheetSaveOptions-klass med standardvärden.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Initierar en ny instans av SpreadsheetSaveOptions-klass med fördefinierat utdatafilformat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Anger utdatafilformat. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initierar en ny instans av SpreadsheetSaveOptions-klass med angiven utdata typ och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileFormat | int | Anger utdatafilformat. |
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
