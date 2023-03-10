---
title: ProcessCompleteEventArgs
second_title: GroupDocs.Signature for .NET API リファレンス
description: 署名検証および検索プロセスの完了イベントに関するデータを提供します
type: docs
weight: 1810
url: /ja/net/groupdocs.signature/processcompleteeventargs/
---
## ProcessCompleteEventArgs class

署名、検証、および検索プロセスの完了イベントに関するデータを提供します。

```csharp
public class ProcessCompleteEventArgs : ProcessEventArgs
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Canceled](../../groupdocs.signature/processcompleteeventargs/canceled) { get; } | プロセスがキャンセルされたかどうかを示します。 |
| [Completed](../../groupdocs.signature/processcompleteeventargs/completed) { get; set; } | プロセス完了のタイム マークを表します。 |
| [Status](../../groupdocs.signature/processeventargs/status) { get; set; } | 現在のプロセス状態を示します。 |
| [Ticks](../../groupdocs.signature/processcompleteeventargs/ticks) { get; set; } | プロセス開始イベント以降にかかった時間をミリ秒で表します。 |
| [TotalSignatures](../../groupdocs.signature/processcompleteeventargs/totalsignatures) { get; set; } | 処理された署名の総数を表します。 |

### 関連項目

* class [ProcessEventArgs](../processeventargs)
* 名前空間 [GroupDocs.Signature](../../groupdocs.signature)
* 組み立て [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->