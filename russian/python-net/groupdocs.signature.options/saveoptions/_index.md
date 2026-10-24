---
title: "Класс SaveOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Указывает дополнительные параметры (например, пароль) при сохранении документа для подписи."
type: docs
url: /ru/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Указывает дополнительные параметры (например, пароль) при сохранении документа для подписи.

Тип SaveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | Инициализирует новый экземпляр класса SaveOptions со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | Инициализирует новый экземпляр класса SaveOptions с указанным типом вывода и флагом перезаписи. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Флаг, определяющий, следует ли автоматически добавлять расширение, если оно отсутствует в пути выходного файла. Значение по умолчанию — False. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Флаг, указывающий, следует ли перезаписать существующий файл новым выходным файлом. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Пароль, используемый для защиты сохранённого подписанного документа. Не поддерживается для документов Image. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | Флаг, указывающий, следует ли использовать пароль из [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) при сохранении подписанного документа как защищённого. Значение по умолчанию — True. Не поддерживается для документов Image. |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
