---
title: VerificationResult
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Instance untuk menyimpan hasil proses verifikasi.
type: docs
weight: 1050
url: /id/net/groupdocs.signature.domain/verificationresult/
---
## VerificationResult class

Instance untuk menyimpan hasil proses verifikasi.

```csharp
public class VerificationResult : IResult
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/verificationresult/destindocumentsize) { get; } | Mengembalikan ukuran dokumen tujuan. Untuk verifikasi variabel ini selalu berisi nol. |
| [IsValid](../../groupdocs.signature.domain/verificationresult/isvalid) { get; } | Mengembalikan true jika proses Verifikasi berhasil sebaliknya false. |
| [ProcessingTime](../../groupdocs.signature.domain/verificationresult/processingtime) { get; } | Mengembalikan waktu eksekusi proses dalam milidetik. |
| [SourceDocumentSize](../../groupdocs.signature.domain/verificationresult/sourcedocumentsize) { get; } | Mengembalikan ukuran dokumen sumber dalam byte |
| [Succeeded](../../groupdocs.signature.domain/verificationresult/succeeded) { get; } | Daftar tanda tangan yang berhasil diverifikasi[`BaseSignature`](../basesignature) . |
| [TotalSignatures](../../groupdocs.signature.domain/verificationresult/totalsignatures) { get; } | Mengembalikan total tanda tangan yang diproses |

### Lihat juga

* interface [IResult](../iresult)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
