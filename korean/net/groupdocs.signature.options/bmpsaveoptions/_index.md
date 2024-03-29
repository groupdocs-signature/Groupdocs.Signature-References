---
title: BmpSaveOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: Bmp 이미지 문서에 대한 옵션 저장.
type: docs
weight: 1290
url: /ko/net/groupdocs.signature.options/bmpsaveoptions/
---
## BmpSaveOptions class

Bmp 이미지 문서에 대한 옵션 저장.

```csharp
public sealed class BmpSaveOptions : ImageSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BmpSaveOptions](bmpsaveoptions)() | 기본값으로 BmpSaveOptions를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | 출력 파일 path 에서 확장자가 누락된 경우 자동으로 확장자를 추가하도록 플래그를 가져오거나 설정합니다. 기본값은 false입니다. |
| [BitsPerPixel](../../groupdocs.signature.options/bmpsaveoptions/bitsperpixel) { get; set; } | 픽셀당 이미지 비트를 가져오거나 설정합니다. |
| [Compression](../../groupdocs.signature.options/bmpsaveoptions/compression) { get; set; } | 압축을 가져오거나 설정합니다. 보다[`BitmapCompression`](../bitmapcompression) . |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
| [HorizontalResolution](../../groupdocs.signature.options/bmpsaveoptions/horizontalresolution) { get; set; } | 수평 해상도를 가져오거나 설정합니다. 반올림으로 인해 결과 해상도가 전달된 와 약간 다를 수 있습니다. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | 기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다. 그렇지 않으면 번호가 접미사인 새 파일이 생성됩니다. 기본적으로 이 값은 true로 설정되어 파일을 덮어씁니다. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | 암호로 보호된 서명된 문서를 저장하기 위한 암호를 가져오거나 설정합니다. 이 속성은 이미지 문서에 지원되지 않습니다. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | 서명된 문서를 보호된 문서로 저장하기 위해 LoadOptions에서 암호를 사용할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. 이 속성은 이미지 문서에 지원되지 않습니다. |
| [VerticalResolution](../../groupdocs.signature.options/bmpsaveoptions/verticalresolution) { get; set; } | 수직 해상도를 가져오거나 설정합니다. 반올림으로 인해 결과 해상도가 전달된 와 약간 다를 수 있습니다. |

### 또한보십시오

* class [ImageSaveOptions](../imagesaveoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
