---
title: DoPaletteCorrection
second_title: GroupDocs.Signature for .NET API リファレンス
description: パレット補正を適用するかどうかを示す値を取得または設定します
type: docs
weight: 40
url: /ja/net/groupdocs.signature.options/gifsaveoptions/dopalettecorrection/
---
## GifSaveOptions.DoPaletteCorrection property

パレット補正を適用するかどうかを示す値を取得または設定します。

```csharp
public bool DoPaletteCorrection { get; set; }
```

### 備考

パレット補正とは、画像が GIF にエクスポートされるたびに、source 画像の色が分析されて、最適な palette を構築することを意味します (画像パレットが存在しないか、オプションで指定されていない場合)。 分析プロセスには時間がかかりますが、出力画像は 最も一致するカラー パレットを持ち、結果は視覚的に優れています.

### 関連項目

* class [GifSaveOptions](../../gifsaveoptions)
* 名前空間 [GroupDocs.Signature.Options](../../gifsaveoptions)
* 組み立て [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
