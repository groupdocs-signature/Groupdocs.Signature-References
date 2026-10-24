---
title: "TextSignOptions класс"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры текстовой подписи."
type: docs
url: /ru/python-net/groupdocs.signature.options/textsignoptions/
is_root: false
weight: 590
---


## TextSignOptions class

Представляет параметры текстовой подписи.

Узнать больше

- Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
- Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

Тип TextSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/) | Инициализирует новый экземпляр класса TextSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsignoptions/__init__/#text) | Инициализирует новый экземпляр класса TextSignOptions с текстом. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/textsignoptions/background/) | Настройки фона подписи. |
| [border](/signature/python-net/groupdocs.signature.options/textsignoptions/border/) | Настройки границы. |
| [font](/signature/python-net/groupdocs.signature.options/textsignoptions/font/) | Шрифт подписи. |
| [fore_color](/signature/python-net/groupdocs.signature.options/textsignoptions/fore_color/) | Цвет переднего плана подписи. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_title/) | Заголовок текстового поля формы, в которое помещается текстовая подпись. Может использоваться только когда `signature_implementation` установлен в `TextSignatureImplementation.FORM_FIELD`. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textsignoptions/form_text_field_type/) | Тип поля формы, в которое помещается текстовая подпись. Это свойство применимо только когда `signature_implementation` установлен в `TextSignatureImplementation.FORM_FIELD` (т.е. TextToFormField). Значение по умолчанию — `FormTextFieldType.ALL_TEXT_TYPES`. |
| [height](/signature/python-net/groupdocs.signature.options/textsignoptions/height/) | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры). Единица измерения определяется свойством `SizeMeasureType`. |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/horizontal_alignment/) | Горизонтальное выравнивание подписи на странице документа. |
| [left](/signature/python-net/groupdocs.signature.options/textsignoptions/left/) | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, как определено свойством `MeasureType` LocationMeasureType). Работает, если горизонтальное выравнивание не указано. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств `left` и `top`. |
| [margin](/signature/python-net/groupdocs.signature.options/textsignoptions/margin/) | Пространство между подписью и краями документа. Применяется только когда указано горизонтальное или вертикальное выравнивание. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/margin_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для отступа. |
| [native](/signature/python-net/groupdocs.signature.options/textsignoptions/native/) | Встроенный атрибут. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/textsignoptions/rotation_angle/) | Угол вращения подписи на странице документа (по часовой стрелке). |
| [shape_position](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_position/) | Позиция фигуры определяет, где фигура должна отображаться в макете документа. Доступно только для документов Word. |
| [shape_type](/signature/python-net/groupdocs.signature.options/textsignoptions/shape_type/) | Тип фигуры для размещения текста. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_id/) | Уникальный идентификатор подписи, используемый в параметрах проверки и поддерживается только для PDF‑документов. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsignoptions/signature_implementation/) | Тип реализации текстовой подписи. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/textsignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/textsignoptions/stretch/) | Режим растяжения на странице документа. |
| [text](/signature/python-net/groupdocs.signature.options/textsignoptions/text/) | Текст подписи. |
| [text_horizontal_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_horizontal_alignment/) | Горизонтальное выравнивание текста внутри подписи, поддерживается только для реализаций подписи Image и Annotation (см. свойство `TextSignatureImplementation` SignatureImplementation). |
| [text_vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/text_vertical_alignment/) | Вертикальное выравнивание текста внутри подписи. |
| [top](/signature/python-net/groupdocs.signature.options/textsignoptions/top/) | Верхняя позиция Y подписи на странице документа, выраженная в единицах измерения (пиксели, проценты или миллиметры). |
| [transparency](/signature/python-net/groupdocs.signature.options/textsignoptions/transparency/) | Прозрачность подписи, число с плавающей точкой от 0.0 (непрозрачная) до 1.0 (прозрачная). По умолчанию 0.0 (непрозрачная). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/textsignoptions/vertical_alignment/) | Вертикальное выравнивание подписи на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/textsignoptions/width/) | Ширина подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры; см. свойства `MeasureType` `SizeMeasureType`). |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Подпись будет размещена на всех страницах документа. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Дополнительный внешний вид подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Тип документа параметров подписи (`DocumentType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Расширения подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Номер страницы документа для подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Параметры для указания страниц, которые необходимо подписать. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Тип подписи (`SignatureType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Позиция Z‑порядка текстовой подписи, определяющая порядок отображения перекрывающихся подписей. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Руководства задач, использующие `TextSignOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
