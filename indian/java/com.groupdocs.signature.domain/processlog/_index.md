---
title: "ProcessLog"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ प्रक्रिया विवरण का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

दस्तावेज़ प्रक्रिया विवरण का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getDate()](#getDate--) | प्रक्रिया की तिथि और समय प्राप्त करें। |
|
|  | [getType()](#getType--) | प्रक्रिया प्रकार प्राप्त करें। |
|
|  | [getMessage()](#getMessage--) | प्रक्रिया विवरण प्राप्त करें। |
|
|  | [getSucceeded()](#getSucceeded--) | सफलतापूर्वक प्रोसेस किए गए हस्ताक्षरों की मात्रा। |
|
|  | [getFailed()](#getFailed--) | प्रोसेसिंग के दौरान विफल हुए हस्ताक्षरों की मात्रा। |
|
|  | [getSignatures()](#getSignatures--) | सफलतापूर्वक प्रोसेस किए गए हस्ताक्षरों की सूची। |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


प्रक्रिया की तिथि और समय प्राप्त करें।


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


प्रक्रिया प्रकार प्राप्त करें।


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


प्रक्रिया विवरण प्राप्त करें।


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


सफलतापूर्वक प्रोसेस किए गए हस्ताक्षरों की मात्रा।


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


प्रोसेसिंग के दौरान विफल हुए हस्ताक्षरों की मात्रा।


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


सफलतापूर्वक प्रोसेस किए गए हस्ताक्षरों की सूची।


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
