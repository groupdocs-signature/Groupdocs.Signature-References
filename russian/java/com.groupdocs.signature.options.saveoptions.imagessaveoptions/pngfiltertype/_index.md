---
title: "PngFilterType"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Представляет тип фильтра PNG‑изображения."
type: docs
weight: 21
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Представляет тип фильтра PNG‑изображения.

## Поля

| Поле | Описание |
| --- | --- |
|  | [None](#None) | null‑фильтр означает отсутствие фильтрации строк данных изображения. |
|
|  | [Sub](#Sub) | sub‑фильтр означает применение вычитающей фильтрации к данным изображения. |
|
|  | [Up](#Up) | up‑фильтр означает применение построчного вычитающего фильтра. |
|
|  | [Avg](#Avg) | avg‑фильтр означает применение среднего фильтра к данным изображения. |
|
|  | [Paeth](#Paeth) | Фильтр предсказания пути. |
|
|  | [Adaptive](#Adaptive) | Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр |
для каждой строки данных.
|
### None {#None}
```
public static final int None
```


null‑фильтр означает отсутствие фильтрации строк данных изображения.


### Sub {#Sub}
```
public static final int Sub
```


sub‑фильтр означает применение вычитающей фильтрации к данным изображения.


### Up {#Up}
```
public static final int Up
```


up‑фильтр означает применение построчного вычитающего фильтра.


### Avg {#Avg}
```
public static final int Avg
```


avg‑фильтр означает применение среднего фильтра к данным изображения.


### Paeth {#Paeth}
```
public static final int Paeth
```


Фильтр предсказания пути.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр
для каждой строки данных. Наилучшее сжатие, самая медленная скорость выполнения.


