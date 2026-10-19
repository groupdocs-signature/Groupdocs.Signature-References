---
title: "SignatureSettings"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Definiert Einstellungen zur Anpassung des Verhaltens."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Definiert Einstellungen zur Anpassung des Verhaltens von [Signature](../../com.groupdocs.signature/signature).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Erstellt eine Standardinstanz von SignatureSettings mit Standardwerten. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Erstellt eine Standardinstanz von SignatureSettings mit der Logger-Implementierung. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Liest oder setzt die Standardsprache, die bei der Dokumentenverarbeitung verwendet wird. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Liest oder setzt die Standardsprache, die bei der Dokumentenverarbeitung verwendet wird. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenteninfo-Ergebnis einbezieht. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenteninfo-Ergebnis einbezieht. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Update-Methode keine Signaturen zum Aktualisieren hat. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Update-Methode keine Signaturen zum Aktualisieren hat. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten standardmäßigen Dokumenten-Metadaten-Signaturen wie Autor, Eigentümer, Erstellungsdatum, Änderungsdatum usw. aufzunehmen. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten standardmäßigen Dokumenten-Metadaten-Signaturen wie Autor, Eigentümer, Erstellungsdatum, Änderungsdatum usw. aufzunehmen. |
|
|  | [getLogger()](#getLogger--) | Die Logger-Implementierung, die für das Protokollieren (Fehler, Warnungen, Traces) verwendet wird. |
|
|  | [getLogLevel()](#getLogLevel--) | Das Protokollierungsniveau, um die Meldungen zu begrenzen (Alle, Traces, Warnungen, Fehler). |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Das Protokollierungsniveau, um die Meldungen zu begrenzen (Alle, Traces, Warnungen, Fehler). |
|
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


Liest oder setzt die Standardsprache, die bei der Dokumentenverarbeitung verwendet wird. Standardwert ist "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Liest oder setzt die Standardsprache, die bei der Dokumentenverarbeitung verwendet wird. Standardwert ist "en-US".


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenteninfo-Ergebnis einbezieht.
Jede Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) hat ein Deleted-Flag.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) zum Erkennen, ob sie gelöscht wurde.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Liest oder setzt das Flag, das gelöschte Signaturen in das Dokumenteninfo-Ergebnis einbezieht.
Jede Signatur [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) hat ein Deleted-Flag.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) zum Erkennen, ob sie gelöscht wurde.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Update-Methode keine Signaturen zum Aktualisieren hat.
Wenn dieses Flag auf true gesetzt ist (standardmäßig), wird das Dokument mit dem entsprechenden Verlauf-Protokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Update-Methode keine Signaturen zum Aktualisieren hat.
Wenn dieses Flag auf false gesetzt ist, wird das Quelldokument überhaupt nicht geändert.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Update-Methode keine Signaturen zum Aktualisieren hat.
Wenn dieses Flag auf true gesetzt ist (standardmäßig), wird das Dokument mit dem entsprechenden Verlauf-Protokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Update-Methode keine Signaturen zum Aktualisieren hat.
Wenn dieses Flag auf false gesetzt ist, wird das Quelldokument überhaupt nicht geändert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat.
Wenn dieses Flag auf true gesetzt ist (standardmäßig), wird das Dokument mit dem entsprechenden Verlauf-Protokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Delete-Methode keine Signaturen zum Entfernen hat.
Wenn dieses Flag auf false gesetzt ist, wird das Quelldokument überhaupt nicht geändert.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Liest oder setzt das Flag, um das Quelldokument erneut zu speichern, wenn die Delete-Methode keine betroffenen Signaturen zum Entfernen hat.
Wenn dieses Flag auf true gesetzt ist (standardmäßig), wird das Dokument mit dem entsprechenden Verlauf-Protokoll (Datum und Vorgangstyp) gespeichert, selbst wenn die Delete-Methode keine Signaturen zum Entfernen hat.
Wenn dieses Flag auf false gesetzt ist, wird das Quelldokument überhaupt nicht geändert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten standardmäßigen Dokumenten-Metadaten-Signaturen wie Autor, Eigentümer, Erstellungsdatum, Änderungsdatum usw. aufzunehmen.
Wenn dieses Flag auf false gesetzt ist (standardmäßig), wird GetDocumentInfo diese Metadaten-Signaturen nicht einbeziehen.
Wenn dieses Flag auf true gesetzt ist, werden die Dokumentinformationen diese standardmäßigen Metadaten-Signaturen enthalten.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Liest oder setzt das Flag, um in die Metadatenliste die eingebetteten standardmäßigen Dokumenten-Metadaten-Signaturen wie Autor, Eigentümer, Erstellungsdatum, Änderungsdatum usw. aufzunehmen.
Wenn dieses Flag auf false gesetzt ist (standardmäßig), wird GetDocumentInfo diese Metadaten-Signaturen nicht einbeziehen.
Wenn dieses Flag auf true gesetzt ist, werden die Dokumentinformationen diese standardmäßigen Metadaten-Signaturen enthalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Die Logger-Implementierung, die für das Protokollieren (Fehler, Warnungen, Traces) verwendet wird. [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Das Protokollierungsniveau, um die Meldungen zu begrenzen (Alle, Traces, Warnungen, Fehler).
LogLevel
.
Standardmäßig ist der Typ All eingestellt.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Das Protokollierungsniveau, um die Meldungen zu begrenzen (Alle, Traces, Warnungen, Fehler).
LogLevel
.
Standardmäßig ist der Typ All eingestellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

