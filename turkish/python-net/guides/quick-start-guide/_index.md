---
title: "Hızlı Başlangıç Kılavuzu"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Sanal bir ortam kurun, groupdocs-signature-net'i yükleyin ve üç temel örneği çalıştırın: bir PDF'yi metin imzası ile imzalayın, imzalar için arama yapın ve onları doğrulayın."
type: docs
url: /tr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Bu kılavuz, GroupDocs.Signature for Python via .NET'i nasıl kurup kullanmaya başlayacağınıza dair hızlı bir genel bakış sunar. Kütüphane, birkaç satır kodla PDF, Word, Excel, PowerPoint, OpenDocument ve görüntü dosyalarındaki elektronik imzaları ekler, bulur, doğrular, günceller ve kaldırır.

## Prerequisites

Devam etmek için, aşağıdakilere sahip olduğunuzdan emin olun:

1. [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/) konusunda açıklanan şekilde yapılandırılmış bir ortam. Linux ve macOS'ta bu, birkaç sistem paketini içerir.
2. İsteğe bağlı olarak, tüm ürün özelliklerini test etmek için bir [Temporary License](https://purchase.groupdocs.com/temporary-license/) alın. Lisans olmadan kütüphane değerlendirme modunda çalışır: iki sayfaya kadar belge işler ve imzaladığı her sayfaya bir değerlendirme satırı ekler. Bkz. [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

En iyi uygulamalar için bağımlılıkları yönetmek amacıyla bir sanal ortam kullanın. Daha fazla bilgi için [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) kılavuzuna bakın.

### Create and Activate a Virtual Environment

Bir sanal ortam oluşturun:

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

Etkinleştirin:

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

[Installation](/signature/python-net/guides/installation/) sayfasına bir sürümü sabitlemek ve PyPI erişimi olmadan kurulum yapmak için bakın.

## Example 1: Sign a PDF with a Text Signature

Bir belge açın, imzayı [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) ile tanımlayın ve imzalı kopyayı kaydedin.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Belgeyi açın; with-blok, dosyayı sona erdiğinde serbest bırakır
    with Signature("sample.pdf") as signature:
        # İlk sayfanın sol ve üst kenarlarından 100 piksel uzakta bir metin imzası
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # İmzala ve sonucu yeni bir dosyaya kaydet; kaynak değişmeden kalır
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Bir belgenin zaten taşıdığı imzaları bulun. `search`, aranan her imza türü için bir seçenek içeren bir liste alır ve bunları `result.signatures` içinde döndürür.

{{< tabs \"search_document_for_signatures\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Her sayfada metin imzalarını arayın
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab "signed.pdf" >}}

`signed.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) tıklayın.

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Bir belgenin beklediğiniz imzayı taşıdığını kontrol edin. Doğrulama, tam olarak bu metne sahip bir metin imzası bulunduğunda başarılı olur.

{{< tabs \"verify_text_signature\">}}
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
{{< tab "signed.pdf" >}}

`signed.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) tıklayın.

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Her örneği, örnek dosyaların yanına kendi `.py` dosyasına kaydedin. Klasörünüz aşağıdaki gibi görünmelidir:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

O klasörden bir örnek çalıştırın:

{{< tabs \"run-the-app\">}}
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

İşiniz bittiğinde, `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakın.

## Apply a License

`GROUPDOCS_LIC_PATH` ortam değişkenini lisans dosyanızın tam yolu olarak ayarlayın; lisans, `groupdocs.signature` içe aktarıldığında otomatik olarak uygulanır. Kod gerekmez. Alternatif olarak, diğer herhangi bir çağrıdan önce kod içinde bir kez uygulayabilirsiniz:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

[Lisanslama](https://docs.groupdocs.com/signature/python-net/licensing/) konusu her iki yöntemi ve ölçülen lisansı kapsar.

## Next Steps

Temel konuları tamamladıktan sonra ek kaynakları keşfedin:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
