---
title: "Электронно подписать документ с подписью штрихкода"
linkTitle: "Barcode Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье объясняется, как добавить подпись штрихкода на страницу документа с различными параметрами, такими как тип штрихкода, текст штрихкода, позиционирование, выравнивание и другие визуальные настройки с помощью GroupDocs.Signature для Python через .NET"
type: docs
url: /ru/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

A **barcode** или **bar code** — это способ представления данных в визуальной, машинно‑читаемой форме. Как правило, штрихкод представляет собой изображение прямоугольной формы, состоящее из параллельных чёрных линий и белых промежутков разной ширины.
Штрихкоды используются в различных областях, где необходима быстрая идентификация — в рамках процесса покупки в розничных магазинах, на складах для отслеживания запасов и в счетах‑фактурах для помощи в бухгалтерии, а также во многих других случаях.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Штрихкоды позволяют хранить данные, связанные с продуктом, такие как даты производства и истечения срока годности, название производителя, страна происхождения и цена продукта. В настоящее время существует множество типов штрихкодов, поскольку разные компании используют различные комбинации цифр и полос в своих штрихкодах в зависимости от потребностей. С точки зрения подписи документа, Barcode может содержать различные символы (буквы, цифры или знаки) и иметь разную длину и размеры в зависимости от типа и настроек для хранения информации подписи, заголовка, темы или коротких зашифрованных данных.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Чтобы указать различные параметры для подписи Barcode, GroupDocs.Signature для Python через .NET предоставляет класс [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). Основные поля:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Ниже приведены шаги для электронного подписания документа подписью Barcode с использованием GroupDocs.Signature для Python через .NET API:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

В этом примере показано, как подписать PDF‑документ подписью Barcode с использованием Python:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Создайте параметры подписи штрихкода с текстом для кодирования
        options = BarcodeSignOptions("John Smith")

        # Установите тип штрихкода
        options.encode_type = BarcodeTypes.CODE128

        # Установите позицию и размер штрихкода
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) чтобы скачать его.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Вы можете дополнительно настроить подпись штрихкода с помощью дополнительных параметров: выравнивание и отступы, цвет полосы, позиция закодированного текста, внутренние отступы, фон, граница и прозрачность:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Передайте текст и тип штрихкода в конструктор
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Разместите штрихкод в правом нижнем углу страницы
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Цвет полосы, закодированный текст под полосами, пространство внутри границы
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Фон, граница и прозрачность
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) чтобы скачать его.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature поддерживает различные типы штрихкодов. Каждый тип принимает свой набор символов и длину, поэтому выбирайте текст, соответствующий типу. В этом примере документ подписывается четырьмя штрихкодами разных типов одним вызовом:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # Один объект параметров подписи на каждый штрихкод, размещённый один под другим
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) чтобы скачать его.

{{< /tab >}}
{{< tab "signed_barcode_types.pdf" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Это руководство демонстрирует, как использовать [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) для добавления подписей на основе штрихкодов в документы. Оно охватывает создание, настройку и применение штрихкодных подписей с поддержкой различных типов штрихкодов и параметров настройки. Для дальнейшего изучения обратитесь к связанным руководствам по информации о документах и продвинутым техникам подписания.

## More Resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы бесплатно генерировать штрихкоды и/или подписывать ваши файлы штрихкодами, вы можете воспользоваться онлайн‑приложением [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Чтобы подписывать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать другие онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
