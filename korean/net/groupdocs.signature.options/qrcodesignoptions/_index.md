---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "QRCode 서명 옵션을 나타냅니다."
type: docs
weight: 1920
url: /ko/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

QR 코드 서명 옵션을 나타냅니다.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | QRCodeSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | QRCodeSignOptions 클래스의 새 인스턴스를 텍스트와 함께 초기화합니다. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명을 삽입합니다. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 추가 서명 모양. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 서명 배경 설정을 가져오거나 설정합니다. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 테두리 설정을 지정합니다. |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | 결과 QR코드 이미지에서 텍스트 정렬을 가져오거나 설정합니다. 기본값은 None입니다. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | QR-Code 내용으로 직렬화할 사용자 지정 객체를 가져오거나 설정합니다. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩 및 디코딩하기 위해 [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Signature Options의 문서 유형을 가져오거나 설정합니다 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | QR-Code 유형을 가져오거나 설정합니다. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장 기능. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 서명의 글꼴을 가져오거나 설정합니다. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | QR-Code 바의 전경 색상을 가져오거나 설정합니다. 이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중히 사용하십시오. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 텍스트 서명을 넣을 양식 필드 유형을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다. 기본값은 AllTextTypes입니다. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다. PDF 파일의 디지털 서명에만 독점적으로 지원됩니다. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 문서 페이지에서 서명의 높이(측정값: 픽셀, 퍼센트 또는 밀리미터, [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 속성을 참조). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 문서 페이지에서 서명의 수평 정렬. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | QR-Code 요소와 결과 이미지 경계 사이의 간격을 가져오거나 설정합니다. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 문서 페이지에서 서명의 왼쪽 X 위치를 측정값(픽셀, 퍼센트 또는 밀리미터, [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 속성 참조)으로 지정합니다. (수평 정렬이 지정되지 않은 경우에 작동합니다). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Left 및 Top 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | QR-code 로고 이미지 파일 이름을 가져오거나 설정합니다. 이 속성은 LogoStream이 지정되지 않은 경우에만 사용됩니다. 이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중히 사용하십시오. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | QR-code 로고 이미지 스트림을 가져오거나 설정합니다. 이 속성이 지정되면 항상 LogoFilePath 대신 사용됩니다. 이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중히 사용하십시오. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동합니다). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 네이티브 속성을 가져오거나 설정합니다. 설정하면 문서별 서명을 사용할 수 있습니다. 워드 프로세싱 문서에 대한 네이티브 텍스트 워터마크는 일반 워터마크와 다릅니다, 예를 들어. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명을 위한 문서 페이지 번호를 가져오거나 설정합니다. 최소값 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | 문서 페이지에 삽입된 서명의 QR-Code 이미지 콘텐츠를 가져오기 위한 플래그를 가져오거나 설정합니다. 이 플래그가 true로 설정되면 QR-Code 서명 이미지 콘텐츠는 필요한 형식인 [`ReturnContentType`](./returncontenttype)으로 원시 이미지 데이터를 유지합니다. 기본적으로 이 옵션은 비활성화되어 있습니다. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환 이미지 콘텐츠 파일 유형을 지정합니다. 기본값은 Null로 설정됩니다. 이는 QR-Code 이미지 콘텐츠를 원본 형식으로 반환한다는 의미입니다. 이 이미지 형식은 [`Format`](../../groupdocs.signature.domain/qrcodesignature/format)에서 지정됩니다. 지원되는 가능한 값은: FileType.JPEG, FileType.PNG, FileType.BMP입니다. 제공된 형식이 지원되지 않으면 .png 형식의 QR-Code 이미지 콘텐츠가 반환됩니다. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 문서 페이지에서 서명의 회전 각도(시계 방향)입니다. |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에만 사용할 수 있습니다. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 텍스트를 배치할 도형 유형을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextStamp인 경우에만 사용할 수 있습니다. 기본값은 Rectangle입니다. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 서명의 고유 ID를 가져오거나 설정합니다. 서명 검증 옵션에서 사용할 수 있습니다. 이 속성은 PDF 문서에서만 지원됩니다. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | 텍스트 서명 구현 유형을 가져오거나 설정합니다. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형을 가져옵니다 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Width와 Height 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | 문서 페이지의 스트레치 모드. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 서명의 텍스트를 가져오거나 설정합니다. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 서명 내부 텍스트의 수평 정렬입니다. 이 기능은 이미지 및 주석 서명 구현에만 지원됩니다( [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation 속성 참조). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 서명 내부 텍스트의 수직 정렬입니다. 이 기능은 이미지 서명 구현에만 지원됩니다( [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation 속성 참조). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 문서 페이지에서 서명의 상단 Y 위치를 측정값(픽셀, 퍼센트 또는 밀리미터, [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 속성 참조)으로 지정합니다. (수직 정렬이 지정되지 않은 경우에 작동합니다). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 서명 투명도를 가져오거나 설정합니다(값은 0.0(불투명)에서 1.0(투명)까지). 기본값은 0(불투명)입니다. |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | 문서 페이지에서 서명의 수직 정렬입니다. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | 문서 페이지에서 서명의 너비를 측정값(픽셀, 퍼센트 또는 밀리미터, [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 속성 참조)으로 지정합니다. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

### 비고

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### 또 보기

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
