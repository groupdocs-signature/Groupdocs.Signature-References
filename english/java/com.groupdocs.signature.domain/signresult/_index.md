---
title: SignResult
second_title: GroupDocs.Signature for Java API Reference
description: Result of signing process for document with newly created signatures.
type: docs
weight: 17
url: /java/com.groupdocs.signature.domain/signresult/
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
| [getSucceeded()](#getSucceeded--) | List of newly created signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures that were failed to create. |
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
