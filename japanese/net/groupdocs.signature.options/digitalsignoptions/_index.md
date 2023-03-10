---
title: DigitalSignOptions
second_title: GroupDocs.Signature for .NET API リファレンス
description: デジタル署名オプションを表します
type: docs
weight: 1340
url: /ja/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

デジタル署名オプションを表します。

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | 証明書ストリームを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | 証明書ファイルを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | 証明書ストリームと画像ストリームを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | 証明書ストリームと画像ファイルを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | 証明書ファイルと画像ストリームを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | 証明書ファイルと画像ファイルを使用して DigitalSignOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | すべてのドキュメント ページに署名を付けます。 このプロパティは、複数フレームの画像形式 (Tiff) にのみ使用できます。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名の外観. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | ボーダー設定を指定 |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | デジタル証明書ファイルのパスを取得または設定します。 このプロパティは、CertificateStream が指定されていない場合にのみ使用されます。 |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | デジタル証明書ストリームを取得または設定します。 このプロパティが指定されている場合、代わりに常にそれが使用されます。 |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | 署名連絡先を取得または設定します。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメント タイプを取得または設定します[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の高さ[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | ドキュメント ページの署名の水平方向の配置。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 署名画像ファイル パスを取得または設定します。 このプロパティは、ImageStream が指定されていない場合にのみ使用されます。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | シグネチャ イメージ ストリームを取得または設定します。 このプロパティが指定されている場合、ImageFilePath の代わりに常に使用されます。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の左 X 位置[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). (水平方向の配置が指定されていない場合に機能します). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | 署名の場所を取得または設定します。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left プロパティと Top プロパティのメジャー タイプ (ピクセル、パーセント、またはミリメートル)。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 署名とドキュメントの端の間のスペースを取得または設定します. (水平または垂直の配置が指定されている場合にのみ機能します). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Margin. のメジャー タイプ (ピクセル、パーセント、またはミリメートル) を取得または設定します。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名用のドキュメント ページ番号を取得または設定します。 最小値で、デフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名するページを指定するオプション。 |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | デジタル証明書のパスワードを取得または設定します。 |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | 署名の理由を取得または設定します。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | ドキュメントに画像を配置する領域の長方形. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | ドキュメント ページの署名の回転角度 (時計回り). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | ドキュメントのデジタル署名のプロパティを取得または設定します。 Pdf ドキュメントに署名するために、インスタンスを使用して高度なプロパティを設定できます。[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 署名タイプを取得[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Width プロパティと Height プロパティのメジャー タイプ (ピクセル、パーセント、またはミリメートル)。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | ドキュメント ページのストレッチ モード。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 測定値 (ピクセル、パーセントまたはミリメートル参照[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). (垂直方向の配置が指定されていない場合に機能します). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 署名の透過性 (0.0 (不透明) から 1.0 (透明) までの値) を取得または設定します。デフォルト値は 0 (不透明). です。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | ドキュメント ページの署名の垂直方向の配置。 |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | 署名の可視性を取得または設定します。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 測定値 (ピクセル、パーセント、またはミリメートル) の文書ページの署名の幅[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES タイプ[`XAdESType`](./xadestype).デフォルト値は None です (XAdES はオフです). 現時点では、XAdES 署名タイプはスプレッドシート ドキュメントに対してのみサポートされています. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | テキスト署名の Z オーダー位置を取得または設定します。 重複する署名の表示順序を決定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 内部リソースをクリアします |

### 備考

**もっと詳しく知る**

* GroupDocs.Signatureによるデジタル電子署名作成の基本的な使い方: [デジタル署名でドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* GroupDocs.Signature: によるデジタル電子署名の設定の高度な使用法[デジタル署名と追加設定を使用してドキュメントを電子署名する高度な使用法](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### 関連項目

* class [ImageSignOptions](../imagesignoptions)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
