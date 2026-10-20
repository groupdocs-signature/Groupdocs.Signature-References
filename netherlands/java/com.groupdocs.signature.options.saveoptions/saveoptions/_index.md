---
title: "SaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Staat toe om extra opties op te geven, zoals een wachtwoord, bij het opslaan van een document om te ondertekenen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Staat toe om extra opties (zoals wachtwoord) op te geven bij het opslaan van een document om te ondertekenen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initialiseert een nieuw exemplaar van de SaveOptions-klasse met standaardwaarden. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Initialiseert een nieuw exemplaar van de SaveOptions-klasse met het opgegeven outputtype en overschrijfvlag. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Haalt op of stelt in of een bestaand bestand moet worden overschreven met een nieuw uitvoerbestand. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Haalt op of stelt in of een bestaand bestand moet worden overschreven met een nieuw uitvoerbestand. |
|
|  | [getPassword()](#getPassword--) | Haalt op of stelt het wachtwoord in om een ondertekend document op te slaan met wachtwoordbeveiliging. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Haalt op of stelt het wachtwoord in om een ondertekend document op te slaan met wachtwoordbeveiliging. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Haalt op of stelt in of het wachtwoord uit LoadOptions moet worden gebruikt om een ondertekend document als beschermd op te slaan. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Haalt op of stelt in of het wachtwoord uit LoadOptions moet worden gebruikt om een ondertekend document als beschermd op te slaan. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Haalt op of stelt de vlag in om automatisch een extensie toe te voegen wanneer deze ontbrak in het pad van het uitvoerbestand. |
Standaardwaarde is false.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Haalt op of stelt de vlag in om automatisch een extensie toe te voegen wanneer deze ontbrak in het pad van het uitvoerbestand. |
Standaardwaarde is false.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initialiseert een nieuw exemplaar van de SaveOptions-klasse met standaardwaarden.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Initialiseert een nieuw exemplaar van de SaveOptions-klasse met het opgegeven outputtype en overschrijfvlag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Vlag of een ondertekend bestand moet worden overschreven met hetzelfde bestand. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Haalt op of stelt in of een bestaand bestand moet worden overschreven met een nieuw uitvoerbestand.
Anders wordt een nieuw bestand aangemaakt met een nummer als achtervoegsel.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Haalt op of stelt in of een bestaand bestand moet worden overschreven met een nieuw uitvoerbestand.
Anders wordt een nieuw bestand aangemaakt met een nummer als achtervoegsel.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt op of stelt het wachtwoord in om een ondertekend document op te slaan met wachtwoordbeveiliging.
Deze eigenschap wordt niet ondersteund voor afbeeldingsdocumenten.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Haalt op of stelt het wachtwoord in om een ondertekend document op te slaan met wachtwoordbeveiliging.
Deze eigenschap wordt niet ondersteund voor afbeeldingsdocumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Haalt op of stelt in of het wachtwoord uit LoadOptions moet worden gebruikt om een ondertekend document als beschermd op te slaan.
Standaardwaarde is true.
Deze eigenschap wordt niet ondersteund voor afbeeldingsdocumenten.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Haalt op of stelt in of het wachtwoord uit LoadOptions moet worden gebruikt om een ondertekend document als beschermd op te slaan.
Standaardwaarde is true.
Deze eigenschap wordt niet ondersteund voor afbeeldingsdocumenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Haalt op of stelt de vlag in om automatisch een extensie toe te voegen wanneer deze ontbrak in het pad van het uitvoerbestand.
Standaardwaarde is false.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Haalt op of stelt de vlag in om automatisch een extensie toe te voegen wanneer deze ontbrak in het pad van het uitvoerbestand.
Standaardwaarde is false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

