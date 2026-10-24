---
title: "Класс WordProcessingSaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет параметры сохранения для документов обработки текста."
type: docs
url: /ru/python-net/groupdocs.signature.options/wordprocessingsaveoptions/
is_root: false
weight: 650
---


## WordProcessingSaveOptions class

Представляет параметры сохранения для документов обработки текста.

Тип WordProcessingSaveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/) | Инициализирует новый экземпляр класса WordProcessingSaveOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format) | Инициализирует новый экземпляр WordProcessingSaveOptions с указанным форматом выходного файла. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#overwrite_existing_file) | Инициализирует новый экземпляр WordProcessingSaveOptions с указанным типом вывода и флагом перезаписи. |
| [__init__](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/__init__/#file_format-overwrite_existing_file) | Инициализирует новый экземпляр WordProcessingSaveOptions с указанным форматом выходного файла и флагом перезаписи. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/file_format/) | Формат файла подписанного документа. |
| [ooxml_compliance](/signature/python-net/groupdocs.signature.options/wordprocessingsaveoptions/ooxml_compliance/) | Необязательный уровень соответствия OOXML для подписанного документа. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию False. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию True. Не поддерживается для документов Image. (унаследовано от [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
