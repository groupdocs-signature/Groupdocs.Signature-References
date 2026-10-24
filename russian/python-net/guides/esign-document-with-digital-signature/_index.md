---
title: "Подписать документ с помощью цифровой подписи"
linkTitle: "Digital Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Узнайте о преимуществах использования цифровых подписей для безопасного подписания документов. Откройте, как программно добавлять цифровые подписи в Python с пошаговыми инструкциями."
type: docs
url: /ru/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

В современную цифровую эпоху обеспечение подлинности и целостности электронных документов имеет решающее значение. Одним из наиболее эффективных методов достижения этой цели является использование цифровых подписей. В этом руководстве мы изучим мир цифровых подписей, объясним, что это такое, почему они важны, и как вы можете использовать GroupDocs.Signature for Python via .NET для беспрепятственного электронного подписания ваших документов.

## What is a Digital Signature?

Цифровая подпись — это криптографический механизм для проверки подлинности и целостности электронных документов. Она обеспечивает надёжную уверенность в том, что документ исходил от известного отправителя и не был изменён неавторизованными источниками. Цифровые подписи обычно представлены сертификатами, содержащими закрытый (для подписи) и открытый (для проверки) ключи. Для этой цели часто используют различные стандарты асимметричной криптографии, такие как формат PFX.
На рисунке ниже показано, как цифровая подпись выглядит на странице PDF‑документа по умолчанию.

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

Истёкшие и ещё не действительные сертификаты отклоняются: `sign` вызывает [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) с сообщением, например «Сертификат подписи истёк ...». Чтобы всё равно подписать с таким сертификатом, установите `allow_expired` или `allow_not_yet_valid` в значение `True`.

### Follow these steps to sign your documents with a digital signature

1. Установите пакет GroupDocs.Signature с помощью pip:
```bash
pip install groupdocs-signature-net
```

2. Создайте новый экземпляр класса [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) и передайте путь к исходному документу в качестве параметра конструктора.
3. Создайте объект [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) с требуемым сертификатом и его паролем.
4. Вызовите метод [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) экземпляра класса [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) и передайте ему объект [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/).

Пример ниже показывает, как подписать PDF‑документ цифровой электронной подписью с помощью Python. Мы можем подписать любой другой поддерживаемый формат документа тем же способом.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Создайте параметры цифровой подписи с файлом сертификата
        options = DigitalSignOptions("certificate.pfx")

        # Установите пароль сертификата
        options.password = "1234567890"

        # Необязательно: изображение, показывающее подпись на странице
        options.image_file_path = "signature.jpg"

        # Установите позицию подписи
        options.left = 100
        options.top = 400

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` — это пример сертификата, используемый в этом примере (пароль `1234567890`). Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), чтобы скачать его.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_digital.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Вы можете дополнительно настроить цифровую подпись с помощью дополнительных параметров: размер подписи на странице, а также контакт, причину и место, сохранённые в ней:

{{< tabs \"sign_with_digital_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Передайте сертификат и изображение внешнего вида в конструктор
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Отобразить подпись на странице в этой позиции и размере
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Информация, хранящаяся в подписи
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

`sample.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` — это пример сертификата, используемый в этом примере (пароль `1234567890`). Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), чтобы скачать его.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_digital_advanced.pdf\" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Вы также можете загрузить сертификат из потока. Держите поток открытым, пока не вернётся `sign`:

{{< tabs \"sign_with_certificate_from_stream\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Загрузите сертификат из потока
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Установить позицию и размер подписи
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

`sample.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` — это пример сертификата, используемый в этом примере (пароль `1234567890`). Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_digital_stream.pdf\" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Это руководство демонстрирует, как использовать [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) для подписи документов цифровыми подписями. В нём объясняется, как загружать документы, настраивать подписи на основе сертификатов и безопасно сохранять подписанные файлы. Также рассматриваются расширенные возможности, такие как внешний вид подписи и информация, хранящаяся в подписи. Обратитесь к связанным ресурсам для получения дополнительных сведений о процессах цифровой подписи.

## More Resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы подписать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
