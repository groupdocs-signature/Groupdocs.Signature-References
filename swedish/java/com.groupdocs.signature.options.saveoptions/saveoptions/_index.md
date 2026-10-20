---
title: "SaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Tillåter att ange ytterligare alternativ såsom lösenord när ett dokument sparas för signering."
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Tillåter att specificera ytterligare alternativ (såsom lösenord) när ett dokument sparas för signering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | Initierar en ny instans av SaveOptions-klassen med standardvärden. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Initierar en ny instans av SaveOptions-klassen med specificerad utmatningstyp och överskrivningsflagga. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Hämtar eller anger om en befintlig fil ska skrivas över med den nya utdatafilen. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Hämtar eller anger om en befintlig fil ska skrivas över med den nya utdatafilen. |
|
|  | [getPassword()](#getPassword--) | Hämtar eller anger lösenord för att spara signerat dokument med lösenordsskydd. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenord för att spara signerat dokument med lösenordsskydd. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | Hämtar eller anger om lösenord från LoadOptions ska användas för att spara signerat dokument som skyddat. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Hämtar eller anger om lösenord från LoadOptions ska användas för att spara signerat dokument som skyddat. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Hämtar eller anger flagga för att automatiskt lägga till filändelse när den saknades i sökvägen för utdatafilen. |
Standardvärdet är falskt.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Hämtar eller anger flagga för att automatiskt lägga till filändelse när den saknades i sökvägen för utdatafilen. |
Standardvärdet är falskt.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Initierar en ny instans av SaveOptions-klassen med standardvärden.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Initierar en ny instans av SaveOptions-klassen med specificerad utmatningstyp och överskrivningsflagga.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flagga som anger om den signerade filen ska skrivas över med samma fil. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Hämtar eller anger om en befintlig fil ska skrivas över med den nya utdatafilen.
Annars kommer en ny fil att skapas med ett nummer som suffix.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Hämtar eller anger om en befintlig fil ska skrivas över med den nya utdatafilen.
Annars kommer en ny fil att skapas med ett nummer som suffix.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar eller anger lösenord för att spara signerat dokument med lösenordsskydd.
Denna egenskap stöds inte för bilddokument.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Hämtar eller anger lösenord för att spara signerat dokument med lösenordsskydd.
Denna egenskap stöds inte för bilddokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Hämtar eller anger om lösenord från LoadOptions ska användas för att spara signerat dokument som skyddat.
Standardvärdet är sant.
Denna egenskap stöds inte för bilddokument.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Hämtar eller anger om lösenord från LoadOptions ska användas för att spara signerat dokument som skyddat.
Standardvärdet är sant.
Denna egenskap stöds inte för bilddokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Hämtar eller anger flagga för att automatiskt lägga till filändelse när den saknades i sökvägen för utdatafilen.
Standardvärdet är falskt.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Hämtar eller anger flagga för att automatiskt lägga till filändelse när den saknades i sökvägen för utdatafilen.
Standardvärdet är falskt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

