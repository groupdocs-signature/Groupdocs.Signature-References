---
title: "DigitalSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "デジタル署名検索の基本オプションを表します"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

デジタル署名検索の基本オプションを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | DigitalSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getComments()](#getComments--) | 検索対象のデジタル署名のコメント。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 検索対象のデジタル署名のコメント。 |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 検索対象のデジタル署名の日付と時刻の範囲。 |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 検索対象のデジタル署名の日付と時刻の範囲。 |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | 検索対象のデジタル署名の日付と時刻の範囲。 |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 検索対象のデジタル署名の日付と時刻の範囲。 |
|
|  | [getSubjectName()](#getSubjectName--) | 空でない値が指定されている場合、検索対象の証明書の識別サブジェクト名を指定します。 |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 空でない値が指定されている場合、検索対象の証明書の識別サブジェクト名を指定します。 |
|
|  | [getIssuerName()](#getIssuerName--) | 空でない値が指定されている場合、検索対象の証明書発行者の識別名を指定します。 |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 空でない値が指定されている場合、検索対象の証明書発行者の識別名を指定します。 |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


DigitalSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### getComments() {#getComments--}
```
public final String getComments()
```


検索対象のデジタル署名のコメント。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


検索対象のデジタル署名のコメント。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


検索対象のデジタル署名の日付と時刻の範囲。null 許容の値は無視されます。


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


検索対象のデジタル署名の日付と時刻の範囲。null 許容の値は無視されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


検索対象のデジタル署名の日付と時刻の範囲。null 許容の値は無視されます。


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


検索対象のデジタル署名の日付と時刻の範囲。null 許容の値は無視されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


空でない値が指定されている場合、検索対象の証明書の識別サブジェクト名を指定します。


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


空でない値が指定されている場合、検索対象の証明書の識別サブジェクト名を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


空でない値が指定されている場合、検索対象の証明書発行者の識別名を指定します。


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


空でない値が指定されている場合、検索対象の証明書発行者の識別名を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

