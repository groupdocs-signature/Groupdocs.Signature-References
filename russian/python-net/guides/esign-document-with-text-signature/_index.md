---
title: "Электронный документ с текстовой подписью"
linkTitle: "Text Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье объясняется, как подписать документ текстовой подписью с использованием GroupDocs.Signature for Python via .NET API. Узнайте, как добавить цифровую подпись в PDF программно на Python."
type: docs
url: /ru/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Электронная подпись **Text** — это произвольный текст, который добавляется в документ естественным способом в зависимости от типа документа. GroupDocs.Signature предоставляет возможность создания текстовой подписи и позволяет настраивать широкий спектр параметров текста — от названия шрифта, размера и цвета до выравнивания, границ, эффектов тени и т.д. Вот как может выглядеть текстовая подпись:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Попробуем добавить текстовую подпись в PDF программно с помощью Python.

Для программного управления текстовыми подписями [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) предоставляет класс [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions), и весь процесс выглядит так:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

В этом примере показано, как добавить текстовую подпись в документ с помощью Python:

{{< tabs \"sign_with_text_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Создайте параметры текстовой подписи
        options = TextSignOptions("John Smith")

        # Установить позицию и размер подписи
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Установите цвет текста и шрифт
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) для его загрузки.

{{< /tab >}}
{{< tab \"signed_text.pdf\" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Вы можете дополнительно настроить текстовую подпись с помощью дополнительных параметров: выравнивание и отступы, стиль шрифта, фон, граница, вращение и прозрачность. Когда задаётся выравнивание, оно заменяет координату `left` или `top`, а `margin` смещает подпись от края страницы.

{{< tabs \"sign_with_text_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # Разместите подпись в правом нижнем углу страницы
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Стиль шрифта и цвет текста
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Фон, граница, вращение и прозрачность
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # Отобразить текст как изображение, что также рисует границу на страницах PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) для его загрузки.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Это руководство объясняет, как добавить текстовые подписи в документы с помощью [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Оно охватывает настройку свойств текста, таких как шрифт, цвет, размер и позиция, а также применение текстовой подписи к документу. Затем подписанный документ сохраняется с добавленной текстовой подписью.

## More Resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы подписать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
