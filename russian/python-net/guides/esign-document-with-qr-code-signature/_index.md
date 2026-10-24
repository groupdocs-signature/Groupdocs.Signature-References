---
title: "Электронная подпись документа с QR‑кодом"
linkTitle: "QR Code Signature"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "В этой статье объясняется, как подписывать документы электронной подписью в виде QR‑кода на странице документа с помощью GroupDocs.Signature для Python через .NET API."
type: docs
url: /ru/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR‑код (или Quick Response code) — это тип двумерного [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/), состоящий из чёрных квадратов, расположенных в квадратной сетке на белом фоне. QR‑коды могут считываться камерами смартфонов или специализированными устройствами, предназначенными для чтения QR‑кодов — ручными сканерами, портативными терминалами, настольными сканерами, встроенными сканерами и т.д. Обычно QR‑коды содержат данные, указывающие на веб‑сайт или приложение, электронную почту, телефонные номера, идентификаторы продуктов или трекеры. Поэтому область применения QR‑кодов охватывает от общего маркетинга и идентификации товаров до управления документами.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Aztec‑код | Код DataMatrix | GS1 DataMatrix | GS1 QR‑код | QR |
| --- | --- | --- | --- | --- | --- |
| **Приложение** | * транспорт и билеты;<br> * в авиапроме для электронных посадочных талонов;<br> * в железнодорожном секторе для билетов, продаваемых онлайн и распечатываемых клиентами или отображаемых на экранах мобильных телефонов. Код сканируется ручным сканером персоналом поезда или на турникете для проверки билета.<br> * медицина — браслеты идентификации пациентов и этикетки для одноразовых лекарств и т.д. | * печатные носители, такие как этикетки и письма;<br> * промышленные инженерные цели — маркировка компонентов и т.п.;<br>  * пищевая промышленность — предотвращение неправильного упаковки и датирования пищевых продуктов; | Используется в<br> * здравоохранении;<br> * государственном секторе;<br> * промышленности.<br> Кодирует дополнительную информацию о предмете, такую как:<br> * вес;<br> * срок годности;<br> * номер партии;<br> * дата производства;<br> * и т.д. | Используется в маркетинге для кодирования дополнительной информации о предмете на упаковке | Широко используется в автомобильной промышленности и мобильных приложениях. Полезен для кодирования большого количества символов данных и конкретных URL‑адресов. |
| **Длина** | 3067 буквенно-цифровых,<br> 3832 цифровых,<br> 1914 байт | 2335 буквенно-цифровых,<br> 3116 цифровых | 2335 буквенно-цифровых,<br> 3116 цифровых,<br> 1556 байт | 7089 буквенно-цифровых,<br> 4296 цифровых,<br> 2953 байт | 4296 буквенно-цифровых,<br> 7089 цифровых,<br> 2953 байт |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

При добавлении электронной подписи QR‑кода к документу основные параметры — это текст для кодирования и [тип QR‑кода](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields), который следует указать через класс [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Ниже представлены шаги для электронной подписи документа с подписью QR‑кода:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Приведённый ниже фрагмент кода демонстрирует, как подписать PDF‑документ подписью QR‑кода с использованием Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Создайте параметры подписи QR‑кода с текстом для кодирования
        options = QrCodeSignOptions("John Smith")

        # Установите тип QR‑кода
        options.encode_type = QrCodeTypes.QR

        # Установите позицию и размер QR‑кода
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Подпишите документ и сохраните результат
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_qr_code.pdf\" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Другие типы QR‑кодов из таблицы выше задаются так же, например `QrCodeTypes.AZTEC` или `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Вот пример, показывающий, как создать более сложную подпись QR‑кода с дополнительной настройкой: выравнивание и отступы, цвет модуля, фон и граница:

{{< tabs \"sign_with_qr_code_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Передайте текст и тип QR‑code конструктору.
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Разместите QR‑code в правом нижнем углу страницы.
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Цвет модуля, фон и пунктирная рамка с небольшим отступом внутри.
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab \"signed_qr_code_advanced.pdf\" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Это руководство демонстрирует, как добавить подписи QR‑кода в документы с помощью [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Оно включает шаги по созданию подписи QR‑кода, настройке её свойств, таких как размер и кодировка, и применению её к документу. Подписи QR‑кода могут использоваться для быстрой проверки подписанного документа.

## More Resources

### GitHub Examples

Вы можете легко запустить приведённый выше код и увидеть работу функции в наших примерах на GitHub:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Вместе с полнофункциональной библиотекой Python мы предоставляем простые, но мощные бесплатные онлайн‑приложения.

Чтобы бесплатно генерировать QR‑коды и/или подписывать ваши файлы QR‑кодами, вы можете использовать онлайн‑приложение [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Чтобы подписывать PDF, Word, Excel, PowerPoint и другие документы, вы можете использовать другие онлайн‑приложения из **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
