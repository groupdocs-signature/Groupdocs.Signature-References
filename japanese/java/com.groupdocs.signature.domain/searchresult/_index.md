---
title: "SearchResult"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "指定されたドキュメント内の署名検索結果です。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

指定されたドキュメント内の署名検索結果です。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 検索プロセスの実行時間をミリ秒で返します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 検索プロセスによって処理された署名の総数を返します。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | ソースドキュメントのサイズを返します。 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 宛先ドキュメントのサイズを返します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 見つかった署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 検索条件により検索プロセスで失敗した署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getSignatures()](#getSignatures--) | 検出された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | 署名の強く型付けされたリストへの変換を提供します。 |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


検索プロセスの実行時間をミリ秒で返します。


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


検索プロセスによって処理された署名の総数を返します。


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


ソースドキュメントのサイズを返します。


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


宛先ドキュメントのサイズを返します。Search メソッドの場合、常に 0 を返します。


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


見つかった署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。このリストは常に等しくなります
署名
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) プロパティ。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


検索条件により検索プロセスで失敗した署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。
現在のバージョンではサポートされていません。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


検出された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


署名の強く型付けされたリストへの変換を提供します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 指定された署名タイプのリストを返します。


T
: リスト内の署名のタイプです。

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

