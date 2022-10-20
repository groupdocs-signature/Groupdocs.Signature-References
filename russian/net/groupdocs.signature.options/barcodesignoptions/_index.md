---
title: BarcodeSignOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет параметры подписи штрихкода.
type: docs
weight: 1190
url: /ru/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

Представляет параметры подписи штрих-кода.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | Инициализирует новый экземпляр класса BarcodeSignOptions со значениями по умолчанию. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Поставить подпись на всех страницах документа. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Внешний вид дополнительной подписи. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Получает или задает настройки фона подписи. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Укажите настройки границ |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | Получает или задает выравнивание текста в результирующем изображении штрих-кода. Значение по умолчанию — None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или установить тип документа для параметров подписи[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | Получает или задает тип штрих-кода. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Получает или задает шрифт подписи. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | Получает или задает основной цвет штрих-кода bar Использование этого свойства может вызвать проблемы с проверкой. Используйте его осторожно. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Получает или задает заголовок поля текстовой формы для размещения в нем текстовой подписи. Это свойство можно использовать только с SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Получает или задает тип поля формы для размещения в нем текстовой подписи. Это свойство можно использовать только с SignatureImplementation = TextToFormField. Значение по умолчанию — AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Высота подписи на странице документа в значениях измерения (в пикселях, процентах или миллиметрах см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Свойство SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | Получает или задает расстояние между элементами штрих-кода и границами результирующего изображения. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Свойство LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Получает или задает расстояние между краями подписи и документа. (работает ТОЛЬКО, если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для Margin. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Получает или задает собственный атрибут. Если он установлен, могут использоваться подписи, специфичные для документа. Например, собственный текстовый водяной знак для документов WordProcessing отличается от обычного. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или устанавливает номер страницы документа для подписи. Минимальное значение по умолчанию: 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания подписываемых страниц. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | Получает или устанавливает флаг для получения содержимого изображения штрих-кода подписи, помещенной на страницу документа. Если этот флаг установлен в значение true, содержимое изображения подписи штрих-кода будет хранить необработанные данные изображения в требуемом формате.[`ReturnContentType`](./returncontenttype) . По умолчанию эта опция отключена. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | Указывает тип файла возвращаемого содержимого изображения подписи штрих-кода, когда свойство ReturnContent включено. По умолчанию установлено значение Null. Это означает возврат содержимого изображения штрих-кода в исходном формате. Этот формат изображения указан в[`Format`](../../groupdocs.signature.domain/barcodesignature/format) Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP. Если предоставленный формат не поддерживается, будет возвращено содержимое изображения штрих-кода в формате .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | Угол поворота подписи на странице документа (по часовой стрелке). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | Получает или задает тип формы для размещения текста. Это свойство можно использовать только с SignatureImplementation = TextStamp. Значение по умолчанию — Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | Получает или задает уникальный идентификатор подписи. Его можно использовать в опциях проверки подписи. Свойство поддерживается только для документов Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | Получает или задает тип реализации текстовой подписи. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | Получить тип подписи[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств ширины и высоты. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | Режим растяжения на странице документа. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | Получает или задает текст подписи. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | Горизонтальное выравнивание текста внутри подписи. Эта функция поддерживается только для реализаций подписи изображения и аннотации (см.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) Свойство реализации подписи). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | Вертикальное выравнивание текста внутри подписи. Эта функция поддерживается только для реализации подписи изображения (см.[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) свойство SignatureImplementation). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | Верхняя Y позиция подписи на странице документа в значениях измерения (пиксели, проценты или миллиметры, см.[`MeasureType`](../../groupdocs.signature.domain/measuretype)Свойство LocationMeasureType). (работает, если вертикальное выравнивание не указано). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | Получает или задает прозрачность подписи (значение от 0,0 (непрозрачная) до 1,0 (прозрачная)). Значение по умолчанию — 0 (непрозрачный). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | Вертикальное выравнивание подписи на странице документа. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | Ширина подписи на странице документа в значениях измерения (в пикселях, процентах или миллиметрах см.[`MeasureType`](../../groupdocs.signature.domain/measuretype) Свойство SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | Получает или задает положение Z-порядка текстовой подписи. Определяет порядок отображения перекрывающихся подписей. |

### Примечания

**Учить больше**

* Основное использование создания электронной подписи штрих-кода с помощью GroupDocs.Signature: [Как подписать документ электронной подписью со штрих-кодом](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Расширенное использование настроек электронной подписи штрих-кода с GroupDocs.Signature: [Расширенное использование документа eSign с подписью штрих-кода и дополнительными настройками](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### Смотрите также

* class [TextSignOptions](../textsignoptions)
* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
