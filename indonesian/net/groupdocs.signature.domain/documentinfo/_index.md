---
title: DocumentInfo
second_title: GroupDocs.Signature untuk Referensi .NET API
description: Menentukan properti deskripsi dokumen.
type: docs
weight: 160
url: /id/net/groupdocs.signature.domain/documentinfo/
---
## DocumentInfo class

Menentukan properti deskripsi dokumen.

```csharp
public class DocumentInfo : IDocumentInfo
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DocumentInfo](documentinfo)() | Menginisialisasi instance baru dari[`DocumentInfo`](../documentinfo)kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BarcodeSignatures](../../groupdocs.signature.domain/documentinfo/barcodesignatures) { get; } | Kumpulan tanda tangan barcode dokumen ditambahkan atau diperbarui oleh[`Signature`](../../groupdocs.signature/signature) metode. |
| [DigitalSignatures](../../groupdocs.signature.domain/documentinfo/digitalsignatures) { get; } | Kumpulan tanda tangan digital dokumen yang ditambahkan atau diperbarui oleh[`Signature`](../../groupdocs.signature/signature) metode. |
| [FileType](../../groupdocs.signature.domain/documentinfo/filetype) { get; set; } | Jenis format file. |
| [FormFields](../../groupdocs.signature.domain/documentinfo/formfields) { get; } | Kumpulan semua Bidang Formulir yang didukung yang ada dalam dokumen. Properti ini hanya didukung untuk jenis dokumen Pdf dan Word Processing. |
| [FormFieldSignatures](../../groupdocs.signature.domain/documentinfo/formfieldsignatures) { get; } | Pengumpulan tanda tangan Bidang Formulir dokumen ditambahkan atau diperbarui oleh[`Signature`](../../groupdocs.signature/signature) metode. |
| [ImageSignatures](../../groupdocs.signature.domain/documentinfo/imagesignatures) { get; } | Koleksi tanda tangan gambar dokumen ditambahkan atau diperbarui oleh[`Signature`](../../groupdocs.signature/signature) metode. |
| [MaxPageHeight](../../groupdocs.signature.domain/documentinfo/maxpageheight) { get; set; } | Menentukan tinggi halaman maksimal. |
| [MetadataSignatures](../../groupdocs.signature.domain/documentinfo/metadatasignatures) { get; } | Kumpulan tanda tangan Metadata dokumen. |
| [PageCount](../../groupdocs.signature.domain/documentinfo/pagecount) { get; set; } | Jumlah halaman dokumen. |
| [Pages](../../groupdocs.signature.domain/documentinfo/pages) { get; set; } | Kumpulan deskripsi halaman dokumen. |
| [ProcessLogs](../../groupdocs.signature.domain/documentinfo/processlogs) { get; } | Pengumpulan proses histori dokumen seperti Sign, Update, Delete. |
| [QrCodeSignatures](../../groupdocs.signature.domain/documentinfo/qrcodesignatures) { get; } | Koleksi tanda tangan kode QR dokumen ditambahkan atau diperbarui oleh[`Signature`](../../groupdocs.signature/signature) metode. |
| [Signatures](../../groupdocs.signature.domain/documentinfo/signatures) { get; } | Koleksi dokumen semua jenis tanda tangan[`BaseSignature`](../basesignature) . |
| [Size](../../groupdocs.signature.domain/documentinfo/size) { get; set; } | Ukuran dokumen dalam bytes. |
| [TextSignatures](../../groupdocs.signature.domain/documentinfo/textsignatures) { get; } | Kumpulan tanda tangan teks dokumen. |
| [WidthForMaxHeight](../../groupdocs.signature.domain/documentinfo/widthformaxheight) { get; set; } | Menentukan lebar untuk tinggi halaman maksimal. |

### Lihat juga

* interface [IDocumentInfo](../idocumentinfo)
* ruang nama [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* perakitan [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
