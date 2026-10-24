---
title: "デジタル署名でドキュメントに署名する"
linkTitle: "Digital Signature"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "デジタル署名を使用してドキュメントを安全に署名するメリットについて学びましょう。ステップバイステップの手順で、Python でプログラム的にデジタル署名を追加する方法を紹介します。"
type: docs
url: /ja/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

デジタル時代の今日、電子文書の真正性と完全性を確保することは極めて重要です。そのための非常に効果的な手段の一つがデジタル署名の利用です。このガイドでは、デジタル署名の概要、重要性、そして GroupDocs.Signature for Python via .NET を活用して文書にシームレスに eSign を行う方法について解説します。

## What is a Digital Signature?

デジタル署名は、電子文書の真正性と完全性を検証するための暗号化メカニズムです。文書が既知の送信者からのものであり、権限のない者によって改ざんされていないことを強く保証します。デジタル署名は通常、署名用のプライベートキーと検証用のパブリックキーを含む証明書で表されます。PFX 形式などのさまざまな公開鍵暗号標準がこの目的で一般的に使用されます。
以下の画像は、PDF 文書ページ上でデジタル署名がデフォルトでどのように表示されるかを示しています。

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

期限切れまたはまだ有効でない証明書は拒否されます。`sign` は [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) を発生させ、たとえば "The signing certificate expired on ..." のようなメッセージを表示します。このような証明書で署名する場合は、`allow_expired` または `allow_not_yet_valid` を `True` に設定してください。

### Follow these steps to sign your documents with a digital signature

1. pip を使用して GroupDocs.Signature パッケージをインストールします:
```bash
pip install groupdocs-signature-net
```

2. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) クラスの新しいインスタンスを作成し、ソースドキュメントのパスをコンストラクタのパラメータとして渡します。
3. 必要な証明書とそのパスワードを指定して、[DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) オブジェクトをインスタンス化します。
4. [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) メソッドを、[Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) クラスのインスタンスで呼び出し、[DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) を渡します。

以下の例は、Python を使用してデジタル電子署名で PDF ドキュメントに署名する方法を示しています。同様の方法で、他のサポートされているドキュメント形式にも署名できます。

{{< tabs \"sign_with_digital_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # 証明書ファイルでデジタル署名オプションを作成します
        options = DigitalSignOptions("certificate.pfx")

        # 証明書のパスワードを設定します
        options.password = "1234567890"

        # オプション: ページ上に署名を表示する画像
        options.image_file_path = "signature.jpg"

        # 署名の位置を設定します
        options.left = 100
        options.top = 400

        # ドキュメントに署名し、結果を保存する
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` はこの例で使用されるサンプル証明書です（パスワードは `1234567890`）。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) をクリックしてください。

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) をクリックしてください。

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

デジタル署名は、ページ上の署名サイズや、署名に保存される連絡先、理由、場所などの追加オプションでさらにカスタマイズできます。

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # コンストラクタに証明書と外観画像を渡します
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # ページ上に署名を、この位置とサイズで表示します
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # 署名に格納された情報
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` はこの例で使用されるサンプル証明書です（パスワードは `1234567890`）。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) をクリックしてください。

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) をクリックしてください。

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

ストリームから証明書を読み込むこともできます。`sign` が返るまでストリームを開いたままにしてください。

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # ストリームから証明書を読み込む
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # 署名の位置とサイズを設定する
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) をクリックしてください。

{{< /tab >}}
{{< tab \"certificate.pfx\" >}}

`certificate.pfx` はこの例で使用されるサンプル証明書です（パスワードは `1234567890`）。ダウンロードするには [ここ](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) をクリックしてください。

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
このガイドでは、[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) を使用してデジタル署名でドキュメントに署名する方法を示します。ドキュメントの読み込み方法、証明書ベースの署名の設定方法、署名済みファイルの安全な保存方法について説明します。また、署名の外観や署名に保存される情報などの高度な機能も取り上げています。デジタル署名ワークフローの詳細については、関連リソースをご参照ください。

## More Resources

### GitHub Examples

上記のコードを簡単に実行して、GitHub のサンプルで機能を実際に確認できます:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

フル機能の Python ライブラリに加えて、シンプルで強力な無料オンラインアプリも提供しています。

PDF、Word、Excel、PowerPoint、その他のドキュメントに署名するには、**[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** のオンラインアプリを使用できます。
