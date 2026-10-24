---
title: "Класс DigitalSignOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры цифровой подписи."
type: docs
url: /ru/python-net/groupdocs.signature.options/digitalsignoptions/
is_root: false
weight: 140
---


## DigitalSignOptions class

Представляет параметры цифровой подписи.

Узнать больше

- Basic usage of creating Digital electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature
- Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced

Тип DigitalSignOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/) | Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path) | Инициализирует новый экземпляр DigitalSignOptions с файлом сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream) | Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-image_file_path) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения внешнего вида. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_file_path-appearence_image_stream) | Инициализирует новый экземпляр DigitalSignOptions с файлом сертификата и потоком изображения внешнего вида. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-image_file_path) | Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата и файлом изображения внешнего вида. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsignoptions/__init__/#certificate_stream-appearence_image_stream) | Инициализирует новый экземпляр DigitalSignOptions с потоком сертификата и потоком изображения внешнего вида. |

### Методы
| Метод | Описание |
| :- | :- |
| [dispose](/signature/python-net/groupdocs.signature.options/imagesignoptions/dispose/) | Очищает внутренние ресурсы. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |
| [from_base64](/signature/python-net/groupdocs.signature.options/imagesignoptions/from_base64/) | Создаёт новый экземпляр ImageSignOptions с предопределённым изображением из строки Base64. (унаследовано от [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [allow_expired](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_expired/) | Флаг, позволяющий подписывать с сертификатом, срок действия которого истек. Значение по умолчанию — False; подпись с просроченным сертификатом вызывает `GroupDocsSignatureException`, и документ не подписывается. |
| [allow_not_yet_valid](/signature/python-net/groupdocs.signature.options/digitalsignoptions/allow_not_yet_valid/) | Флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался. Значение по умолчанию — False; подпись с таким сертификатом вызывает `GroupDocsSignatureException`, и документ не подписывается. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) | Путь к файлу цифрового сертификата. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) | Поток цифрового сертификата. Если это свойство указано, оно всегда используется вместо CertificateFilePath. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/) | Контакт подписи. |
| [custom_sign_hash](/signature/python-net/groupdocs.signature.options/digitalsignoptions/custom_sign_hash/) | Пользовательская функция хеш-подписания, используемая для подписи документа, позволяющая пользователям реализовать собственную логику цифровой подписи. |
| [height](/signature/python-net/groupdocs.signature.options/digitalsignoptions/height/) | Высота области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры; см. `MeasureType`). |
| [horizontal_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/horizontal_alignment/) | Горизонтальное выравнивание изображения на странице документа. |
| [left](/signature/python-net/groupdocs.signature.options/digitalsignoptions/left/) | Левая позиция X области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры, определенные `MeasureType.location_measure_type`). |
| [location](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) | Расположение подписи. |
| [location_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/location_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств left и top. |
| [margin](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin/) | Пространство, задаваемое по умолчанию между изображением и краями документа (применяется, когда указано горизонтальное или вертикальное выравнивание). |
| [margin_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/margin_measure_type/) | Тип измерения отступа (пиксели, проценты или миллиметры). |
| [password](/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) | Пароль цифрового сертификата. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) | Причина подписи. |
| [rotation_angle](/signature/python-net/groupdocs.signature.options/digitalsignoptions/rotation_angle/) | Угол вращения по часовой стрелке. |
| [signature](/signature/python-net/groupdocs.signature.options/digitalsignoptions/signature/) | Свойства цифровой подписи для документа. Для подписи PDF можно задать расширенные свойства, используя экземпляр [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/). |
| [size_measure_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/size_measure_type/) | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [stretch](/signature/python-net/groupdocs.signature.options/digitalsignoptions/stretch/) | Режим растягивания на странице документа. |
| [top](/signature/python-net/groupdocs.signature.options/digitalsignoptions/top/) | Верхняя позиция Y области подписи на странице документа в единицах измерения (пиксели, проценты или миллиметры; см. `MeasureType` `LocationMeasureType`). |
| [transparency](/signature/python-net/groupdocs.signature.options/digitalsignoptions/transparency/) | Прозрачность цифровой подписи, в диапазоне от 0.0 до 1.0. По умолчанию 0. |
| [use_ltv](/signature/python-net/groupdocs.signature.options/digitalsignoptions/use_ltv/) | Флаг проверки LTV (Long Term Validation). |
| [vertical_alignment](/signature/python-net/groupdocs.signature.options/digitalsignoptions/vertical_alignment/) | Вертикальное выравнивание изображения на странице документа. |
| [visible](/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) | Видимость подписи. |
| [width](/signature/python-net/groupdocs.signature.options/digitalsignoptions/width/) | Ширина области подписи на странице документа в измерениях (пиксели, проценты или миллиметры). Единица измерения определяется `MeasureType` через свойство SizeMeasureType. |
| [xad_es_type](/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) | Тип XAdES. Значение по умолчанию — None (XAdES отключен). |
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
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Передайте сертификат и изображение внешнего вида в конструктор
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Отобразить подпись на странице в этой позиции и размере
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Информация, хранящаяся в подписи
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```

### Guides
Руководства задач, использующие `DigitalSignOptions`:

* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
