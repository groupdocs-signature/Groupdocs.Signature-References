---
title: "DigitalSignature"
second_title: "GroupDocs.Signature for .NET API リファレンス"
description: "デジタル署名プロパティを含みます。"
type: docs
weight: 150
url: /ja/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

デジタル署名プロパティを含みます。

```csharp
public class DigitalSignature : BaseSignature
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | デフォルトパラメータで Digital signature を初期化します。 |
| [DigitalSignature](digitalsignature#constructor_4)(string) | 既知の SignatureId で Digital signature を初期化します。 |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | 指定された証明書で Digital signature を作成します。 |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | 指定された X509 ストアに基づいて Digital signature を作成します。指定されたストアの最初の証明書が使用されます。 |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | 指定された X509 ストアと証明書インデックスに基づいて Digital signature を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | X509 証明書を取得または設定します。 |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | 証明書のカスタムストア名を指定します。 |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | 証明書のストアの場所を指定します。 |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | 証明書のストア名を指定します。 |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | 署名目的のコメントを取得または設定します。 |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 署名の作成日を取得または設定します。 |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | この署名が文書から削除されたかどうかを示すフラグを取得します。このプロパティは、削除された署名のリストを保持するための文書履歴ログレコードでのみ使用されます。 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 署名の高さを指定します。 |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | このコンポーネントが署名か文書コンテンツかを示すフラグを取得または設定します。このプロパティは Update メソッドと共に使用され、要素を署名 (true) または文書要素 (false) として設定します。 |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | このデジタル署名が有効で、文書が改ざんされていない場合は true を保持します。 |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 署名の左位置を指定します。 |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 署名の変更日を取得または設定します。 |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 署名が見つかったページを指定します。 |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | 文書内の署名を Update または Delete メソッドで変更するための一意の署名識別子です。このプロパティは Sign または Search メソッドが呼び出された後に自動的に設定されます。以前に保存されていた場合は、署名を操作するために手動で設定することができます。 |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 署名のタイプを指定します。 |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | 文書が署名された時刻を取得または設定します。 |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | 証明書のサムプリントを取得します。 |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 署名の上位置を指定します。 |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 署名の幅を指定します。 |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | XAdES タイプ [`XAdESType`](./xadestype)。デフォルト値は None（XAdES はオフ）です。現在、この XAdES 署名タイプは Spreadsheet ドキュメントでのみサポートされています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | バーコード署名インスタンスをクローンします。 |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | 署名プロパティを比較するために Equals メソッドを上書きします |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | GetHashCode メソッドをオーバーライドします |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | すべてのシステム X509 証明書ストアから Digital signatures をロードします。 |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | 証明書ストレージから Digital signatures をロードします。 |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | 証明書ストレージから Digital signatures をロードします。 |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | 特定の場所に配置されたデジタル証明書ストレージから Digital signatures をロードします。 |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | 特定の場所に配置されたデジタル証明書ストレージから Digital signatures をロードします。 |

### 関連項目

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
