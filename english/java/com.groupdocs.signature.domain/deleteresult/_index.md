---
title: DeleteResult
second_title: GroupDocs.Signature for Java API Reference
description: Result of signatures deletion from the document.
type: docs
weight: 12
url: /java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Result of signature(s) deletion from the document.
## Methods

| Method | Description |
| --- | --- |
| [getSucceeded()](#getSucceeded--) | List of successfully deleted signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures that were not deleted [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


List of successfully deleted signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


List of signatures that were not deleted [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
