---
title: "クイックスタートガイド"
linkTitle: "Quick Start Guide"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "仮想環境を設定し、groupdocs-signature-net をインストールして、3 つの最小例を実行します：テキスト署名で PDF に署名し、署名を検索し、検証します。"
type: docs
url: /ja/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


このガイドは、GroupDocs.Signature for Python via .NET のセットアップと使用開始方法の概要を簡潔に示します。このライブラリは、数行のコードで PDF、Word、Excel、PowerPoint、OpenDocument、画像ファイルに電子署名を追加、検索、検証、更新、削除できます。

## Prerequisites

続行するには、以下が揃っていることを確認してください：

1. [システム要件](https://docs.groupdocs.com/signature/python-net/system-requirements/) トピックで説明されているように構成された環境。Linux と macOS ではいくつかのシステムパッケージが必要です。
2. 任意で、すべての製品機能をテストするための [一時ライセンス](https://purchase.groupdocs.com/temporary-license/)。ライセンスがない場合、ライブラリは評価モードで動作し、最大 2 ページまでのドキュメントを処理し、署名された各ページに評価ラインを追加します。[ライセンス](https://docs.groupdocs.com/signature/python-net/licensing/) を参照してください。

## Set Up Your Development Environment

ベストプラクティスとして、依存関係管理のために仮想環境を使用してください。詳細は [仮想環境の作成と使用](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) ガイドをご覧ください。

### Create and Activate a Virtual Environment

仮想環境を作成する:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

それを有効化する:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
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

バージョンを固定し、PyPI にアクセスできない状態でインストールする方法については、[Installation](/signature/python-net/guides/installation/) を参照してください。

## Example 1: Sign a PDF with a Text Signature

ドキュメントを開き、[TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) を使用して署名を記述し、署名済みのコピーを保存します。

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # ドキュメントを開きます；with ブロックは終了時にファイルを解放します。
    with Signature("sample.pdf") as signature:
        # 最初のページの左端と上端から 100 ピクセル離れた位置にテキスト署名を配置します。
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # 署名して結果を新しいファイルに保存します；元のファイルは変更されません。
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "signed_sample.pdf" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

ドキュメントが既に持つ署名を検索します。`search` は検索オプションのリストを受け取り、署名タイプごとに1つずつ検索し、結果を `result.signatures` に返します。

{{< tabs "search_document_for_signatures">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # 各ページでテキスト署名を検索します
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "search-document-signatures.txt" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

ドキュメントが期待する署名を持っているか確認します。テキストが完全に一致するテキスト署名が見つかったとき、検証は成功します。

{{< tabs "verify_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` はこの例で使用されるサンプルファイルです。[here](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "verify-text-signature.txt" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

各例をサンプルファイルの隣にあるそれぞれの `.py` ファイルに保存します。フォルダーは以下のようになるはずです：

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

そのフォルダーからサンプルを実行します：

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

完了したら、`deactivate` を実行するかシェルを閉じて仮想環境を無効化してください。

## Apply a License

`GROUPDOCS_LIC_PATH` 環境変数をライセンスファイルのフルパスに設定すると、`groupdocs.signature` をインポートした時にライセンスが自動的に適用されます。コードは不要です。あるいは、他の呼び出しの前にコード内で一度適用してください：

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

この[ライセンス](https://docs.groupdocs.com/signature/python-net/licensing/) のトピックでは、両方の方法と従量課金ライセンスについて説明しています。

## Next Steps

基本を完了したら、追加のリソースを探ってみてください：
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
