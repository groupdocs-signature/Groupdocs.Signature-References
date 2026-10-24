---
title: "Класс QrCodeSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи QR‑кода."
type: docs
url: /ru/python-net/groupdocs.signature.options/qrcodesignoptions/
is_root: false
weight: 480
---


## QrCodeSignOptions class

Представляет параметры подписи QR‑кода.

- Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature
- Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced

Тип QrCodeSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/) | Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text) | Инициализирует экземпляр параметров подписи QR-кода с указанным текстом. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/#text-encode_type) | Инициализирует новый экземпляр класса QrCodeSignOptions с текстом. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/code_text_alignment/) | Выравнивание текста в результирующем изображении QR-кода, значение по умолчанию — None. |
| [data](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data/) | Пользовательский объект для сериализации в содержимое QR-кода. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/data_encryption/) | Реализация шифрования данных, используемая для кодирования и декодирования текста или данных подписи QR-кода. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type/) | Тип QR‑Code. |
| [fore_color](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/fore_color/) | Цвет переднего плана полос QR‑code; использование этого свойства может вызвать проблемы с проверкой, поэтому используйте его осторожно. |
| [height](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/height/) | Высота области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры; см. `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/horizontal_alignment/) | Горизонтальное выравнивание QR‑code на странице документа. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/inner_margins/) | Пространство между элементами QR‑code и границами результирующего изображения. |
| [left](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/left/) | Левая позиция X области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств left и top. |
| [logo_file_path](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_file_path/) | Имя файла изображения логотипа QR‑code. |
| [logo_stream](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/logo_stream/) | Поток изображения логотипа QR‑code. |
| [margin](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin/) | Пространство, которое по умолчанию указывается между изображением и краями документа (работает, если указано горизонтальное или вертикальное выравнивание). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/margin_measure_type/) | Тип измерения отступа (пиксели, проценты или миллиметры). |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content/) | Флаг для получения содержимого изображения QR‑Code подписи, размещённой на странице документа. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/return_content_type/) | Тип файла возвращаемого содержимого изображения подписи QR‑Code, когда включено свойство `return_content`. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/rotation_angle/) | Угол вращения в градусах по часовой стрелке. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/stretch/) | Режим растягивания на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/top/) | Верхняя позиция Y области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). Единица определяется свойством `LocationMeasureType` типа `MeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/transparency/) | Прозрачность подписи QR‑code. Значение варьируется от 0,0 до 1,0, по умолчанию 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/vertical_alignment/) | Вертикальное выравнивание изображения на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/width/) | Ширина области подписи на странице документа в измерениях (пиксели, проценты или миллиметры, как определено `MeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Подпись будет размещена на всех страницах документа. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Дополнительный внешний вид подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Настройки фона подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Настройки границы. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Тип документа параметров подписи (`DocumentType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Расширения подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Шрифт подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Заголовок текстового поля формы, в которое помещается текстовая подпись. Может использоваться только когда `signature_implementation` установлен в `TextSignatureImplementation.FORM_FIELD`. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Тип поля формы, в которое помещается текстовая подпись. Это свойство применимо только когда `signature_implementation` установлен в `TextSignatureImplementation.FORM_FIELD` (т.е. TextToFormField). Значение по умолчанию — `FormTextFieldType.ALL_TEXT_TYPES`. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Встроенный атрибут. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Номер страницы документа для подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Параметры для указания страниц, которые необходимо подписать. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Позиция фигуры определяет, где фигура должна отображаться в макете документа. Доступно только для документов Word. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Тип фигуры для размещения текста. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Уникальный идентификатор подписи, используемый в параметрах проверки и поддерживаемый только для PDF‑документов. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Тип реализации текстовой подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Тип подписи (`SignatureType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Текст подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Горизонтальное выравнивание текста внутри подписи, поддерживается только для реализаций подписи типа Image и Annotation (см. свойство SignatureImplementation типа `TextSignatureImplementation`). (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Вертикальное выравнивание текста внутри подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Позиция Z‑порядка текстовой подписи, определяющая порядок отображения перекрывающихся подписей. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Пример

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

        signature.sign("signed.pdf", options)
```

### Guides
Руководства по задачам, использующие `QrCodeSignOptions`:

* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
