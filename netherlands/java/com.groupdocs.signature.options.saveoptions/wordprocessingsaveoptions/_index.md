---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Opslaanopties voor WordProcessing‑documenten."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Opslaanopties voor WordProcessing‑documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met standaardwaarden. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoertype en overschrijvingsvlag. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Haalt of stelt het bestandsformaat van het ondertekende document in. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | Optioneel OOXML‑conformiteitsniveau voor het ondertekende document. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | Optioneel OOXML‑conformiteitsniveau voor het ondertekende document. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met standaardwaarden.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoerbestandtype [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoertype en overschrijvingsvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Vlag of een ondertekend bestand moet worden overschreven met hetzelfde bestand. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de WordProcessingSaveOptions‑klasse met het opgegeven uitvoerbestandsformaat en overschrijvingsvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileFormat | int | Uitvoerbestandtype [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


Optioneel OOXML‑conformiteitsniveau voor het ondertekende document. Indien ingesteld, overschrijft het
de conformiteit van het oorspronkelijke document. Wanneer
null
(standaard), de geladen document‑
conformiteit wordt behouden. Alleen gerespecteerd voor OOXML‑formaten
(Docx, Docm, Dotx, Dotm, FlatOpc en FlatOpc‑varianten).


De waarde is een van [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


Optioneel OOXML‑conformiteitsniveau voor het ondertekende document. Indien ingesteld, overschrijft het
de conformiteit van het oorspronkelijke document. Wanneer
null
(standaard), de geladen document‑
conformiteit wordt behouden. Alleen gerespecteerd voor OOXML‑formaten
(Docx, Docm, Dotx, Dotm, FlatOpc en FlatOpc‑varianten).


De waarde is een van [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie


**Returns:**
java.lang.String -
