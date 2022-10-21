---
title: PngSaveOptions
second_title: Справочник по API GroupDocs.Signature для .NET
description: Png Параметры сохранения для документов изображений.
type: docs
weight: 1480
url: /ru/net/groupdocs.signature.options/pngsaveoptions/
---
## PngSaveOptions class

Png Параметры сохранения для документов изображений.

```csharp
public sealed class PngSaveOptions : ImageSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngSaveOptions](pngsaveoptions)() | Создает PngSaveOptions со значениями по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Получает или устанавливает флаг для автоматического добавления расширения, если оно отсутствовало в выходном файле. path Значение по умолчанию — false. |
| [BitDepth](../../groupdocs.signature.options/pngsaveoptions/bitdepth) { get; set; } | Битовая глубина. |
| [ColorType](../../groupdocs.signature.options/pngsaveoptions/colortype) { get; set; } | Получает или задает тип[`PngColorType`](../pngcolortype) . |
| [CompressionLevel](../../groupdocs.signature.options/pngsaveoptions/compressionlevel) { get; set; } | Уровень сжатия изображения png в диапазоне от 0 до 9, где 9 — максимальное сжатие , а 0 — режим сохранения. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | Получает или задает формат файла подписанного документа. |
| [FilterType](../../groupdocs.signature.options/pngsaveoptions/filtertype) { get; set; } | Получает или задает тип фильтра[`PngFilterType`](../pngfiltertype) используется во время процесса сохранения файла png. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Получает или задает, перезаписывать ли существующий файл новым выходным файлом. В противном случае будет создан новый файл с номером в качестве суффикса. По умолчанию для этого значения установлено значение true, что означает, что файл будет перезаписан. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | Получает или задает пароль для сохранения подписанного документа с защитой паролем. Это свойство не поддерживается для документов-изображений. |
| [Progressive](../../groupdocs.signature.options/pngsaveoptions/progressive) { get; set; } | Получает или задает значение, указывающее, является ли этот параметр PngSaveOptions прогрессивным. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | Получает или задает, следует ли использовать пароль из LoadOptions для сохранения подписанного документа как защищенного. Значение по умолчанию — true. Это свойство не поддерживается для документов-изображений. |

### Смотрите также

* class [ImageSaveOptions](../imagesaveoptions)
* пространство имен [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* сборка [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->