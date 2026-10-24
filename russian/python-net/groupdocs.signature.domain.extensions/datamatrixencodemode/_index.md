---
title: "Класс DataMatrixEncodeMode"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Перечисление DataMatrixEncodeMode — справочник GroupDocs.Signature for Python via .NET API."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

Тип DataMatrixEncodeMode раскрывает следующие члены:

### Поля
| Поле | Описание |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Автоматически выбирает лучший режим кодирования для DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Кодирует один буквенно-цифровой или два числовых символа на байт |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Кодировать 8‑битные значения |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Кодировать с использованием кодировки, указанной в BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Использует кодировку C40. Кодирует заглавные буквенно-цифровые символы, строчные и специальные символы |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Использует кодировку Text. Кодирует строчные буквенно-цифровые символы, заглавные и специальные символы. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Использует кодировку EDIFACT. Использует шесть бит на символ, кодирует цифры, заглавные буквы и многие знаки пунктуации, но не поддерживает строчные буквы. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Использует кодировку ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в code-text. Формат: \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Допустимые схемы кодирования: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Пример расширенного code-text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\ doubled\\edifact:EdifactEncodedText\" Все обратные слеши (\\) должны быть удвоены в тексте. |

### См. также
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
