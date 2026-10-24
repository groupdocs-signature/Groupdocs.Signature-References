---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で SpreadsheetSaveOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/spreadsheetsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で SpreadsheetSaveOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

事前定義された出力ファイル形式で SpreadsheetSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | 出力ファイル形式を指定します。 |

## __init__ {#file_format-overwrite_existing_file}

指定された出力ファイル形式と上書きフラグで SpreadsheetSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `SpreadsheetSaveFileFormat` | 出力ファイル形式を指定します。 |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

### 関連項目
* class [`SpreadsheetSaveOptions`](/signature/python-net/groupdocs.signature.options/spreadsheetsaveoptions/)
