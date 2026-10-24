---
title: "Belgeyi Dijital İmza ile İmzala"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belgeleri güvenli bir şekilde imzalamak için dijital imzaların kullanımının faydalarını öğrenin. Python'da programlı olarak dijital imzalar eklemenin adım adım talimatlarını keşfedin."
type: docs
url: /tr/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

Günümüz dijital çağında, elektronik belgelerin özgünlüğünün ve bütünlüğünün sağlanması çok önemlidir. Bunu başarmanın son derece etkili bir yöntemi dijital imzaların kullanılmasıdır. Bu kılavuzda, dijital imzaların ne olduğunu, neden gerekli olduklarını ve GroupDocs.Signature for Python via .NET'i nasıl kullanarak belgelerinizi sorunsuz bir şekilde e-imzalayabileceğinizi açıklayacağız.

## What is a Digital Signature?

Dijital imza, elektronik belgelerin özgünlüğünü ve bütünlüğünü doğrulamak için kullanılan kriptografik bir mekanizmadır. Belgenin bilinen bir göndericiden geldiğine ve yetkisiz kaynaklar tarafından değiştirilmediğine güçlü bir güvence sağlar. Dijital imzalar genellikle özel (imzalama için) ve genel (doğrulama için) anahtarları içeren sertifikalarla temsil edilir. PFX formatı gibi çeşitli açık anahtar kriptografi standartları bu amaçla yaygın olarak kullanılır.
Aşağıdaki resim, bir PDF belge sayfasında dijital imzanın varsayılan olarak nasıl göründüğünü gösterir.

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

Süresi dolmuş ve henüz geçerli olmayan sertifikalar reddedilir: `sign` [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) hatasını, "İmza sertifikası ... tarihinde süresi dolmuş" gibi bir mesajla yükseltir. Yine de bu tür bir sertifika ile imzalamak için `allow_expired` veya `allow_not_yet_valid` değerini `True` olarak ayarlayın.

### Follow these steps to sign your documents with a digital signature

1. GroupDocs.Signature paketini pip kullanarak kurun:
```bash
pip install groupdocs-signature-net
```

2. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) sınıfının yeni bir örneğini oluşturun ve kaynak belge yolunu yapıcı parametresi olarak geçirin.
3. Gerekli sertifika ve şifresiyle [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) nesnesini örnekleyin.
4. [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) sınıfı örneğinin [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) metodunu çağırın ve ona [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) nesnesini geçirin.

Aşağıdaki örnek, Python kullanarak bir PDF belgesini dijital e-imza ile nasıl imzalayacağınızı gösterir. Aynı şekilde diğer desteklenen belge formatlarını da imzalayabiliriz.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Sertifika dosyasıyla dijital imza seçenekleri oluşturun
        options = DigitalSignOptions("certificate.pfx")

        # Sertifika şifresini ayarlayın
        options.password = "1234567890"

        # İsteğe bağlı: sayfada imzayı gösteren bir görüntü
        options.image_file_path = "signature.jpg"

        # İmza konumunu ayarlayın
        options.left = 100
        options.top = 400

        # Belgeyi imzalayın ve sonucu kaydedin
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` bu örnekte kullanılan örnek sertifikadır (parola `1234567890`). İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Dijital imzayı ek seçeneklerle daha da özelleştirebilirsiniz: sayfadaki imzanın boyutu ve içinde saklanan iletişim, neden ve konum bilgileri:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Sertifikayı ve görünüm görselini yapıcıya geçirin
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # İmzayı sayfada, bu konum ve boyutta göster
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # İmzada depolanan bilgi
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

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` bu örnekte kullanılan örnek sertifikadır (parola `1234567890`). İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) tıklayın.

{{< /tab >}}
{{< tab "signature.jpg" >}}

`signature.jpg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) tıklayın.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Sertifikayı bir akıştan da yükleyebilirsiniz. `sign` döndürülene kadar akışı açık tutun:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Sertifikayı bir akıştan yükleyin
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # İmza konumunu ve boyutunu ayarlayın
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

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` bu örnekte kullanılan örnek sertifikadır (parola `1234567890`). İndirmek için [buraya](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) tıklayın.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Bu kılavuz, belgeleri dijital imzalarla imzalamak için [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) nasıl kullanılacağını gösterir. Belgelerin nasıl yükleneceğini, sertifika tabanlı imzaların nasıl yapılandırılacağını ve imzalı dosyaların güvenli bir şekilde nasıl kaydedileceğini açıklar. İmzanın görünümü ve imzada saklanan bilgiler gibi gelişmiş özellikler de ele alınmaktadır. Dijital imzalama iş akışlarıyla ilgili ek ayrıntılar için ilgili kaynaklara bakın.

## More Resources

### GitHub Examples

Yukarıdaki kodu kolayca çalıştırabilir ve GitHub örneklerimizde özelliğin nasıl çalıştığını görebilirsiniz:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Tam özellikli Python kütüphanesiyle birlikte, basit ama güçlü ücretsiz çevrimiçi uygulamalar da sunuyoruz.

PDF, Word, Excel, PowerPoint ve diğer belgeleri imzalamak için **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)** adresindeki çevrimiçi uygulamaları kullanabilirsiniz.
