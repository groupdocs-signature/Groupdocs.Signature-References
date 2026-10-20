---
title: "LoadOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Staat toe extra opties op te geven, zoals een wachtwoord bij het openen van een document om te ondertekenen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Staat toe om extra opties (zoals wachtwoord) op te geven bij het openen van een document om te ondertekenen.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een gespecificeerd bestandstype. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Haalt het wachtwoord op of stelt het in om een beschermd document te openen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Haalt het wachtwoord op of stelt het in om een beschermd document te openen. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | Haalt een vlag op of stelt deze in die aangeeft of bronnen die buiten het document zijn opgeslagen, worden overgeslagen bij het laden. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Haalt een vlag op of stelt deze in die aangeeft of bronnen die buiten het document zijn opgeslagen, worden overgeslagen bij het laden. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Haalt delen van adressen van externe bronnen op of stelt deze in die mogelijk geladen kunnen worden terwijl |
#getSkipExternalResources().getSkipExternalResources() is true.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Haalt delen van adressen van externe bronnen op of stelt deze in die mogelijk geladen kunnen worden terwijl |
#getSkipExternalResources().getSkipExternalResources() is true.
|
|  | [getPermissions()](#getPermissions--) | De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Interne setter, gebruikt door documentlaadprocessoren om permissies die uit het bestand zijn geparseerd vast te leggen. |
|
|  | [getFileType()](#getFileType--) | Haalt het bestandstype van het document op. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Stelt het bestandstype van het document in, zodat het niet wordt gedetecteerd uit de documentinhoud. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de LoadOptions-klasse met een gespecificeerd bestandstype.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | Het bestandstype van het document, zie #setFileType(FileType).setFileType(FileType). |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Haalt het wachtwoord op of stelt het in om een beschermd document te openen.
Het zal ook worden gebruikt om het ondertekende document als beschermd op te slaan.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Haalt het wachtwoord op of stelt het in om een beschermd document te openen.
Het zal ook worden gebruikt om het ondertekende document als beschermd op te slaan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Haalt een vlag op of stelt deze in die aangeeft of bronnen die buiten het document zijn opgeslagen, worden overgeslagen bij het laden.
De standaardwaarde is true.


Een document kan verwijzen naar bronnen buiten het: gekoppelde afbeeldingen en INCLUDEPICTURE-velden in tekstverwerking
documenten, gekoppelde afbeeldingen in presentaties en spreadsheets, afbeeldingen en stijlbladen waar een SVG-afbeelding naar verwijst.
Het laden van zo'n bron betekent het opvragen van het adres dat in het document staat. Op een server die verwerkt
documenten van andere personen, wat een server-side request forgery-risico is, en bij een offline installatie de
verzoek mislukt of wacht op een time-out.


Wanneer true, worden externe bronnen niet geladen, behalve die waarvan het adres een van
#getWhitelistedResources().getWhitelistedResources(). Overgeslagen bronnen worden niet weergegeven in paginavoorbeelden of in documenten opgeslagen als
afbeeldingen, en afbeelding-, barcode- en QR-code-zoekopdrachten zien ze niet. Ingesloten afbeeldingen worden niet beïnvloed, en
hyperlinks worden nooit gevolgd. De instelling geldt ook voor documenten in archieven.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Haalt een vlag op of stelt deze in die aangeeft of bronnen die buiten het document zijn opgeslagen, worden overgeslagen bij het laden.
De standaardwaarde is true. Zie #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Haalt delen van adressen van externe bronnen op of stelt deze in die mogelijk geladen kunnen worden terwijl
#getSkipExternalResources().getSkipExternalResources() is true. Een adres wordt geladen wanneer het er een bevat, ongeacht hoofdlettergebruik.
Lege waarden worden genegeerd. De standaard is een lege lijst; null instellen wist deze.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Haalt delen van adressen van externe bronnen op of stelt deze in die mogelijk geladen kunnen worden terwijl
#getSkipExternalResources().getSkipExternalResources() is true. Zie #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


De PDF-documentrechten, zoals afdrukken, wijzigen en gegevensextractie.
Alleen voor PDF-documenten. Alleen-lezen \\u2014 automatisch ingevuld tijdens het laden van het document.
De waarde is een combinatie van vlaggen uit [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Interne setter, gebruikt door documentlaadprocessoren om permissies die uit het bestand zijn geparseerd vast te leggen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Haalt het bestandstype van het document op. Wanneer het [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) is (de standaard),
wordt het bestandstype gedetecteerd op basis van de inhoud van het document.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Stelt het bestandstype van het document in, zodat het niet wordt gedetecteerd uit de documentinhoud.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

