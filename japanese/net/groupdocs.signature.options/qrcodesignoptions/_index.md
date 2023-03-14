---
title: QrCodeSignOptions
second_title: GroupDocs.Signature for .NET API リファレンス
description: QR コード署名オプションを表します
type: docs
weight: 1630
url: /ja/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

QR コード署名オプションを表します。

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | QRCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | QRCodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | BarcodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を入れます. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名の外観. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 署名の背景設定を取得または設定します。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | ボーダー設定を指定 |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | 結果の QR コード イメージ内のテキストの配置を取得または設定します。 デフォルト値は None です。 |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | QR コード コンテンツにシリアル化するカスタム オブジェクトを取得または設定します。 |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | の実装を取得または設定します[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) QR コード署名テキストまたはデータ プロパティをエンコードおよびデコードするためのインターフェイス。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメント タイプを取得または設定します[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | QR コード タイプを取得または設定します。 |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 署名のフォントを取得または設定します。 |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | QR コード バーのフォア カラーを取得または設定します このプロパティを使用すると、検証で問題が発生する可能性があります。慎重に使用してください。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | テキスト署名を入れるテキスト フォーム フィールドのタイトルを取得または設定します。 このプロパティは、SignatureImplementation = TextToFormField でのみ使用できます。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | テキスト署名を入れるフォーム フィールドのタイプを取得または設定します。 このプロパティは、SignatureImplementation = TextToFormField. でのみ使用できます。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の高さ[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType プロパティ). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | ドキュメント ページの署名の水平方向の配置。 |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | QR コード要素と結果画像の境界線の間のスペースを取得または設定します。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の左 X 位置[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType プロパティ). (水平方向の配置が指定されていない場合に機能します). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Left プロパティと Top プロパティのメジャー タイプ (ピクセル、パーセント、またはミリメートル)。 |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | QR コード ロゴ イメージ ファイル名を取得または設定します。 このプロパティは、LogoStream が指定されていない場合にのみ使用されます。 このプロパティを使用すると、検証で問題が発生する可能性があります。慎重に使用してください。 |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | QR コード ロゴ イメージ ストリームを取得または設定します。 このプロパティが指定されている場合、LogoFilePath の代わりに常に使用されます。 このプロパティを使用すると、検証で問題が発生する可能性があります。慎重に使用してください。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 署名とドキュメントの端の間のスペースを取得または設定します. (水平または垂直の配置が指定されている場合にのみ機能します). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Margin. のメジャー タイプ (ピクセル、パーセント、またはミリメートル) を取得または設定します。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | ネイティブ属性を取得または設定します。設定されている場合、ドキュメント固有の署名を使用できます. WordProcessing ドキュメントのネイティブ テキストの透かしは、通常とは異なります。たとえば、 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名用のドキュメント ページ番号を取得または設定します。 最小値で、デフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名するページを指定するオプション。 |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | ドキュメント ページに配置された署名の QR コード イメージ コンテンツを取得するためのフラグを取得または設定します。[`ReturnContentType`](./returncontenttype) . デフォルトでは、このオプションは無効になっています. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | ReturnContent プロパティが有効な場合に、返される QR コード署名の画像コンテンツのファイル タイプを指定します。 デフォルトでは Null に設定されています。これは、QR コード イメージ コンテンツを元の形式で返すことを意味します。 この画像フォーマットは[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) サポートされている可能性のある値は、FileType.JPEG、FileType.PNG、FileType.BMP です。 提供された形式がサポートされていない場合、.png 形式の QR コード画像コンテンツが返されます。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | ドキュメント ページの署名の回転角度 (時計回り). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | テキストを配置する形状のタイプを取得または設定します。 このプロパティは、SignatureImplementation = TextStamp. でのみ使用できます。デフォルト値は Rectangle. です。 |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 署名の一意の ID を取得または設定します。署名検証オプションで使用できます。 プロパティは Pdf ドキュメントでのみサポートされています. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | テキスト署名の実装の種類を取得または設定します。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 署名タイプを取得[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Width プロパティと Height プロパティのメジャー タイプ (ピクセル、パーセント、またはミリメートル)。 |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | ドキュメント ページのストレッチ モード。 |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 署名のテキストを取得または設定します。 |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 署名内のテキストの水平方向の配置。 この機能は、画像および注釈署名の実装でのみサポートされています (参照[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation プロパティ). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 署名内のテキストの垂直方向の配置。 この機能は、画像署名の実装 でのみサポートされています (参照[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation プロパティ)。 |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 測定値 (ピクセル、パーセントまたはミリメートル参照[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType プロパティ). (垂直方向の配置が指定されていない場合に機能). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 署名の透過性 (0.0 (不透明) から 1.0 (透明) までの値) を取得または設定します。デフォルト値は 0 (不透明). です。 |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | ドキュメント ページの署名の垂直方向の配置。 |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | メジャー値のドキュメント ページの署名の幅 (ピクセル、パーセント、またはミリメートルを参照)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType プロパティ). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | テキスト署名の Z オーダー位置を取得または設定します。 重複する署名の表示順序を決定します。 |

### 備考

**もっと詳しく知る**

* GroupDocs.SignatureによるQRコード電子署名作成の基本的な使い方: [QRコード署名でドキュメントに電子署名する方法](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* GroupDocs.SignatureによるQRコード電子署名の設定の高度な使い方: [QRコード署名と追加設定を使用してドキュメントを電子署名する高度な使用法](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### 関連項目

* class [TextSignOptions](../textsignoptions)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
