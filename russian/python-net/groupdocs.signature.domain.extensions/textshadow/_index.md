---
title: "Класс TextShadow"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Представляет свойства теней текста для текстовых подписей."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/textshadow/
is_root: false
weight: 380
---


## TextShadow class

Представляет свойства теней текста для текстовых подписей.

Результат может различаться в зависимости от типа подписи и формата документа.

TextShadow рекомендуется использовать с подписью `TextAsImage` для всех поддерживаемых типов документов, а также с простыми [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) и [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) в качестве водяного знака для таблиц (`.xslx`) и презентаций (`.pptx`).

Простой [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature/) для документов Word (`.docx`) также рекомендуется, но имеет ограниченную функциональность.

Тип TextShadow раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/__init__/) | Инициализирует TextShadow с параметрами по умолчанию. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | Получает копию этого объекта. (унаследовано от [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [angle](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/angle/) | Угол размещения тени относительно текста. Значение по умолчанию — 0. |
| [blur](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/blur/) | Размытие тени. Значение по умолчанию — 4. |
| [color](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/color/) | Цвет тени. Значение по умолчанию — Black. |
| [distance](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/distance/) | Расстояние от текста до тени. |
| [transparency](/signature/python-net/groupdocs.signature.domain.extensions/textshadow/transparency/) | Прозрачность тени. |

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
