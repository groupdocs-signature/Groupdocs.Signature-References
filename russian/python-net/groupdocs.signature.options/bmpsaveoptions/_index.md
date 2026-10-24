---
title: "Класс BmpSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры сохранения BMP для графических документов."
type: docs
url: /ru/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

Представляет параметры сохранения BMP для графических документов.

Тип BmpSaveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | Инициализирует BmpSaveOptions со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | Количество бит на пиксель изображения. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | Сжатие. См. `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | Горизонтальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от установленного значения. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | Вертикальное разрешение; обратите внимание, что из‑за округления полученное разрешение может немного отличаться от установленного значения. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию False. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Формат файла подписанного документа. (унаследовано от [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию True. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
