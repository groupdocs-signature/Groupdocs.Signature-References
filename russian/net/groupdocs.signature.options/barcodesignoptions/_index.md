---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет параметры подписи штрих‑кода."
type: docs
weight: 1450
url: /ru/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Представляет параметры подписи штрих‑кода.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Разместить подпись на всех страницах документа. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Дополнительный внешний вид подписи. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Получает или задает настройки фона подписи. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Укажите настройки границы |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Получает или задает выравнивание текста в результирующем изображении штрихкода. Значение по умолчанию — None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или задать тип документа для параметров подписи [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Получает или задает тип штрихкода. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Получает или задает шрифт подписи. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Получает или задает цвет передних полос штрихкода. Использование этого свойства может вызвать проблемы с проверкой. Используйте его осторожно. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Получает или задает заголовок текстового поля формы для размещения в нём текстовой подписи. Это свойство может использоваться только с SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Получает или задает тип поля формы для размещения в нём текстовой подписи. Это свойство может использоваться только с SignatureImplementation = TextToFormField. Значение по умолчанию — AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Получает или задает алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Получает или задает пространство между элементами штрихкода и границами результирующего изображения. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Получает или задает расстояние между подписью и краями документа. (работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для отступа. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Получает или задает родной атрибут. Если он установлен, могут использоваться подписи, специфичные для документа. Родной текстовый водяной знак для документов WordProcessing отличается от обычного, например. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или задает номер страницы документа для подписи. Минимальное и значение по умолчанию — 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания страниц, которые необходимо подписать. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Получает или задает флаг для получения содержимого изображения штрихкода подписи, размещённой на странице документа. Если этот флаг установлен в true, содержимое изображения штрихкода подписи будет сохранять необработанные данные изображения в требуемом формате [`ReturnContentType`](./returncontenttype). По умолчанию эта опция отключена. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Указывает тип файла возвращаемого содержимого изображения штрихкода подписи, когда свойство ReturnContent включено. По умолчанию установлено Null. Это означает возврат содержимого изображения штрихкода в оригинальном формате. Этот формат изображения задаётся в [`Format`](../../groupdocs.signature.domain/barcodesignature/format). Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP. Если указанный формат не поддерживается, будет возвращено содержимое изображения штрихкода в формате .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | Определяет, где форма должна отображаться в макете документа. Доступно только для документов Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Получает или задает тип фигуры для размещения текста. Это свойство может использоваться только с SignatureImplementation = TextStamp. Значение по умолчанию — Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Получает или задает уникальный идентификатор подписи. Его можно использовать в параметрах проверки подписи. Свойство поддерживается только для PDF‑документов. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Получает или задает тип реализации текстовой подписи. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Width и Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Режим растягивания на Document Page. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Получает или задает текст подписи. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Горизонтальное выравнивание текста внутри подписи. Эта функция поддерживается только для реализаций подписи Image и Annotation (см. свойство [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Вертикальное выравнивание текста внутри подписи. Эта функция поддерживается только для реализации подписи Image (см. свойство [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Верхняя позиция Y подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если вертикальное выравнивание не указано). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0.0 (непрозрачный) до 1.0 (прозрачный)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ширина подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает позицию Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

### Примечания

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### См. также

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
