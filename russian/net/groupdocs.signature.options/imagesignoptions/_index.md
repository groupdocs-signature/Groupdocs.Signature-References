---
title: ImageSignOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет параметры подписи изображения.
type: docs
weight: 1340
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
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | Инициализирует новый экземпляр класса ImageSignOptions с потоком изображений. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | Инициализирует новый экземпляр класса ImageSignOptions с файлом изображения. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Ставить подпись на все страницы документа. Это свойство можно использовать только для многокадровых форматов изображений (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Внешний вид дополнительной подписи. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Укажите настройки границ |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или установить тип документа для параметров подписи[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Высота подписи на странице документа в значениях измерения (в пикселях, процентах или миллиметрах см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Получает или задает путь к файлу изображения подписи. Это свойство используется, только если не указан ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Получает или задает поток изображения подписи. Если это свойство указано, оно всегда используется вместо ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Получает или задает расстояние между краями подписи и документа. (работает ТОЛЬКО, если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или устанавливает номер страницы документа для подписи. Минимальное значение по умолчанию: 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания подписываемых страниц. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Прямоугольник области для размещения изображения на документе. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств ширины и высоты. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Режим растяжения на странице документа. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Верхняя Y позиция подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если не указано вертикальное выравнивание). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0,0 (непрозрачная) до 1,0 (прозрачная)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ширина подписи на странице документа в значениях меры (пиксели, проценты или миллиметры)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает положение Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | Создает новый экземпляр класса ImageSignOptions с предопределенным изображением из Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Очищает внутренние ресурсы |

### Примечания

**Учить больше**

* Основное использование создания электронной подписи изображения с помощью GroupDocs.Signature: [Как подписать документ электронной подписью с подписью изображения](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* Расширенное использование настроек электронной подписи Изображение с GroupDocs.Signature: [Расширенное использование документа eSign с подписью изображения и дополнительными настройками](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### Смотрите также

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
