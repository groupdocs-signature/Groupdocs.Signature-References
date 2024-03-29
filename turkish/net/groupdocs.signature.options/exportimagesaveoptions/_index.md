---
title: ExportImageSaveOptions
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Belgeleri image. olarak dışa aktarmak için kaydetme seçenekleri
type: docs
weight: 1360
url: /tr/net/groupdocs.signature.options/exportimagesaveoptions/
---
## ExportImageSaveOptions class

Belgeleri image. olarak dışa aktarmak için kaydetme seçenekleri

```csharp
public class ExportImageSaveOptions : ImageSaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor)() | Varsayılan değerlerle ExportAsImageSaveOptions sınıfının yeni bir örneğini başlatır. |
| [ExportImageSaveOptions](exportimagesaveoptions#constructor_1)(ImageSaveFileFormat) | Belirtilen dosya biçimiyle ExportAsImageSaveOptions sınıfının yeni bir örneğini başlatır. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | Çıktı dosyası path 'de eksik olduğunda uzantıyı otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false. |
| [Border](../../groupdocs.signature.options/exportimagesaveoptions/border) { get; set; } | Görüntü kenarlığı ayarlarını alır veya ayarlar. Varsayılan olarak bu değer ayarlanmamıştır. |
| [ExportAllPages](../../groupdocs.signature.options/exportimagesaveoptions/exportallpages) { get; set; } | Her sayfayı dışa aktarmak için işaretleyin. |
| [FileFormat](../../groupdocs.signature.options/imagesaveoptions/fileformat) { get; set; } | İmzalı belgenin dosya biçimini alır veya ayarlar. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | Mevcut dosyanın üzerine yeni çıktı dosyası yazılıp yazılmayacağını ayarlar veya alır. Aksi takdirde, sonek olarak sayı ile yeni dosya oluşturulur. Varsayılan olarak bu değer, dosyanın üzerine yazılacağı anlamına gelen true olarak ayarlanır. |
| [PageColumns](../../groupdocs.signature.options/exportimagesaveoptions/pagecolumns) { get; set; } | Dışa aktarılan görüntüler için sütun sayısını alır veya ayarlar. Resimleri arka arkaya koymanız gerekiyorsa bu özelliği kullanın. |
| [PageNumber](../../groupdocs.signature.options/exportimagesaveoptions/pagenumber) { get; set; } | Dışa aktarma için belge sayfa numarasını alır veya ayarlar. Minimum değer 1. 'dir. |
| [PagesSetup](../../groupdocs.signature.options/exportimagesaveoptions/pagessetup) { get; set; } | İmzalanacak sayfaları belirtmek için seçenekler. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | İmzalı belgeyi parola korumalı olarak kaydetmek için parolayı alır veya ayarlar. Bu özellik Görüntü belgeleri için desteklenmez. |
| [TiffMultipage](../../groupdocs.signature.options/exportimagesaveoptions/tiffmultipage) { get; set; } | Belge sayfalarını Tiff görüntüsünde farklı çerçevelere yerleştirin. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan parola kullanılıp kullanılmayacağını ayarlar. Varsayılan değer true'dur. Bu özellik Görüntü belgeleri için desteklenmez. |

### Ayrıca bakınız

* class [ImageSaveOptions](../imagesaveoptions)
* ad alanı [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* toplantı [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
