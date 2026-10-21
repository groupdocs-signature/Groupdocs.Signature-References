---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "デジタル署名オプションを表します。"
type: docs
weight: 1560
url: /ja/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

デジタル署名オプションを表します。

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | デフォルト値で DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | 証明書ストリームで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | 証明書ファイルで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | 証明書ストリームと画像ストリームで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | 証明書ストリームと画像ファイルで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | 証明書ファイルと画像ストリームで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | 証明書ファイルと画像ファイルで DigitalSignOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | 有効期限が切れた証明書での署名を許可するフラグを取得または設定します。デフォルト値は false です。期限切れの証明書で署名しようとすると [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) がスローされ、ドキュメントは署名されません。 |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | 有効期間がまだ開始されていない証明書での署名を許可するフラグを取得または設定します。デフォルト値は false です。そのような証明書で署名しようとすると [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception) がスローされ、ドキュメントは署名されません。 |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を配置します。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名外観。 |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 境界設定を指定します |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | デジタル証明書ファイルのパスを取得または設定します。このプロパティは CertificateStream が指定されていない場合にのみ使用されます。 |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | デジタル証明書ストリームを取得または設定します。このプロパティが指定されている場合、常に CertificateFilePath の代わりに使用されます。 |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | 署名の連絡先を取得または設定します。 |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | カスタムハッシュ署名関数を取得または設定し、ユーザーが独自のデジタル署名ロジックを実装できるようにします。これにより外部証明書での署名が可能になり、さまざまなハッシュアルゴリズムをサポートします。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメントタイプを取得または設定します [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張機能。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。PDF ファイルのデジタル署名でのみサポートされます。 |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 文書ページ上の署名の高さを測定値（ピクセル、パーセント、またはミリメートル）で指定します（[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType を参照）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 文書ページ上の署名の水平配置。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 署名画像ファイルのパスを取得または設定します。このプロパティは ImageStream が指定されていない場合にのみ使用されます。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 署名画像ストリームを取得または設定します。このプロパティが指定されている場合、常に ImageFilePath の代わりに使用されます。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | ドキュメントページ上の署名の左側 X 位置（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType を参照）。（水平揃えが指定されていない場合に機能します）。 |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | 署名の位置を取得または設定します。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | 左および上プロパティの測定単位（ピクセル、パーセント、ミリメートル）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 署名とドキュメントの端との間のスペースを取得または設定します。（水平または垂直揃えが指定されている場合にのみ機能します）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名対象のドキュメントページ番号を取得または設定します。最小値およびデフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名対象ページを指定するオプションです。 |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | デジタル証明書のパスワードを取得または設定します。 |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | 署名の理由を取得または設定します。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 画像をドキュメントに配置する領域の矩形です。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | ドキュメントページ上の署名の回転角度（時計回り）。 |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 形状がドキュメントレイアウト内で表示される位置を定義します。Word ドキュメントでのみ利用可能です。 |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | 文書デジタル署名のプロパティを取得または設定します。Pdf ドキュメントに署名する場合、[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) のインスタンスを使用して高度なプロパティを設定できます。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 署名タイプを取得します [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 幅と高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | ドキュメントページのストレッチモード。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | ドキュメントページ上の署名の上部 Y 位置（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType を参照）。（垂直揃えが指定されていない場合に機能します）。 |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 署名の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。デフォルト値は 0（不透明）です。 |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | ltv（Long Term Validation）検証フラグを取得/設定します。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | ドキュメントページ上の署名の垂直揃えです。 |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | 署名の可視性を取得または設定します。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | ドキュメントページ上の署名の幅（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType を参照）。 |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES タイプ [`XAdESType`](./xadestype)。デフォルト値は None（XAdES はオフ）です。現在、この XAdES 署名タイプは Spreadsheet ドキュメントでのみサポートされています。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | テキスト署名の Z オーダー位置を取得または設定します。重なり合う署名の表示順序を決定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 内部リソースをクリアします |

### 備考

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### 関連項目

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
