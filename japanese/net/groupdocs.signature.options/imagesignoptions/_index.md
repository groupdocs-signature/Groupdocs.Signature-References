---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "画像署名オプションを表します。"
type: docs
weight: 1670
url: /ja/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

画像署名オプションを表します。

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | ImageSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | ImageSignOptions クラスの新しいインスタンスを画像ストリームで初期化します。 |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | ImageSignOptions クラスの新しいインスタンスを画像ファイルで初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | すべての文書ページに署名を配置します。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 追加の署名外観。 |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 境界設定を指定します |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 署名オプションのドキュメントタイプを取得または設定します [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 署名拡張機能。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。PDF ファイルのデジタル署名でのみサポートされます。 |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 文書ページ上の署名の高さを測定値（ピクセル、パーセント、またはミリメートル）で指定します（[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType を参照）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 文書ページ上の署名の水平配置。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 署名画像ファイルのパスを取得または設定します。このプロパティは ImageStream が指定されていない場合にのみ使用されます。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 署名画像ストリームを取得または設定します。このプロパティが指定されている場合、常に ImageFilePath の代わりに使用されます。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | ドキュメントページ上の署名の左側 X 位置（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType を参照）。（水平揃えが指定されていない場合に機能します）。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | 左および上プロパティの測定単位（ピクセル、パーセント、ミリメートル）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 署名とドキュメントの端との間のスペースを取得または設定します。（水平または垂直揃えが指定されている場合にのみ機能します）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 署名対象のドキュメントページ番号を取得または設定します。最小値およびデフォルト値は 1 です。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 署名対象ページを指定するオプションです。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 画像をドキュメントに配置する領域の矩形です。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | ドキュメントページ上の署名の回転角度（時計回り）。 |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 形状がドキュメントレイアウト内で表示される位置を定義します。Word ドキュメントでのみ利用可能です。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 署名タイプを取得します [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 幅と高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | ドキュメントページのストレッチモード。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | ドキュメントページ上の署名の上部 Y 位置（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType を参照）。（垂直揃えが指定されていない場合に機能します）。 |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 署名の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。デフォルト値は 0（不透明）です。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | ドキュメントページ上の署名の垂直揃えです。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | ドキュメントページ上の署名の幅（測定値：ピクセル、パーセント、またはミリメートルは [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType を参照）。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | テキスト署名の Z オーダー位置を取得または設定します。重なり合う署名の表示順序を決定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Base64 からの事前定義画像を使用して ImageSignOptions クラスの新しいインスタンスを作成します。 |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 内部リソースをクリアします |

### 備考

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### 関連項目

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
