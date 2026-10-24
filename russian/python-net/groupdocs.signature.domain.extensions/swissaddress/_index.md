---
title: "Класс SwissAddress"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет адрес кредитора или должника."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Представляет адрес кредитора или должника.

Вы можете либо задать улицу, номер дома, почтовый индекс и город (структурированный тип адреса), либо строку адреса 1 и 2 (тип объединённых элементов адреса).

Тип SwissAddress раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | Строка адреса 1, содержащая название улицы, номер дома или почтовый ящик, является необязательной и используется только для адресов с объединёнными элементами. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | Строка адреса 2, содержащая почтовый индекс и город, обязательна для адресов с объединёнными элементами. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Двухбуквенный код страны ISO. Код страны обязателен, если только весь адрес не содержит null или пустых значений. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | Номер дома. Это поле используется только для структурированных адресов и является необязательным. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Имя, либо имя и фамилия физического лица, либо название компании юридического лица. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Почтовый индекс. Это поле используется только для структурированных адресов. Для этого типа оно обязательно. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | Улица адреса без номера дома; необязательно и используется только для структурированных адресов. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | Город или населённый пункт, используется только для структурированных адресов и обязателен для этого типа. |

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
