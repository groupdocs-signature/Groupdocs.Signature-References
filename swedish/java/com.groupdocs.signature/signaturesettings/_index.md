---
title: "SignatureSettings"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Definierar inställningar för att anpassa beteendet."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Definierar inställningar för att anpassa [Signature](../../com.groupdocs.signature/signature) beteendet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Skapar standardinstans av SignatureSettings med standardvärden. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Skapar standardinstans av SignatureSettings med Logger‑implementeringen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Hämtar eller anger standardkultur som ska användas under dokumentbehandling. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Hämtar eller anger standardkultur som ska användas under dokumentbehandling. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Hämtar eller anger flagga som inkluderar raderade signaturer i Document Info‑resultatet. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Hämtar eller anger flagga som inkluderar raderade signaturer i Document Info‑resultatet. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Hämtar eller anger flagga för att spara om källdokumentet när Update‑metoden inte har några signaturer att uppdatera. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Hämtar eller anger flagga för att spara om källdokumentet när Update‑metoden inte har några signaturer att uppdatera. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Hämtar eller anger flagga för att spara om källdokumentet när Delete‑metoden inte har några påverkade signaturer att ta bort. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Hämtar eller anger flagga för att spara om källdokumentet när Delete‑metoden inte har några påverkade signaturer att ta bort. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Hämtar eller anger flagga för att inkludera i Metadata‑listan de inbäddade standarddokumentmetadata‑signaturerna såsom Författare, Ägare, dokumentets skapandedatum, ändringsdatum osv. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Hämtar eller anger flagga för att inkludera i Metadata‑listan de inbäddade standarddokumentmetadata‑signaturerna såsom Författare, Ägare, dokumentets skapandedatum, ändringsdatum osv. |
|
|  | [getLogger()](#getLogger--) | Logger‑implementeringen som används för loggning (Fel, Varningar, Spår). |
|
|  | [getLogLevel()](#getLogLevel--) | Hämtar eller anger vilka typer av meddelanden som skickas till loggern. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Hämtar eller anger vilka typer av meddelanden som skickas till loggern. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Skapar standardinstans av SignatureSettings med standardvärden.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Skapar standardinstans av SignatureSettings med Logger‑implementeringen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Hämtar eller anger standardkultur som ska användas under dokumentbehandling. Standardvärdet är \"en-US\".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Hämtar eller anger standardkultur som ska användas under dokumentbehandling. Standardvärdet är \"en-US\".


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Hämtar eller anger flagga som inkluderar raderade signaturer i Document Info‑resultatet.
Varje Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) har Deleted-flagga
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) för att upptäcka om den har raderats.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Hämtar eller anger flagga som inkluderar raderade signaturer i Document Info‑resultatet.
Varje Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) har Deleted-flagga
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) för att upptäcka om den har raderats.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Hämtar eller anger flagga för att spara om källdokumentet när Update‑metoden inte har några signaturer att uppdatera.
Om denna flagga är satt till true (standard) kommer dokumentet att sparas med motsvarande historikprocesslogg (datum och operationstyp) även om Update-metoden inte har några signaturer att uppdatera.
När denna flagga är satt till false kommer källdokumentet inte att modifieras alls.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Hämtar eller anger flagga för att spara om källdokumentet när Update‑metoden inte har några signaturer att uppdatera.
Om denna flagga är satt till true (standard) kommer dokumentet att sparas med motsvarande historikprocesslogg (datum och operationstyp) även om Update-metoden inte har några signaturer att uppdatera.
När denna flagga är satt till false kommer källdokumentet inte att modifieras alls.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Hämtar eller anger flagga för att spara om källdokumentet när Delete‑metoden inte har några påverkade signaturer att ta bort.
Om denna flagga är satt till true (standard) kommer dokumentet att sparas med motsvarande historikprocesslogg (datum och operationstyp) även om Delete‑metoden inte har några signaturer att ta bort.
När denna flagga är satt till false kommer källdokumentet inte att modifieras alls.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Hämtar eller anger flagga för att spara om källdokumentet när Delete‑metoden inte har några påverkade signaturer att ta bort.
Om denna flagga är satt till true (standard) kommer dokumentet att sparas med motsvarande historikprocesslogg (datum och operationstyp) även om Delete‑metoden inte har några signaturer att ta bort.
När denna flagga är satt till false kommer källdokumentet inte att modifieras alls.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Hämtar eller anger flagga för att inkludera i Metadata‑listan de inbäddade standarddokumentmetadata‑signaturerna såsom Författare, Ägare, dokumentets skapandedatum, ändringsdatum osv.
Om denna flagga är satt till false (standard) kommer GetDocumentInfo inte att inkludera dessa metadata‑signaturer.
När denna flagga är satt till true kommer dokumentinformationen att inkludera dessa standard‑metadata‑signaturer.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Hämtar eller anger flagga för att inkludera i Metadata‑listan de inbäddade standarddokumentmetadata‑signaturerna såsom Författare, Ägare, dokumentets skapandedatum, ändringsdatum osv.
Om denna flagga är satt till false (standard) kommer GetDocumentInfo inte att inkludera dessa metadata‑signaturer.
När denna flagga är satt till true kommer dokumentinformationen att inkludera dessa standard‑metadata‑signaturer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Logger-implementationen som används för loggning (Errors, Warnings, Traces). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Hämtar eller anger vilka typer av meddelanden som skickas till loggern.
Värdet är en uppsättning av [LogLevel](../../com.groupdocs.signature.logging/loglevel)-flaggor som kan kombineras, till exempel

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
loggar ingenting.
Standardvärdet är
LogLevel.All
: errors, warnings och traces.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Hämtar eller anger vilka typer av meddelanden som skickas till loggern.
Värdet är en uppsättning av [LogLevel](../../com.groupdocs.signature.logging/loglevel)-flaggor som kan kombineras, till exempel

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
loggar ingenting.
Standardvärdet är
LogLevel.All
: errors, warnings och traces.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

