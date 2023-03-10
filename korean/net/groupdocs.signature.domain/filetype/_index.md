---
title: FileType
second_title: .NET API 참조용 GroupDocs.Signature
description: 파일 형식을 나타냅니다.
type: docs
weight: 450
url: /ko/net/groupdocs.signature.domain/filetype/
---
## FileType class

파일 형식을 나타냅니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | 파일 유형 이름 예: "Microsoft Word 문서". |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 현재 여부를 결정합니다.[`FileType`](../filetype)지정된 것과 동일합니다[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 개체와 동일합니다. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 현재 해시 코드를 반환합니다.[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 현재 개체를 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | 지원되는 파일 유형 검색 |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 여부를 결정합니다.[`FileType`](../filetype) 객체는 동일합니다. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 여부를 결정합니다.[`FileType`](../filetype) 개체가 동일하지 않습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | 비트맵 이미지 파일(.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 독립적이며 DIB(장치 독립적 비트맵) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing(.cdr)은 디지털 이미지를 인코딩하고 압축하기 위해 CorelDRAW로 기본적으로 생성되는 벡터 드로잉 이미지 파일입니다. 이러한 도면 파일에는 이미지 내용의 벡터 표현을 위한 텍스트, 선, 모양, 이미지, 색상 및 효과가 포함되어 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | 컴퓨터 그래픽 메타파일(.cgm)은 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료 플랫폼 독립적 국제 표준 메타파일 형식입니다. CGM은 이미지 생성을 위해 객체 지향 접근 방식과 많은 기능 제공을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW 메타파일 교환 이미지 파일(.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | 쉼표로 구분된 값 파일(.csv)은 쉼표로 구분된 값이 있는 데이터 레코드가 포함된 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM 이미지(.dcm)는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu 이미지(.djvu)는 특히 텍스트, 그림, 이미지 및 사진의 조합을 포함하는 스캔 문서 및 책을 위한 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word 문서(.doc)는 Microsoft Word 또는 기타 워드 프로세싱 문서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML 매크로 사용 문서(.docm)는 매크로를 실행할 수 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML 문서(.docx)는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년부터 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word 문서 템플릿(.dot)은 추가 DOC 또는 DOCX 파일 생성을 위한 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML 매크로 사용 문서 템플릿(.dotm)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML 문서 템플릿(.dotx)은 추가 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | 향상된 Windows 메타파일(.emf)은 그래픽 이미지를 장치 독립적으로 나타냅니다. EMF의 메타 파일은 모든 출력 장치에서 구문 분석한 후 저장된 이미지를 렌더링할 수 있는 시간순의 가변 길이 레코드로 구성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | 캡슐화된 포스트스크립트 파일(.eps)은 단일 페이지의 모양을 설명하는 캡슐화된 포스트스크립트 언어 프로그램을 설명합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File(.gif)은 고도로 압축된 이미지 유형입니다. 각 이미지 GIF는 일반적으로 픽셀당 최대 8비트를 허용하고 이미지 전체에 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG 이미지(.jpeg)는 손실 압축 방식을 사용하여 저장되는 일종의 이미지 형식입니다. 압축 결과 출력 이미지는 저장소 크기와 이미지 품질 간의 절충안입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG 이미지(.jpg)는 손실 압축 방식을 사용하여 저장되는 일종의 이미지 형식입니다. 압축 결과 출력 이미지는 저장소 크기와 이미지 품질 간의 절충안입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument 그래픽 파일(.odg)은 Apache OpenOffice의 Draw 응용 프로그램에서 드로잉 요소를 벡터 이미지로 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument 프레젠테이션(.odp)은 OASISOpen 표준에서 OpenOffice.org에서 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument 스프레드시트(.ods)는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument 텍스트 문서(.odt)는 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument 프레젠테이션 템플릿(.otp)은 OASIS OpenDocument 표준 형식의 응용 프로그램에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument 스프레드시트 템플릿(.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument 문서 템플릿(.ott)은 OASIS의 OpenDocument 표준 형식을 준수하는 응용 프로그램에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | 프린터 명령 언어 문서(.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File(.pdf)은 Adobe에서 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | 확장 가능한 벡터 그래픽 파일(.svg)은 이미지 모양을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 스칼라 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic(.png)은 무손실 압축을 사용하는 래스터 이미지 파일 형식의 한 유형입니다. 이 파일 형식은 GIF(Graphics Interchange Format)를 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint 템플릿(.pot)은 PowerPoint 97-2003 버전에서 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML 매크로 사용 프레젠테이션 템플릿(.potm)은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 생성하는 데 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML 프레젠테이션 템플릿(.potx)은 Microsoft PowerPoint 2007 이상에서 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint 슬라이드 쇼(.pps)는 슬라이드 쇼 목적으로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML 매크로 사용 슬라이드(.ppsm)는 Microsoft PowerPoint 2007 이상에서 만든 매크로 사용 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML 슬라이드 쇼(.ppsx) 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint 프레젠테이션(.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML 매크로 사용 프레젠테이션은 Microsoft PowerPoint 2007 이상 버전에서 만든 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML 프레젠테이션(.pptx)은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 프레젠테이션 파일 형식 PPT의 이전 버전인 바이너리와 달리 PPTX 형식은 Microsoft PowerPoint 개방형 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | 포스트스크립트 파일(.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop 문서(.psd)는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 기본 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | 리치 텍스트 형식 파일(.rtf)은 응용 프로그램 내에서 사용하기 위해 형식이 지정된 텍스트 및 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | 확장 가능한 벡터 그래픽 파일(.svg)은 이미지 모양을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 스칼라 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | 태그가 지정된 이미지 파일(.tif)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색 공간에서 이중 수준, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format(.tiff)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색 공간에서 이중 수준, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | 탭으로 구분된 값 파일(.tsv)은 일반 텍스트 형식의 탭으로 구분된 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | 일반 텍스트 파일(.txt)은 일반 텍스트를 줄 형태로 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard 파일(.vcf)은 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 형식은 널리 사용되는 정보 교환 응용 프로그램 간의 데이터 교환에 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP 이미지(.webp)는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 크기를 상당히 줄이면서 동일한 이미지 품질을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows 메타파일(.wmf)은 벡터 및 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows 메타파일(WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect 문서(.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel 스프레드시트(.xls)는 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램으로 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel 이진 스프레드시트(.xlsb)는 Excel 통합 문서 콘텐츠를 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML 매크로 사용 스프레드시트(.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML 스프레드시트(.xlsx)는 Microsoft Office 2007 릴리스와 함께 Microsoft에서 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel 이진 템플릿(.xlt)은 Excel 템플릿 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML 파일 템플릿(.xltm)은 Excel 템플릿 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltm) . |

### 비고

**더 알아보기**

* GroupDocs.Signature에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Signature에서 지원하는 문서 형식](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* C#에서 지원되는 형식 목록을 가져오는 방법에 대한 추가 정보: [C# 코드에서 지원되는 파일 형식을 얻는 방법](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
