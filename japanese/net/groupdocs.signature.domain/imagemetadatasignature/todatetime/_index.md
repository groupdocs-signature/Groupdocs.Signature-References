---
title: ToDateTime
second_title: GroupDocs.Signature for .NET API リファレンス
description: DateTime に変換します
type: docs
weight: 90
url: /ja/net/groupdocs.signature.domain/imagemetadatasignature/todatetime/
---
## ToDateTime() {#todatetime}

DateTime に変換します。

```csharp
public override DateTime ToDateTime()
```

### 戻り値

Metadata Signature 値を DateTime として返します。

### 備考

メタデータ値を変換できなかった場合、例外をスローします。 元の値が文字列ベースの場合、デフォルトのカルチャ プロパティ情報が SignatureSettings プロパティから使用されます[`DefaultCulture`](../../../groupdocs.signature/signaturesettings/defaultculture)

### 関連項目

* class [ImageMetadataSignature](../../imagemetadatasignature)
* 名前空間 [GroupDocs.Signature.Domain](../../imagemetadatasignature)
* 組み立て [GroupDocs.Signature](../../../)

---

## ToDateTime(IFormatProvider) {#todatetime_1}

DateTime に変換します。

```csharp
public override DateTime ToDateTime(IFormatProvider provider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| provider | IFormatProvider | データ変換操作で使用するフォーマット データ プロバイダー。 |

### 戻り値

Metadata Signature 値を DateTime として返します。

### 備考

メタデータ値を変換できなかった場合、例外をスローします

### 関連項目

* class [ImageMetadataSignature](../../imagemetadatasignature)
* 名前空間 [GroupDocs.Signature.Domain](../../imagemetadatasignature)
* 組み立て [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->