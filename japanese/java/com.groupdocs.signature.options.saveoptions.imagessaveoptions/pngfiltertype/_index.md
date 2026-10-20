---
title: "PngFilterType"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PNG 画像のフィルタタイプを表します。"
type: docs
weight: 21
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngfiltertype/
---
**Inheritance:**
java.lang.Object
```
public final class PngFilterType
```

PNG 画像のフィルタタイプを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [None](#None) | null-filterは、画像データ行に対してフィルタリングを行わないことを意味します。 |
|
|  | [Sub](#Sub) | sub filterは、画像データに減算フィルタリングが適用されることを意味します。 |
|
|  | [Up](#Up) | up filterは、行ごとの減算フィルタが適用されることを意味します。 |
|
|  | [Avg](#Avg) | avg filterは、画像データに平均フィルタが適用されることを意味します。 |
|
|  | [Paeth](#Paeth) | path predictor filterです。 |
|
|  | [Adaptive](#Adaptive) | 適応フィルタリングは、保存プロセスが最適なフィルタを選択することを意味します |
各データ行に対して。
|
### None {#None}
```
public static final int None
```


null-filterは、画像データ行に対してフィルタリングを行わないことを意味します。


### Sub {#Sub}
```
public static final int Sub
```


sub filterは、画像データに減算フィルタリングが適用されることを意味します。


### Up {#Up}
```
public static final int Up
```


up filterは、行ごとの減算フィルタが適用されることを意味します。


### Avg {#Avg}
```
public static final int Avg
```


avg filterは、画像データに平均フィルタが適用されることを意味します。


### Paeth {#Paeth}
```
public static final int Paeth
```


path predictor filterです。


### Adaptive {#Adaptive}
```
public static final int Adaptive
```


適応フィルタリングは、保存プロセスが最適なフィルタを選択することを意味します
各データ行に対して。最高の圧縮率、最も遅い実行時間。


