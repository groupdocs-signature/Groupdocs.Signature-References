---
title: "PngFilterType"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili tipe filter gambar PNG."
type: docs
weight: 21
url: /id/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Mewakili tipe filter gambar PNG.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [None](#None) | Filter null, berarti tidak ada penyaringan untuk baris data gambar. |
|
|  | [Sub](#Sub) | Filter sub, berarti penyaringan subtraktif akan diterapkan pada data gambar. |
|
|  | [Up](#Up) | Filter up, berarti penyaringan pengurangan baris demi baris akan diterapkan. |
|
|  | [Avg](#Avg) | Filter avg, berarti bahwa filter rata-rata akan diterapkan pada data gambar. |
|
|  | [Paeth](#Paeth) | Filter prediktor jalur. |
|
|  | [Adaptive](#Adaptive) | Penyaringan adaptif, berarti proses penyimpanan akan memilih filter yang paling cocok |
untuk setiap baris data.
|
### None {#None}
```
public static final int None
```


Filter null, berarti tidak ada penyaringan untuk baris data gambar.


### Sub {#Sub}
```
public static final int Sub
```


Filter sub, berarti penyaringan subtraktif akan diterapkan pada data gambar.


### Up {#Up}
```
public static final int Up
```


Filter up, berarti penyaringan pengurangan baris demi baris akan diterapkan.


### Avg {#Avg}
```
public static final int Avg
```


Filter avg, berarti bahwa filter rata-rata akan diterapkan pada data gambar.


### Paeth {#Paeth}
```
public static final int Paeth
```


Filter prediktor jalur.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Penyaringan adaptif, berarti proses penyimpanan akan memilih filter yang paling cocok
untuk setiap baris data. Kompresi terbaik, waktu eksekusi paling lambat.


