---
title: "FormFieldSignOptions"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "PDF ドキュメント用の FormField 署名オプションのクラスを表します。"
type: docs
weight: 1600
url: /ja/net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

PDF ドキュメント用の FormField 署名オプションのクラスを表します。

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | デフォルト値で PdfFormFieldSignOptions クラスの新しいインスタンスを初期化します。 |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | FormField 署名で PdfFormFieldSignOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を配置します。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名外観。 |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 署名の背景設定を取得または設定します。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 境界設定を指定します |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメントタイプを取得または設定します [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張機能。 |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 署名のフォントを取得または設定します。 |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | 署名の前景色を取得または設定します。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | テキスト署名を配置するテキストフォームフィールドのタイトルを取得または設定します。このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | テキスト署名を配置するフォームフィールドのタイプを取得または設定します。このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。デフォルト値は AllTextTypes です。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。PDF ファイルのデジタル署名でのみサポートされます。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | ドキュメントページ上の署名の高さ（測定単位はピクセル、パーセント、またはミリメートルです。[`MeasureType`](../../groupdocs.signature.domain/measuretype) の SizeMeasureType プロパティをご参照ください）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 文書ページ上の署名の水平配置。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | ドキュメントページ上の署名の左側 X 位置（測定値はピクセル、パーセント、またはミリメートルで、[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType プロパティを参照）。（水平揃えが指定されていない場合に機能します）。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 左および上プロパティの測定単位（ピクセル、パーセント、ミリメートル）。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 署名とドキュメントの端との間のスペースを取得または設定します。（水平または垂直揃えが指定されている場合にのみ機能します）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | ネイティブ属性を取得または設定します。これが設定されている場合、ドキュメント固有の署名を使用できるようになります。WordProcessing ドキュメント用のネイティブテキスト透かしは、通常のものとは異なります（例）。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名対象のドキュメントページ番号を取得または設定します。最小値およびデフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名対象ページを指定するオプションです。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | ドキュメントページ上の署名の回転角度（時計回り）。 |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | 形状がドキュメントレイアウト内で表示される位置を定義します。Word ドキュメントでのみ利用可能です。 |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | テキストを配置する形状のタイプを取得または設定します。このプロパティは SignatureImplementation = TextStamp の場合にのみ使用できます。デフォルト値は Rectangle です。 |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | 署名の FormField を取得または設定します。 |
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

* Basic usage of creating FormField electronic signature by GroupDocs.Signature: [How to eSign document with FormField signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with FormField signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### 関連項目

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
