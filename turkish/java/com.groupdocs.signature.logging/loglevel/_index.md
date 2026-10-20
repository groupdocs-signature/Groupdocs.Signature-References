---
title: "LogLevel"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "SignatureSettings içinde ayarlanan logger'a hangi tür mesajların iletileceğini belirtir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Hangi tür mesajların ayarlanan günlükçüye iletileceğini belirtir
SignatureSettings
.
Değerler bayraklardır ve birleştirilebilir, örneğin
LogLevel.Error \| LogLevel.Warning
.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [None](#None) | Hiçbir şey kaydedilmez. |
|
|  | [Error](#Error) | Hatalar: bir işlem başarısız oldu. |
|
|  | [Warning](#Warning) | Uyarılar: bir işlem başarılı oldu, ancak sonucu beklediğiniz gibi olmayabilir. |
|
|  | [Trace](#Trace) | İzler: bir işlemin adımları, örneğin başlangıcı ve sonu. |
|
|  | [All](#All) | Hatalar, uyarılar ve izler. |
|
### None {#None}
```
public static final int None
```


Hiçbir şey kaydedilmez.


### Error {#Error}
```
public static final int Error
```


Hatalar: bir işlem başarısız oldu.


### Warning {#Warning}
```
public static final int Warning
```


Uyarılar: bir işlem başarılı oldu, ancak sonucu beklediğiniz gibi olmayabilir.


### Trace {#Trace}
```
public static final int Trace
```


İzler: bir işlemin adımları, örneğin başlangıcı ve sonu.


### All {#All}
```
public static final int All
```


Hatalar, uyarılar ve izler. Bu varsayılan ayardır.


