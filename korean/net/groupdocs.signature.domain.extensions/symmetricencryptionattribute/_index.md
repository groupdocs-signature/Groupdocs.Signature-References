---
title: SymmetricEncryptionAttribute
second_title: .NET API 참조용 GroupDocs.Signature
description: 객체 직렬화 문자열을 암호화/암호 해독하도록 인스턴스 직렬화에 지시합니다.
type: docs
weight: 390
url: /ko/net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/
---
## SymmetricEncryptionAttribute class

객체 직렬화 문자열을 암호화/암호 해독하도록 인스턴스 직렬화에 지시합니다.

```csharp
[AttributeUsage(AttributeTargets.Class | AttributeTargets.Struct)]
public sealed class SymmetricEncryptionAttribute : Attribute, IDataEncryption
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor)(SymmetricAlgorithmType, string) | 매개변수와 기본 암호로 대칭 알고리즘을 생성합니다. |
| [SymmetricEncryptionAttribute](symmetricencryptionattribute#constructor_1)(SymmetricAlgorithmType, string, string) | 매개변수로 대칭 알고리즘을 생성합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Decode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/decode)(string) | 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 전달된 문자열을 해독합니다 |
| [Encode](../../groupdocs.signature.domain.extensions/symmetricencryptionattribute/encode)(string) | 제공된 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 문자열을 암호화합니다 |

### 또한보십시오

* interface [IDataEncryption](../idataencryption)
* 네임스페이스 [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->