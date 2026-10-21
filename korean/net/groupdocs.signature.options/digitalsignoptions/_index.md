---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "디지털 서명 옵션을 나타냅니다."
type: docs
weight: 1560
url: /ko/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

디지털 서명 옵션을 나타냅니다.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | 기본값으로 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | 인증서 스트림을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | 인증서 파일을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | 인증서 스트림과 이미지 스트림을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | 인증서 스트림과 이미지 파일을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | 인증서 파일과 이미지 스트림을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | 인증서 파일과 이미지 파일을 사용하여 DigitalSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | 유효 기간이 끝난 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. 기본값은 false이며, 만료된 인증서로 서명하면 [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)이 발생하고 문서는 서명되지 않습니다. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | 유효 기간이 아직 시작되지 않은 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. 기본값은 false이며, 이러한 인증서로 서명하면 [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)이 발생하고 문서는 서명되지 않습니다. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명을 삽입합니다. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 추가 서명 모양. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 테두리 설정을 지정합니다. |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | 디지털 인증서 파일 경로를 가져오거나 설정합니다. 이 속성은 CertificateStream이 지정되지 않은 경우에만 사용됩니다. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | 디지털 인증서 스트림을 가져오거나 설정합니다. 이 속성이 지정되면 항상 CertificateFilePath 대신 사용됩니다. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | 서명 연락처를 가져오거나 설정합니다. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | 사용자가 자체 디지털 서명 로직을 구현할 수 있도록 사용자 정의 해시 서명 함수를 가져오거나 설정합니다. 이를 통해 외부 인증서로 서명할 수 있으며 다양한 해시 알고리즘을 지원합니다. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Signature Options의 문서 유형을 가져오거나 설정합니다 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장 기능. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다. PDF 파일의 디지털 서명에만 독점적으로 지원됩니다. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 문서 페이지에서 서명의 높이를 측정 값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType을 참조하십시오. |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 문서 페이지에서 서명의 수평 정렬. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 서명 이미지 파일 경로를 가져오거나 설정합니다. 이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 서명 이미지 스트림을 가져오거나 설정합니다. 이 속성이 지정되면 항상 ImageFilePath 대신 사용됩니다. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 문서 페이지에서 서명의 왼쪽 X 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 ([`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수평 정렬이 지정되지 않은 경우에 작동합니다). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | 서명 위치를 가져오거나 설정합니다. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left 및 Top 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동합니다). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명을 위한 문서 페이지 번호를 가져오거나 설정합니다. 최소값 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | 디지털 인증서의 비밀번호를 가져오거나 설정합니다. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | 서명의 이유를 가져오거나 설정합니다. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 문서에 이미지를 배치할 영역의 사각형입니다. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 문서 페이지에서 서명의 회전 각도(시계 방향)입니다. |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에만 사용할 수 있습니다. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | 문서 디지털 서명의 속성을 가져오거나 설정합니다. Pdf 문서에 서명하려면 [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) 인스턴스를 사용하여 고급 속성을 설정할 수 있습니다. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형을 가져옵니다 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Width와 Height 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 문서 페이지의 스트레치 모드. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 문서 페이지에서 서명의 상단 Y 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 ([`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수직 정렬이 지정되지 않은 경우에 작동합니다). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 서명 투명도를 가져오거나 설정합니다(값은 0.0(불투명)에서 1.0(투명)까지). 기본값은 0(불투명)입니다. |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | ltv(장기 검증) 검증 플래그를 가져오거나 설정합니다. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 문서 페이지에서 서명의 수직 정렬입니다. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | 서명의 가시성을 가져오거나 설정합니다. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 문서 페이지에서 서명의 너비를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType. |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES 유형 [`XAdESType`](./xadestype). 기본값은 None (XAdES 비활성화). 현재 XAdES 서명 유형은 Spreadsheet 문서에서만 지원됩니다. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 내부 리소스를 정리합니다 |

### 비고

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### 또 보기

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
