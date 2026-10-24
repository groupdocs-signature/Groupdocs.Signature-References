---
title: "__init__ コンストラクタ"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "Padding クラスの新しいインスタンスをゼロ値で初期化します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Padding クラスの新しいインスタンスをゼロ値で初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.signature.domain import Padding

# デフォルト（ゼロ）値でパディングオブジェクトを作成する
default_padding = Padding()
```

## __init__ {#all}

Padding クラスの新しいインスタンスを、すべての辺に対して指定されたパディングサイズを使用して初期化します。

```python
def __init__(self, all):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| all | `int` | すべてのエッジのパディングに使用される測定単位の数。 |

### 例

```python
# すべての側面で 5 ユニットの均一なパディング
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Padding クラスの新しいインスタンスを、指定されたパディングサイズを使用して初期化します。

```python
def __init__(self, left, right, top, bottom):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| left | `int` | 左側のパディングサイズ。 |
| right | `int` | 右側のパディングサイズ。 |
| top | `int` | 上側のパディングサイズ。 |
| bottom | `int` | 下部のパディングサイズです。 |

### 例

```python
from groupdocs.signature.domain import Padding

# 右側と下側のオフセットでパディングを作成します
margin = Padding(right=40, bottom=60)
```

### 関連項目
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
