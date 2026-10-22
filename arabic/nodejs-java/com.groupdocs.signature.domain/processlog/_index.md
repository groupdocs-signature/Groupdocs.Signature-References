---
title: "ProcessLog"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل تفاصيل عملية المستند."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

يمثل تفاصيل عملية المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDate()](#getDate--) | احصل على تاريخ ووقت العملية. |
| [getType()](#getType--) | احصل على نوع العملية. |
| [getMessage()](#getMessage--) | احصل على وصف العملية. |
| [getSucceeded()](#getSucceeded--) | كمية التواقيع التي تم معالجتها بنجاح. |
| [getFailed()](#getFailed--) | كمية التواقيع التي فشلت أثناء المعالجة. |
| [getSignatures()](#getSignatures--) | قائمة التواقيع التي تم معالجتها بنجاح. |
### getDate() {#getDate--}
```
public final Date getDate()
```


احصل على تاريخ ووقت العملية.

**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


احصل على نوع العملية.

**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


احصل على وصف العملية.

**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


كمية التواقيع التي تم معالجتها بنجاح.

**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


كمية التواقيع التي فشلت أثناء المعالجة.

**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


قائمة التواقيع التي تم معالجتها بنجاح.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
