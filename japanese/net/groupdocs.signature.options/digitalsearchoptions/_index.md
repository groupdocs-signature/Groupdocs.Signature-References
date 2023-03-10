---
title: DigitalSearchOptions
second_title: GroupDocs.Signature for .NET API リファレンス
description: デジタル署名の検索オプションを表します
type: docs
weight: 1330
url: /ja/net/groupdocs.signature.options/digitalsearchoptions/
---
## DigitalSearchOptions class

デジタル署名の検索オプションを表します。

```csharp
public class DigitalSearchOptions : SearchOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DigitalSearchOptions](digitalsearchoptions)() | DigitalSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | 各ドキュメント ページで検索するフラグ。デフォルトでは、この値は true. に設定されています。 |
| [Comments](../../groupdocs.signature.options/digitalsearchoptions/comments) { get; set; } | 検索するデジタル署名のコメント. |
| [IssuerName](../../groupdocs.signature.options/digitalsearchoptions/issuername) { get; set; } | 空でない値の場合、検索する証明書発行者の識別名を指定します。 |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | 検索用のドキュメント ページ番号を取得または設定します。 値はオプションです。 |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | 署名検索用のページを指定するオプション。 |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalsearchoptions/signdatetimefrom) { get; set; } | 検索するデジタル署名の日付と時刻の範囲。 Null 許容値は無視されます。 |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalsearchoptions/signdatetimeto) { get; set; } | 検索するデジタル署名の日付と時刻の範囲。 Null 許容値は無視されます。 |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | IsSignature としてマークされた署名のみを返すフラグ。デフォルト値は false で、指定された条件に一致するすべての署名を返すことを示します. |
| [SubjectName](../../groupdocs.signature.options/digitalsearchoptions/subjectname) { get; set; } | 空でない値の場合、検索する証明書のサブジェクト識別名を指定します。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Signature: によるデジタル電子署名検索の基本的な使い方[ドキュメント内のデジタル署名を eSearch する方法](https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
* GroupDocs.Signature: によるデジタル電子署名の検索設定の高度な使用法[ドキュメントでの eSearch デジタル署名の高度な使用と追加設定](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

### 関連項目

* class [SearchOptions](../searchoptions)
* 名前空間 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->