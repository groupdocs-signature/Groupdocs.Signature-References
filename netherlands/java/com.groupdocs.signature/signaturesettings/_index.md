---
title: "SignatureSettings"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Definieert instellingen voor het aanpassen van gedrag."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Definieert instellingen voor het aanpassen van het gedrag van [Signature](../../com.groupdocs.signature/signature).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Maakt een standaard SignatureSettings‑instantie met standaardwaarden. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Maakt een standaard SignatureSettings‑instantie met de Logger‑implementatie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Haalt op of stelt de standaardcultuur in die tijdens documentverwerking wordt gebruikt. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Haalt op of stelt de standaardcultuur in die tijdens documentverwerking wordt gebruikt. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Haalt op of stelt de vlag in die verwijderde handtekeningen opneemt in het Document‑Info‑resultaat. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Haalt op of stelt de vlag in die verwijderde handtekeningen opneemt in het Document‑Info‑resultaat. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Update‑methode geen handtekeningen heeft om bij te werken. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Update‑methode geen handtekeningen heeft om bij te werken. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Haalt op of stelt de vlag in om de ingebedde standaard document‑metadata‑handtekeningen, zoals Auteur, Eigenaar, aanmaakdatum van het document, wijzigingsdatum, enz., op te nemen in de Metadata‑lijst. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Haalt op of stelt de vlag in om de ingebedde standaard document‑metadata‑handtekeningen, zoals Auteur, Eigenaar, aanmaakdatum van het document, wijzigingsdatum, enz., op te nemen in de Metadata‑lijst. |
|
|  | [getLogger()](#getLogger--) | De logger‑implementatie die wordt gebruikt voor loggen (Fouten, Waarschuwingen, Traces). |
|
|  | [getLogLevel()](#getLogLevel--) | Haalt op of stelt in welke soorten berichten naar de logger worden doorgestuurd. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Haalt op of stelt in welke soorten berichten naar de logger worden doorgestuurd. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Maakt een standaard SignatureSettings‑instantie met standaardwaarden.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Maakt een standaard SignatureSettings‑instantie met de Logger‑implementatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Haalt op of stelt de standaardcultuur in die tijdens documentverwerking wordt gebruikt. Standaardwaarde is "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Haalt op of stelt de standaardcultuur in die tijdens documentverwerking wordt gebruikt. Standaardwaarde is "en-US".


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Haalt op of stelt de vlag in die verwijderde handtekeningen opneemt in het Document‑Info‑resultaat.
Elke Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) heeft een Deleted‑vlag.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) om te detecteren of het verwijderd is.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Haalt op of stelt de vlag in die verwijderde handtekeningen opneemt in het Document‑Info‑resultaat.
Elke Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) heeft een Deleted‑vlag.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) om te detecteren of het verwijderd is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Update‑methode geen handtekeningen heeft om bij te werken.
Als deze vlag op true staat (standaard) wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en type bewerking), zelfs als Update method geen handtekeningen heeft om bij te werken.
Wanneer deze vlag op false staat, wordt het brondocument helemaal niet gewijzigd.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Update‑methode geen handtekeningen heeft om bij te werken.
Als deze vlag op true staat (standaard) wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en type bewerking), zelfs als Update method geen handtekeningen heeft om bij te werken.
Wanneer deze vlag op false staat, wordt het brondocument helemaal niet gewijzigd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen.
Als deze vlag op true staat (standaard) wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en type bewerking), zelfs als Delete method geen handtekeningen heeft om te verwijderen.
Wanneer deze vlag op false staat, wordt het brondocument helemaal niet gewijzigd.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Haalt op of stelt de vlag in om het brondocument opnieuw op te slaan wanneer de Delete‑methode geen getroffen handtekeningen heeft om te verwijderen.
Als deze vlag op true staat (standaard) wordt het document opgeslagen met het bijbehorende geschiedenisproceslogboek (datum en type bewerking), zelfs als Delete method geen handtekeningen heeft om te verwijderen.
Wanneer deze vlag op false staat, wordt het brondocument helemaal niet gewijzigd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Haalt op of stelt de vlag in om de ingebedde standaard document‑metadata‑handtekeningen, zoals Auteur, Eigenaar, aanmaakdatum van het document, wijzigingsdatum, enz., op te nemen in de Metadata‑lijst.
Als deze vlag op false staat (standaard) zal GetDocumentInfo deze metadata‑handtekeningen niet opnemen.
Wanneer deze vlag op true staat, zal de documentinformatie deze standaard metadata‑handtekeningen opnemen.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Haalt op of stelt de vlag in om de ingebedde standaard document‑metadata‑handtekeningen, zoals Auteur, Eigenaar, aanmaakdatum van het document, wijzigingsdatum, enz., op te nemen in de Metadata‑lijst.
Als deze vlag op false staat (standaard) zal GetDocumentInfo deze metadata‑handtekeningen niet opnemen.
Wanneer deze vlag op true staat, zal de documentinformatie deze standaard metadata‑handtekeningen opnemen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


De logger‑implementatie die wordt gebruikt voor loggen (Errors, Warnings, Traces). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Haalt op of stelt in welke soorten berichten naar de logger worden doorgestuurd.
De waarde is een set van [LogLevel](../../com.groupdocs.signature.logging/loglevel)‑vlaggen die gecombineerd kunnen worden, bijvoorbeeld

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
logt niets.
Standaard is
LogLevel.All
: errors, warnings en traces.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Haalt op of stelt in welke soorten berichten naar de logger worden doorgestuurd.
De waarde is een set van [LogLevel](../../com.groupdocs.signature.logging/loglevel)‑vlaggen die gecombineerd kunnen worden, bijvoorbeeld

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
logt niets.
Standaard is
LogLevel.All
: errors, warnings en traces.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

