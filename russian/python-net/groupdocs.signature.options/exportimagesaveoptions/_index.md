---
title: "Класс ExportImageSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры сохранения для экспорта документов в изображение."
type: docs
url: /ru/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Представляет параметры сохранения для экспорта документов в изображение.

Тип ExportImageSaveOptions предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | Инициализирует новый экземпляр класса ExportAsImageSaveOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Инициализирует новый экземпляр ExportAsImageSaveOptions с указанным форматом файла. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Настройки границы изображения. По умолчанию это значение не установлено. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Флаг для экспорта каждой страницы. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Количество столбцов для экспортируемых изображений. Используйте это свойство, если нужно разместить изображения в строке. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Номер страницы документа для экспорта (минимальное значение — 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | Параметры для указания страниц, которые необходимо подписать. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Страницы документа размещаются в разных кадрах TIFF‑изображения. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию False. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Формат файла подписанного документа. (унаследовано от [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию True. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
