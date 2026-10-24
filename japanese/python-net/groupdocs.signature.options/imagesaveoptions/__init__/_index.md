---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で ImagesSaveOptions クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/imagesaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で ImagesSaveOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#overwrite_existing_file}

上書きフラグ付きで ImagesSaveOptions クラスの新しいインスタンスを初期化します。

```python
def __init__(self, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

## __init__ {#file_format-overwrite_existing_file}

指定された出力ファイル形式と上書きフラグで ImagesSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `ImageSaveFileFormat` | 出力ファイルタイプ。 |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

### 関連項目
* class [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)
