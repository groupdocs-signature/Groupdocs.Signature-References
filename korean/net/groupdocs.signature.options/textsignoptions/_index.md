---
title: TextSignOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 텍스트 서명 옵션을 나타냅니다.
type: docs
weight: 1730
url: /ko/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

텍스트 서명 옵션을 나타냅니다.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | 기본값을 사용하여 TextSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | text. 를 사용하여 TextSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명하십시오. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 시그니처 추가 등장. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 서명 배경 설정을 가져오거나 설정합니다. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 테두리 설정 지정 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 서명 옵션의 문서 유형 가져오기 또는 설정[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 서명의 글꼴을 가져오거나 설정합니다. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | 서명의 전면 색상을 가져오거나 설정합니다. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField. 에서만 사용할 수 있습니다. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 텍스트 서명을 넣을 양식 필드의 유형을 가져오거나 설정합니다. 이 속성은 SignatureImplementation = TextToFormField와 함께만 사용할 수 있습니다. 기본 값은 AllTextTypes. 입니다. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 측정값 에서 문서 페이지의 서명 높이(픽셀, 퍼센트 또는 밀리미터 참조)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 속성). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 문서 페이지의 서명 가로 정렬. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 측정값 의 문서 페이지에서 서명의 왼쪽 X 위치(픽셀, 퍼센트 또는 밀리미터는[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 속성). (수평 정렬이 지정되지 않은 경우 작동). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 공간을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 기본 특성을 가져오거나 설정합니다. 설정된 경우 문서별 서명을 사용할 수 있습니다. WordProcessing 문서의 기본 텍스트 워터마크는 예를 들어 일반과 다릅니다. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명할 문서 페이지 번호를 가져오거나 설정합니다. 최소 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
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

* GroupDocs.Signature에 의한 텍스트 전자 서명 생성의 기본 사용법: [텍스트 서명으로 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* GroupDocs.Signature를 사용한 텍스트 전자 서명 설정의 고급 사용: [텍스트 서명 및 추가 설정으로 전자 서명 문서에 대한 고급 사용](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### 또한보십시오

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
