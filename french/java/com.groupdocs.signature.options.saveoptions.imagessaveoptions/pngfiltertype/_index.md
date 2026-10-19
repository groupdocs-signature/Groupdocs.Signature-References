---
title: "PngFilterType"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente le type de filtre d'image PNG."
type: docs
weight: 21
url: /fr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Représente le type de filtre d'image PNG.

## Champs

| Champ | Description |
| --- | --- |
|  | [None](#None) | Le null-filter, signifie aucune filtration des lignes de données d'image. |
|
|  | [Sub](#Sub) | Le sub filter, signifie qu'un filtrage soustractif sera appliqué aux données d'image. |
|
|  | [Up](#Up) | Le up filter, signifie qu'un filtre de soustraction ligne par ligne sera appliqué. |
|
|  | [Avg](#Avg) | Le avg filter, signifie que le filtre moyen sera appliqué aux données d'image. |
|
|  | [Paeth](#Paeth) | Le filtre path predictor. |
|
|  | [Adaptive](#Adaptive) | Le filtrage adaptatif, signifie que le processus d'enregistrement choisira le filtre le plus adapté |
pour chaque ligne de données.
|
### None {#None}
```
public static final int None
```


Le null-filter, signifie aucune filtration des lignes de données d'image.


### Sub {#Sub}
```
public static final int Sub
```


Le sub filter, signifie qu'un filtrage soustractif sera appliqué aux données d'image.


### Up {#Up}
```
public static final int Up
```


Le up filter, signifie qu'un filtre de soustraction ligne par ligne sera appliqué.


### Avg {#Avg}
```
public static final int Avg
```


Le avg filter, signifie que le filtre moyen sera appliqué aux données d'image.


### Paeth {#Paeth}
```
public static final int Paeth
```


Le filtre path predictor.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Le filtrage adaptatif, signifie que le processus d'enregistrement choisira le filtre le plus adapté
pour chaque ligne de données. Meilleure compression, temps d'exécution le plus lent.


