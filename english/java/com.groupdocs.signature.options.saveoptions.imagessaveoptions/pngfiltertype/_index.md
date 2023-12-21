---
title: PngFilterType
second_title: GroupDocs.Signature for Java API Reference
description: Represents PNG image filter type.
type: docs
weight: 21
url: /java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

Represents PNG image filter type.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The null-filter, means no filtering for image data rows. |
| [Sub](#Sub) | The sub filter, means subtractive filtering will be applied to image data. |
| [Up](#Up) | The up filter, means row-by-row subtraction filter will be applied. |
| [Avg](#Avg) | The avg filter, means, that average filter will be applied to image data. |
| [Paeth](#Paeth) | The path predictor filter. |
| [Adaptive](#Adaptive) | Adaptive filtering, means that saving process will choose most suitable filter for each data row. |
### None {#None}
```
public static final int None
```


The null-filter, means no filtering for image data rows.

### Sub {#Sub}
```
public static final int Sub
```


The sub filter, means subtractive filtering will be applied to image data.

### Up {#Up}
```
public static final int Up
```


The up filter, means row-by-row subtraction filter will be applied.

### Avg {#Avg}
```
public static final int Avg
```


The avg filter, means, that average filter will be applied to image data.

### Paeth {#Paeth}
```
public static final int Paeth
```


The path predictor filter.

### Adaptive {#Adaptive}
```
public static final int Adaptive
```


Adaptive filtering, means that saving process will choose most suitable filter for each data row. Best compression, slowest execution time.

