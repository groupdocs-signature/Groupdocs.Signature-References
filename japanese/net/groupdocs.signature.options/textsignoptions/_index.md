---
title: TextSignOptions
second_title: GroupDocs.Signature for .NET API リファレンス
description: テキスト署名オプションを表します
type: docs
weight: 1730
url: /ja/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

テキスト署名オプションを表します。

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | TextSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [TextSignOptions](textsignoptions#constructor_1)(string) | TextSignOptions クラスの新しいインスタンスを text. で初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を入れます. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名の外観. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 署名の背景設定を取得または設定します。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | ボーダー設定を指定 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメント タイプを取得または設定します[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 署名のフォントを取得または設定します。 |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | 署名の前の色を取得または設定します。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | テキスト署名を入れるテキスト フォーム フィールドのタイトルを取得または設定します。 このプロパティは、SignatureImplementation = TextToFormField でのみ使用できます。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | テキスト署名を入れるフォーム フィールドのタイプを取得または設定します。 このプロパティは、SignatureImplementation = TextToFormField. でのみ使用できます。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の高さ[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType プロパティ). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | ドキュメント ページの署名の水平方向の配置。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | メジャー値 (ピクセル、パーセント、またはミリメートルを参照) の文書ページの署名の左 X 位置[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType プロパティ). (水平方向の配置が指定されていない場合に機能します). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Left プロパティと Top プロパティのメジャー タイプ (ピクセル、パーセント、またはミリメートル)。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 署名とドキュメントの端の間のスペースを取得または設定します. (水平または垂直の配置が指定されている場合にのみ機能します). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Margin. のメジャー タイプ (ピクセル、パーセント、またはミリメートル) を取得または設定します。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | ネイティブ属性を取得または設定します。設定されている場合、ドキュメント固有の署名を使用できます. WordProcessing ドキュメントのネイティブ テキストの透かしは、通常とは異なります。たとえば、 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名用のドキュメント ページ番号を取得または設定します。 最小値で、デフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名するページを指定するオプション。 |
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

* GroupDocs.Signatureによるテキスト電子署名作成の基本的な使い方: [テキスト署名付きの文書に電子署名する方法](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* GroupDocs.Signature: によるテキスト電子署名の設定の高度な使用法[テキスト署名と追加設定を使用してドキュメントを電子署名する高度な使用法](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### 関連項目

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
