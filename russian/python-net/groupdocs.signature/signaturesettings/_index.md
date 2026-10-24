---
title: "Класс SignatureSettings"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет настройки для настройки поведения Signature."
type: docs
url: /ru/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Представляет настройки для настройки поведения [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Тип SignatureSettings раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Инициализирует экземпляр SignatureSettings со значениями по умолчанию. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Инициализирует экземпляр SignatureSettings со внедрённой реализацией Logger. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Культура по умолчанию, используемая при обработке документов. Значение по умолчанию — "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Флаг, указывающий, включены ли стандартные подписи метаданных документа, такие как Автор, Владелец, дата создания и дата изменения, в список метаданных. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Флаги уровней логирования, определяющие, какие типы сообщений передаются в [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Реализация логгера, используемая для записи (Ошибки, Предупреждения, Трассировки). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Флаг, определяющий, будет ли исходный документ пересохранён, когда метод Delete не имеет затронутых подписей для удаления. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Флаг, определяющий, будет ли исходный документ пересохранён, когда метод `Update` не имеет подписей для обновления. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Флаг, определяющий, включаются ли удалённые подписи в результат информации о документе. Каждый [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) имеет флаг `Deleted`, указывающий, была ли она удалена. |

### См. также
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
