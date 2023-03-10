---
title: Padding
second_title: GroupDocs.Signature for .NET API リファレンス
description: 要素に関連付けられたパディングまたはマージン情報を表します.
type: docs
weight: 640
url: /ja/net/groupdocs.signature.domain/padding/
---
## Padding class

要素に関連付けられたパディングまたはマージン情報を表します.

```csharp
public class Padding : ICloneable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Padding](padding#constructor)() | ゼロ値を使用して Padding クラスの新しいインスタンスを初期化します。 |
| [Padding](padding#constructor_1)(int) | すべてのエッジに指定されたパディング サイズを使用して、Padding クラスの新しいインスタンスを初期化します。 |
| [Padding](padding#constructor_2)(int, int, int, int) | 指定されたパディング サイズを使用して、パディング クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [All](../../groupdocs.signature.domain/padding/all) { get; set; } | すべてのエッジのパディング値を取得または設定します。 左または上などの部分的なエッジを変更すると、このプロパティは 0 になります。 |
| [Bottom](../../groupdocs.signature.domain/padding/bottom) { get; set; } | 下端のパディング値を取得または設定します。 |
| [Horizontal](../../groupdocs.signature.domain/padding/horizontal) { get; } | 右端と左端の結合されたパディングを取得します. |
| [Left](../../groupdocs.signature.domain/padding/left) { get; set; } | 左端のパディング値を取得または設定します。 |
| [Right](../../groupdocs.signature.domain/padding/right) { get; set; } | 右端のパディング値を取得または設定します。 |
| [Top](../../groupdocs.signature.domain/padding/top) { get; set; } | 上端のパディング値を取得または設定します。 |
| [Vertical](../../groupdocs.signature.domain/padding/vertical) { get; } | 上端と下端の結合されたパディングを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.signature.domain/padding/clone)() | このオブジェクトのコピーを取得します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Empty](../../groupdocs.signature.domain/padding/empty) | パディングなしの Padding オブジェクトを提供します。 |

### 関連項目

* 名前空間 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->