---
title: IResult
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Common interface for signature process result.
type: docs
weight: 21
url: /nodejs-java/com.groupdocs.signature.domain/iresult/
---```
public interface IResult
```

Common interface for signature process result.
## Methods

| Method | Description |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Returns the execution time of the process in milliseconds |
| [getTotalSignatures()](#getTotalSignatures--) | Returns the total processed signatures |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Returns source document size |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Returns destination document size |
| [getSucceeded()](#getSucceeded--) | List of successfully processed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures that were not processed [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public abstract long getProcessingTime()
```


Returns the execution time of the process in milliseconds

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public abstract int getTotalSignatures()
```


Returns the total processed signatures

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public abstract long getSourceDocumentSize()
```


Returns source document size

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public abstract long getDestinDocumentSize()
```


Returns destination document size

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public abstract List<BaseSignature> getSucceeded()
```


List of successfully processed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public abstract List<BaseSignature> getFailed()
```


List of signatures that were not processed [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
