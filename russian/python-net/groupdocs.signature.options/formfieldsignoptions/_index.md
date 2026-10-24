---
title: "Класс FormFieldSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи FormField для PDF‑документов."
type: docs
url: /ru/python-net/groupdocs.signature.options/formfieldsignoptions/
is_root: false
weight: 180
---


## FormFieldSignOptions class

Представляет параметры подписи FormField для PDF‑документов.

Предоставляет параметры для создания или обновления подписей полей формы в PDF‑файлах.

- Basic usage of creating FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature
- Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced

Тип FormFieldSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/) | Инициализирует новый экземпляр класса PdfFormFieldSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/#signature) | Инициализирует новый экземпляр класса PdfFormFieldSignOptions с подписью FormField. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/height/) | Высота области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры; см. `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/horizontal_alignment/) | Горизонтальное выравнивание изображения на странице документа. |
| [left](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/left/) | Левая позиция X области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| [margin](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin/) | Пространство по умолчанию между изображением и краями документа (применяется, когда установлено горизонтальное или вертикальное выравнивание). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/margin_measure_type/) | Тип измерения отступа (пиксели, проценты или миллиметры). |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/rotation_angle/) | Угол вращения, измеряется по часовой стрелке. |
| [signature](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/signature/) | FormField подписи. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/stretch/) | Режим растяжения на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/top/) | Верхняя позиция Y области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType` для типа измерения местоположения. |
| [transparency](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/transparency/) | Прозрачность подписи поля формы. Значение варьируется от 0,0 до 1,0, по умолчанию 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/vertical_alignment/) | Вертикальное выравнивание изображения на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/width/) | Ширина области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры; см. `MeasureType` SizeMeasureType). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Подпись будет размещена на всех страницах документа. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Дополнительный внешний вид подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Настройки фона подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Настройки границы. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Тип документа параметров подписи (`DocumentType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Расширения подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Шрифт подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Цвет переднего плана подписи. (унаследовано от [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)) |
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
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        text_field = TextFormFieldSignature("FieldText", "Value1")
        options = FormFieldSignOptions(text_field)
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
