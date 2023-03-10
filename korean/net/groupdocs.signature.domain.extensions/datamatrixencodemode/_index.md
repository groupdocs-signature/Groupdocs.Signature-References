---
title: DataMatrixEncodeMode
second_title: .NET API 참조용 GroupDocs.Signature
description: DataMatrix 인코더의 인코딩 모드 기본값은 Auto
type: docs
weight: 220
url: /ko/net/groupdocs.signature.domain.extensions/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

DataMatrix 인코더의 인코딩 모드, 기본값은 Auto

```csharp
public enum DataMatrixEncodeMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | DataMatrix 인코딩을 위한 최상의 인코딩 모드를 자동으로 선택합니다 |
| ASCII | `1` | byte 당 영숫자 1개 또는 숫자 2개를 인코딩합니다. |
| Full | `6` | 8비트 값을 인코딩합니다. |
| Custom | `7` | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding 에 지정된 인코딩으로 인코딩 |
| C40 | `8` | C40 인코딩을 사용합니다. 인코딩 대문자 영숫자, 소문자 및 특수 문자 |
| Text | `9` | 텍스트 인코딩을 사용합니다. 소문자 영숫자, 대문자 및 특수 문자를 인코딩합니다. |
| EDIFACT | `10` | EDIFACT 인코딩을 사용합니다. 문자당 6비트를 사용하고 숫자, 대문자 및 많은 문장 부호를 인코딩하지만 소문자는 지원하지 않습니다. |
| ANSIX12 | `11` | ANSI X12 인코딩을 사용합니다. |
| ExtendedCodetext | `12` | ExtendedCodetext 모드를 사용하면 code-text. 형식에서 인코딩 체계를 수동으로 전환할 수 있습니다. "\Encodation_scheme_name:text\Encodation_scheme_name:text". 허용되는 인코딩 체계: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. 확장 코드- 텍스트 예: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" 텍스트에서 모든 백슬래시(\)는 두 배가 되어야 합니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->