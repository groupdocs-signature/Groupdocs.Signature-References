---
title: "DataMatrixEncodeMode 클래스"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "DataMatrixEncodeMode 열거형 — .NET API를 통한 Python용 GroupDocs.Signature 참조."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

DataMatrixEncodeMode 유형은 다음 멤버를 노출합니다:

### 필드
| 필드 | 설명 |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | DataMatrix 인코딩에 가장 적합한 인코드 모드를 자동으로 선택합니다 |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | 바이트당 하나의 영숫자 문자 또는 두 개의 숫자 문자를 인코딩합니다 |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | 8비트 값을 인코딩합니다 |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding에 지정된 인코딩으로 인코딩합니다 |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | C40 인코딩을 사용합니다. 대문자 영숫자, 소문자 및 특수 문자를 인코딩합니다 |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | 텍스트 인코딩을 사용합니다. 소문자 영숫자, 대문자 및 특수 문자를 인코딩합니다. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하며, 숫자, 대문자와 다양한 구두점을 인코딩하지만 소문자는 지원하지 않습니다. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | ANSI X12 인코딩을 사용합니다. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | ExtendedCodetext 모드는 코드-텍스트에서 인코딩 방식을 수동으로 전환할 수 있게 합니다. 형식: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text". 허용되는 인코딩 방식은: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. 확장 코드-텍스트 예시: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" 모든 역슬래시(\\)는 텍스트에서 두 배로 표시되어야 합니다. |

### 또 보기
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
