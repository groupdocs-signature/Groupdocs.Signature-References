---
title: "SignatureSettings"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Définit les paramètres pour personnaliser le comportement."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Définit les paramètres pour personnaliser le comportement de [Signature](../../com.groupdocs.signature/signature).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | Crée une instance par défaut de SignatureSettings avec les valeurs par défaut. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Crée une instance par défaut de SignatureSettings avec l'implémentation du Logger. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | Obtient ou définit la culture par défaut à utiliser pendant le traitement du document. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Obtient ou définit la culture par défaut à utiliser pendant le traitement du document. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Obtient ou définit le drapeau qui inclut les signatures supprimées dans le résultat des informations du document. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Obtient ou définit le drapeau qui inclut les signatures supprimées dans le résultat des informations du document. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Update n'a aucune signature à mettre à jour. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Update n'a aucune signature à mettre à jour. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Delete n'a aucune signature affectée à supprimer. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Delete n'a aucune signature affectée à supprimer. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Obtient ou définit le drapeau pour inclure dans la liste des métadonnées les signatures de métadonnées de document standard intégrées comme Auteur, Propriétaire, date de création du document, date de modification, etc. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Obtient ou définit le drapeau pour inclure dans la liste des métadonnées les signatures de métadonnées de document standard intégrées comme Auteur, Propriétaire, date de création du document, date de modification, etc. |
|
|  | [getLogger()](#getLogger--) | L'implémentation du journal utilisée pour la journalisation (Errors, Warnings, Traces). |
|
|  | [getLogLevel()](#getLogLevel--) | Le niveau de journalisation pour limiter les messages (All, Traces, Warnings, Errors). |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | Le niveau de journalisation pour limiter les messages (All, Traces, Warnings, Errors). |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Crée une instance par défaut de SignatureSettings avec les valeurs par défaut.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Crée une instance par défaut de SignatureSettings avec l'implémentation du Logger.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Obtient ou définit la culture par défaut à utiliser pendant le traitement du document. La valeur par défaut est "en-US".


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Obtient ou définit la culture par défaut à utiliser pendant le traitement du document. La valeur par défaut est "en-US".


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Obtient ou définit le drapeau qui inclut les signatures supprimées dans le résultat des informations du document.
Chaque Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) possède le drapeau Deleted
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) pour détecter s'il a été supprimé.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Obtient ou définit le drapeau qui inclut les signatures supprimées dans le résultat des informations du document.
Chaque Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) possède le drapeau Deleted
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) pour détecter s'il a été supprimé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Update n'a aucune signature à mettre à jour.
Si ce drapeau est défini sur true (par défaut), le document sera enregistré avec le journal du processus d'historique correspondant (date et type d'opération) même si la méthode Update n'a aucune signature à mettre à jour.
Lorsque ce drapeau est défini sur false, le document source ne sera pas du tout modifié.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Update n'a aucune signature à mettre à jour.
Si ce drapeau est défini sur true (par défaut), le document sera enregistré avec le journal du processus d'historique correspondant (date et type d'opération) même si la méthode Update n'a aucune signature à mettre à jour.
Lorsque ce drapeau est défini sur false, le document source ne sera pas du tout modifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Delete n'a aucune signature affectée à supprimer.
Si ce drapeau est défini sur true (par défaut), le document sera enregistré avec le journal du processus d'historique correspondant (date et type d'opération) même si la méthode Delete n'a aucune signature à supprimer.
Lorsque ce drapeau est défini sur false, le document source ne sera pas du tout modifié.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Obtient ou définit le drapeau pour resauvegarder le document source lorsque la méthode Delete n'a aucune signature affectée à supprimer.
Si ce drapeau est défini sur true (par défaut), le document sera enregistré avec le journal du processus d'historique correspondant (date et type d'opération) même si la méthode Delete n'a aucune signature à supprimer.
Lorsque ce drapeau est défini sur false, le document source ne sera pas du tout modifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Obtient ou définit le drapeau pour inclure dans la liste des métadonnées les signatures de métadonnées de document standard intégrées comme Auteur, Propriétaire, date de création du document, date de modification, etc.
Si ce drapeau est défini sur false (par défaut), la méthode GetDocumentInfo n'inclura pas ces signatures de métadonnées.
Lorsque ce drapeau est défini sur true, les informations du document incluront ces signatures de métadonnées standard.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Obtient ou définit le drapeau pour inclure dans la liste des métadonnées les signatures de métadonnées de document standard intégrées comme Auteur, Propriétaire, date de création du document, date de modification, etc.
Si ce drapeau est défini sur false (par défaut), la méthode GetDocumentInfo n'inclura pas ces signatures de métadonnées.
Lorsque ce drapeau est défini sur true, les informations du document incluront ces signatures de métadonnées standard.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implémentation du journal utilisé pour la journalisation (Erreurs, Avertissements, Traces). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


Le niveau de journalisation pour limiter les messages (All, Traces, Warnings, Errors).
LogLevel
.
Par défaut, le type de niveau All est défini.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


Le niveau de journalisation pour limiter les messages (All, Traces, Warnings, Errors).
LogLevel
.
Par défaut, le type de niveau All est défini.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

