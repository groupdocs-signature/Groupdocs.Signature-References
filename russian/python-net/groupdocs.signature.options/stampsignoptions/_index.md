---
title: "Класс StampSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры подписи штампом."
type: docs
url: /ru/python-net/groupdocs.signature.options/stampsignoptions/
is_root: false
weight: 570
---


## StampSignOptions class

Представляет параметры подписи штампом.

Узнать больше:
- Basic usage of creating Stamp electronic signature by GroupDocs.Signature: How to eSign document with Stamp signature (https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
- Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: Advanced usage to eSign document with Stamp signature and additional settings (https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

Тип StampSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/) | Инициализирует новый экземпляр класса StampSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/stampsignoptions/__init__/#left-top-width-height) | Инициализирует новый экземпляр класса StampSignOptions с параметрами выравнивания. |

### Методы
| Метод | Описание |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Очищает внутренние ресурсы. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Создаёт новый экземпляр ImageSignOptions с предопределённым изображением из строки Base64. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background](/signature/python-net/groupdocs.signature.options/stampsignoptions/background/) | Фон штампа. |
| [background_color_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_color_crop_type/) | Тип обрезки фонового цвета подписи. |
| [background_image_crop_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/background_image_crop_type/) | Тип обрезки фонового изображения подписи. |
| [height](/signature/python-net/groupdocs.signature.options/stampsignoptions/height/) | Высота области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/horizontal_alignment/) | Горизонтальное выравнивание изображения на странице документа. |
| [inner_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/inner_lines/) | Список внутренних линий, отображаемых как набор прямоугольников. |
| [left](/signature/python-net/groupdocs.signature.options/stampsignoptions/left/) | Левая позиция X области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType` `LocationMeasureType`. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств left и top. |
| [margin](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin/) | Пространство, задаваемое по умолчанию между изображением и краями документа (работает, если указано горизонтальное или вертикальное выравнивание). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/margin_measure_type/) | Тип измерения отступа (пиксели, проценты или миллиметры). |
| [outer_lines](/signature/python-net/groupdocs.signature.options/stampsignoptions/outer_lines/) | Список внешних линий, отображаемых как концентрические круги. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/stampsignoptions/rotation_angle/) | Угол вращения по часовой стрелке. |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stamp_type](/signature/python-net/groupdocs.signature.options/stampsignoptions/stamp_type/) | Тип штампа. По умолчанию `Round`. |
| [stretch](/signature/python-net/groupdocs.signature.options/stampsignoptions/stretch/) | Режим растягивания на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/stampsignoptions/top/) | Верхняя позиция Y области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры). См. `MeasureType` `LocationMeasureType`. |
| [transparency](/signature/python-net/groupdocs.signature.options/stampsignoptions/transparency/) | Прозрачность подписи штампа. Значение варьируется от 0.0 до 1.0, по умолчанию 0. |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/stampsignoptions/vertical_alignment/) | Вертикальное выравнивание штампа на странице документа. |
| [width](/signature/python-net/groupdocs.signature.options/stampsignoptions/width/) | Ширина области подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры). Единица измерения определяется `MeasureType` SizeMeasureType. |
| [all_pages](/signature/python-net/groupdocs.signature.options/signoptions/all_pages/) | Подпись будет размещена на всех страницах документа. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [appearance](/signature/python-net/groupdocs.signature.options/signoptions/appearance/) | Дополнительный внешний вид подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [border](/signature/python-net/groupdocs.signature.options/imagesignoptions/border/) | Настройки границы для подписи изображением. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [document_type](/signature/python-net/groupdocs.signature.options/signoptions/document_type/) | Тип документа параметров подписи (`DocumentType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/signoptions/extensions/) | Расширения подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/signoptions/hash_algorithm/) | Алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [image_file_path](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_file_path/) | Путь к файлу изображения подписи, используется только если `image_stream` не указан. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [image_stream](/signature/python-net/groupdocs.signature.options/imagesignoptions/image_stream/) | Поток изображения подписи. Если указан, он всегда используется вместо ImageFilePath. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/signoptions/page_number/) | Номер страницы документа для подписи. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/signoptions/pages_setup/) | Параметры для указания страниц, которые необходимо подписать. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [rectangle](/signature/python-net/groupdocs.signature.options/imagesignoptions/rectangle/) | Прямоугольник области для размещения изображения в документе. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/imagesignoptions/shape_position/) | Позиция формы определяет, где форма должна отображаться в макете документа. Доступно только для документов Word. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [signature_type](/signature/python-net/groupdocs.signature.options/signoptions/signature_type/) | Тип подписи (`SignatureType`). (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |
| [zorder](/signature/python-net/groupdocs.signature.options/signoptions/zorder/) | Позиция Z‑порядка текстовой подписи, определяющая порядок отображения перекрывающихся подписей. (унаследовано от [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/)) |

### Пример

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import StampSignOptions

with Signature("sample.docx") as signature:
    options = StampSignOptions()
    options.left = 380
    options.top = 520
    options.width = 160
    options.height = 160
    # настраивайте дополнительные параметры штампа по мере необходимости
    signature.sign(options)
```

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
