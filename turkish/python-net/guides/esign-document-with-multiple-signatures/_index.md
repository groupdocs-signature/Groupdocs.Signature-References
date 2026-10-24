---
title: "Birden Çok İmza ile eİmza Belgesi"
linkTitle: "Multiple Types eSign"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu makale, GroupDocs.Signature for Python via .NET API kullanarak çeşitli tiplerde birden çok imza ile bir belgeyi nasıl imzalayacağınızı açıklar."
type: docs
url: /tr/python-net/guides/esign-document-with-multiple-signatures/
is_root: false
weight: 80
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) allows signing a document with several signatures simultaneously and even apply signatures of different types to the same document.

Bunu yapmak şu kadar basittir:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path or stream as a constructor parameter.
* Instantiate all required sign options objects depending on signature type:
    * [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) - for Barcode signatures;
    * [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) - for Digital signatures;
    * [FormFieldSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/formfieldsignoptions) - for Form-field signatures;
    * [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) - for Image signatures;
    * [MetadataSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/metadatasignoptions) - for Metadata signatures;
    * [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) - for QR-code signatures
    * [StampSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/stampsignoptions) - for Stamp signatures;
    * [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) - for Text signatures.
* Fill the collection with sign options from the previous step.  
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the collection of sign options to it.

Aşağıdaki kod parçacığı, Python kullanarak bir PDF belgesine aynı anda birden çok imza ile nasıl eİmza atılacağını gösterir:

{{< tabs \"sign_with_multiple_signatures\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import (
    BarcodeSignOptions, DigitalSignOptions, QrCodeSignOptions, TextSignOptions)
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes

def sign_with_multiple_signatures():
    with Signature("sample.pdf") as signature:
        # Metin imza seçeneklerini tanımlayın
        text_options = TextSignOptions("This is test message")
        text_options.left = 100
        text_options.top = 360
        text_options.width = 200
        text_options.height = 30

        # Barkod imza seçeneklerini tanımlayın
        barcode_options = BarcodeSignOptions("123456")
        barcode_options.encode_type = BarcodeTypes.CODE128
        barcode_options.left = 100
        barcode_options.top = 420
        barcode_options.width = 200
        barcode_options.height = 60

        # QR kod imza seçeneklerini tanımlayın
        qrcode_options = QrCodeSignOptions("JohnSmith")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.left = 100
        qrcode_options.top = 520
        qrcode_options.width = 100
        qrcode_options.height = 100

        # Sertifika ve görünüm resmi içeren dijital imza seçeneklerini tanımlayın
        digital_options = DigitalSignOptions("certificate.pfx")
        digital_options.password = "1234567890"
        digital_options.image_file_path = "signature.jpg"
        digital_options.left = 350
        digital_options.top = 520
        digital_options.width = 160
        digital_options.height = 100

        # Belgeyi imza seçenekleri listesiyle imzalayın
        list_options = [text_options, barcode_options, qrcode_options, digital_options]
        result = signature.sign("signed_multiple.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` bu örnekte kullanılan örnek sertifikadır (parola `1234567890`). İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/certificate.pfx) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab \"signed_multiple.pdf\" >}}
```text
Binary file (PDF, 740 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures/signed_multiple.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Multiple Signatures Example

İşte farklı stiller ve konumlarla birden fazla imza eklemeyi gösteren daha gelişmiş bir örnek. Her imza, sayfa kenarlarından hizalama ve kenar boşluğu ile yerleştirilir:

{{< tabs "sign_with_multiple_signatures_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions, QrCodeSignOptions, TextSignOptions
from groupdocs.signature.domain import (
    HorizontalAlignment, Padding, QrCodeTypes, SignatureFont, VerticalAlignment)

def sign_with_multiple_signatures_advanced():
    with Signature("sample.pdf") as signature:
        # Sayfa başlığının altında, sağ üst köşede kalın metin imzası
        text_options = TextSignOptions("Approved by John Smith")
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        text_options.font = font
        text_options.width = 280
        text_options.height = 40
        text_options.vertical_alignment = VerticalAlignment.TOP
        text_options.horizontal_alignment = HorizontalAlignment.RIGHT
        text_options.margin = Padding(top=170, right=20)

        # Alt sol köşede damga resmi
        image_options = ImageSignOptions("stamp.png")
        image_options.width = 100
        image_options.height = 100
        image_options.vertical_alignment = VerticalAlignment.BOTTOM
        image_options.horizontal_alignment = HorizontalAlignment.LEFT
        image_options.margin = Padding(left=20, bottom=20)

        # Alt sağ köşede QR kodu
        qrcode_options = QrCodeSignOptions("https://www.example.com/verify")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.width = 100
        qrcode_options.height = 100
        qrcode_options.vertical_alignment = VerticalAlignment.BOTTOM
        qrcode_options.horizontal_alignment = HorizontalAlignment.RIGHT
        qrcode_options.margin = Padding(right=20, bottom=20)

        # Belgeyi imza seçenekleri listesiyle imzalayın
        list_options = [text_options, image_options, qrcode_options]
        result = signature.sign("signed_multiple_advanced.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "stamp.png" >}}

`stamp.png` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/stamp.png) tıklayın.

{{< /tab >}}
{{< tab "signed_multiple_advanced.pdf" >}}
```text
Binary file (PDF, 178 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures_advanced/signed_multiple_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) kullanarak bir belgeye birden fazla elektronik imza türü (ör. metin, barkod, resim) uygulamayı gösterir. Farklı imza türlerini nasıl birleştireceğinizi, her birini nasıl yapılandıracağınızı ve imzalı belgeyi birden fazla imza stiliyle nasıl kaydedeceğinizi açıklar.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** adresindeki çevrimiçi uygulamaları kullanabilirsiniz.
