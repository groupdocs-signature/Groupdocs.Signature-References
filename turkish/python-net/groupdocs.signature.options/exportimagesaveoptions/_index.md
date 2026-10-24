---
title: "ExportImageSaveOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belgeleri görüntüye dışa aktarmak için kaydetme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

Belgeleri görüntüye dışa aktarmak için kaydetme seçeneklerini temsil eder.

ExportImageSaveOptions türü aşağıdaki üyeleri içerir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | ExportAsImageSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | Belirtilen dosya biçimiyle ExportAsImageSaveOptions sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | Görüntü kenar ayarları. Varsayılan olarak bu değer ayarlanmamıştır. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | Her sayfayı dışa aktarmak için bayrak. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | Dışa aktarılan görüntüler için sütun sayısı. Görüntüleri bir satırda yerleştirmeniz gerekiyorsa bu özelliği kullanın. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | Dışa aktarma için belge sayfa numarası (minimum değer 1'dir). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | İmzalanacak sayfaları belirtmek için seçenekler. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | Belge sayfaları bir TIFF görüntüsünde farklı çerçevelere yerleştirilir. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklenip eklenmeyeceğini belirleyen bayrak. Varsayılan değer False'tir. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | İmzalı belgenin dosya formatı. ([`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/) üzerinden devralınmıştır) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Mevcut bir dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını gösteren bayrak. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kaydedilen imzalı belgeyi korumak için kullanılan şifre. Görüntü belgeleri için desteklenmez. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | İmzalı belgeyi korumalı olarak kaydederken [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) içindeki şifrenin kullanılıp kullanılmayacağını gösteren bayrak. Varsayılan değer True'tir. Görüntü belgeleri için desteklenmez. ([`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) üzerinden devralınmıştır) |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
