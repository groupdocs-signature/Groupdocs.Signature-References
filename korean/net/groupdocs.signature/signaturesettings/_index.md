---
title: SignatureSettings
second_title: .NET API 참조용 GroupDocs.Signature
description: 사용자 지정을 위한 설정을 정의합니다.Signature./signature 행동.
type: docs
weight: 1890
url: /ko/net/groupdocs.signature/signaturesettings/
---
## SignatureSettings class

사용자 지정을 위한 설정을 정의합니다.[`Signature`](../signature) 행동.

```csharp
public class SignatureSettings
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SignatureSettings](signaturesettings#constructor)() | 기본값으로 기본 SignatureSettings 인스턴스를 생성합니다. |
| [SignatureSettings](signaturesettings#constructor_1)(ILogger) | 로거 구현으로 기본 SignatureSettings 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DefaultCulture](../../groupdocs.signature/signaturesettings/defaultculture) { get; set; } | 문서 처리 중에 사용할 기본 문화권을 가져오거나 설정합니다. 기본값은 "en-US"입니다. |
| [IncludeStandardMetadataSignatures](../../groupdocs.signature/signaturesettings/includestandardmetadatasignatures) { get; set; } | 메타데이터에 포함할 플래그를 가져오거나 설정합니다. 작성자, 소유자, 문서 생성 날짜, 수정 날짜 등과 같은 포함된 표준 문서 메타데이터 서명을 나열합니다. signatures. 이 플래그가 true로 설정되면 문서 정보에 이러한 표준 메타데이터 서명이 포함됩니다. |
| [Logger](../../groupdocs.signature/signaturesettings/logger) { get; } | 로깅에 사용되는 로거 구현(오류, 경고, 추적).[`ILogger`](../../groupdocs.signature.logging/ilogger) . |
| [LogLevel](../../groupdocs.signature/signaturesettings/loglevel) { get; set; } | 메시지를 제한하는 로깅 수준(모두, 추적, 경고, 오류).[`LogLevel`](./loglevel) . 기본적으로 모든 레벨 유형이 설정됩니다. |
| [SaveDocumentOnEmptyDelete](../../groupdocs.signature/signaturesettings/savedocumentonemptydelete) { get; set; } | Delete 메서드에 제거할 영향을 받는 서명이 없을 때 소스 문서를 다시 저장하도록 플래그를 가져오거나 설정합니다. 이 플래그가 true로 설정되면(기본값) 문서는 해당 기록 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다. 삭제 메서드에는 제거할 서명이 없습니다. 이 플랫이 false로 설정되면 소스 문서가 전혀 수정되지 않습니다. |
| [SaveDocumentOnEmptyUpdate](../../groupdocs.signature/signaturesettings/savedocumentonemptyupdate) { get; set; } | Update 메서드에 업데이트할 서명이 없을 때 원본 문서를 다시 저장하도록 플래그를 가져오거나 설정합니다. 이 플래그가 true로 설정되면(기본값) 문서는 업데이트하더라도 해당 기록 프로세스 로그(날짜 및 작업 유형)와 함께 저장됩니다. 메서드에 업데이트할 서명이 없습니다. 이 플랫이 false로 설정되면 소스 문서가 전혀 수정되지 않습니다. |
| [ShowDeletedSignaturesInfo](../../groupdocs.signature/signaturesettings/showdeletedsignaturesinfo) { get; set; } | 삭제된 서명을 문서 정보 결과에 포함하는 플래그를 가져오거나 설정합니다. 각 서명[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 플래그 삭제됨[`Deleted`](../../groupdocs.signature.domain/basesignature/deleted) 삭제되었는지 감지합니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature](../../groupdocs.signature)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
