---
title: IResult
second_title: GroupDocs.Signature for Java API Reference
description: Common interface for signature process result.
type: docs
weight: 21
url: /java/com.groupdocs.signature.domain/iresult/
---```
public interface IResult
```

Common interface for signature process result.
## Methods

| Method | Description |
| --- | --- |
| [getSucceeded()](#getSucceeded--) | List of successfully processed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures that were not processed [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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
