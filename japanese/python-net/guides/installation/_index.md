---
title: "インストール"
linkTitle: "Installation"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "PyPI から .NET を介した GroupDocs.Signature for Python をインストールし、requirements.txt に固定するか、オフライン環境用に事前にダウンロードした wheel をインストールしてください。その後、インストールを確認します。"
type: docs
url: /ja/python-net/guides/installation/
is_root: false
weight: 10
---


GroupDocs.Signature for Python via .NET は、組み込みの .NET ランタイムをバンドルした自己完結型の wheel として配布されています。単一の `py3-none-{platform}` wheel は、Windows、Linux、macOS（Intel および Apple Silicon）上の Python **3.5 – 3.14** で動作します。Windows では他に何も必要ありませんが、Linux と macOS では以下に示すいくつかのシステムパッケージが必要です。

インストールする前に、[System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) を確認してください。ホイールをインストールするには、glibc 2.27 以上の Linux、または macOS 12 以上、さらに pip 20.3 以上が必要です。Linux では ICU、fontconfig、`libgdiplus`、Microsoft のコアフォントをインストールし、macOS では `mono-libgdiplus` をインストールしてください。

## Install Package from PyPI

すべてのパッケージは [PyPI](https://pypi.org/project/groupdocs-signature-net/) にホストされています。最新バージョンは `pip` でインストールしてください：

{{< tabs "install-from-pypi">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

既存のインストールを最新リリースにアップグレードするには、`--upgrade` フラグを追加してください：

```bash
python3 -m pip install --upgrade groupdocs-signature-net
```

[virtual environment](https://docs.python.org/3/library/venv.html) の使用が推奨されます。これにより、パッケージとその依存関係がシステムの Python から分離された状態を保てます。`venv` の設定手順については、[Quick Start Guide](/signature/python-net/guides/quick-start-guide/) を参照してください。

## Add the Package to `requirements.txt`

再現性のあるビルドのために、プロジェクトの `requirements.txt` でバージョンを固定してください：

```text
groupdocs-signature-net==26.10.0
```

次に、すべての依存関係を一度にインストールします：

```bash
python3 -m pip install -r requirements.txt
```

## Install from a Pre-Downloaded Wheel

PyPI にアクセスできない環境（例：ネットワークから切り離された CI ランナーやロックダウンされたサーバー）では、プラットフォームに対応したホイールをダウンロードし、ローカルファイルからインストールしてください。

お使いのオペレーティングシステムと CPU アーキテクチャに一致するホイールを、[GroupDocs.Signature releases](https://releases.groupdocs.com/signature/python-net/) ページからダウンロードしてください：

| プラットフォーム | ホイールファイル名の末尾は | 最小対応システム |
| --- | --- | --- |
| Windows 64-bit | `py3-none-win_amd64.whl` | — |
| Linux x64 (glibc) | `py3-none-manylinux_2_27_x86_64.whl` | glibc 2.27（Ubuntu 18.04、Debian 10、RHEL 8） |
| macOS Apple Silicon (M-series) | `py3-none-macosx_12_0_arm64.whl` | macOS 12 |
| macOS Intel | `py3-none-macosx_12_0_x86_64.whl` | macOS 12 |

26.10 以降、ファイル名には各ホイールが対応する最小システムが記載されるようになり、pip 20.3 以上では起動できないランタイムをインストールしないよう、古いホイールは事前に拒否されます。26.1 までのホイールは `manylinux1_x86_64`、`macosx_10_14_x86_64`、`macosx_11_0_arm64` とタグ付けされ、32 ビット Windows 用ホイール（`win32`）も含まれていましたが、現在は 32 ビットホイールは提供されていません。そのため、Windows では 64 ビット Python を使用してください。

`pip` でダウンロードしたファイルをインストールします（ファイル名はダウンロードしたホイールに置き換えてください）：

{{< tabs "install-from-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install .\groupdocs_signature_net-26.10.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_signature_net-26.10.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

ホイールファイル名を明示的に指定してください：PowerShell はネイティブコマンドで `*` ワイルドカードを展開しないため、`pip install groupdocs_signature_net-*.whl` は失敗します。

## Verify the Installation

パッケージがインストールされ、インポート可能であることを確認してください：

```bash
python3 -c "from groupdocs.signature import Signature; print('GroupDocs.Signature is ready')"
```

`pip` でインストールされたバージョンを確認することもできます：

```bash
python3 -m pip show groupdocs-signature-net
```

## Next Steps

- Follow the [Quick Start Guide](/signature/python-net/guides/quick-start-guide/) to sign your first document.
- Clone the [examples repository](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET) and read [How to Run Examples](https://docs.groupdocs.com/signature/python-net/how-to-run-examples/).
- Set up a [license](https://docs.groupdocs.com/signature/python-net/licensing/) to remove the evaluation limitations.
- If the installation or the first run fails, see [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/).
- If you work with AI agents or LLMs, see [Agents and LLM Integration](https://docs.groupdocs.com/signature/python-net/agents-and-llm-integration/) for MCP and `AGENTS.md` details.
