---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で WordProcessingSaveOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で WordProcessingSaveOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

指定された出力ファイル形式で WordProcessingSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `WordProcessingSaveFileFormat` | 出力ファイルタイプ `WordProcessingSaveFileFormat` です。 |

## __init__ {#overwrite_existing_file}

指定された出力タイプと上書きフラグで WordProcessingSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

## __init__ {#file_format-overwrite_existing_file}

指定された出力ファイル形式と上書きフラグで WordProcessingSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `WordProcessingSaveFileFormat` | 出力ファイルタイプ。 |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

### 関連項目
* class [`WordProcessingSaveOptions`](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/)
