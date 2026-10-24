---
title: "Поле EXTENDED_CODETEXT"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в code-text."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в code-text. Формат: \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\". Допустимые схемы кодирования: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Пример расширенного code-text: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\ doubled\\edifact:EdifactEncodedText\" Все обратные слеши (\\) должны быть удвоены в тексте.

### Значение
`12`

### См. также
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
