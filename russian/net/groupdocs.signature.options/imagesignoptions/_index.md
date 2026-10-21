---
title: "ImageSignOptions"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет параметры подписи изображения."
type: docs
weight: 1670
url: /ru/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

Представляет параметры подписи изображения.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | Инициализирует новый экземпляр класса ImageSignOptions со значениями по умолчанию. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Инициализирует новый экземпляр класса ImageSignOptions с потоком изображения. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Инициализирует новый экземпляр класса ImageSignOptions с файлом изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Разместить подпись на всех страницах документа. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Дополнительный внешний вид подписи. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Укажите настройки границы |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или задать тип документа для параметров подписи [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Получает или задает алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Получает или задает путь к файлу изображения подписи. Это свойство используется только если ImageStream не указан. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Получает или задает поток изображения подписи. Если это свойство указано, оно всегда используется вместо ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Получает или задает расстояние между подписью и краями документа. (работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для отступа. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или задает номер страницы документа для подписи. Минимальное и значение по умолчанию — 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания страниц, которые необходимо подписать. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Прямоугольник области для размещения изображения в документе. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | Определяет, где форма должна отображаться в макете документа. Доступно только для документов Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Режим растягивания на Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Верхняя позиция Y подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если вертикальное выравнивание не указано). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ширина подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает позицию Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Создаёт новый экземпляр класса ImageSignOptions с предопределённым изображением из Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Очищает внутренние ресурсы |

### Примечания

**Learn more**

* Basic usage of creating Image electronic signature by GroupDocs.Signature: [How to eSign document with Image signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Advanced usage of settings of Image electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Image signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### См. также

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
