---
title: "Event クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "標準的なQRコードイベントの詳細を表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain.extensions/event/
is_root: false
weight: 90
---


## Event class

標準的なQRコードイベントの詳細を表します。

Event 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/event/__init__/) | デフォルト値で Event インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/signature/python-net/groupdocs.signature.domain.extensions/event/equals/#obj) | この Event と別の Event を等価性で比較します。 |
| [equals_object](/signature/python-net/groupdocs.signature.domain.extensions/event/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain.extensions/event/get_hash_code/) | Event のハッシュコードを返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [description](/signature/python-net/groupdocs.signature.domain.extensions/event/description/) | イベントの説明。 |
| [end_date](/signature/python-net/groupdocs.signature.domain.extensions/event/end_date/) | イベントの終了日時。 |
| [location](/signature/python-net/groupdocs.signature.domain.extensions/event/location/) | イベントの場所。 |
| [start_date](/signature/python-net/groupdocs.signature.domain.extensions/event/start_date/) | イベントの開始日時。 |
| [title](/signature/python-net/groupdocs.signature.domain.extensions/event/title/) | イベントのタイトル。 |

### 例

```python
from datetime import datetime
from groupdocs.signature.domain.extensions import Event

event_qr = Event()
event_qr.title = "Meeting"
event_qr.description = "Productivity issues"
event_qr.location = "room 408"
event_qr.start_date = datetime(2022, 6, 19, 15, 30, 0)
event_qr.end_date = datetime(2022, 6, 19, 17, 0, 0)
```

### 関連項目
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
