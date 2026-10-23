---
title: "StampTypes"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Damga türleri konteyneri."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.signature.domain.stamps/stamptypes/
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
| [Round](#Round) | Yuvarlak damga türü nesnesi. |
| [Square](#Square) | Kare damga türü nesnesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Tüm damga türleri. |
| [parse(String parsingType)](#parse-java.lang.String-) | pasringType adıyla damga türünü döndürür. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType adıyla damga türünü döndürür. |
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


Yuvarlak damga türü nesnesi.

### Square {#Square}
```
public static final StampType Square
```


Kare damga türü nesnesi.

### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


Tüm damga türleri.

**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


pasringType adıyla damga türünü döndürür. Damganın adı bilinmediğinde - istisna fırlatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Damga türü adının kaynak dizesi. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType adıyla damga türünü döndürür. Damganın adı bilinmediğinde - istisna fırlatılmaz ve yöntem null değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Damga türü adının kaynak dizesi. |

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.
