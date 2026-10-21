---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет параметры подписи QRCode."
type: docs
weight: 1920
url: /ru/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

Представляет параметры подписи QR‑Code.

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | Инициализирует новый экземпляр класса QRCodeSignOptions со значениями по умолчанию. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | Инициализирует новый экземпляр класса QRCodeSignOptions с текстом. |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | Инициализирует новый экземпляр класса BarcodeSignOptions с текстом. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | Разместить подпись на всех страницах документа. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | Дополнительный внешний вид подписи. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | Получает или задает настройки фона подписи. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | Укажите настройки границы |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | Получает или задает выравнивание текста в результирующем изображении QR-кода. Значение по умолчанию — None. |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | Получает или задает пользовательский объект для сериализации в содержимое QR-кода. |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | Получает или задает реализацию интерфейса [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) для кодирования и декодирования текста подписи QR-Code или свойств данных. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | Получить или задать тип документа для параметров подписи [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | Получает или задает тип QR-Code. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | Расширения подписи. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | Получает или задает шрифт подписи. |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | Получает или задает цвет Fore полос QR-Code. Использование этого свойства может вызвать проблемы с проверкой. Используйте его осторожно. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | Получает или задает заголовок текстового поля формы для размещения в нём текстовой подписи. Это свойство может использоваться только с SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | Получает или задает тип поля формы для размещения в нём текстовой подписи. Это свойство может использоваться только с SignatureImplementation = TextToFormField. Значение по умолчанию — AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | Получает или задает алгоритм хеширования, используемый для криптографических операций. Поддерживается исключительно для цифровых подписей в PDF‑файлах. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | Высота подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | Горизонтальное выравнивание подписи на странице документа. |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | Получает или задает расстояние между элементами QR-Code и границами результирующего изображения. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | Левая позиция X подписи на странице документа в измерительных значениях (пиксели, проценты или миллиметры, см. свойство [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (работает, если горизонтальное выравнивание не указано). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Тип измерения (пиксели, проценты или миллиметры) для свойств Left и Top. |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | Получает или задает имя файла изображения логотипа QR-code. Это свойство используется только если LogoStream не указан. Использование этого свойства может вызвать проблемы с проверкой. Используйте его осторожно. |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | Получает или задает поток изображения логотипа QR-code. Если это свойство указано, оно всегда используется вместо LogoFilePath. Использование этого свойства может вызвать проблемы с проверкой. Используйте его осторожно. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | Получает или задает расстояние между подписью и краями документа. (работает ТОЛЬКО если указано горизонтальное или вертикальное выравнивание). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | Получает или задает тип измерения (пиксели, проценты или миллиметры) для отступа. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | Получает или задает родной атрибут. Если он установлен, могут использоваться подписи, специфичные для документа. Родной текстовый водяной знак для документов WordProcessing отличается от обычного, например. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | Получает или задает номер страницы документа для подписи. Минимальное и значение по умолчанию — 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | Параметры для указания страниц, которые необходимо подписать. |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | Получает или задает флаг для получения содержимого изображения QR-Code подписи, размещённой на странице документа. Если этот флаг установлен в true, содержимое изображения подписи QR-Code будет сохранять необработанные данные изображения в требуемом формате [`ReturnContentType`](./returncontenttype). По умолчанию эта опция отключена. |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | Указывает тип файла возвращаемого содержимого изображения подписи QR-Code, когда свойство ReturnContent включено. По умолчанию установлено Null. Это означает возврат содержимого изображения QR-Code в оригинальном формате. Этот формат изображения указывается в [`Format`](../../groupdocs.signature.domain/qrcodesignature/format). Возможные поддерживаемые значения: FileType.JPEG, FileType.PNG, FileType.BMP. Если указанный формат не поддерживается, будет возвращено содержимое изображения QR-Code в формате .png. |
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

* Basic usage of creating QR-Code electronic signature by GroupDocs.Signature: [How to eSign document with QR-Code signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* Advanced usage of settings of QR-Code electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with QR-Code signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### См. также

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
