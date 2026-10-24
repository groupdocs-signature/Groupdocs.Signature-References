---
title: "ImageSignOptions класс"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи изображения."
type: docs
url: /ru/python-net/groupdocs.signature.options/imagesignoptions/
is_root: false
weight: 250
---


## ImageSignOptions class

Представляет параметры подписи изображения.

Узнать больше:
- Basic usage of creating Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature
- Advanced usage of settings of Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced

Тип ImageSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/) | Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_file_path) | Инициализирует ImageSignOptions файлом изображения. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesignoptions/__init__/#image_stream) | Инициализирует новый экземпляр ImageSignOptions потоком изображения. |

### Методы
| Метод | Описание |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Очищает внутренние ресурсы. |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/#base_64_content) | Создаёт новый экземпляр ImageSignOptions с предопределённым изображением из строки Base64. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Настройки границы для подписи изображения. |
| [height](/signature/python-net/groupdocs.signature.options/imagesignoptions/height/) | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры; см. `MeasureType` SizeMeasureType). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/horizontal_alignment/) | Горизонтальное выравнивание подписи на странице документа. |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Путь к файлу изображения подписи, используется только если `image_stream` не указан. |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Поток изображения подписи. Если указан, он всегда используется вместо ImageFilePath. |
| [left](/signature/python-net/groupdocs.signature.options/imagesignoptions/left/) | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры). Работает, если горизонтальное выравнивание не указано. См. `MeasureType` для типа измерения положения. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств left и top. |
| [margin](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin/) | Пространство между подписью и краями документа. Работает только если указано горизонтальное или вертикальное выравнивание. |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/margin_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для отступа. |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Прямоугольник области для размещения изображения в документе. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rotation_angle/) | Угол вращения подписи на странице документа (по часовой стрелке). |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Позиция фигуры определяет, где фигура должна отображаться в макете документа. Доступно только для документов Word. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/imagesignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/imagesignoptions/stretch/) | Режим растягивания на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/imagesignoptions/top/) | Верхняя позиция Y подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры), как определено `MeasureType` LocationMeasureType. Работает, если вертикальное выравнивание не указано. |
| [transparency](/signature/python-net/groupdocs.signature.options/imagesignoptions/transparency/) | Прозрачность подписи, варьирующая от 0.0 (непрозрачная) до 1.0 (прозрачная), по умолчанию 0 (непрозрачная). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/imagesignoptions/vertical_alignment/) | Вертикальное выравнивание подписи на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/imagesignoptions/width/) | Ширина подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры `MeasureType` тип измерения размера). |
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

        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Guides
Руководства задач, использующие `ImageSignOptions`:

* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
