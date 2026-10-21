---
title: "StampSignOptions"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "스탬프 서명 옵션을 나타냅니다."
type: docs
weight: 2000
url: /ko/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

스탬프 서명 옵션을 나타냅니다.

```csharp
public class StampSignOptions : ImageSignOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | StampSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | StampSignOptions 클래스의 새 인스턴스를 정렬 옵션과 함께 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명을 삽입합니다. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 추가 서명 모양. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | 스탬프 배경을 가져오거나 설정합니다. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | 서명의 배경 색상 자르기 유형을 가져오거나 설정합니다. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | 서명의 배경 이미지 자르기 유형을 가져오거나 설정합니다. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 테두리 설정을 지정합니다. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Signature Options의 문서 유형을 가져오거나 설정합니다 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장 기능. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 암호화 작업에 사용할 해시 알고리즘을 가져오거나 설정합니다. PDF 파일의 디지털 서명에만 독점적으로 지원됩니다. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 문서 페이지에서 서명의 높이를 측정 값(픽셀, 퍼센트 또는 밀리미터)으로 지정합니다. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType을 참조하십시오. |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 문서 페이지에서 서명의 수평 정렬. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 서명 이미지 파일 경로를 가져오거나 설정합니다. 이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 서명 이미지 스트림을 가져오거나 설정합니다. 이 속성이 지정되면 항상 ImageFilePath 대신 사용됩니다. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | 사각형 집합으로 렌더링된 내부 선 목록입니다. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 문서 페이지에서 서명의 왼쪽 X 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 ([`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수평 정렬이 지정되지 않은 경우에 작동합니다). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left 및 Top 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동합니다). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | 동심원으로 렌더링된 외부 선 목록입니다. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명을 위한 문서 페이지 번호를 가져오거나 설정합니다. 최소값 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 문서에 이미지를 배치할 영역의 사각형입니다. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 문서 페이지에서 서명의 회전 각도(시계 방향)입니다. |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 도형이 문서 레이아웃에 표시될 위치를 정의합니다. Word 문서에만 사용할 수 있습니다. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형을 가져옵니다 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Width와 Height 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | 스탬프 유형을 가져오거나 설정합니다. 기본값은 원형입니다. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 문서 페이지의 스트레치 모드. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 문서 페이지에서 서명의 상단 Y 위치를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 ([`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수직 정렬이 지정되지 않은 경우에 작동합니다). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 서명 투명도를 가져오거나 설정합니다(값은 0.0(불투명)에서 1.0(투명)까지). 기본값은 0(불투명)입니다. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 문서 페이지에서 서명의 수직 정렬입니다. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 문서 페이지에서 서명의 너비를 측정값(픽셀, 퍼센트 또는 밀리미터)으로 표시합니다 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z-순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 내부 리소스를 정리합니다 |

### 비고

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### 또 보기

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
