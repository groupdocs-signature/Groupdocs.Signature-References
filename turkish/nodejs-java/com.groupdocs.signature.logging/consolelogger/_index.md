---
title: "ConsoleLogger"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Günlük mesajlarını dosyaya yazar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Günlük mesajlarını dosyaya yazar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) | Konsola bir logger oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Konsola bir hata mesajı yazar. |
| [trace(String message)](#trace-java.lang.String-) | Konsola bir izleme mesajı yazar. |
| [warning(String message)](#warning-java.lang.String-) | Konsola bir uyarı mesajı yazar; Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


Konsola bir logger oluştur.

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Konsola bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki geri döndürülemez olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata mesajı. |
| istisna | java.lang.Exception | İstisna. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Konsola bir izleme mesajı yazar. İzleme günlük mesajları, uygulama akışı hakkında genellikle faydalı bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İzleme mesajı. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Konsola bir uyarı mesajı yazar; Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Uyarı mesajı. |

