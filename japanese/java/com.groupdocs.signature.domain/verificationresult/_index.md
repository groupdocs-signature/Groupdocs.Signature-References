---
title: "VerificationResult"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "検証プロセスの結果を保持するインスタンスです。"
type: docs
weight: 20
url: /ja/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

検証プロセスの結果を保持するインスタンスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | プロセスの実行時間をミリ秒単位で返します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理された署名の総数を返します。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | ソースドキュメントのサイズをバイト単位で返します |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 宛先ドキュメントのサイズを返します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 正常に検証された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 検証プロセスに失敗した署名のリスト。 |
|
|  | [isValid()](#isValid--) | 検証プロセスが成功した場合は true を、そうでない場合は false を返します。 |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 検証プロセスが成功した場合は true を、そうでない場合は false を返します。 |
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


ソースドキュメントのサイズをバイト単位で返します


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


宛先ドキュメントのサイズを返します。検証の場合、この変数は常に 0 が含まれます。


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


正常に検証された署名のリスト [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。
現在、このプロパティはサポートされていません。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


検証プロセスに失敗した署名のリスト。
現在、このプロパティはサポートされていません。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


検証プロセスが成功した場合は true を、そうでない場合は false を返します。


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


検証プロセスが成功した場合は true を、そうでない場合は false を返します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

