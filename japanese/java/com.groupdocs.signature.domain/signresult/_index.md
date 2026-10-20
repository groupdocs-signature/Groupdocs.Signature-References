---
title: "SignResult"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "新規作成された署名を含むドキュメントの署名プロセス結果です。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

新規作成された署名を含むドキュメントの署名プロセス結果です。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | プロセスの実行時間をミリ秒で返します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理された署名の総数を返します。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | ソースドキュメントのサイズを返します。 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 宛先ドキュメントのサイズを返します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 新しく作成された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 作成に失敗した署名のリスト。 |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


プロセスの実行時間をミリ秒で返します。


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


ソースドキュメントのサイズを返します。


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


宛先ドキュメントのサイズを返します。


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


新しく作成された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


作成に失敗した署名のリスト。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
