---
title: "FileType"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "ファイルタイプを表します。"
type: docs
weight: 610
url: /ja/net/groupdocs.signature.domain/filetype/
---
## FileType class

ファイルタイプを表します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | ファイルタイプ名 例: "Microsoft Word Document"。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | ファイル拡張子をファイルタイプにマップします。 |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 現在の [`FileType`](../filetype) が指定された [`FileType`](../filetype) オブジェクトと同じかどうかを判断します。 |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 現在の [`FileType`](../filetype) が指定されたオブジェクトと同じかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 現在の [`FileType`](../filetype) オブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | サポートされているファイルタイプを取得します |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 2つの [`FileType`](../filetype) オブジェクトが同じかどうかを判断します。 |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 2つの[`FileType`](../filetype) オブジェクトが同一でないかどうかを判定します。 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) は、ロスレス圧縮を使用するラスタ画像ファイル形式です。GIF 形式の代替として、著作権制限なしでアニメーションをサポートするために PNG の拡張として開発されました。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/apng)をご覧ください。 |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | WordPerfect ドキュメント (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Bitmap Image File (.bmp) はビットマップデジタル画像を保存するために使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ (DIB) ファイル形式とも呼ばれます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/bmp)をご覧ください。 |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) は、CorelDRAW でネイティブに作成されるベクタ描画画像ファイルで、デジタル画像をエンコードおよび圧縮して保存します。このような描画ファイルには、テキスト、線、形状、画像、色、効果が含まれ、画像内容をベクタで表現します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/cdr)をご覧ください。 |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) は、ベクタ画像（2D）、ラスタ画像、テキストの保存と交換のための、無料でプラットフォームに依存しない国際標準メタファイル形式です。CGM はオブジェクト指向アプローチと多数の機能を提供し、画像生成を支援します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/cgm)をご覧ください。 |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW Metafile Exchange Image File (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Comma Separated Values File (.csv) は、カンマ区切りの値でデータレコードを含むプレーンテキストファイルを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/csv)をご覧ください。 |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM Image (.dcm) は、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/dcm)をご覧ください。 |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu Image (.djvu) は、テキスト、図面、画像、写真が組み合わさったスキャン文書や書籍向けに設計されたグラフィックファイル形式です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/djvu)をご覧ください。 |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word Document (.doc) は、Microsoft Word やその他のワードプロセッサで生成されたバイナリ形式の文書を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/doc)をご覧ください。 |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) は、マクロ実行機能を備えた Microsoft Word 2007 以降で生成された文書です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/docm)をご覧ください。 |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) は、Microsoft Word 文書の代表的な形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、従来のプレーンバイナリ形式から XML とバイナリファイルの組み合わせに構造が変更されました。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/docx)をご覧ください。 |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word Document Template (.dot) は、Microsoft Word が作成するテンプレートファイルで、今後の DOC や DOCX ファイル生成のために事前に書式設定された設定を保持します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dot)をご覧ください。 |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dotm)をご覧ください。 |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) は、Microsoft Word が作成するテンプレートファイルで、今後の DOCX ファイル生成のために事前に書式設定された設定を保持します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/dotx)をご覧ください。 |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) は、デバイスに依存せずにグラフィック画像を表します。EMF のメタファイルは、可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像をレンダリングできます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/emf)をご覧ください。 |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript File (.eps) は、単一ページの外観を記述する Encapsulated PostScript 言語プログラムを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/eps)をご覧ください。 |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) は、非常に圧縮された画像形式です。GIF は通常、1 ピクセルあたり最大 8 ビット、全体で最大 256 色を使用できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/gif)をご覧ください。 |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | GZip 圧縮アーカイブ (.gz) は、高い圧縮率でファイルを圧縮します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/compression/gz)をご覧ください。 |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG Image (.jpeg) は、非可逆圧縮方式で保存される画像形式です。圧縮結果として得られる画像は、保存サイズと画質のバランスを取ったものになります。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/jpeg)をご覧ください。 |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG Image (.jpg) は、非可逆圧縮方式で保存される画像形式です。圧縮結果として得られる画像は、保存サイズと画質のバランスを取ったものになります。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/jpeg)をご覧ください。 |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | LZip 圧縮アーカイブ (.lz) は、高い圧縮率でファイルを圧縮します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/compression/lz)をご覧ください。 |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument Graphic File (.odg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクタ画像として保存するために使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/odg)をご覧ください。 |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument Presentation (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーションファイル形式を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/presentation/odp)をご覧ください。 |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) は、ユーザーが編集可能な OpenDocument Spreadsheet Document 形式を指します。データは ODF ファイル内に行と列として保存されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/ods)で確認できます。 |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument Text Document (.odt) は、OpenDocument Text File 形式に基づくワードプロセッシングアプリケーションで作成される文書タイプです。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/odt)で確認できます。 |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument Presentation Template (.otp) は、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/otp)で確認できます。 |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument Spreadsheet Template (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument Document Template (.ott) は、OASIS の OpenDocument 標準形式に準拠してアプリケーションが生成するテンプレート文書を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/ott)で確認できます。 |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Printer Command Language Document (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) は、1990 年代に Adobe が作成した文書の一種です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で文書やその他の参照資料を表現する標準を導入することでした。このファイル形式の詳細は[here](https://wiki.fileformat.com/view/pdf)で確認できます。 |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Personal Information Exchange (.pfx) ファイルは、パスワードで保護された証明書で、アプリケーションのコード署名に一般的に使用されます。このファイル形式の詳細は[here](https://fileinfo.com/extension/pfx)で確認できます。 |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスター画像ファイル形式の一種です。このファイル形式は Graphics Interchange Format (GIF) の代替として作成され、著作権制限がありません。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/png)で確認できます。 |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint Template (.pot) は、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint のテンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pot)で確認できます。 |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) は、マクロに対応した Microsoft PowerPoint のテンプレートファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらなるプレゼンテーションファイルを作成するために使用できる既定設定が含まれています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potm)で確認できます。 |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) は、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint のテンプレートプレゼンテーションを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potx)で確認できます。 |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) は、スライドショー目的で Microsoft PowerPoint を使用して作成されます。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pps)で確認できます。 |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) は、Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショー形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsm)で確認できます。 |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) ファイルは、Microsoft PowerPoint 2007 以降を使用してスライドショー目的で作成されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsx)で確認できます。 |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) は、スライドショーとして表示するためのスライド集合で構成された PowerPoint ファイルを表します。これは Microsoft PowerPoint 97-2003 が使用するバイナリファイル形式を指定しています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppt)で確認できます。 |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation は、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーションファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptm)で確認できます。 |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) は、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。従来のバイナリ形式 PPT と異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptx)で確認できます。 |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) は、グラフィックデザインと開発に使用される Adobe Photoshop のネイティブファイル形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/psd)で確認できます。 |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) は、アプリケーション内で使用するための書式付きテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/rtf)で確認できます。 |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | High compressed archive (.7z) は、高い圧縮率でファイルやフォルダーを圧縮するアーカイブです。このファイル形式の詳細は[here](https://wiki.fileformat.com/page-description-language/7z)で確認できます。 |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用するスケーラブルベクターグラフィックスファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/page-description-language/svg)で確認できます。 |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Unixベースのユーティリティである (.tar) は、1つ以上のファイルやディレクトリを保持できるアーカイブです。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/tar/)で確認できます。 |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga) は、TARGA とも呼ばれる、Truevision Inc. が開発したラスター画像ファイル形式です。さまざまな色深度とオプションの RLE 圧縮をサポートし、ビデオゲーム、アニメーションパイプライン、グラフィックアプリケーションで高品質な画像レンダリングとオプションのアルファチャンネルサポートのために一般的に使用されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/tga)で確認できます。 |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) は、このファイル形式標準に準拠したさまざまなデバイスでの使用を目的としたラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できる機能があります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/tiff)で確認できます。 |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠したさまざまなデバイスでの使用を目的としたラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できる機能があります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/tiff)で確認できます。 |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) は、タブで区切られたプレーンテキスト形式のデータを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/tsv)で確認できます。 |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) は、行単位のプレーンテキストを含む文書を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/txt)で確認できます。 |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 不明なファイルタイプを表します。 |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) は、連絡先情報を保存するためのデジタルファイル形式です。この形式は、一般的な情報交換アプリケーション間でのデータ交換に広く使用されています。このファイル形式の詳細は[here](https://wiki.fileformat.com/email/vcf)で確認できます。 |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) は、可逆圧縮と非可逆圧縮に基づく最新のラスタウェブ画像ファイル形式です。画像サイズを大幅に削減しながら同等の画質を提供します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/webp)で確認できます。 |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) は、ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/wmf)で確認できます。 |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect ドキュメント (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) は、Excel バイナリ ファイル形式を表します。この形式のファイルは、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシートプログラムでも作成できます。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xls)で確認できます。 |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) は、Excel バイナリ ファイル形式を指定します。この形式は、Excel ブックの内容を定義するレコードと構造の集合です。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsb)で確認できます。 |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsm)で確認できます。 |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) は、Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel 文書向けの広く知られた形式です。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlsx)で確認できます。 |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) は、Excel テンプレート ファイル形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xlt)で確認できます。 |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm) は、Excel テンプレート ファイル形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/spreadsheet/xltm)で確認できます。 |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip) は、可逆データ圧縮をサポートするアーカイブ ファイル形式です。1つまたは複数のファイルやディレクトリを格納できます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/zip/)で確認できます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 関連項目

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
