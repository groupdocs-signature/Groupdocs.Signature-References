---
title: "Класс Metered"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Управляет лицензированием с оплатой за использование."
type: docs
url: /ru/python-net/groupdocs.signature/metered/
is_root: false
weight: 40
---


## Metered class

Управляет лицензированием с оплатой за использование.

Лицензии Metered выставляют счет по фактическому потреблению (обычно страниц или
обработанных документов). Установите пару публичный/приватный ключ один раз при
запуске приложения; обёртка отправляет данные об использовании обратно в GroupDocs
лицензионный сервер в фоновом режиме.

Тип Metered раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get_consumption_credit](/signature/python-net/groupdocs.signature/metered/get_consumption_credit/) | Возвращает количество использованных кредитов до текущего момента. |
| [get_consumption_quantity](/signature/python-net/groupdocs.signature/metered/get_consumption_quantity/) | Возвращает объём обработанных данных до текущего момента. |
| [set_metered_key](/signature/python-net/groupdocs.signature/metered/set_metered_key/#public_key-private_key) | Активировать тарификацию Metered с указанной парой публичный/приватный ключ. |

### См. также
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
