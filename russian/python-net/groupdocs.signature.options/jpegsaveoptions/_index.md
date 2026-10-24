---
title: "Класс JpegSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры сохранения JPEG для графических документов."
type: docs
url: /ru/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

Представляет параметры сохранения JPEG для графических документов.

Тип JpegSaveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | Инициализирует JpegSaveOptions со значениями по умолчанию. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | Количество битов на канал для без потерь JPEG‑изображения. Поддерживаемые значения находятся в диапазоне от 2 до 8 битов на канал. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | Тип цвета для JPEG‑изображения. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | Комментарий к файлу JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | Тип сжатия. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | Качество изображения. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | Режим округления образца, используемый для приведения 8‑битного значения к n‑битному значению `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию False. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | Формат файла подписанного документа. (унаследовано от [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию True. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
