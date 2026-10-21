---
title: "FileType"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "파일 유형을 나타냅니다."
type: docs
weight: 610
url: /ko/net/groupdocs.signature.domain/filetype/
---
## FileType class

파일 유형을 나타냅니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | 파일명 접미사(마침표 "." 포함) 예: ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | 파일 유형 이름 예: "Microsoft Word Document". |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 현재 [`FileType`](../filetype)와 지정된 [`FileType`](../filetype) 객체가 동일한지 확인합니다. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 현재 [`FileType`](../filetype)가 지정된 객체와 동일한지 확인합니다. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 현재 [`FileType`](../filetype) 객체의 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | 지원되는 파일 유형을 검색합니다 |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 두 [`FileType`](../filetype) 객체가 동일한지 확인합니다. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 두 [`FileType`](../filetype) 객체가 동일하지 않은지 여부를 결정합니다. |

## Fields

| 이름 | 설명 |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png)는 무손실 압축을 사용하는 래스터 이미지 파일 형식입니다. 애니메이션을 지원하기 위해 PNG의 확장으로 개발되었으며, 저작권 제한이 없는 GIF 형식의 대안으로 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/apng)에서 확인하세요. |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | WordPerfect 문서 (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 무관하며 장치 독립 비트맵(DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/bmp)에서 확인하세요. |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr)은 CorelDRAW에서 기본적으로 생성되는 벡터 드로잉 이미지 파일로, 인코딩 및 압축된 디지털 이미지를 저장합니다. 이러한 드로잉 파일에는 텍스트, 선, 도형, 이미지, 색상 및 효과가 포함되어 이미지 내용을 벡터 형태로 표현합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/cdr)에서 확인하세요. |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm)은 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료이며 플랫폼에 독립적인 국제 표준 메타파일 형식입니다. CGM은 객체 지향 접근 방식과 다양한 기능을 제공하여 이미지 제작을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/page-description-language/cgm)에서 확인하세요. |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW 메타파일 교환 이미지 파일 (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv)은 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/csv)에서 확인하세요. |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm)은 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dcm)에서 확인하세요. |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu)은 텍스트, 도면, 이미지 및 사진이 결합된 스캔 문서와 책을 위해 설계된 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/djvu)에서 확인하세요. |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc)은 Microsoft Word 또는 기타 워드 프로세서에서 생성된 문서를 바이너리 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/doc)에서 확인하세요. |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm)은 매크로 실행 기능을 갖춘 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docm)에서 확인하세요. |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx)은 Microsoft Word 문서의 널리 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입되었으며, 이 새로운 문서 형식의 구조는 기존의 순수 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docx)에서 확인하세요. |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dot)에서 확인하세요. |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm)은 Microsoft Word 2007 이상에서 생성된 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotm)에서 확인하세요. |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotx)에서 확인하세요. |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf)은 장치에 독립적으로 그래픽 이미지를 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있어, 어떤 출력 장치에서도 파싱 후 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/emf)에서 확인하세요. |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps)는 단일 페이지의 모습을 설명하는 Encapsulated PostScript 언어 프로그램을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/page-description-language/eps)에서 확인하세요. |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif)는 고도로 압축된 이미지 유형입니다. 각 GIF 이미지는 일반적으로 픽셀당 최대 8비트, 전체 이미지에 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/gif)에서 확인하세요. |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | GZip compressed archive (.gz)는 높은 압축 비율로 파일을 압축합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/compression/gz)에서 확인하세요. |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG Image (.jpeg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/jpeg)에서 확인하세요. |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Image (.jpg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/jpeg)에서 확인하세요. |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | LZip compressed archive (.lz)는 높은 압축 비율로 파일을 압축합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/compression/lz)에서 확인하세요. |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg)는 Apache OpenOffice의 Draw 애플리케이션에서 벡터 이미지로 그림 요소를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/odg)에서 확인하세요. |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp)는 OpenOffice.org에서 OASISOpen 표준으로 사용되는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/odp)에서 확인하세요. |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods)는 사용자가 편집할 수 있는 OpenDocument Spreadsheet 문서 형식을 의미합니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/ods)에서 확인하세요. |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt)는 OpenDocument Text 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/odt)에서 확인하세요. |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp)는 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/otp)에서 확인하세요. |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet Template (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott)는 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/ott)에서 확인하세요. |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printer Command Language Document (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf)는 1990년대 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/view/pdf)에서 확인하세요. |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Personal Information Exchange (.pfx) 파일은 비밀번호로 보호된 인증서 파일로, 일반적으로 애플리케이션 코드 서명에 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/pfx)에서 확인하세요. |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png)는 무손실 압축을 사용하는 래스터 이미지 파일 형식입니다. 이 파일 형식은 Graphics Interchange Format (GIF)을 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/png)에서 확인하세요. |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint Template (.pot)는 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/pot)에서 확인하세요. |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm)는 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/potm)에서 확인하세요. |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx)는 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/potx)에서 확인하세요. |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps)는 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용해 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/pps)에서 확인하세요. |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm)는 Microsoft PowerPoint 2007 이상으로 만든 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/ppsm)에서 확인하세요. |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint 2007 이상을 사용해 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/ppsx)에서 확인하세요. |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt)는 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/ppt)에서 확인하세요. |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 지원 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/pptm)에서 확인하세요. |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx)는 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전의 바이너리 PPT 형식과 달리 PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/pptx)에서 확인하세요. |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd)는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop 고유의 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/psd)에서 확인하세요. |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf)는 애플리케이션 내에서 사용하기 위한 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/rtf)에서 확인하세요. |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | High compressed archive (.7z)는 높은 압축 비율로 파일과 폴더를 압축합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/7z)에서 확인하세요. |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg)는 이미지의 모습을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 스케일러블 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/svg)에서 확인하세요. |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Unix 기반 유틸리티인 (.tar)는 하나 이상의 파일이나 디렉터리를 보관할 수 있는 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/tar/)에서 확인하세요. |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga), 또한 TARGA로 알려진,는 Truevision Inc.에서 개발한 래스터 이미지 파일 형식입니다. 다양한 색 깊이와 선택적 RLE 압축을 지원합니다. TGA 파일은 비디오 게임, 애니메이션 파이프라인 및 그래픽 애플리케이션에서 고품질 이미지 렌더링과 선택적 알파 채널 지원을 위해 일반적으로 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tga)에서 확인하세요. |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 여러 색 공간에서 이진 레벨, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지를 나타냅니다. 여러 색 공간에서 이진 레벨, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv)은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt)은 줄 형태의 일반 텍스트를 포함하는 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf)은 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 형식은 널리 사용되는 정보 교환 애플리케이션 간 데이터 교환에 많이 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/vcf). |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp)은 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 품질을 유지하면서 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf)은 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile (WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/wmf). |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect 문서 (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls)은 Excel Binary File Format을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb)은 Excel Binary File Format을 지정하며, 이는 Excel 워크북 내용을 정의하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm)은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx)은 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt)은 Excel Template File Format을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm)은 Excel Template File Format을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip)은 무손실 데이터 압축을 지원하는 압축 파일 형식입니다. 하나 이상의 파일이나 디렉터리를 포함할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/zip/). |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 또 보기

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
