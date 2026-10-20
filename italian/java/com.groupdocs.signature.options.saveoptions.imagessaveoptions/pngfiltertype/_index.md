---
title: "PngFilterType"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta il tipo di filtro dell'immagine PNG."
type: docs
weight: 21
url: /it/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Rappresenta il tipo di filtro dell'immagine PNG.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [None](#None) | Il filtro null, indica nessun filtraggio per le righe dei dati dell'immagine. |
|
|  | [Sub](#Sub) | Il filtro sub, indica che verrà applicato un filtraggio sottrattivo ai dati dell'immagine. |
|
|  | [Up](#Up) | Il filtro up, indica che verrà applicato un filtro di sottrazione riga per riga. |
|
|  | [Avg](#Avg) | Il filtro avg, indica che verrà applicato un filtro medio ai dati dell'immagine. |
|
|  | [Paeth](#Paeth) | Il filtro predittore di percorso. |
|
|  | [Adaptive](#Adaptive) | Il filtraggio adattivo, indica che il processo di salvataggio sceglierà il filtro più adatto |
per ogni riga di dati.
|
### None {#None}
```
public static final int None
```


Il filtro null, indica nessun filtraggio per le righe dei dati dell'immagine.


### Sub {#Sub}
```
public static final int Sub
```


Il filtro sub, indica che verrà applicato un filtraggio sottrattivo ai dati dell'immagine.


### Up {#Up}
```
public static final int Up
```


Il filtro up, indica che verrà applicato un filtro di sottrazione riga per riga.


### Avg {#Avg}
```
public static final int Avg
```


Il filtro avg, indica che verrà applicato un filtro medio ai dati dell'immagine.


### Paeth {#Paeth}
```
public static final int Paeth
```


Il filtro predittore di percorso.


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Il filtraggio adattivo, indica che il processo di salvataggio sceglierà il filtro più adatto
per ogni riga di dati. Compressione migliore, tempo di esecuzione più lento.


