---
title: "DeleteResult"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントから署名を削除した結果です。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

ドキュメントから署名の削除結果です。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | プロセスの実行時間をミリ秒単位で返します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理された署名の総数を返します。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 元のドキュメントサイズを返します。 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 更新されたドキュメントサイズを返します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 正常に削除された署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 削除されなかった署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


プロセスの実行時間をミリ秒単位で返します。


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


処理された署名の総数を返します。


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


元のドキュメントサイズを返します。


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


更新されたドキュメントサイズを返します。


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


正常に削除された署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


削除されなかった署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
