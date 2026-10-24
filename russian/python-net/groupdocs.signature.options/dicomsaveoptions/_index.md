---
title: "Класс DicomSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры сохранения для DICOM‑изображений."
type: docs
url: /ru/python-net/groupdocs.signature.options/dicomsaveoptions/
is_root: false
weight: 100
---


## DicomSaveOptions class

Представляет параметры сохранения для DICOM‑изображений.

Тип DicomSaveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/__init__/) | Инициализирует DicomSaveOptions со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [xmp_entries](/signature/python-net/groupdocs.signature.options/dicomsaveoptions/xmp_entries/) | Данные XMP для DICOM. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию False. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Формат файла подписанного документа. (унаследовано от [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию True. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
