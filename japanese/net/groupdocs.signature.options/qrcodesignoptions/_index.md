---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "QRCode 署名オプションを表します。"
type: docs
weight: 1920
url: /ja/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

QRコード署名オプションを表します。

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | QRCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | QRCodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を配置します。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名外観。 |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 署名の背景設定を取得または設定します。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 境界設定を指定します |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | 結果の QR コード画像内のテキストの配置を取得または設定します。既定値は None です。 |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | QR コードのコンテンツにシリアライズするカスタムオブジェクトを取得または設定します。 |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) インターフェイスの実装を取得または設定します。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメントタイプを取得または設定します [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | QR-Code のタイプを取得または設定します。 |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張機能。 |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 署名のフォントを取得または設定します。 |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | QR-Code のバーの Fore color を取得または設定します。このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | テキスト署名を配置するテキストフォームフィールドのタイトルを取得または設定します。このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | テキスト署名を配置するフォームフィールドのタイプを取得または設定します。このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。デフォルト値は AllTextTypes です。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。PDF ファイルのデジタル署名でのみサポートされます。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | ドキュメントページ上の署名の高さ（測定単位はピクセル、パーセント、またはミリメートルです。[`MeasureType`](../../groupdocs.signature.domain/measuretype) の SizeMeasureType プロパティをご参照ください）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 文書ページ上の署名の水平配置。 |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | QR-Code 要素と結果画像の境界間のスペースを取得または設定します。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | ドキュメントページ上の署名の左側 X 位置（測定値はピクセル、パーセント、またはミリメートルで、[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType プロパティを参照）。（水平揃えが指定されていない場合に機能します）。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 左および上プロパティの測定単位（ピクセル、パーセント、ミリメートル）。 |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | QR-code ロゴ画像のファイル名を取得または設定します。このプロパティは LogoStream が指定されていない場合にのみ使用されます。このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。 |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | QR-code ロゴ画像のストリームを取得または設定します。このプロパティが指定されている場合、常に LogoFilePath の代わりに使用されます。このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 署名とドキュメントの端との間のスペースを取得または設定します。（水平または垂直揃えが指定されている場合にのみ機能します）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | ネイティブ属性を取得または設定します。これが設定されている場合、ドキュメント固有の署名を使用できるようになります。WordProcessing ドキュメント用のネイティブテキスト透かしは、通常のものとは異なります（例）。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名対象のドキュメントページ番号を取得または設定します。最小値およびデフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名対象ページを指定するオプションです。 |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | ドキュメントページに配置された署名の QR-Code 画像コンテンツを取得するフラグを取得または設定します。このフラグが true に設定されている場合、QR-Code 署名画像コンテンツは必要な形式 [`ReturnContentType`](./returncontenttype) による生データを保持します。デフォルトではこのオプションは無効です。 |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | ReturnContent プロパティが有効な場合の QR-Code 署名の返却画像コンテンツのファイルタイプを指定します。デフォルトでは Null に設定されています。これは QR-Code 画像コンテンツを元の形式で返すことを意味します。この画像形式は [`Format`](../../groupdocs.signature.domain/qrcodesignature/format) で指定されます。サポートされる可能な値は: FileType.JPEG、FileType.PNG、FileType.BMP です。指定された形式がサポートされていない場合、QR-Code 画像コンテンツは .png 形式で返されます。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | ドキュメントページ上の署名の回転角度（時計回り）。 |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | 形状がドキュメントレイアウト内で表示される位置を定義します。Word ドキュメントでのみ利用可能です。 |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | テキストを配置する形状のタイプを取得または設定します。このプロパティは SignatureImplementation = TextStamp の場合にのみ使用できます。デフォルト値は Rectangle です。 |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 署名の一意の ID を取得または設定します。署名検証オプションで使用できます。このプロパティは Pdf ドキュメントでのみサポートされます。 |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | テキスト署名実装のタイプを取得または設定します。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 署名タイプを取得します [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | 幅と高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | ドキュメントページのストレッチモード。 |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 署名のテキストを取得または設定します。 |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 署名内テキストの水平揃え。この機能は Image および Annotation 署名実装でのみサポートされます（[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation プロパティを参照）。 |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 署名内テキストの垂直揃え。この機能は Image 署名実装でのみサポートされます（[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation プロパティを参照）。 |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | ドキュメントページ上の署名の上部 Y 位置（測定値はピクセル、パーセント、またはミリメートルで、[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType プロパティを参照）。（垂直揃えが指定されていない場合に機能します）。 |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 署名の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。デフォルト値は 0（不透明）です。 |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | ドキュメントページ上の署名の垂直揃えです。 |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | ドキュメントページ上の署名の幅（測定値はピクセル、パーセント、またはミリメートルで、[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType プロパティを参照）。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | テキスト署名の Z オーダー位置を取得または設定します。重なり合う署名の表示順序を決定します。 |

### 備考

**Learn more**

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### 関連項目

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
