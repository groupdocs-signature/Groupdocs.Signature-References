---
title: "ProcessLog"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメント処理の詳細を表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

ドキュメント処理の詳細を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDate()](#getDate--) | プロセスの日付と時刻を取得します。 |
|
|  | [getType()](#getType--) | プロセスのタイプを取得します。 |
|
|  | [getMessage()](#getMessage--) | プロセスの説明を取得します。 |
|
|  | [getSucceeded()](#getSucceeded--) | 正常に処理された署名の数。 |
|
|  | [getFailed()](#getFailed--) | 処理中に失敗した署名の数。 |
|
|  | [getSignatures()](#getSignatures--) | 正常に処理された署名のリストです。 |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


プロセスの日付と時刻を取得します。


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


プロセスのタイプを取得します。


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


プロセスの説明を取得します。


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


正常に処理された署名の数。


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


処理中に失敗した署名の数。


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


正常に処理された署名のリストです。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
