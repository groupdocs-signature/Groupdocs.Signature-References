---
title: "FileType"
second_title: "GroupDocs.Signature for .NET API Reference"
description: "Представляет тип файла."
type: docs
weight: 610
url: /ru/net/groupdocs.signature.domain/filetype/
---
## FileType class

Представляет тип файла.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.signature.domain/filetype/extension) { get; } | Суффикс имени файла (включая точку "."), например ".doc". |
| [FileFormat](../../groupdocs.signature.domain/filetype/fileformat) { get; } | Название типа файла, например "Microsoft Word Document". |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.signature.domain/filetype/fromextension)(string) | Сопоставляет расширение файла типу файла. |
| [Equals](../../groupdocs.signature.domain/filetype/equals#equals)(FileType) | Определяет, является ли текущий [`FileType`](../filetype) тем же объектом, что и указанный [`FileType`](../filetype). |
| override [Equals](../../groupdocs.signature.domain/filetype/equals#equals_1)(object) | Определяет, является ли текущий [`FileType`](../filetype) тем же объектом, что и указанный объект. |
| override [GetHashCode](../../groupdocs.signature.domain/filetype/gethashcode)() | Возвращает хеш-код текущего объекта [`FileType`](../filetype). |
| override [ToString](../../groupdocs.signature.domain/filetype/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [GetSupportedFileTypes](../../groupdocs.signature.domain/filetype/getsupportedfiletypes)() | Получает поддерживаемые типы файлов |
| [operator ==](../../groupdocs.signature.domain/filetype/op_equality) | Определяет, являются ли два объекта [`FileType`](../filetype) одинаковыми. |
| [operator !=](../../groupdocs.signature.domain/filetype/op_inequality) | Определяет, не являются ли два объекта [`FileType`](../filetype) одинаковыми. |

## Fields

| Имя | Описание |
| --- | --- |
| static readonly [APNG](../../groupdocs.signature.domain/filetype/apng) | Animated Portable Network Graphics (.png) — растровый формат файлов изображений, использующий без потерь сжатие. Он был разработан как расширение PNG для поддержки анимации, служа альтернативой формату GIF без ограничений по авторским правам. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/apng). |
| static readonly [AZW3](../../groupdocs.signature.domain/filetype/azw3) | Документ WordPerfect (.wpd) |
| static readonly [BMP](../../groupdocs.signature.domain/filetype/bmp) | Файл растрового изображения (.bmp) используется для хранения цифровых битовых изображений. Эти изображения независимы от графического адаптера и также называются форматом файлов device independent bitmap (DIB). Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/bmp). |
| static readonly [CDR](../../groupdocs.signature.domain/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) — векторный файл рисунка, изначально создаваемый в CorelDRAW для хранения закодированных и сжатых цифровых изображений. Такой файл рисунка содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/cdr). |
| static readonly [CGM](../../groupdocs.signature.domain/filetype/cgm) | Computer Graphics Metafile (.cgm) — бесплатный, независимый от платформы, международный стандартный формат метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно-ориентированный подход и множество функций для создания изображений. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CMX](../../groupdocs.signature.domain/filetype/cmx) | Файл обмена метафайлами CorelDRAW (.cmx) |
| static readonly [CSV](../../groupdocs.signature.domain/filetype/csv) | Файл значений, разделённых запятыми (.csv) представляет собой текстовые файлы, содержащие записи данных с разделёнными запятыми значениями. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [DCM](../../groupdocs.signature.domain/filetype/dcm) | Изображение DICOM (.dcm) представляет собой цифровое изображение, которое хранит медицинскую информацию о пациентах, такую как МРТ, КТ‑сканирование и ультразвуковые изображения. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/dcm). |
| static readonly [DJVU](../../groupdocs.signature.domain/filetype/djvu) | Изображение DjVu (.djvu) — графический формат файлов, предназначенный для отсканированных документов и книг, особенно тех, которые содержат комбинацию текста, рисунков, изображений и фотографий. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/djvu). |
| static readonly [DOC](../../groupdocs.signature.domain/filetype/doc) | Документ Microsoft Word (.doc) представляет собой документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном формате файла. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.signature.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) — документ Microsoft Word 2007 или более новой версии с возможностью выполнения макросов. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.signature.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) — известный формат документов Microsoft Word. Введённый в 2007 году вместе с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого бинарного на комбинацию XML‑ и бинарных файлов. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.signature.domain/filetype/dot) | Шаблон документа Word (.dot) — файлы шаблонов, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания последующих файлов DOC или DOCX. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.signature.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) представляет собой файл шаблона, созданный в Microsoft Word 2007 или более новой версии. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.signature.domain/filetype/dotx) | Word Open XML Document Template (.dotx) — файлы шаблонов, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания последующих файлов DOCX. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.signature.domain/filetype/emf) | Enhanced Windows Metafile (.emf) представляет графические изображения независимо от устройства. Метапланы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выводном устройстве. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/emf). |
| static readonly [EPS](../../groupdocs.signature.domain/filetype/eps) | Файл Encapsulated PostScript (.eps) описывает программу языка Encapsulated PostScript, которая описывает внешний вид одной страницы. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [GIF](../../groupdocs.signature.domain/filetype/gif) | Файл Graphical Interchange Format (.gif) — это тип сильно сжатого изображения. Для каждого изображения GIF обычно допускает до 8 бит на пиксель, и в изображении допускается до 256 цветов. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/gif). |
| static readonly [GZip](../../groupdocs.signature.domain/filetype/gzip) | Сжатый архив GZip (.gz) сжимает файлы с высоким коэффициентом сжатия. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/compression/gz). |
| static readonly [JPEG](../../groupdocs.signature.domain/filetype/jpeg) | Изображение JPEG (.jpeg) — это тип формата изображения, сохраняемый методом сжатия с потерями. Получаемое изображение, как результат сжатия, представляет собой компромисс между размером хранения и качеством изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.signature.domain/filetype/jpg) | Изображение JPEG (.jpg) — это тип формата изображения, сохраняемый методом сжатия с потерями. Получаемое изображение, как результат сжатия, представляет собой компромисс между размером хранения и качеством изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/jpeg). |
| static readonly [LZip](../../groupdocs.signature.domain/filetype/lzip) | Сжатый архив LZip (.lz) сжимает файлы с высоким коэффициентом сжатия. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/compression/lz). |
| static readonly [ODG](../../groupdocs.signature.domain/filetype/odg) | Файл OpenDocument Graphic (.odg) используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.signature.domain/filetype/odp) | Файл OpenDocument Presentation (.odp) представляет формат презентаций, используемый в OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.signature.domain/filetype/ods) | Файл OpenDocument Spreadsheet (.ods) обозначает формат электронных таблиц OpenDocument, который может редактироваться пользователем. Данные хранятся в файле ODF в виде строк и столбцов. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.signature.domain/filetype/odt) | Документ OpenDocument Text (.odt) — это тип документов, создаваемых текстовыми процессорами на основе формата OpenDocument Text. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OTP](../../groupdocs.signature.domain/filetype/otp) | Шаблон презентации OpenDocument (.otp) представляет файлы шаблонов презентаций, созданные приложениями в соответствии со стандартом OASIS OpenDocument. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.signature.domain/filetype/ots) | Шаблон электронных таблиц OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.signature.domain/filetype/ott) | Шаблон документа OpenDocument (.ott) представляет шаблоны документов, генерируемые приложениями в соответствии со стандартом OpenDocument от OASIS. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [PCL](../../groupdocs.signature.domain/filetype/pcl) | Документ Printer Command Language (.pcl) |
| static readonly [PDF](../../groupdocs.signature.domain/filetype/pdf) | Файл Portable Document Format (.pdf) — это тип документа, созданный Adobe в 1990‑х годах. Цель этого формата файлов заключалась в введении стандарта представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/view/pdf). |
| static readonly [PFX](../../groupdocs.signature.domain/filetype/pfx) | Файл Personal Information Exchange (.pfx) — это защищённый паролем сертификат, часто используемый для подписи кода вашего приложения. Узнайте больше об этом формате файла [здесь](https://fileinfo.com/extension/pfx). |
| static readonly [PNG](../../groupdocs.signature.domain/filetype/png) | Файл Portable Network Graphic (.png) — это тип растрового формата изображения, использующий сжатие без потерь. Этот формат был создан как замена Graphics Interchange Format (GIF) и не имеет ограничений по авторским правам. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.signature.domain/filetype/pot) | Шаблон PowerPoint (.pot) представляет файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97‑2003. Узнайте больше об этом формате файла [здесь](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.signature.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) — это файлы шаблонов Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 и новее и содержат настройки по умолчанию, которые можно использовать для создания последующих файлов презентаций. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.signature.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) представляет шаблоны презентаций Microsoft PowerPoint, создаваемые в Microsoft PowerPoint 2007 и новее. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.signature.domain/filetype/pps) | PowerPoint Slide Show (.pps) создаются с помощью Microsoft PowerPoint для показа слайдов. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97‑2003. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.signature.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) представляет формат файлов показа слайдов с поддержкой макросов, созданный в Microsoft PowerPoint 2007 или новее. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.signature.domain/filetype/ppsx) | Файлы PowerPoint Open XML Slide Show (.ppsx) создаются с помощью Microsoft PowerPoint 2007 и новее для показа слайдов. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.signature.domain/filetype/ppt) | PowerPoint Presentation (.ppt) представляет файл PowerPoint, содержащий набор слайдов для отображения в виде слайд-шоу. Он определяет бинарный формат файлов, используемый Microsoft PowerPoint 97‑2003. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.signature.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation — это файлы презентаций с поддержкой макросов, создаваемые в Microsoft PowerPoint 2007 и более новых версиях. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.signature.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) — это файлы презентаций, созданные с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата презентаций PPT, который был бинарным, формат PPTX основан на открытом XML‑формате презентаций Microsoft PowerPoint. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.signature.domain/filetype/ps) | Файл PostScript (.ps) |
| static readonly [PSD](../../groupdocs.signature.domain/filetype/psd) | Adobe Photoshop Document (.psd) представляет собственный формат файлов Adobe Photoshop, используемый для разработки и создания графики. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/psd). |
| static readonly [RTF](../../groupdocs.signature.domain/filetype/rtf) | Rich Text Format File (.rtf) представляет метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SevenZip](../../groupdocs.signature.domain/filetype/sevenzip) | High compressed archive (.7z) — архив, сжимающий файлы и папки с высоким коэффициентом сжатия. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/page-description-language/7z). |
| static readonly [SVG](../../groupdocs.signature.domain/filetype/svg) | Scalable Vector Graphics File (.svg) — это файл масштабируемой векторной графики, использующий основанный на XML текстовый формат для описания внешнего вида изображения. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [TAR](../../groupdocs.signature.domain/filetype/tar) | Unix‑утилита для сбора одного или нескольких файлов (.tar) — это архив, который может содержать один или несколько файлов или каталогов. Узнайте больше о этом формате файлов [здесь](https://docs.fileformat.com/compression/tar/). |
| static readonly [TGA](../../groupdocs.signature.domain/filetype/tga) | Truevision TGA (.tga), также известный как TARGA, — это растровый графический формат, разработанный компанией Truevision Inc. Он поддерживает различные глубины цвета и опциональное RLE‑сжатие. Файлы TGA часто используются в видеоиграх, анимационных пайплайнах и графических приложениях для высококачественного рендеринга изображений с поддержкой опционального альфа‑канала. Узнайте больше о этом формате файлов [здесь](https://wiki.fileformat.com/image/tga). |
| static readonly [TIF](../../groupdocs.signature.domain/filetype/tif) | Tagged Image File (.tif) представляет растровые изображения, предназначенные для использования на различных устройствах, поддерживающих этот стандарт формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображений в нескольких цветовых пространствах. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.signature.domain/filetype/tiff) | Tagged Image File Format (.tiff) представляет растровые изображения, предназначенные для использования на различных устройствах, поддерживающих этот стандарт формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображений в нескольких цветовых пространствах. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.signature.domain/filetype/tsv) | Tab Separated Values File (.tsv) представляет данные, разделённые табуляциями, в формате обычного текста. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.signature.domain/filetype/txt) | Plain Text File (.txt) представляет текстовый документ, содержащий обычный текст в виде строк. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.signature.domain/filetype/unknown) | Представляет неизвестный тип файла. |
| static readonly [VCF](../../groupdocs.signature.domain/filetype/vcf) | vCard File (.vcf) — это цифровой формат файла для хранения контактной информации. Этот формат широко используется для обмена данными между популярными приложениями обмена информацией. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/email/vcf). |
| static readonly [WEBP](../../groupdocs.signature.domain/filetype/webp) | WebP Image (.webp) — современный растровый веб-формат изображения, основанный на без потерь и с потерями сжатии. Он обеспечивает такое же качество изображения, одновременно значительно уменьшая размер файла. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.signature.domain/filetype/wmf) | Windows Metafile (.wmf) представляет Microsoft Windows Metafile (WMF) для хранения как векторных, так и растровых изображений. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/image/wmf). |
| static readonly [WPD](../../groupdocs.signature.domain/filetype/wpd) | Документ WordPerfect (.wpd) |
| static readonly [XLS](../../groupdocs.signature.domain/filetype/xls) | Excel Spreadsheet (.xls) представляет Excel Binary File Format. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.signature.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) определяет Excel Binary File Format, который представляет собой набор записей и структур, описывающих содержимое рабочей книги Excel. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.signature.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) — тип файлов электронных таблиц, поддерживающих макросы. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.signature.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) — известный формат документов Microsoft Excel, представленный Microsoft вместе с выпуском Microsoft Office 2007. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.signature.domain/filetype/xlt) | Excel binary Template (.xlt) представляет Excel Template File Format. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.signature.domain/filetype/xltm) | Excel Office OpenXML file Template (.xltm) представляет Excel Template File Format. Узнайте больше о этом формате файла [здесь](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [ZIP](../../groupdocs.signature.domain/filetype/zip) | Document ZIP archive (.zip) — формат архивного файла, поддерживающий безпотерьное сжатие данных. Может содержать один или несколько файлов или каталогов. Узнайте больше о этом формате файла [здесь](https://docs.fileformat.com/compression/zip/). |

### Примечания

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
* More about how to get supported formats list in C#: [How to get supported file formats in C# code](https://docs.groupdocs.com/display/signaturenet/Get+supported+file+formats)

### См. также

* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
