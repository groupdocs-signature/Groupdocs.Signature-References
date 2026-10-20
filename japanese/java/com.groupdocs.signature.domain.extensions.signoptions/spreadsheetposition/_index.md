---
title: "SpreadsheetPosition"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スプレッドシートドキュメントの署名位置を定義します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain.extensions.signoptions/spreadsheetposition/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class SpreadsheetPosition extends SignatureExtension
```

スプレッドシートドキュメントの署名位置を定義します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SpreadsheetPosition(int row, int column)](#SpreadsheetPosition-int-int-) | 事前定義された行と列を使用して Spreadsheer siganture 位置を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getRow()](#getRow--) | 署名の上部行番号を取得または設定します（最小値は 0 です）。 |
|
|  | [setRow(int value)](#setRow-int-) | 署名の上部行番号を取得または設定します（最小値は 0 です）。 |
|
|  | [getColumn()](#getColumn--) | 署名の左側列番号を取得または設定します（最小値は 0 です）。 |
|
|  | [setColumn(int value)](#setColumn-int-) | 署名の左側列番号を取得または設定します（最小値は 0 です）。 |
|
### SpreadsheetPosition(int row, int column) {#SpreadsheetPosition-int-int-}
```
public SpreadsheetPosition(int row, int column)
```


事前定義された行と列を使用して Spreadsheer siganture 位置を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 行 | int |  |
| 列 | int |  |

### getRow() {#getRow--}
```
public final int getRow()
```


署名の上部行番号を取得または設定します（最小値は 0 です）。


**Returns:**
int
### setRow(int value) {#setRow-int-}
```
public final void setRow(int value)
```


署名の上部行番号を取得または設定します（最小値は 0 です）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getColumn() {#getColumn--}
```
public final int getColumn()
```


署名の左側列番号を取得または設定します（最小値は 0 です）。


**Returns:**
int
### setColumn(int value) {#setColumn-int-}
```
public final void setColumn(int value)
```


署名の左側列番号を取得または設定します（最小値は 0 です）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

