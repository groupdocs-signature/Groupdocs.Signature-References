---
title: "color_resolution プロパティ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "GIF の色解像度です。"
type: docs
url: /ja/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

GIF の色解像度です。

Color Resolution - 元画像で使用可能な各プライマリ色のビット数から 1 を引いた値です。この値は、グラフィックで選択された色が含まれる全パレットのサイズを表し、実際にグラフィックで使用された色の数を示すものではありません。例えば、このフィールドの値が 3 の場合、元画像のパレットは各プライマリ色につき 4 ビットで画像が作成されていたことを意味します。この値は、ソースマシンで全パレットのすべての色が利用可能でなくても、元パレットの豊かさを示すために設定すべきです。

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### 関連項目
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
