---
title: DigitalSignOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет параметры цифровой подписи.
type: docs
weight: 1260
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
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | Инициализирует новый экземпляр класса DigitalSignOptions потоком сертификата. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и потоком изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | Инициализирует новый экземпляр класса DigitalSignOptions с потоком сертификата и файлом изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и потоком изображения. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | Инициализирует новый экземпляр класса DigitalSignOptions с файлом сертификата и файлом изображения. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Ставить подпись на все страницы документа. Это свойство можно использовать только для многокадровых форматов изображений (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Внешний вид дополнительной подписи. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Укажите настройки границ |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | Получает или задает путь к файлу цифрового сертификата. Это свойство используется, только если не указан CertificateStream. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | Получает или устанавливает поток цифровых сертификатов. Если это свойство указано, оно всегда используется вместо CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | Получает или задает контакт подписи. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или установить тип документа для параметров подписи[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Высота подписи на странице документа в значениях измерения (в пикселях, процентах или миллиметрах см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Получает или задает путь к файлу изображения подписи. Это свойство используется, только если не указан ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Получает или задает поток изображения подписи. Если это свойство указано, оно всегда используется вместо ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | Получает или задает расположение подписи. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Получает или задает расстояние между краями подписи и документа. (работает ТОЛЬКО, если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или устанавливает номер страницы документа для подписи. Минимальное значение по умолчанию: 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания подписываемых страниц. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | Получает или устанавливает пароль цифрового сертификата. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | Получает или устанавливает причину подписи. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Прямоугольник области для размещения изображения на документе. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | Получает или задает свойства цифровой подписи документа. Для подписи документов Pdf можно установить дополнительные свойства с помощью экземпляра[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств ширины и высоты. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Режим растяжения на странице документа. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Верхняя Y позиция подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если не указано вертикальное выравнивание). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0,0 (непрозрачная) до 1,0 (прозрачная)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | Получает или устанавливает видимость подписи. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ширина подписи на странице документа в значениях меры (пиксели, проценты или миллиметры)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | Тип XAdES[`XAdESType`](./xadestype) . Значение по умолчанию — None (XAdES выключен). На данный момент тип подписи XAdES поддерживается только для электронных таблиц. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает положение Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Очищает внутренние ресурсы |

### Примечания

**Учить больше**

* Базовое использование для создания ЭЦП с помощью GroupDocs.Signature: [Как подписать документ электронной цифровой подписью](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Расширенное использование настроек ЭЦП с GroupDocs.Signature: [Расширенное использование документа eSign с цифровой подписью и дополнительными настройками](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### Смотрите также

* class [ImageSignOptions](../imagesignoptions)
* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
