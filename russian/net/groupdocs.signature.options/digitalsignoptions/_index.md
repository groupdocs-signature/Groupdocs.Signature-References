---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет параметры цифровой подписи."
type: docs
weight: 1560
url: /ru/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

Представляет параметры цифровой подписи.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | Инициализирует новый экземпляр класса DigitalSignOptions со значениями по умолчанию. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и потоком изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и файлом изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и потоком изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого истек. Значение по умолчанию — false: подпись с просроченным сертификатом вызывает [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), и документ не подписывается. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | Получает или задает флаг, позволяющий подписывать с сертификатом, срок действия которого еще не начался. Значение по умолчанию — false: подпись с таким сертификатом вызывает [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception), и документ не подписывается. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Разместить подпись на всех страницах документа. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Дополнительный внешний вид подписи. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Укажите настройки границы |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Получает или задает путь к файлу цифрового сертификата. Это свойство используется только если CertificateStream не указан. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Получает или задает поток цифрового сертификата. Если это свойство указано, оно всегда используется вместо CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Получает или задает контакт подписи. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | Получает или задает пользовательскую функцию хеш‑подписи, позволяя пользователям реализовать собственную логику цифровой подписи. Это позволяет подписывать с внешними сертификатами и поддерживает различные алгоритмы хеширования. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или задать тип документа для параметров подписи [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Получает или задает алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Получает или задает путь к файлу изображения подписи. Это свойство используется только если ImageStream не указан. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Получает или задает поток изображения подписи. Если это свойство указано, оно всегда используется вместо ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Получает или задает расположение подписи. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Получает или задает расстояние между подписью и краями документа. (работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для отступа. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или задает номер страницы документа для подписи. Минимальное и значение по умолчанию — 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания страниц, которые необходимо подписать. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Получает или задает пароль цифрового сертификата. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Получает или задает причину подписи. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Прямоугольник области для размещения изображения в документе. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Определяет, где форма должна отображаться в макете документа. Доступно только для документов Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Получает или задает свойства цифровой подписи документа. Для подписи PDF‑документов можно задать расширенные свойства, используя экземпляр [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Режим растягивания на Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Верхняя позиция Y подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если вертикальное выравнивание не указано). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). Значение по умолчанию — 0 (непрозрачный). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | Получает/задает флаг проверки ltv (Long Term Validation). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Получает или задает видимость подписи. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ширина подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Тип XAdES [`XAdESType`](./xadestype). Значение по умолчанию — None (XAdES отключён). В данный момент тип подписи XAdES поддерживается только для документов Spreadsheet. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает позицию Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Очищает внутренние ресурсы |

### Примечания

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### См. также

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
