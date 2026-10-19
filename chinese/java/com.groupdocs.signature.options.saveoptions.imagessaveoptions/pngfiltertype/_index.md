---
title: "PngFilterType"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示 PNG 图像过滤器类型。"
type: docs
weight: 21
url: /zh/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

表示 PNG 图像过滤器类型。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | null-filter 表示对图像数据行不进行过滤。 |
|
|  | [Sub](#Sub) | sub filter 表示将对图像数据应用减法过滤。 |
|
|  | [Up](#Up) | up filter 表示将应用逐行减法过滤。 |
|
|  | [Avg](#Avg) | avg filter 表示将对图像数据应用平均过滤。 |
|
|  | [Paeth](#Paeth) | path predictor filter。 |
|
|  | [Adaptive](#Adaptive) | 自适应过滤表示保存过程将选择最合适的过滤器 |
针对每一数据行。
|
### None {#None}
```
public static final int None
```


null-filter 表示对图像数据行不进行过滤。


### Sub {#Sub}
```
public static final int Sub
```


sub filter 表示将对图像数据应用减法过滤。


### Up {#Up}
```
public static final int Up
```


up filter 表示将应用逐行减法过滤。


### Avg {#Avg}
```
public static final int Avg
```


avg filter 表示将对图像数据应用平均过滤。


### Paeth {#Paeth}
```
public static final int Paeth
```


path predictor filter。


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


自适应过滤表示保存过程将选择最合适的过滤器
针对每一数据行。最佳压缩，执行时间最慢。


