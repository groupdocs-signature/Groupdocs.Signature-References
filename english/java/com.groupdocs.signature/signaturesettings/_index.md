---
title: SignatureSettings
second_title: GroupDocs.Signature for Java API Reference
description: Defines settings for customizing  behavior.
type: docs
weight: 11
url: /java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

Defines settings for customizing [Signature](../../com.groupdocs.signature/signature) behavior.
## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | Creates default SignatureSettings instance with default values. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Creates default SignatureSettings instance with the Logger implementation. |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | Gets or sets default culture to be used during document processing. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | Gets or sets default culture to be used during document processing. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | Gets or sets flag that includes deleted signatures into Document Info result. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | Gets or sets flag that includes deleted signatures into Document Info result. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Gets or sets flag to resave source document when Update method has no signatures to update. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Gets or sets flag to resave source document when Update method has no signatures to update. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Gets or sets flag to resave source document when Delete method has no affected signatures to remove. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Gets or sets flag to resave source document when Delete method has no affected signatures to remove. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc. |
| [getLogger()](#getLogger--) | The logger implementation used for logging (Errors, Warnings, Traces). |
| [getLogLevel()](#getLogLevel--) | The level of the logging to limit the messages (All, Traces, Warnings, Errors). |
| [setLogLevel(int value)](#setLogLevel-int-) | The level of the logging to limit the messages (All, Traces, Warnings, Errors). |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


Creates default SignatureSettings instance with default values.

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Creates default SignatureSettings instance with the Logger implementation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


Gets or sets default culture to be used during document processing. Default value is "en-US".

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


Gets or sets default culture to be used during document processing. Default value is "en-US".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


Gets or sets flag that includes deleted signatures into Document Info result. Each Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) has Deleted flag  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) to detect if it was deleted.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


Gets or sets flag that includes deleted signatures into Document Info result. Each Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) has Deleted flag  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) to detect if it was deleted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Gets or sets flag to resave source document when Update method has no signatures to update. If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Update method has no signatures to update. When this flat is set to false source document will not be modified at all.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Gets or sets flag to resave source document when Update method has no signatures to update. If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Update method has no signatures to update. When this flat is set to false source document will not be modified at all.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Gets or sets flag to resave source document when Delete method has no affected signatures to remove. If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Delete method has no signatures to remove. When this flat is set to false source document will not be modified at all.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Gets or sets flag to resave source document when Delete method has no affected signatures to remove. If this flag is set to true (by default) document will be saving with corresponding history process log (date and operation type) even if Delete method has no signatures to remove. When this flat is set to false source document will not be modified at all.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc. If this flag is set to false (by default) the GetDocumentInfo will not include these metadata signatures. When this flag is set to true the document information will include these standard metadata signatures.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Gets or sets flag to include into the Metadata List the embedded standard document metadata signatures like Author, Owner, document creation date, modified date, etc. If this flag is set to false (by default) the GetDocumentInfo will not include these metadata signatures. When this flag is set to true the document information will include these standard metadata signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


The logger implementation used for logging (Errors, Warnings, Traces). [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


The level of the logging to limit the messages (All, Traces, Warnings, Errors).  LogLevel . BY default the All level type is set.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


The level of the logging to limit the messages (All, Traces, Warnings, Errors).  LogLevel . BY default the All level type is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

