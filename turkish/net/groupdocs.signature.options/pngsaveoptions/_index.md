---
title: PngSaveOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Png Görüntü belgeleri için seçenekleri kaydetme.
type: docs
weight: 1480
url: /tr/net/groupdocs.signature.options/pngsaveoptions/
---
## PngSaveOptions class

Png Görüntü belgeleri için seçenekleri kaydetme.

```csharp
public sealed class PngSaveOptions : ImageSaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PngSaveOptions](pngsaveoptions)() | Varsayılan değerlerle PngSaveOptions oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Çıktı dosyası path 'de eksik olduğunda uzantıyı otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false. |
| [BitDepth](../../groupdocs.signature.options/pngsaveoptions/bitdepth) { get; set; } | Bit derinliği. |
| [ColorType](../../groupdocs.signature.options/pngsaveoptions/colortype) { get; set; } | Türünü alır veya ayarlar.[`PngColorType`](../pngcolortype) . |
| [CompressionLevel](../../groupdocs.signature.options/pngsaveoptions/compressionlevel) { get; set; } | 0-9 aralığında png görüntü sıkıştırma düzeyi, burada 9 maksimum sıkıştırma ve 0 depolama modudur. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | İmzalı belgenin dosya biçimini alır veya ayarlar. |
| [FilterType](../../groupdocs.signature.options/pngsaveoptions/filtertype) { get; set; } | Filtre türünü alır veya ayarlar[`PngFilterType`](../pngfiltertype) png dosyası kaydetme işlemi sırasında kullanılır. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Mevcut dosyanın üzerine yeni çıktı dosyası yazılıp yazılmayacağını ayarlar veya alır. Aksi takdirde, sonek olarak sayı ile yeni dosya oluşturulur. Varsayılan olarak bu değer, dosyanın üzerine yazılacağı anlamına gelen true olarak ayarlanır. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | İmzalı belgeyi parola korumalı olarak kaydetmek için parolayı alır veya ayarlar. Bu özellik Görüntü belgeleri için desteklenmez. |
| [Progressive](../../groupdocs.signature.options/pngsaveoptions/progressive) { get; set; } | Bu PngSaveOptions'ın aşamalı olup olmadığını belirten bir değer alır veya ayarlar. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan parola kullanılıp kullanılmayacağını ayarlar. Varsayılan değer true'dur. Bu özellik Görüntü belgeleri için desteklenmez. |

### Ayrıca bakınız

* class [ImageSaveOptions](../imagesaveoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->