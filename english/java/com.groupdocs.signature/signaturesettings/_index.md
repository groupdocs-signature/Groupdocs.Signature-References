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
| [SignatureSettings()](#SignatureSettings--) |  |
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
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


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

