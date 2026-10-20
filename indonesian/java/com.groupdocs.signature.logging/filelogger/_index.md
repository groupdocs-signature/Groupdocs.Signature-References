---
title: "FileLogger"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menulis pesan log ke file."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Menulis pesan log ke file.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Buat logger ke file. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Menulis pesan kesalahan ke konsol. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Menulis pesan jejak ke konsol. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Menulis pesan peringatan ke konsol; |
Pesan log peringatan memberikan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Buat logger ke file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | java.lang.String | Nama file lengkap dengan path |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Menulis pesan kesalahan ke konsol.
Pesan log error memberikan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan kesalahan. |
|
|  | exception | java.lang.Exception | Pengecualian. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Menulis pesan jejak ke konsol.
Pesan log jejak memberikan informasi yang umumnya berguna tentang alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan jejak. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Menulis pesan peringatan ke konsol;
Pesan log peringatan memberikan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | message | java.lang.String | Pesan peringatan. |
|

