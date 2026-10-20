---
title: "DocumentInfo"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントの説明プロパティを定義します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

ドキュメントの説明プロパティを定義します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | ドキュメントページ数。 |
|
|  | [setPageCount(int value)](#setPageCount-int-) | ドキュメントページ数。 |
|
|  | [getPages()](#getPages--) | ドキュメントページの説明のコレクション。 |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | ドキュメントページの説明のコレクション。 |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | 最大ページ高さの幅を指定します。 |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | 最大ページ高さの幅を指定します。 |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | 最大ページ高さを指定します。 |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | 最大ページ高さを指定します。 |
|
|  | [getFileType()](#getFileType--) | ファイル形式タイプ。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | ファイル形式タイプ。 |
|
|  | [getSize()](#getSize--) | バイト単位のドキュメントサイズ。 |
|
|  | [setSize(long value)](#setSize-long-) | バイト単位のドキュメントサイズ。 |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | ドキュメントテキスト署名のコレクション。 |
|
|  | [getImageSignatures()](#getImageSignatures--) | [Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメント画像署名のコレクション。 |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | [Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントデジタル署名のコレクション。 |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | [Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントバーコード署名のコレクション。 |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | [Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントQRコード署名のコレクション。 |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | [Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントフォームフィールド署名のコレクション。 |
|
|  | [getFormFields()](#getFormFields--) | ドキュメント内のすべての既存のサポートされているフォームフィールドのコレクションです。 |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | ドキュメントメタデータ署名のコレクションです。 |
|
|  | [getProcessLogs()](#getProcessLogs--) | 署名、更新、削除などのドキュメント履歴プロセスのコレクションです。 |
|
|  | [getSignatures()](#getSignatures--) | ドキュメントのすべてのタイプの署名のコレクションです [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


[DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) クラスの新しいインスタンスを初期化します。


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


ドキュメントページ数。


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


ドキュメントページ数。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


ドキュメントページの説明のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


ドキュメントページの説明のコレクション。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


最大ページ高さの幅を指定します。


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


最大ページ高さの幅を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


最大ページ高さを指定します。


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


最大ページ高さを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


ファイル形式タイプ。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


ファイル形式タイプ。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


バイト単位のドキュメントサイズ。


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


バイト単位のドキュメントサイズ。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


ドキュメントテキスト署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


[Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメント画像署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


[Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントデジタル署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


[Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントバーコード署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


[Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントQRコード署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


[Signature](../../com.groupdocs.signature/signature) メソッドによって追加または更新されたドキュメントフォームフィールド署名のコレクション。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


ドキュメント内のすべての既存のサポートされているフォームフィールドのコレクションです。このプロパティは PDF および Word Processing ドキュメントタイプでのみサポートされます。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


ドキュメントメタデータ署名のコレクションです。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


署名、更新、削除などのドキュメント履歴プロセスのコレクションです。


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


ドキュメントのすべてのタイプの署名のコレクションです [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
