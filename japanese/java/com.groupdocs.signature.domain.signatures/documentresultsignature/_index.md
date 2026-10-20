---
title: "DocumentResultSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "新規作成された署名を含むドキュメントのアーカイブ署名プロセスの結果。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

新規作成された署名を含むドキュメントのアーカイブ署名プロセスの結果。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileName()](#getFileName--) | ドキュメントファイル名 |
|
|  | [getProcessingTime()](#getProcessingTime--) | プロセスの実行時間をミリ秒で返します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理された署名の総数を返します。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | ソースドキュメントのサイズを返します。 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 宛先ドキュメントのサイズを返します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 正常に処理された署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | プロセス中に失敗した署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getErrorMessage()](#getErrorMessage--) | ドキュメントの処理中にエラーが発生した場合、このプロパティにはエラーメッセージが含まれます。 |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


ドキュメントファイル名


**Returns:**
java.lang.String
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


正常に処理された署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


プロセス中に失敗した署名の一覧 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


ドキュメントの処理中にエラーが発生した場合、このプロパティにはエラーメッセージが含まれます。


**Returns:**
java.lang.String
