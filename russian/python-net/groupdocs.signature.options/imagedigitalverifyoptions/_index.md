---
title: "Класс ImageDigitalVerifyOptions"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Содержит параметры для проверки цифровых подписей в растровых изображениях."
type: docs
url: /ru/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

Содержит параметры для проверки цифровых подписей в растровых изображениях.

Тип ImageDigitalVerifyOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | Инициализирует новый экземпляр класса ImageDigitalVerifyOptions для проверки цифровых (стеганографических) подписей в растровых изображениях. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | Вероятность, возвращаемая методом AnalyzePercentageDigitalSignature (0‑100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | Процент порога обнаружения для частичного извлечения (0‑100). По умолчанию 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | Пароль, использованный для встраивания подписи. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | Свойство определяет, выполняется ли полное извлечение данных (AnalyzePercentageDigitalSignature) для максимальной точности. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | Флаг, указывающий, должна ли проверяться каждая страница документа. По умолчанию значение True. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | Дополнительные расширения для проверки альтернативных параметров подписи. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | Флаг свойства valid. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | Номер страницы документа, подлежащей проверке; если не задан, проверяются все страницы документа при первом вхождении (минимальное значение 1). (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | Параметры страниц для указания страниц, подлежащих проверке. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | Позиция фигуры в макете документа, используемая для проверки подписей в заголовках/колонтитулах. (унаследовано от [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### См. также
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
