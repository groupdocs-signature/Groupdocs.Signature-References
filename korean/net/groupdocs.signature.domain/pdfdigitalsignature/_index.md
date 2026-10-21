---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "PDF 디지털 서명 속성을 포함합니다."
type: docs
weight: 840
url: /ko/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

PDF 디지털 서명 속성을 포함합니다.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | 인증서 없이 Pdf 디지털 서명을 초기화합니다. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | 지정된 인증서를 사용하여 Pdf 디지털 서명을 생성합니다. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | 지정된 X509 저장소를 기반으로 Pdf 디지털 서명을 초기화합니다. 지정된 저장소의 첫 번째 인증서가 사용됩니다. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | 지정된 X509 저장소와 인증서 인덱스를 기반으로 Pdf 디지털 서명을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 인증서를 가져오거나 설정합니다. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | 인증서의 사용자 지정 저장소 이름을 지정합니다. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | 인증서의 저장소 위치를 지정합니다. |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | 인증서의 저장소 이름을 지정합니다. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | 서명 목적 주석을 가져오거나 설정합니다. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | 서명자가 제공하는 정보로, 수신자가 서명자에게 연락하여 서명을 확인할 수 있도록 합니다(예: 전화번호). |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 서명 생성 날짜를 가져오거나 설정합니다. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그를 가져옵니다. 이 속성은 삭제된 서명의 목록을 유지하기 위한 문서 기록 로그 레코드에만 사용됩니다. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 서명의 높이를 지정합니다. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다. 이 속성은 Update 메서드와 함께 사용되어 요소를 서명(true) 또는 문서 요소(false)로 설정합니다. |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | 이 디지털 서명이 유효하고 문서가 변조되지 않은 경우 true를 유지합니다. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 서명의 왼쪽 위치를 지정합니다. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | 서명 시의 CPU 호스트 이름 또는 물리적 위치입니다. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 서명 수정 날짜를 가져오거나 설정합니다. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 서명이 발견된 페이지를 지정합니다. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | 서명 이유, 예를 들어 (I agreeРІР‚В¦)와 같습니다. |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | 서명 속성을 표시/숨기도록 강제합니다. ShowProperties가 true인 경우 서명 필드는 미리 정의된 외관 형식을 가지며, 디지털 서명자: {[`ContactInfo`](./contactinfo)} 날짜: {Date} 이유: {[`Reason`](./reason)} 위치: {[`Location`](./location)}이며, 기본값으로 ShowProperties는 true입니다. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Update 또는 Delete 메서드를 통해 문서에서 서명을 수정하기 위한 고유 서명 식별자입니다. 이 속성은 Sign 또는 Search 메서드가 호출된 후 자동으로 설정됩니다. 이전에 저장된 경우 서명을 조작하기 위해 수동으로 설정할 수 있습니다. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 서명의 유형을 지정합니다. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | 문서가 서명된 시간을 가져오거나 설정합니다. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | 인증서의 지문을 가져옵니다. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | Pdf 디지털 서명의 타임스탬프입니다. 기본값은 null입니다. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 서명의 상단 위치를 지정합니다. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | Pdf 디지털 서명의 유형입니다. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 서명의 너비를 지정합니다. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES 유형 [`XAdESType`](../digitalsignature/xadestype). 기본값은 None이며 (XAdES가 비활성화됨). 현재 XAdES 서명 유형은 스프레드시트 문서에서만 지원됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | Barcode 서명 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다 |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | GetHashCode 메서드를 재정의합니다 |

### 또 보기

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
