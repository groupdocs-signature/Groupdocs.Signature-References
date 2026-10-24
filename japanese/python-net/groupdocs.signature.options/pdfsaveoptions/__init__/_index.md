---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デフォルト値で PdfSaveOptions の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

デフォルト値で PdfSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_format}

指定された出力ファイル形式で PdfSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 出力ファイルタイプ `PdfSaveFileFormat`。 |

## __init__ {#overwrite_existing_file}

上書きフラグを使用して PdfSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

## __init__ {#file_format-overwrite_existing_file}

指定された出力ファイル形式と上書きフラグで PdfSaveOptions の新しいインスタンスを初期化します。

```python
def __init__(self, file_format, overwrite_existing_file):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_format | `PdfSaveFileFormat` | 出力ファイルタイプ。 |
| overwrite_existing_file | `bool` | 同じファイルで署名済みファイルを上書きするかどうかのフラグ。 |

### 例

```python
from groupdocs.signature.options import PdfSaveOptions
from groupdocs.signature.domain import PdfSaveFileFormat

# PDF 形式で保存オプションを作成し、既存のファイルの上書きを許可する
save_options = PdfSaveOptions(fileFormat=PdfSaveFileFormat.PDF, overwriteExistingFile=True)
```

### 関連項目
* class [`PdfSaveOptions`](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/)
