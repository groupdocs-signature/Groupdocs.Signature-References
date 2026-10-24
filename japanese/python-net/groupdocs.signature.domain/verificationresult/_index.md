---
title: "VerificationResult クラス"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "検証プロセスの結果を保持するインスタンスを表します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

検証プロセスの結果を保持するインスタンスを表します。

VerificationResult 型は次のメンバーを公開します：

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | 宛先ドキュメントのサイズ。検証時、この変数は常にゼロです。 |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | 検証プロセスに失敗した署名の一覧。 |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | 検証結果；検証プロセスが成功した場合は True、そうでない場合は False。 |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | プロセスの実行時間（ミリ秒）。 |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | ソースドキュメントのサイズ（バイト単位）。 |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | 正常に検証された署名の一覧 [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)。 |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | 処理された署名の総数。 |

### 例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### 関連項目
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
