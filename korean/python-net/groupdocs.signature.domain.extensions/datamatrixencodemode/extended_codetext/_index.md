---
title: "EXTENDED_CODETEXT 필드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "ExtendedCodetext 모드는 코드-텍스트에서 인코딩 방식을 수동으로 전환할 수 있게 합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

ExtendedCodetext 모드는 코드-텍스트에서 인코딩 방식을 수동으로 전환할 수 있게 합니다. 형식: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text". 허용되는 인코딩 방식은: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. 확장 코드-텍스트 예시: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" 모든 역슬래시(\\)는 텍스트에서 두 배로 표시되어야 합니다.

### 값
`12`

### 또 보기
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
