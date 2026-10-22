---
title: "SignatureSettings"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Definiert Einstellungen zur Anpassung des Verhaltens."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Definiert Einstellungen zur Anpassung des [Signature](../../com.groupdocs.signature/signature)-Verhaltens.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | Erstellt eine Standardinstanz von SignatureSettings mit Standardwerten. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Erstellt eine Standardinstanz von SignatureSettings mit der Logger-Implementierung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | Liest oder setzt die Standardsprache, die während der Dokumentenverarbeitung verwendet wird. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Liest oder setzt die Standardsprache, die während der Dokumentenverarbeitung verwendet wird. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenten-Info-Ergebnis einbezieht. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenten-Info-Ergebnis einbezieht. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Liest oder setzt das Flag, das das Quell-Dokument neu speichert, wenn die Update-Methode keine Signaturen zum Aktualisieren hat. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Liest oder setzt das Flag, das das Quell-Dokument neu speichert, wenn die Update-Methode keine Signaturen zum Aktualisieren hat. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Liest oder setzt das Flag, das das Quell-Dokument neu speichert, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Liest oder setzt das Flag, das das Quell-Dokument neu speichert, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten Standard‑Dokumentmetadaten‑Signaturen wie Autor, Eigentümer, Erstellungsdatum des Dokuments, Änderungsdatum usw. aufzunehmen. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten Standard‑Dokumentmetadaten‑Signaturen wie Autor, Eigentümer, Erstellungsdatum des Dokuments, Änderungsdatum usw. aufzunehmen. |
| [getLogger()](#getLogger--) | Die Logger-Implementierung, die für das Protokollieren (Errors, Warnings, Traces) verwendet wird. |
| [getLogLevel()](#getLogLevel--) | Das Protokollierungslevel, um die Meldungen zu begrenzen (All, Traces, Warnings, Errors). |
| [setLogLevel(int value)](#setLogLevel-int-) | Das Protokollierungslevel, um die Meldungen zu begrenzen (All, Traces, Warnings, Errors). |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Erstellt eine Standardinstanz von SignatureSettings mit Standardwerten.

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Erstellt eine Standardinstanz von SignatureSettings mit der Logger-Implementierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Liest oder setzt die Standardkultur, die während der Dokumentverarbeitung verwendet wird. Der Standardwert ist \"en-US\".

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Liest oder setzt die Standardkultur, die während der Dokumentverarbeitung verwendet wird. Der Standardwert ist \"en-US\".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenten‑Info‑Ergebnis einschließt. Jede Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) hat das Deleted‑Flag  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) um zu erkennen, ob sie gelöscht wurde.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenten‑Info‑Ergebnis einschließt. Jede Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) hat das Deleted‑Flag  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) um zu erkennen, ob sie gelöscht wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Liest oder setzt das Flag, das das Quell‑Dokument neu speichert, wenn die Update‑Methode keine Signaturen zum Aktualisieren hat. Wenn dieses Flag auf true (standardmäßig) gesetzt ist, wird das Dokument mit dem entsprechenden Verlauf‑Prozessprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Update‑Methode keine Signaturen zum Aktualisieren hat. Wenn dieses Flag auf false gesetzt ist, wird das Quell‑Dokument überhaupt nicht geändert.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Liest oder setzt das Flag, das das Quell‑Dokument neu speichert, wenn die Update‑Methode keine Signaturen zum Aktualisieren hat. Wenn dieses Flag auf true (standardmäßig) gesetzt ist, wird das Dokument mit dem entsprechenden Verlauf‑Prozessprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Update‑Methode keine Signaturen zum Aktualisieren hat. Wenn dieses Flag auf false gesetzt ist, wird das Quell‑Dokument überhaupt nicht geändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Liest oder setzt das Flag, das das Quell‑Dokument neu speichert, wenn die Delete‑Methode keine betroffenen Signaturen zum Entfernen hat. Wenn dieses Flag auf true (standardmäßig) gesetzt ist, wird das Dokument mit dem entsprechenden Verlauf‑Prozessprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Delete‑Methode keine Signaturen zum Entfernen hat. Wenn dieses Flag auf false gesetzt ist, wird das Quell‑Dokument überhaupt nicht geändert.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Liest oder setzt das Flag, das das Quell‑Dokument neu speichert, wenn die Delete‑Methode keine betroffenen Signaturen zum Entfernen hat. Wenn dieses Flag auf true (standardmäßig) gesetzt ist, wird das Dokument mit dem entsprechenden Verlauf‑Prozessprotokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Delete‑Methode keine Signaturen zum Entfernen hat. Wenn dieses Flag auf false gesetzt ist, wird das Quell‑Dokument überhaupt nicht geändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten Standard‑Dokumentmetadaten‑Signaturen wie Autor, Eigentümer, Erstellungsdatum des Dokuments, Änderungsdatum usw. aufzunehmen. Wenn dieses Flag auf false (standardmäßig) gesetzt ist, wird GetDocumentInfo diese Metadaten‑Signaturen nicht einbeziehen. Wenn dieses Flag auf true gesetzt ist, wird die Dokumentinformation diese Standard‑Metadaten‑Signaturen enthalten.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten Standard‑Dokumentmetadaten‑Signaturen wie Autor, Eigentümer, Erstellungsdatum des Dokuments, Änderungsdatum usw. aufzunehmen. Wenn dieses Flag auf false (standardmäßig) gesetzt ist, wird GetDocumentInfo diese Metadaten‑Signaturen nicht einbeziehen. Wenn dieses Flag auf true gesetzt ist, wird die Dokumentinformation diese Standard‑Metadaten‑Signaturen enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Die Logger-Implementierung, die für das Protokollieren (Errors, Warnings, Traces) verwendet wird. [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Das Protokollierungslevel, um die Meldungen zu begrenzen (All, Traces, Warnings, Errors).  LogLevel. Standardmäßig ist das All‑Level gesetzt.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Das Protokollierungslevel, um die Meldungen zu begrenzen (All, Traces, Warnings, Errors).  LogLevel. Standardmäßig ist das All‑Level gesetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

