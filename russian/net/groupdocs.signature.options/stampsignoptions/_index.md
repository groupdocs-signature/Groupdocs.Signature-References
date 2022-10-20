---
title: StampSignOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет параметры подписи штампа.
type: docs
weight: 1630
url: /ru/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

Представляет параметры подписи штампа.

```csharp
public class StampSignOptions : ImageSignOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | Инициализирует новый экземпляр класса StampSignOptions со значениями по умолчанию. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр класса StampSignOptions с параметрами выравнивания. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | Ставить подпись на все страницы документа. Это свойство можно использовать только для многокадровых форматов изображений (Tiff). |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Внешний вид дополнительной подписи. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | Получает или задает фон штампа. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | Получает или задает тип обрезки цвета фона подписи. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | Получает или задает тип обрезки фонового изображения подписи. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | Укажите настройки границ |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или установить тип документа для параметров подписи[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | Высота подписи на странице документа в значениях измерения (в пикселях, процентах или миллиметрах см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | Получает или задает путь к файлу изображения подписи. Это свойство используется, только если не указан ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | Получает или задает поток изображения подписи. Если это свойство указано, оно всегда используется вместо ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | Список внутренних линий, отображаемых в виде набора прямоугольников. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | Получает или задает расстояние между краями подписи и документа. (работает ТОЛЬКО, если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | Список внешних линий, отображаемых в виде концентрических кругов. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или устанавливает номер страницы документа для подписи. Минимальное значение по умолчанию: 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания подписываемых страниц. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | Прямоугольник области для размещения изображения на документе. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств ширины и высоты. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | Получает или задает тип штампа. Значение по умолчанию — Round. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | Режим растяжения на странице документа. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | Верхняя Y позиция подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если не указано вертикальное выравнивание). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0,0 (непрозрачная) до 1,0 (прозрачная)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | Ширина подписи на странице документа в значениях меры (пиксели, проценты или миллиметры)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает положение Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | Очищает внутренние ресурсы |

### Примечания

**Учить больше**

* Основное использование создания электронной подписи Stamp с помощью GroupDocs.Signature: [Как подписать документ электронной подписью с печатью подписи](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Расширенное использование настроек электронной подписи Stamp с GroupDocs.Signature: [Расширенное использование документа eSign с подписью Stamp и дополнительными настройками](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### Смотрите также

* class [ImageSignOptions](../imagesignoptions)
* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
