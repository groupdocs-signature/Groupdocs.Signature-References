---
title: "StampTypes"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Damga türleri konteyneri."
type: docs
weight: 16
url: /tr/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

Damga türleri konteyneri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Round](#Round) | Yuvarlak damga tipi nesnesi. |
|
|  | [Square](#Square) | Kare damga tipi nesnesi. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tüm damga tipleri. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType adıyla damga tipini döndürür. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType adıyla damga tipini döndürür. |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Yuvarlak damga tipi nesnesi.


### Square {#Square}
```
public static final StampType Square
```


Kare damga tipi nesnesi.


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Tüm damga tipleri.


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


pasringType adıyla damga tipini döndürür. Damga adı bilinmediğinde - istisna fırlatılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | parsingType | java.lang.String | Damga tipi adının kaynak dizesi. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType adıyla damga tipini döndürür. Damga adı bilinmediğinde - istisna fırlatılmaz ve yöntem null değer döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | parsingType | java.lang.String | Damga tipi adının kaynak dizesi. |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

