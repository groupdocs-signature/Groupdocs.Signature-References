---
title: "do_palette_correction プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "パレット補正が適用されているかどうかを示すフラグです。"
type: docs
url: /ja/python-net/groupdocs.signature.options/gifsaveoptions/do_palette_correction/
is_root: false
weight: 2030
---


## do_palette_correction property

パレット補正が適用されているかどうかを示すフラグです。

パレット補正とは、画像を GIF にエクスポートするたびに、ソース画像の色が解析され、最適なパレットが構築されることを意味します（画像パレットが存在しない場合やオプションで指定されていない場合）。解析には時間がかかりますが、出力画像は最適なカラーパレットを持ち、視覚的により優れた結果となります。

### Definition:
```python
@property
def do_palette_correction(self):
    ...
@do_palette_correction.setter
def do_palette_correction(self, value):
    ...
```

### 関連項目
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
