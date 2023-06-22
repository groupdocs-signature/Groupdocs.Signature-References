---
title: DocumentResultSignature
second_title: GroupDocs.Signature for Java API Reference
description: Result of processing archive document signing process for document with newly created signatures.
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Result of processing archive document signing process for document with newly created signatures.
## Methods

| Method | Description |
| --- | --- |
| [getFileName()](#getFileName--) | Document file name |
| [getProcessingTime()](#getProcessingTime--) | Returns the execution time of the process in milliseconds |
| [getTotalSignatures()](#getTotalSignatures--) | Returns the total processed signatures |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Returns source document size |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Returns destination document size |
| [getSucceeded()](#getSucceeded--) | List of successfully processed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of the signatures that failed during the process [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Document file name

**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returns the execution time of the process in milliseconds

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returns the total processed signatures

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returns source document size

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returns destination document size

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


List of successfully processed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


List of the signatures that failed during the process [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
