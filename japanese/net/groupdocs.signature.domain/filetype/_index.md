---
title: FileType
second_title: GroupDocs.Signature for .NET API リファレンス
description: ファイルの種類を表します
type: docs
weight: 450
url: /ja/net/groupdocs.signature.domain/filetype/
---
## FileType class

ファイルの種類を表します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | ファイル名のサフィックス (ピリオド "." を含む) 例: ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | ファイルの種類名 (例: "Microsoft Word ドキュメント". |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | ファイル拡張子をファイル タイプにマップします。 |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | 現在の[`FileType`](../filetype)指定と同じです[`FileType`](../filetype)object. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype)指定されたオブジェクトと同じです. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | 現在のハッシュ コードを返します。[`FileType`](../filetype)object. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | サポートされているファイル タイプを取得します |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | 2 つの[`FileType`](../filetype)オブジェクトは同じです. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | 2 つの[`FileType`](../filetype)オブジェクトは同じではありません. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | ビットマップ イメージ ファイル (.bmp) は、ビットマップ デジタル イメージの保存に使用されます。これらの画像はグラフィックス アダプターに依存せず、デバイスに依存しないビットマップ (DIB) ファイル形式とも呼ばれます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/bmp) |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw ベクター グラフィック ドローイング (.cdr) は、エンコードおよび圧縮されたデジタル画像を保存するために CorelDRAW でネイティブに作成されるベクター描画画像ファイルです。このような図面ファイルには、テキスト、線、図形、画像、色、および画像コンテンツのベクトル表現用の効果が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/cdr) |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | コンピューター グラフィックス メタファイル (.cgm) は、ベクター グラフィックス (2D)、ラスター グラフィックス、およびテキストを格納および交換するための、プラットフォームに依存しない無料の国際標準メタファイル形式です。 CGM は、オブジェクト指向のアプローチと、画像生成のための多くの機能規定を使用します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/cgm) |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | CorelDRAW メタファイル Exchange イメージ ファイル (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | カンマ区切り値ファイル (.csv) は、カンマ区切りの値を持つデータのレコードを含むプレーン テキスト ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | DICOM 画像 (.dcm) は、MRI、CT スキャン、超音波画像などの患者の医療情報を格納するデジタル画像を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/dcm) |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | DjVu 画像 (.djvu) は、スキャンした文書や書籍、特にテキスト、図、画像、写真の組み合わせを含むものを対象としたグラフィック ファイル形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/djvu) |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Microsoft Word ドキュメント (.doc) は、Microsoft Word またはその他のワープロ ドキュメントによって生成されたドキュメントをバイナリ ファイル形式で表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML マクロ有効ドキュメント (.docm) は、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年の Microsoft Office 2007 のリリースで導入されたこの新しいドキュメント形式の構造は、プレーン バイナリから XML とバイナリ ファイルの組み合わせに変更されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Word ドキュメント テンプレート (.dot) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML マクロ有効ドキュメント テンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML ドキュメント テンプレート (.dotx) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | 拡張 Windows メタファイル (.emf) は、デバイスに依存しないグラフィック イメージを表します。 EMF のメタファイルは、保存された画像を任意の出力デバイスで解析した後にレンダリングできる、時系列の可変長レコードで構成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/emf) |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Encapsulated PostScript ファイル (.eps) は、単一ページの外観を記述する Encapsulated PostScript 言語プログラムを記述します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/eps) |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Graphical Interchange Format File (.gif) は、高度に圧縮されたイメージの一種です。各画像の GIF では通常、1 ピクセルあたり最大 8 ビットが許可され、画像全体で最大 256 色が許可されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/gif) |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | JPEG 画像 (.jpeg) は、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージ サイズと画質のトレードオフになります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | JPEG 画像 (.jpg) は、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージ サイズと画質のトレードオフになります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg) |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | OpenDocument グラフィック ファイル (.odg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター イメージとして保存するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/odg) |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | OpenDocument プレゼンテーション (.odp) は、OASISOpen 標準で OpenOffice.org が使用するプレゼンテーション ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/odp) |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | OpenDocument スプレッドシート (.ods) は、ユーザーが編集できる OpenDocument スプレッドシート ドキュメント形式を表します。データは ODF ファイル内に行と列に保存されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | OpenDocument テキスト ドキュメント (.odt) は、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | OpenDocument プレゼンテーション テンプレート (.otp) は、OASIS OpenDocument 標準形式のアプリケーションによって作成されたプレゼンテーション テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/otp) |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | OpenDocument スプレッドシート テンプレート (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | OpenDocument ドキュメント テンプレート (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | プリンター コマンド言語ドキュメント (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) は、1990 年代に Adobe によって作成されたドキュメントの一種です。このファイル形式の目的は、ドキュメントやその他の参考資料を、アプリケーション ソフトウェア、ハードウェア、およびオペレーティング システムに依存しない形式で表現するための標準を導入することでした。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/view/pdf) |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | スケーラブル ベクター グラフィックス ファイル (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用するスカラー ベクター グラフィックス ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphic (.png) は、可逆圧縮を使用するラスター イメージ ファイル形式の一種です。このファイル形式は、Graphics Interchange Format (GIF) の代替として作成されたもので、著作権の制限はありません。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/png) |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | PowerPoint テンプレート (.pot) は、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pot) |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML マクロ対応プレゼンテーション テンプレート (.potm) は、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。 POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できる既定の設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potm) |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML プレゼンテーション テンプレート (.potx) は、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potx) |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint スライド ショー (.pps) は、スライド ショー用に Microsoft PowerPoint を使用して作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pps) |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML マクロ有効スライド (.ppsm) は、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライド ショー ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | PowerPoint Open XML スライド ショー (.ppsx) ファイルは、スライド ショー用に Microsoft PowerPoint 2007 以降を使用して作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML マクロ有効プレゼンテーションは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ有効プレゼンテーション ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML プレゼンテーション (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイル形式に基づいています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | PostScript ファイル (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop ドキュメント (.psd) は、グラフィックのデザインと開発に使用される Adobe Photoshop のネイティブ ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/psd) |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | リッチ テキスト形式ファイル (.rtf) は、アプリケーション内で使用するために書式設定されたテキストとグラフィックスをエンコードする方法を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | スケーラブル ベクター グラフィックス ファイル (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用するスカラー ベクター グラフィックス ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | タグ付きイメージ ファイル (.tif) は、このファイル形式標準に準拠するさまざまなデバイスで使用するためのラスター イメージを表します。 2 値、グレースケール、パレット カラー、フルカラーの画像データを複数の色空間で表現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/tiff) |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠するさまざまなデバイスで使用するためのラスター イメージを表します。 2 値、グレースケール、パレット カラー、フルカラーの画像データを複数の色空間で表現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/tiff) |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | タブ区切り値ファイル (.tsv) は、プレーン テキスト形式のタブで区切られたデータを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | プレーン テキスト ファイル (.txt) は、行形式のプレーン テキストを含むテキスト ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/txt) |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | 不明なファイル タイプを表します。 |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard ファイル (.vcf) は、連絡先情報を保存するためのデジタル ファイル形式です。この形式は、一般的な情報交換アプリケーション間のデータ交換に広く使用されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/vcf) |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP 画像 (.webp) は、可逆圧縮と非可逆圧縮に基づく最新のラスター Web 画像ファイル形式です。画像サイズを大幅に縮小しながら、同じ画質を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/webp) |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows メタファイル (.wmf) は、ベクターおよびビットマップ形式の画像データを格納するための Microsoft Windows メタファイル (WMF) を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/wmf) |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | WordPerfect ドキュメント (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel スプレッドシート (.xls) は、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel バイナリ スプレッドシート (.xlsb) は、Excel ブックのコンテンツを指定するレコードと構造のコレクションである Excel バイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML マクロ対応スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft Office 2007 のリリースで Microsoft によって導入された Microsoft Excel ドキュメントのよく知られた形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel バイナリ テンプレート (.xlt) は、Excel テンプレート ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML ファイル テンプレート (.xltm) は、Excel テンプレート ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltm) |

### 備考

**もっと詳しく知る**

* GroupDocs.Signature でサポートされているファイル タイプの詳細: [GroupDocs.Signature でサポートされているドキュメント形式](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* C# でサポートされている形式のリストを取得する方法の詳細: [C# コードでサポートされているファイル形式を取得する方法](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### 関連項目

* 名前空間 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
