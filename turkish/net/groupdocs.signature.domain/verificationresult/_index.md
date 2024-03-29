---
title: VerificationResult
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Doğrulama işleminin sonuçlarının tutulacağı örnek.
type: docs
weight: 1050
url: /tr/net/groupdocs.signature.domain/verificationresult/
---
## VerificationResult class

Doğrulama işleminin sonuçlarının tutulacağı örnek.

```csharp
public class VerificationResult : IResult
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/verificationresult/destindocumentsize) { get; } | Hedef belge boyutunu döndürür. Doğrulama için bu değişken her zaman sıfır içerir. |
| [IsValid](../../groupdocs.signature.domain/verificationresult/isvalid) { get; } | Doğrulama işlemi başarılıysa true, aksi takdirde false döndürür. |
| [ProcessingTime](../../groupdocs.signature.domain/verificationresult/processingtime) { get; } | İşlemin yürütme süresini milisaniye cinsinden döndürür. |
| [SourceDocumentSize](../../groupdocs.signature.domain/verificationresult/sourcedocumentsize) { get; } | Kaynak belge boyutunu bytes olarak döndürür |
| [Succeeded](../../groupdocs.signature.domain/verificationresult/succeeded) { get; } | Başarıyla doğrulanan imzaların listesi[`BaseSignature`](../basesignature) . |
| [TotalSignatures](../../groupdocs.signature.domain/verificationresult/totalsignatures) { get; } | Toplam işlenen imzaları döndürür |

### Ayrıca bakınız

* interface [IResult](../iresult)
* ad alanı [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
