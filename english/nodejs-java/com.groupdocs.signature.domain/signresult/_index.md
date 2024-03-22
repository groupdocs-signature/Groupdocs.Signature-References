---
title: SignResult
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Result of signing process for document with newly created signatures.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Result of signing process for document with newly created signatures.
## Methods

| Method | Description |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Returns the execution time of the process in milliseconds |
| [getTotalSignatures()](#getTotalSignatures--) | Returns the total processed signatures |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Returns source document size |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Returns destination document size |
| [getSucceeded()](#getSucceeded--) | List of newly created signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures that were failed to create. |
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


List of newly created signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


List of signatures that were failed to create.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
