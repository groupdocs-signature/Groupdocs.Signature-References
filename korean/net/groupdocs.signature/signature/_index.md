---
title: Signature
second_title: .NET API 참조용 GroupDocs.Signature
description: 문서 서명 프로세스를 제어하는 메인 클래스를 나타냅니다.
type: docs
weight: 1880
url: /ko/net/groupdocs.signature/signature/
---
## Signature class

문서 서명 프로세스를 제어하는 메인 클래스를 나타냅니다.

```csharp
public class Signature : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) stream. 에서 제공하는 문서가 포함된 클래스 |
| [Signature](signature#constructor_4)(string) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 파일 경로. 에서 제공하는 문서가 있는 클래스 인스턴스 |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 스트림 및 로드 옵션에서 제공하는 문서가 있는 클래스LoadOptions . |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature)스트림에서 제공하는 문서가 있는 클래스 인스턴스 및[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_5)(string, LoadOptions) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 파일 경로에서 제공하는 문서가 있는 클래스 인스턴스 및LoadOptions . |
| [Signature](signature#constructor_7)(string, SignatureSettings) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 파일 경로에서 제공하는 문서가 있는 클래스 인스턴스 및[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 스트림에서 제공하는 문서가 있는 클래스 인스턴스, 로드 옵션LoadOptions 및 설정[`SignatureSettings`](../signaturesettings) . |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | 의 새 인스턴스를 초기화합니다.[`Signature`](../signature) 파일 경로에서 제공하는 문서가 있는 클래스 인스턴스,LoadOptions 그리고[`SignatureSettings`](../signaturesettings) . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 전달된 서명을 삭제합니다.[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 문서에서. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 전달된 서명 목록을 삭제합니다.[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 문서에서. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | 특정 유형 목록의 서명을 삭제합니다.[`SignatureType`](../../groupdocs.signature.domain/signaturetype) 문서에서. 서명 방법으로 추가되고 서명으로 표시된 서명만[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 제거됩니다. 다음 서명 유형이 지원됩니다: 텍스트, 이미지, 디지털, 바코드, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 전달된 서명 목록을 삭제합니다.[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 문서에서. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | 특정 유형의 서명을 삭제합니다.[`SignatureType`](../../groupdocs.signature.domain/signaturetype) 문서에서. 서명 방법으로 추가되고 서명으로 표시된 서명만[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 제거됩니다. 다음 서명 유형이 지원됩니다: 텍스트, 이미지, 디지털, 바코드, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | 문서에서 특정 서명 ID로 서명을 삭제합니다. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | IDisposable 인터페이스를 구현하여 내부 리소스 정리 |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | 문서 페이지 미리보기를 생성합니다. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | 문서 페이지에 대한 정보 가져오기: 해당 크기, 최대 페이지 높이, 최대 높이가 있는 페이지 너비. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | 문서에서 서명을 검색합니다.[`SearchOptions`](../../groupdocs.signature.options/searchoptions) 목록. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | 문서에서 지정된 서명 유형을 검색합니다.[`SignatureType`](../../groupdocs.signature.domain/signaturetype) 값. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | 문서에서 서명을 검색합니다.[`SearchOptions`](../../groupdocs.signature.options/searchoptions) 옵션. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | 문서에서 서명의 정확한 유형을 검색합니다.[`SignatureType`](../../groupdocs.signature.domain/signaturetype) 값. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | 컬렉션이 포함된 서명 문서[`SignOptions`](../../groupdocs.signature.options/signoptions) 결과를 스트림에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | 다음으로 문서에 서명[`SignOptions`](../../groupdocs.signature.options/signoptions) 결과를 스트림에 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | 컬렉션이 포함된 서명 문서[`SignOptions`](../../groupdocs.signature.options/signoptions) 지정된 파일 경로에 결과를 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | 다음으로 문서에 서명[`SignOptions`](../../groupdocs.signature.options/signoptions) 지정된 파일 경로에 결과를 저장합니다. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | 컬렉션이 포함된 서명 문서[`SignOptions`](../../groupdocs.signature.options/signoptions)미리 정의된 스트림에 결과를 저장합니다.[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | 다음으로 문서에 서명[`SignOptions`](../../groupdocs.signature.options/signoptions)미리 정의된 스트림에 결과를 저장합니다.[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | 컬렉션이 포함된 서명 문서[`SignOptions`](../../groupdocs.signature.options/signoptions) 미리 정의된 지정된 파일 경로에 결과를 저장합니다.[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | 다음으로 문서에 서명[`SignOptions`](../../groupdocs.signature.options/signoptions) 미리 정의된 지정된 파일 경로에 결과를 저장합니다.[`SaveOptions`](../../groupdocs.signature.options/saveoptions) . |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | 서명을 통과한 업데이트[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 문서에서. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | 전달된 서명 업데이트[`BaseSignature`](../../groupdocs.signature.domain/basesignature) 문서에서. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | VerifyOptions 데이터 목록으로 문서 서명을 확인합니다. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 지정된 VerifyOptions 데이터로 문서 서명을 확인합니다. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 지정된 SignOptions를 기반으로 서명 미리 보기를 생성합니다.[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 서명 검색 프로세스가 완료되면 발생합니다. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 시그니처 검색 진행률이 변경된 경우 발생합니다. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 서명 검색 프로세스가 시작되면 발생합니다. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | 문서 서명 프로세스가 완료되면 발생합니다. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | 문서 서명 프로세스가 변경된 경우 발생합니다. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | 문서 서명 프로세스가 시작되면 발생합니다. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 서명 확인 프로세스가 완료되면 발생합니다. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 서명 확인 프로세스가 변경된 경우 발생합니다. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 서명 확인 프로세스가 시작되면 발생합니다. |

### 비고

**더 알아보기**

* GroupDocs.Signature 기능에 대한 추가 정보: [GroupDocs.Signature 개발자 가이드](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature](../../groupdocs.signature)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
