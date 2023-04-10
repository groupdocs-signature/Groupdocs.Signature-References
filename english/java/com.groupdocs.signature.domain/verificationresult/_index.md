---
title: VerificationResult
second_title: GroupDocs.Signature for Java API Reference
description: Instance to keep results of verification process.
type: docs
weight: 20
url: /java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instance to keep results of verification process.
## Methods

| Method | Description |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Returns the execution time of the process in milliseconds. |
| [getTotalSignatures()](#getTotalSignatures--) | Returns the total processed signatures |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Returns source document size in bytes |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Returns the destination document size. |
| [isValid()](#isValid--) | Returns true if Verification process was successful otherwise false. |
| [setValid(boolean value)](#setValid-boolean-) | Returns true if Verification process was successful otherwise false. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returns the execution time of the process in milliseconds.

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


Returns source document size in bytes

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returns the destination document size. For verification this variable always contains zero.

**Returns:**
long
### isValid() {#isValid--}
```
public final boolean isValid()
```


Returns true if Verification process was successful otherwise false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Returns true if Verification process was successful otherwise false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

