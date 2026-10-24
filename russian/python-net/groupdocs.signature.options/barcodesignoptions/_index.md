---
title: "Класс BarcodeSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи штрих-кода."
type: docs
url: /ru/python-net/groupdocs.signature.options/barcodesignoptions/
is_root: false
weight: 20
---


## BarcodeSignOptions class

Представляет параметры подписи штрих-кода.

Узнать больше

- Basic usage of creating Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature
- Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings

Тип BarcodeSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/) | Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesignoptions/__init__/#text-encode_type) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [code_text_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/code_text_alignment/) | Выравнивание текста в полученном изображении штрихкода. Значение по умолчанию — None. |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type/) | Тип штрихкода. |
| [fore_color](/signature/python-net/groupdocs.signature.options/barcodesignoptions/fore_color/) | Цвет передних полос штрихкода; его использование может вызвать проблемы с проверкой, поэтому используйте его осторожно. |
| [height](/signature/python-net/groupdocs.signature.options/barcodesignoptions/height/) | Высота области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType` для типа измерения размера. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/horizontal_alignment/) | Горизонтальное выравнивание изображения на странице документа. |
| [inner_margins](/signature/python-net/groupdocs.signature.options/barcodesignoptions/inner_margins/) | Пространство между элементами штрихкода и границами результирующего изображения. |
| [left](/signature/python-net/groupdocs.signature.options/barcodesignoptions/left/) | Левая позиция X области подписи на странице документа, выраженная в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств left и top. |
| [margin](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin/) | Пространство, которое по умолчанию указывается между изображением и краями документа (применяется, когда установлено горизонтальное или вертикальное выравнивание). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/margin_measure_type/) | Тип измерения отступа (пиксели, проценты или миллиметры). |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content/) | Флаг, указывающий, следует ли получать содержимое изображения штрихкода подписи, размещённой на странице документа. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/return_content_type/) | Тип файла возвращаемого содержимого изображения подписи Barcode, когда включено свойство `return_content`. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/barcodesignoptions/rotation_angle/) | Угол вращения по часовой стрелке. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/barcodesignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/barcodesignoptions/stretch/) | Режим растягивания на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/barcodesignoptions/top/) | Верхняя позиция Y области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType` LocationMeasureType. |
| [transparency](/signature/python-net/groupdocs.signature.options/barcodesignoptions/transparency/) | Прозрачность подписи штрихкода, варьирующая от 0.0 (полностью непрозрачна) до 1.0 (полностью прозрачна); по умолчанию 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/barcodesignoptions/vertical_alignment/) | Вертикальное выравнивание изображения штрихкода на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/barcodesignoptions/width/) | Ширина области подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры), определённых `MeasureType`. |
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
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode():
    with Signature("sample.pdf") as signature:
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        background = Background()
        background.color = Color.light_yellow
        options.background = background

        border = Border()
        options.border = border

        signature.sign("signed.pdf", options)
```

### Guides
Руководства задач, использующие `BarcodeSignOptions`:

* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
