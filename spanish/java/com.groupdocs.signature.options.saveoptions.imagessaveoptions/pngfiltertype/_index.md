---
title: "PngFilterType"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa el tipo de filtro de imagen PNG."
type: docs
weight: 21
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Representa el tipo de filtro de imagen PNG.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [None](#None) | El filtro nulo, significa sin filtrado para las filas de datos de la imagen. |
|
|  | [Sub](#Sub) | El filtro sub, significa que se aplicará filtrado sustractivo a los datos de la imagen. |
|
|  | [Up](#Up) | El filtro up, significa que se aplicará un filtro de sustracción fila por fila. |
|
|  | [Avg](#Avg) | El filtro avg, significa que se aplicará un filtro promedio a los datos de la imagen. |
|
|  | [Paeth](#Paeth) | El filtro predictor de ruta. |
|
|  | [Adaptive](#Adaptive) | Filtrado adaptativo, significa que el proceso de guardado elegirá el filtro más adecuado |
para cada fila de datos.
|
### None {#None}
```
public static final int None
```


El filtro nulo, significa sin filtrado para las filas de datos de la imagen.


### Sub {#Sub}
```
public static final int Sub
```


El filtro sub, significa que se aplicará filtrado sustractivo a los datos de la imagen.


### Up {#Up}
```
public static final int Up
```


El filtro up, significa que se aplicará un filtro de sustracción fila por fila.


### Avg {#Avg}
```
public static final int Avg
```


El filtro avg, significa que se aplicará un filtro promedio a los datos de la imagen.


### Paeth {#Paeth}
```
public static final int Paeth
```


El filtro predictor de ruta.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Filtrado adaptativo, significa que el proceso de guardado elegirá el filtro más adecuado
para cada fila de datos. Mejor compresión, tiempo de ejecución más lento.


