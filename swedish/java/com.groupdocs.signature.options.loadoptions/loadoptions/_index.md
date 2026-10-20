---
title: "LoadOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Tillåter att ange ytterligare alternativ såsom lösenord när ett dokument öppnas för signering."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Tillåter att ange ytterligare alternativ (t.ex. lösenord) när ett dokument öppnas för signering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initierar en ny instans av LoadOptions-klassen. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Initierar en ny instans av LoadOptions-klassen med en specificerad filtyp. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Hämtar eller anger lösenord för att öppna ett skyddat dokument. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger lösenord för att öppna ett skyddat dokument. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | Hämtar eller anger en flagga som anger om resurser lagrade utanför dokumentet ska hoppas över när det laddas. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Hämtar eller anger en flagga som anger om resurser lagrade utanför dokumentet ska hoppas över när det laddas. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Hämtar eller anger delar av adresser till externa resurser som kan laddas medan |
#getSkipExternalResources().getSkipExternalResources() is true.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Hämtar eller anger delar av adresser till externa resurser som kan laddas medan |
#getSkipExternalResources().getSkipExternalResources() is true.
|
|  | [getPermissions()](#getPermissions--) | PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Intern setter, används av dokumentladdningsprocessorer för att registrera behörigheter som lästs från filen. |
|
|  | [getFileType()](#getFileType--) | Hämtar filtypen för dokumentet. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Anger filtypen för dokumentet, så den inte upptäcks från dokumentets innehåll. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initierar en ny instans av LoadOptions-klassen.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Initierar en ny instans av LoadOptions-klassen med en specificerad filtyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | Filtypen för dokumentet, se #setFileType(FileType).setFileType(FileType). |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar eller anger lösenord för att öppna ett skyddat dokument.
Den kommer också att användas för att spara signerat dokument som skyddat.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Hämtar eller anger lösenord för att öppna ett skyddat dokument.
Den kommer också att användas för att spara signerat dokument som skyddat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Hämtar eller anger en flagga som anger om resurser lagrade utanför dokumentet ska hoppas över när det laddas.
Standardvärdet är true.


Ett dokument kan referera till resurser utanför det: länkade bilder och INCLUDEPICTURE-fält i ordbehandling
dokument, länkade bilder i presentationer och kalkylblad, bilder och stilmallar som en SVG-bild refererar till.
Att ladda en sådan resurs innebär att begära adressen som är skriven i dokumentet. På en server som bearbetar
dokument från andra personer, vilket är en server‑sidig begäran‑förfalskningsrisk, och på en offline‑installation
misslyckas begäran eller väntar på en tidsgräns.


När true laddas inte externa resurser, förutom de vars adress innehåller en av
#getWhitelistedResources().getWhitelistedResources(). Överhoppade resurser ritas inte i sidförhandsgranskningar eller i dokument som sparas som
bilder, och bild‑, streckkod‑ och QR‑kod‑sökning ser dem inte. Inbäddade bilder påverkas inte, och
hyperlänkar följs aldrig. Inställningen gäller också för dokument i arkiv.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Hämtar eller anger en flagga som anger om resurser lagrade utanför dokumentet ska hoppas över när det laddas.
Standardvärdet är true. Se #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Hämtar eller anger delar av adresser till externa resurser som kan laddas medan
#getSkipExternalResources().getSkipExternalResources() är true. En adress laddas när den innehåller en av dem, utan att ta hänsyn till versaler.
Tomma värden ignoreras. Standard är en tom lista; att sätta null rensar den.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Hämtar eller anger delar av adresser till externa resurser som kan laddas medan
#getSkipExternalResources().getSkipExternalResources() är true. Se #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion.
Endast för PDF-dokument. Skrivskyddad \\u2014 fylls i automatiskt vid inläsning av dokumentet.
Värdet är en flaggkombination från [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Intern setter, används av dokumentladdningsprocessorer för att registrera behörigheter som lästs från filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Hämtar filtypen för dokumentet. När den är [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (standard),
detekteras filtypen från dokumentets innehåll.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Anger filtypen för dokumentet, så den inte upptäcks från dokumentets innehåll.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

