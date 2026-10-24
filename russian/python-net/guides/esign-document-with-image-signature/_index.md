---
title: "Электронная подпись документа с изображением"
linkTitle: "Image Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье показано, как добавить изображение подписи на страницу документа с помощью GroupDocs.Signature для Python через .NET."
type: docs
url: /ru/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

**Изображение** в качестве подписи — это альтернативный способ представить любые данные в визуальном виде. Этот тип электронной подписи позволяет создавать пользовательские изображения с логотипом компании, инициалами отправителя, именами и т.д.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Вот шаги для создания подписи‑изображения на странице документа:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Этот пример показывает, как подписать PDF‑документ подписью‑изображением с использованием Python:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Создать параметры подписи изображения с файлом изображения
        options = ImageSignOptions("signature.jpg")

        # Установить позицию и размер подписи
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Вы можете дополнительно настроить подпись‑изображение с помощью дополнительных параметров: выравнивание и отступы, вращение, прозрачность и рамка. Когда задаётся выравнивание, оно заменяет координату `left` или `top`, а `margin` смещает подпись от края страницы.

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # Разместите подпись в правом нижнем углу страницы
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Поверните изображение и сделайте его на 20% прозрачным
        options.rotation_angle = 10
        options.transparency = 0.2

        # Нарисуйте пунктирную рамку вокруг изображения
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Вы также можете загрузить изображение подписи из потока. Держите поток открытым до тех пор, пока не вернётся `sign`:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Загрузите изображение подписи из потока
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` — это примерный файл, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg), чтобы скачать его.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Это руководство демонстрирует, как использовать [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) для добавления подписей на основе изображений в документы. Оно охватывает загрузку документа, настройку свойств подписи‑изображения (таких как размер, позиция и прозрачность) и сохранение подписанного документа. Также обсуждаются расширенные параметры настройки, например изменение внешнего вида изображения и выравнивание подписи. Для получения дополнительной информации изучите связанные ресурсы по подписанию документов.

## More Resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы бесплатно создавать подписи‑изображения и/или подписывать ваши файлы с их помощью, вы можете использовать онлайн‑приложение [Generate Image](https://products.groupdocs.app/signature/generate/image).

Чтобы подписывать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать другие онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
