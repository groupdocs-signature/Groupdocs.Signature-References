---
title: FileType
second_title: Справочник по API GroupDocs.Signature для .NET
description: Представляет тип файла.
type: docs
weight: 450
url: /ru/net/groupdocs.signature.domain/filetype/
---
## FileType class

Представляет тип файла.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Суффикс имени файла (включая точку "."), например, ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Имя типа файла, например, "Документ Microsoft Word". |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Сопоставляет расширение файла с типом файла. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Определяет, является ли текущий[`FileType`](../filetype)такое же, как указано[`FileType`](../filetype) объект. |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Определяет, является ли текущий[`FileType`](../filetype) совпадает с указанным объектом. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Возвращает хеш-код для текущего[`FileType`](../filetype) объект. |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Извлекает поддерживаемые типы файлов |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Определяет, являются ли два[`FileType`](../filetype) объекты одинаковые. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Определяет, являются ли два[`FileType`](../filetype) объекты не одинаковы. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Файл растрового изображения (.bmp) используется для хранения растровых цифровых изображений. Эти изображения не зависят от графического адаптера и также называются форматом файла DIB, независимым от устройства. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/bmp) . |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | Векторный графический рисунок CorelDraw (.cdr) — это файл изображения векторного рисунка, изначально созданный в CorelDRAW для хранения закодированных и сжатых цифровых изображений. Такой файл чертежа содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Метафайл компьютерной графики (.cgm) — это бесплатный, независимый от платформы, международный стандартный формат метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно-ориентированный подход и множество функциональных возможностей для создания изображений. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | Файл изображения обмена метафайлами CorelDRAW (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Файл значений, разделенных запятыми (.csv), представляет собой текстовые файлы, содержащие записи данных со значениями, разделенными запятыми. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | Изображение DICOM (.dcm) представляет собой цифровое изображение, в котором хранится медицинская информация о пациентах, такая как МРТ, компьютерная томография и ультразвуковые изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | Изображение DjVu (.djvu) — это формат графического файла, предназначенный для отсканированных документов и книг, особенно тех, которые содержат сочетание текста, рисунков, изображений и фотографий. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Документ Microsoft Word (.doc) представляет собой документы, сгенерированные Microsoft Word или другими текстовыми редакторами, в двоичном формате файла. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Документ Word Open XML с поддержкой макросов (.docm) — это документ, созданный в Microsoft Word 2007 или более поздней версии с возможностью запуска макросов. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Документ Microsoft Word Open XML (.docx) — широко известный формат документов Microsoft Word. Представленный в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого двоичного файла на комбинацию XML и двоичных файлов. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Шаблон документа Word (.dot) — это файлы шаблонов, созданные Microsoft Word с предварительно отформатированными настройками для создания дополнительных файлов DOC или DOCX. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Шаблон документа Word Open XML с поддержкой макросов (.dotm) представляет собой файл шаблона, созданный с помощью Microsoft Word 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Шаблон документа Word Open XML (.dotx) — это файлы шаблонов, созданные Microsoft Word для предварительно отформатированных настроек для создания дополнительных файлов DOCX. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Расширенный метафайл Windows (.emf) представляет графические изображения независимо от устройства. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отображать сохраненное изображение после анализа на любом устройстве вывода. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/image/emf) . |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Файл Encapsulated PostScript (.eps) описывает языковую программу Encapsulated PostScript, которая описывает внешний вид отдельной страницы. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Файл графического формата обмена (.gif) представляет собой тип сильно сжатого изображения. Для каждого изображения в формате GIF обычно допускается до 8 бит на пиксель, а в изображении допускается до 256 цветов. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/gif) . |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | Изображение JPEG (.jpeg) — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Выходное изображение, полученное в результате сжатия, представляет собой компромисс между размером хранилища и качеством изображения. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | Изображение JPEG (.jpg) — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Выходное изображение, полученное в результате сжатия, представляет собой компромисс между размером хранилища и качеством изображения. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | Графический файл OpenDocument (.odg) используется приложением Draw Apache OpenOffice для хранения элементов чертежа в виде векторного изображения. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | Презентация OpenDocument (.odp) представляет собой формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | Электронная таблица OpenDocument (.ods) означает формат документа электронной таблицы OpenDocument, который может редактировать пользователь. Данные хранятся в файле ODF в виде строк и столбцов. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | Текстовый документ OpenDocument (.odt) — это тип документов, созданных с помощью приложений для обработки текстов, основанных на формате текстового файла OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | Шаблон презентации OpenDocument (.otp) представляет собой файлы шаблонов презентаций, созданные приложениями в стандартном формате OASIS OpenDocument. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | Шаблон электронной таблицы OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | Шаблон документа OpenDocument (.ott) представляет шаблоны документов, созданные приложениями в соответствии со стандартным форматом OpenDocument OASIS. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Документ языка управления принтером (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Portable Document Format File (.pdf) — это тип документа, созданный Adobe еще в 1990-х годах. Цель этого формата файла состояла в том, чтобы ввести стандарт для представления документов и других справочных материалов в формате, который не зависит от прикладного программного обеспечения, аппаратного обеспечения, а также операционной системы. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Файл масштабируемой векторной графики (.svg) — это файл скалярной векторной графики, который использует текстовый формат на основе XML для описания внешнего вида изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Portable Network Graphics (.png) — это тип файла растрового изображения, в котором используется сжатие без потерь. Этот формат файла был создан в качестве замены формата обмена графикой (GIF) и не имеет ограничений авторского права. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | Шаблон PowerPoint (.pot) представляет собой файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | Шаблон презентации PowerPoint Open XML с поддержкой макросов (.potm) — это файлы шаблонов Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются с помощью PowerPoint 2007 или более поздней версии и содержат параметры по умолчанию, которые можно использовать для создания дополнительных файлов презентаций. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | Шаблон презентации PowerPoint Open XML (.potx) представляет собой шаблон презентации Microsoft PowerPoint, созданный с помощью Microsoft PowerPoint 2007 и более поздних версий. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | Слайд-шоу PowerPoint (.pps) создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файла PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | Слайд PowerPoint Open XML с поддержкой макросов (.ppsm) представляет собой формат файла слайд-шоу с поддержкой макросов, созданный с помощью Microsoft PowerPoint 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | Файлы слайд-шоу PowerPoint Open XML (.ppsx) создаются с помощью Microsoft PowerPoint 2007 и более поздних версий для целей слайд-шоу. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | Презентация PowerPoint (.ppt) представляет собой файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | Презентация PowerPoint Open XML с поддержкой макросов — это файлы презентаций с поддержкой макросов, созданные с помощью Microsoft PowerPoint 2007 или более поздних версий. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | Презентация PowerPoint Open XML (.pptx) — это файлы презентаций, созданные с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файла презентации PPT, которая была двоичной, формат PPTX основан на формате файла презентации Microsoft PowerPoint open XML. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | Файл PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Документ Adobe Photoshop (.psd) представляет собой собственный формат файлов Adobe Photoshop, используемый для проектирования и разработки графики. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/psd) . |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Файл форматированного текста (.rtf) представляет собой метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Файл масштабируемой векторной графики (.svg) — это файл скалярной векторной графики, который использует текстовый формат на основе XML для описания внешнего вида изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Файл изображения с тегами (.tif) представляет собой растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файлов. Он способен описывать двухуровневые, полутоновые, палитры и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Формат файла изображения с тегами (.tiff) представляет растровые изображения, которые предназначены для использования на различных устройствах, соответствующих этому стандарту формата файлов. Он способен описывать двухуровневые, полутоновые, палитры и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Файл значений, разделенных табуляцией (.tsv) представляет данные, разделенные табуляцией, в текстовом формате. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Файл обычного текста (.txt) представляет собой текстовый документ, содержащий обычный текст в виде строк. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Представляет неизвестный тип файла. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | Файл vCard (.vcf) — это цифровой формат файла для хранения контактной информации. Этот формат широко используется для обмена данными между популярными приложениями для обмена информацией. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/email/vcf) . |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | Изображение WebP (.webp) — это современный формат файлов растровых веб-изображений, основанный на сжатии без потерь и с потерями. Он обеспечивает такое же качество изображения при значительном уменьшении размера изображения. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Метафайл Windows (.wmf) представляет собой метафайл Microsoft Windows (WMF) для хранения векторных и растровых изображений. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | Документ WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Электронная таблица Excel (.xls) представляет собой формат двоичного файла Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Двоичная электронная таблица Excel (.xlsb) указывает формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Электронная таблица Excel Open XML с поддержкой макросов (.xlsm) — это тип файлов электронных таблиц, поддерживающих макросы. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Электронная таблица Microsoft Excel Open XML (.xlsx) — широко известный формат документов Microsoft Excel, который был представлен корпорацией Майкрософт в выпуске Microsoft Office 2007. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Двоичный шаблон Excel (.xlt) представляет формат файла шаблона Excel. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Шаблон файла Excel Office OpenXML (.xltm) представляет формат файла шаблона Excel. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/spreadsheet/xltm) . |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Signature: [Форматы документов, поддерживаемые GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* Подробнее о том, как получить список поддерживаемых форматов в C#: [Как получить поддерживаемые форматы файлов в коде C#](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### Смотрите также

* пространство имен [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
