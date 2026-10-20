---
title: "DocumentInfo"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 설명 속성을 정의합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

문서 설명 속성을 정의합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | 문서 페이지 수. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | 문서 페이지 수. |
|
|  | [getPages()](#getPages--) | 문서 페이지 설명의 컬렉션. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | 문서 페이지 설명의 컬렉션. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | 최대 페이지 높이에 대한 너비를 지정합니다. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | 최대 페이지 높이에 대한 너비를 지정합니다. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | 최대 페이지 높이를 지정합니다. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | 최대 페이지 높이를 지정합니다. |
|
|  | [getFileType()](#getFileType--) | 파일 형식 유형. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | 파일 형식 유형. |
|
|  | [getSize()](#getSize--) | 문서 크기(바이트). |
|
|  | [setSize(long value)](#setSize-long-) | 문서 크기(바이트). |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | 문서 텍스트 서명의 컬렉션. |
|
|  | [getImageSignatures()](#getImageSignatures--) | 문서 이미지 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션. |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | 문서 디지털 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션. |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | 문서 바코드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션. |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | 문서 QR 코드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션. |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | 문서 양식 필드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션. |
|
|  | [getFormFields()](#getFormFields--) | 문서에 존재하는 모든 지원되는 양식 필드의 컬렉션. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | 문서 메타데이터 서명의 컬렉션. |
|
|  | [getProcessLogs()](#getProcessLogs--) | 서명, 업데이트, 삭제와 같은 문서 히스토리 프로세스의 컬렉션. |
|
|  | [getSignatures()](#getSignatures--) | 문서 모든 유형 서명의 컬렉션 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


[DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) 클래스의 새 인스턴스를 초기화합니다.


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


문서 페이지 수.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


문서 페이지 수.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


문서 페이지 설명의 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


문서 페이지 설명의 컬렉션.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


최대 페이지 높이에 대한 너비를 지정합니다.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


최대 페이지 높이에 대한 너비를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


최대 페이지 높이를 지정합니다.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


최대 페이지 높이를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


파일 형식 유형.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


파일 형식 유형.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


문서 크기(바이트).


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


문서 크기(바이트).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


문서 텍스트 서명의 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


문서 이미지 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


문서 디지털 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


문서 바코드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


문서 QR 코드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


문서 양식 필드 서명을 [Signature](../../com.groupdocs.signature/signature) 메서드로 추가하거나 업데이트한 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


문서에 존재하는 모든 지원되는 양식 필드의 컬렉션입니다. 이 속성은 Pdf 및 Word Processing 문서 유형에만 지원됩니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


문서 메타데이터 서명의 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


서명, 업데이트, 삭제와 같은 문서 히스토리 프로세스의 컬렉션.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


문서 모든 유형 서명의 컬렉션 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
