---
title: "Класс Mailmark2D"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Кодирует и декодирует текст, встроенный в Royal Mail 2D Mailmark."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Кодирует и декодирует текст, встроенный в Royal Mail 2D Mailmark.

Тип Mailmark2D раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Инициализирует комбинированные данные Royal Mail Mailmark со значениями основных и вторичных данных по умолчанию. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Возвращает копию этого объекта. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | Класс элемента. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | Опциональное пространство для использования клиентом. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | Режим кодирования штрих‑кода DataMatrix. Значение по умолчанию: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | Тип 2D Mailmark определяет размер штрих‑кода Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | Свойство содержит почтовый индекс адреса доставки с DPS, который для внутренних адресов состоит из района (1‑2 символа), округа (1‑2 символа), сектора (1 символ), подразделения (2 символа) и DPS (2 символа), должен соответствовать действительному формату PAF®, и имеет максимальную длину 9 символов. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | Идентификатор полезной нагрузки штрих‑кода Royal Mail Mailmark для каждого типа продукта. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Уникальный идентификатор элемента в рамках Supply Chain ID, требуемый на каждом штрих‑коде Mailmark для уникальной иденфикации минимум 90 дней (максимальное значение: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Почтовый код возврата отправителю без DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Флаг, указывающий уровень запрашиваемой услуги возврата отправителю. Максимальная длина — 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Уникальная группа клиентов, участвующих в рассылке. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | Идентификатор страны UPU (максимальная длина: 4 символа). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | Идентификатор версии штрих‑кода, относящийся к каждому идентификатору типа информации. |

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
