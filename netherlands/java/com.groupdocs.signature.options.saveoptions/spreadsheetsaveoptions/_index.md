---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslaanopties voor spreadsheet‑documenten."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Opslaanopties voor spreadsheet‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met standaardwaarden. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met een vooraf gedefinieerd uitvoerbestandsformaat. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met het opgegeven uitvoertype en overschrijvingsvlag. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met standaardwaarden.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met een vooraf gedefinieerd uitvoerbestandsformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Specificeert het uitvoerbestandsformaat. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de SpreadsheetSaveOptions‑klasse met het opgegeven uitvoertype en overschrijvingsvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Specificeert het uitvoerbestandsformaat. |
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

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
