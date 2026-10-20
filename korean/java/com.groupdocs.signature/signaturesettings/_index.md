---
title: "SignatureSettings"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

[Signature](../../com.groupdocs.signature/signature) 동작을 사용자 정의하기 위한 설정을 정의합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | 기본값을 사용하여 기본 SignatureSettings 인스턴스를 생성합니다. |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger 구현을 사용하여 기본 SignatureSettings 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | 문서 처리 중에 사용할 기본 문화권을 가져오거나 설정합니다. |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | 문서 처리 중에 사용할 기본 문화권을 가져오거나 설정합니다. |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | 삭제된 서명을 Document Info 결과에 포함하는 플래그를 가져오거나 설정합니다. |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | 삭제된 서명을 Document Info 결과에 포함하는 플래그를 가져오거나 설정합니다. |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다. |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다. |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Delete 메서드에 제거할 영향을 받은 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다. |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Delete 메서드에 제거할 영향을 받은 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다. |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Author, Owner, 문서 생성 날짜, 수정 날짜 등과 같은 내장 표준 문서 메타데이터 서명을 메타데이터 목록에 포함하는 플래그를 가져오거나 설정합니다. |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Author, Owner, 문서 생성 날짜, 수정 날짜 등과 같은 내장 표준 문서 메타데이터 서명을 메타데이터 목록에 포함하는 플래그를 가져오거나 설정합니다. |
|
|  | [getLogger()](#getLogger--) | 로깅에 사용되는 로거 구현 (Errors, Warnings, Traces). |
|
|  | [getLogLevel()](#getLogLevel--) | 로거에 전달되는 메시지 종류를 가져오거나 설정합니다. |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | 로거에 전달되는 메시지 종류를 가져오거나 설정합니다. |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


기본값을 사용하여 기본 SignatureSettings 인스턴스를 생성합니다.


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Logger 구현을 사용하여 기본 SignatureSettings 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


문서 처리 중에 사용할 기본 문화권을 가져오거나 설정합니다. 기본값은 "en-US"입니다.


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


문서 처리 중에 사용할 기본 문화권을 가져오거나 설정합니다. 기본값은 "en-US"입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


삭제된 서명을 Document Info 결과에 포함하는 플래그를 가져오거나 설정합니다.
각 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 에는 Deleted 플래그가 있습니다.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) 삭제 여부를 감지하기 위해.


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


삭제된 서명을 Document Info 결과에 포함하는 플래그를 가져오거나 설정합니다.
각 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) 에는 Deleted 플래그가 있습니다.
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) 삭제 여부를 감지하기 위해.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다.
이 플래그가 true(기본값)로 설정된 경우, Update 메서드에 업데이트할 서명이 없더라도 문서는 해당 이력 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다.
이 플래그가 false로 설정되면 원본 문서는 전혀 수정되지 않습니다.


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다.
이 플래그가 true(기본값)로 설정된 경우, Update 메서드에 업데이트할 서명이 없더라도 문서는 해당 이력 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다.
이 플래그가 false로 설정되면 원본 문서는 전혀 수정되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Delete 메서드에 제거할 영향을 받은 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다.
이 플래그가 true(기본값)로 설정된 경우, Delete 메서드에 제거할 서명이 없더라도 문서는 해당 이력 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다.
이 플래그가 false로 설정되면 원본 문서는 전혀 수정되지 않습니다.


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Delete 메서드에 제거할 영향을 받은 서명이 없을 때 원본 문서를 다시 저장하는 플래그를 가져오거나 설정합니다.
이 플래그가 true(기본값)로 설정된 경우, Delete 메서드에 제거할 서명이 없더라도 문서는 해당 이력 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다.
이 플래그가 false로 설정되면 원본 문서는 전혀 수정되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Author, Owner, 문서 생성 날짜, 수정 날짜 등과 같은 내장 표준 문서 메타데이터 서명을 메타데이터 목록에 포함하는 플래그를 가져오거나 설정합니다.
이 플래그가 false(기본값)로 설정된 경우, GetDocumentInfo는 이러한 메타데이터 서명을 포함하지 않습니다.
이 플래그가 true로 설정되면 문서 정보에 이러한 표준 메타데이터 서명이 포함됩니다.


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Author, Owner, 문서 생성 날짜, 수정 날짜 등과 같은 내장 표준 문서 메타데이터 서명을 메타데이터 목록에 포함하는 플래그를 가져오거나 설정합니다.
이 플래그가 false(기본값)로 설정된 경우, GetDocumentInfo는 이러한 메타데이터 서명을 포함하지 않습니다.
이 플래그가 true로 설정되면 문서 정보에 이러한 표준 메타데이터 서명이 포함됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


로깅에 사용되는 로거 구현 (Errors, Warnings, Traces). [ILogger](../../com.groupdocs.signature.logging/ilogger).


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


로거에 전달되는 메시지 종류를 가져오거나 설정합니다.
값은 결합할 수 있는 [LogLevel](../../com.groupdocs.signature.logging/loglevel) 플래그 집합이며, 예를 들어

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
아무것도 기록하지 않습니다.
기본값은
LogLevel.All
: 오류, 경고 및 추적.


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


로거에 전달되는 메시지 종류를 가져오거나 설정합니다.
값은 결합할 수 있는 [LogLevel](../../com.groupdocs.signature.logging/loglevel) 플래그 집합이며, 예를 들어

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
아무것도 기록하지 않습니다.
기본값은
LogLevel.All
: 오류, 경고 및 추적.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

