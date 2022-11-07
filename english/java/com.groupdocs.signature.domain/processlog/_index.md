---
title: ProcessLog
second_title: GroupDocs.Editor for Java API Reference
description: Represents document process details.
type: docs
weight: 15
url: /java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Represents document process details.
## Methods

| Method | Description |
| --- | --- |
| [getDate()](#getDate--) | Get the process date and time. |
| [getType()](#getType--) | Get the process type. |
| [getMessage()](#getMessage--) | Get the process description. |
| [getSucceeded()](#getSucceeded--) | Quantity of successfully processed signatures. |
| [getFailed()](#getFailed--) | Quantity of signatures that failed during processing. |
| [getSignatures()](#getSignatures--) | The list of successfully processed signatures. |
### getDate() {#getDate--}
```
public final Date getDate()
```


Get the process date and time.

**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Get the process type.

**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Get the process description.

**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Quantity of successfully processed signatures.

**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Quantity of signatures that failed during processing.

**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


The list of successfully processed signatures.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
