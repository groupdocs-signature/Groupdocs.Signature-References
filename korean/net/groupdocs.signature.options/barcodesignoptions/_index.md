---
title: BarcodeSignOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 바코드 서명 옵션을 나타냅니다.
type: docs
weight: 1260
url: /ko/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

바코드 서명 옵션을 나타냅니다.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | 기본값을 사용하여 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | text. 를 사용하여 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | text. 를 사용하여 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명하십시오. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 시그니처 추가 등장. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 서명 배경 설정을 가져오거나 설정합니다. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 테두리 설정 지정 |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | 결과 바코드 이미지의 텍스트 정렬을 가져오거나 설정합니다. 기본값은 없음입니다. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 서명 옵션의 문서 유형 가져오기 또는 설정[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | 바코드 유형을 가져오거나 설정합니다. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 서명의 글꼴을 가져오거나 설정합니다. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | 바코드 바의 Fore 색상을 가져오거나 설정합니다. 이 속성을 사용하면 확인 문제가 발생할 수 있습니다. 조심히 사용하세요. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField. 에서만 사용할 수 있습니다. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 텍스트 서명을 넣을 양식 필드의 유형을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField와 함께만 사용할 수 있습니다. 기본 값은 AllTextTypes. 입니다. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 측정값 에서 문서 페이지의 서명 높이(픽셀, 퍼센트 또는 밀리미터 참조)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 속성). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 문서 페이지의 서명 가로 정렬. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | 바코드 요소와 결과 이미지 테두리 사이의 공간을 가져오거나 설정합니다. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 측정값 의 문서 페이지에서 서명의 왼쪽 X 위치(픽셀, 퍼센트 또는 밀리미터는[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 속성). (수평 정렬이 지정되지 않은 경우 작동). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 공간을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 기본 특성을 가져오거나 설정합니다. 설정된 경우 문서별 서명을 사용할 수 있습니다. WordProcessing 문서의 기본 텍스트 워터마크는 예를 들어 일반과 다릅니다. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명할 문서 페이지 번호를 가져오거나 설정합니다. 최소 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | 문서 페이지에 있는 서명의 바코드 이미지 콘텐츠를 가져오도록 플래그를 가져오거나 설정합니다. 이 플래그가 true로 설정되면 바코드 서명 이미지 콘텐츠는 필요한 형식으로 원시 이미지 데이터를 유지합니다.[`ReturnContentType`](./returncontenttype) . 기본적으로 이 옵션은 비활성화되어 있습니다. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다. 기본적으로 Null로 설정됩니다. 이는 Barcode 이미지 콘텐츠를 원본 형식으로 반환하는 것을 의미합니다. 이 이미지 형식은 다음에 지정됩니다.[`Format`](../../groupdocs.signature.domain/barcodesignature/format) 가능한 지원 값은 FileType.JPEG, FileType.PNG, FileType.BMP입니다. 제공된 형식이 지원되지 않으면 .png 형식의 바코드 이미지 콘텐츠가 반환됩니다. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 문서 페이지의 서명 회전 각도(시계 방향). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 텍스트를 넣을 도형의 유형을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextStamp와 함께만 사용할 수 있습니다. 기본 값은 Rectangle입니다. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 서명의 고유 ID를 가져오거나 설정합니다. 서명 확인 옵션에서 사용할 수 있습니다. 속성은 PDF 문서에만 지원됩니다. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | 텍스트 서명 구현 유형을 가져오거나 설정합니다. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형 가져오기[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | 너비 및 높이 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | 문서 페이지의 스트레치 모드. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 서명 텍스트를 가져오거나 설정합니다. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 서명 내부 텍스트의 가로 정렬. 이 기능은 이미지 및 주석 서명 구현 에만 지원됩니다(참조[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) 서명 구현 속성). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 서명 내부 텍스트의 수직 정렬. 이 기능은 이미지 서명 구현 에서만 지원됩니다(참조[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) 서명 구현 속성). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 측정값 의 문서 페이지에서 서명의 위쪽 Y 위치(픽셀, 퍼센트 또는 밀리미터는[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType 속성). (수직 정렬이 지정되지 않은 경우 작동). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 서명 투명도(0.0(불투명)에서 1.0(투명) 사이의 값)를 가져오거나 설정합니다. 기본값은 0(불투명)입니다. |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | 문서 페이지의 서명 세로 정렬. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | 측정값 의 문서 페이지 서명 너비(픽셀, 퍼센트 또는 밀리미터 참조)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 속성). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z 순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

### 비고

**더 알아보기**

* GroupDocs.Signature에 의한 바코드 전자 서명 생성의 기본 사용법: [바코드 서명으로 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* GroupDocs.Signature를 사용한 바코드 전자 서명 설정의 고급 사용: [바코드 서명 및 추가 설정으로 문서에 전자 서명하기 위한 고급 사용](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### 또한보십시오

* class [TextSignOptions](../textsignoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
