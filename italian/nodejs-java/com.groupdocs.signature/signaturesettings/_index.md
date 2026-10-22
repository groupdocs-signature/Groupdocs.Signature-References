---
title: "SignatureSettings"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Definisce le impostazioni per personalizzare il comportamento."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Definisce le impostazioni per personalizzare il comportamento di [Signature](../../com.groupdocs.signature/signature).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | Crea un'istanza predefinita di SignatureSettings con valori predefiniti. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Crea un'istanza predefinita di SignatureSettings con l'implementazione del Logger. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | Ottiene o imposta la cultura predefinita da utilizzare durante l'elaborazione del documento. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Ottiene o imposta la cultura predefinita da utilizzare durante l'elaborazione del documento. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Ottiene o imposta il flag che include le firme eliminate nel risultato delle Informazioni del Documento. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Ottiene o imposta il flag che include le firme eliminate nel risultato delle Informazioni del Documento. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Ottiene o imposta il flag per risalvare il documento di origine quando il metodo Update non ha firme da aggiornare. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Ottiene o imposta il flag per risalvare il documento di origine quando il metodo Update non ha firme da aggiornare. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Ottiene o imposta il flag per risalvare il documento di origine quando il metodo Delete non ha firme interessate da rimuovere. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Ottiene o imposta il flag per risalvare il documento di origine quando il metodo Delete non ha firme interessate da rimuovere. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Ottiene o imposta il flag per includere nella Lista dei Metadati le firme di metadati standard del documento incorporate, come Autore, Proprietario, data di creazione del documento, data di modifica, ecc. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Ottiene o imposta il flag per includere nella Lista dei Metadati le firme di metadati standard del documento incorporate, come Autore, Proprietario, data di creazione del documento, data di modifica, ecc. |
| [getLogger()](#getLogger--) | L'implementazione del logger utilizzata per la registrazione (Errors, Warnings, Traces). |
| [getLogLevel()](#getLogLevel--) | Il livello di registrazione per limitare i messaggi (All, Traces, Warnings, Errors). |
| [setLogLevel(int value)](#setLogLevel-int-) | Il livello di registrazione per limitare i messaggi (All, Traces, Warnings, Errors). |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Crea un'istanza predefinita di SignatureSettings con valori predefiniti.

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Crea un'istanza predefinita di SignatureSettings con l'implementazione del Logger.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Ottiene o imposta la cultura predefinita da utilizzare durante l'elaborazione del documento. Il valore predefinito è "en-US".

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Ottiene o imposta la cultura predefinita da utilizzare durante l'elaborazione del documento. Il valore predefinito è "en-US".

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Ottiene o imposta il flag che include le firme eliminate nel risultato delle informazioni sul documento. Ogni Firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) ha il flag Deleted BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) per rilevare se è stata eliminata.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Ottiene o imposta il flag che include le firme eliminate nel risultato delle informazioni sul documento. Ogni Firma [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) ha il flag Deleted BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) per rilevare se è stata eliminata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Update non ha firme da aggiornare. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Update non ha firme da aggiornare. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Update non ha firme da aggiornare. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Update non ha firme da aggiornare. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Delete non ha firme interessate da rimuovere. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Delete non ha firme da rimuovere. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Ottiene o imposta il flag per risalvare il documento sorgente quando il metodo Delete non ha firme interessate da rimuovere. Se questo flag è impostato su true (per impostazione predefinita) il documento verrà salvato con il relativo registro di processo storico (data e tipo di operazione) anche se il metodo Delete non ha firme da rimuovere. Quando questo flag è impostato su false il documento sorgente non verrà modificato affatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Ottiene o imposta il flag per includere nella Lista dei Metadati le firme di metadati standard incorporate nel documento, come Autore, Proprietario, data di creazione del documento, data di modifica, ecc. Se questo flag è impostato su false (per impostazione predefinita) il metodo GetDocumentInfo non includerà queste firme di metadati. Quando questo flag è impostato su true le informazioni del documento includeranno queste firme di metadati standard.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Ottiene o imposta il flag per includere nella Lista dei Metadati le firme di metadati standard incorporate nel documento, come Autore, Proprietario, data di creazione del documento, data di modifica, ecc. Se questo flag è impostato su false (per impostazione predefinita) il metodo GetDocumentInfo non includerà queste firme di metadati. Quando questo flag è impostato su true le informazioni del documento includeranno queste firme di metadati standard.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implementazione del logger utilizzata per la registrazione (Errori, Avvisi, Tracce). [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Il livello di logging per limitare i messaggi (All, Traces, Warnings, Errors). LogLevel. Per impostazione predefinita è impostato il livello All.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Il livello di logging per limitare i messaggi (All, Traces, Warnings, Errors). LogLevel. Per impostazione predefinita è impostato il livello All.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

