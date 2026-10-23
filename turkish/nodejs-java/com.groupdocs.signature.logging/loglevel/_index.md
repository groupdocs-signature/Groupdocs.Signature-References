---
title: "LogLevel"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Mevcut Günlük Seviyesi türlerini belirtir."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

Mevcut Log Level türlerini belirtir. Bu enum, birden fazla olası değeri etkin bitler olarak ayarlamak için bayrak olarak kullanılabilir. Örnek: LogLevel.Error | LogLevel.Warning veya LogLevel.Error | LogLevel.Trace
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Günlükleme sınırlaması yok; izleme, uyarı ve hatalardan tüm bilgiler kaydedilecektir. |
| [Error](#Error) | Günlükleme sınırlaması yok; izleme, uyarı ve hatalardan tüm bilgiler kaydedilecektir. |
| [Warning](#Warning) | All seviyesiyle aynı, Trace seviyesi dahil tüm mesajlar kaydedilecektir |
| [Trace](#Trace) | Warning'dan Error seviyesine kadar mesajları içerecek günlük seviyesi |
| [All](#All) | Tüm Log seviyesi olayları (Error, Warning, Trace) günlük kaydına dahil edilecektir |
### None {#None}
```
public static final int None
```


Günlükleme sınırlaması yok; izleme, uyarı ve hatalardan tüm bilgiler kaydedilecektir.

### Error {#Error}
```
public static final int Error
```


Günlükleme sınırlaması yok; izleme, uyarı ve hatalardan tüm bilgiler kaydedilecektir.

### Warning {#Warning}
```
public static final int Warning
```


All seviyesiyle aynı, Trace seviyesi dahil tüm mesajlar kaydedilecektir

### Trace {#Trace}
```
public static final int Trace
```


Warning'dan Error seviyesine kadar mesajları içerecek günlük seviyesi

### All {#All}
```
public static final int All
```


Tüm Log seviyesi olayları (Error, Warning, Trace) günlük kaydına dahil edilecektir

