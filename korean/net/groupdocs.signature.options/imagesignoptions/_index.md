---
title: ImageSignOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 이미지 서명 옵션을 나타냅니다.
type: docs
weight: 1420
url: /ko/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

이미지 서명 옵션을 나타냅니다.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | 기본값으로 ImageSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | 이미지 스트림을 사용하여 ImageSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | 이미지 파일을 사용하여 ImageSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | 모든 문서 페이지에 서명을 넣습니다. 이 속성은 다중 프레임 이미지 형식(Tiff)에만 사용할 수 있습니다. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 시그니처 추가 등장. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 테두리 설정 지정 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 서명 옵션의 문서 유형 가져오기 또는 설정[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 측정값 에서 문서 페이지의 서명 높이(픽셀, 퍼센트 또는 밀리미터 참조)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 문서 페이지의 서명 가로 정렬. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 서명 이미지 파일 경로를 가져오거나 설정합니다. 이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 서명 이미지 스트림을 가져오거나 설정합니다. 이 속성이 지정되면 항상 ImageFilePath 대신 사용됩니다. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 측정값 의 문서 페이지에서 서명의 왼쪽 X 위치(픽셀, 퍼센트 또는 밀리미터는[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수평 정렬이 지정되지 않은 경우 작동). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | 왼쪽 및 위쪽 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 서명과 문서 가장자리 사이의 공간을 가져오거나 설정합니다. (수평 또는 수직 정렬이 지정된 경우에만 작동). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 여백에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명할 문서 페이지 번호를 가져오거나 설정합니다. 최소 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 문서에 이미지를 넣을 영역의 사각형. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 문서 페이지의 서명 회전 각도(시계 방향). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형 가져오기[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 너비 및 높이 속성에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터). |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 문서 페이지의 스트레치 모드. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 측정값 의 문서 페이지에서 서명의 위쪽 Y 위치(픽셀, 퍼센트 또는 밀리미터는[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (수직 정렬이 지정되지 않은 경우 작동). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 서명 투명도(0.0(불투명)에서 1.0(투명) 사이의 값)를 가져오거나 설정합니다. 기본값은 0(불투명)입니다. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 문서 페이지의 서명 세로 정렬. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 측정값의 문서 페이지 서명 너비 (픽셀, 퍼센트 또는 밀리미터[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z 순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Base64의 미리 정의된 이미지를 사용하여 ImageSignOptions 클래스의 새 인스턴스를 만듭니다. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 내부 리소스 지우기 |

### 비고

**더 알아보기**

* GroupDocs.Signature에 의한 이미지 전자 서명 생성의 기본 사용법: [이미지 서명으로 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* GroupDocs.Signature를 사용한 이미지 전자 서명 설정의 고급 사용: [이미지 서명 및 추가 설정으로 전자 서명 문서에 대한 고급 사용](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### 또한보십시오

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
