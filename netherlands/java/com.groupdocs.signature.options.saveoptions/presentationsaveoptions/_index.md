---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslaanopties voor presentatiedocumenten."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Opslaanopties voor presentatiedocumenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met standaardwaarden. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met een gespecificeerd uitvoertype en overschrijfvlag. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Initialiseert een nieuw exemplaar van de PresentationSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag. |
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
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met standaardwaarden.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met een gespecificeerd uitvoerbestandformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoerbestandtype [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de PresentationSaveOptions-klasse met een gespecificeerd uitvoertype en overschrijfvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Vlag of een ondertekend bestand moet worden overschreven met hetzelfde bestand. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de PresentationSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoerbestandtype [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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
