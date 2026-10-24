---
title: "SaveOptions sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir belgeyi imzalamak için kaydederken ek seçenekler (örneğin şifre) belirtir."
type: docs
url: /tr/python-net/groupdocs.signature.options/saveoptions/
is_root: false
weight: 520
---


## SaveOptions class

Bir belgeyi imzalamak için kaydederken ek seçenekler (örneğin şifre) belirtir.

SaveOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/) | SaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [__init__](/signature/python-net/groupdocs.signature.options/saveoptions/__init__/#overwrite_existing_file) | SaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklenip eklenmeyeceğini belirleyen bayrak. Varsayılan değer False'tur. |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | Yeni çıktı dosyasıyla mevcut bir dosyanın üzerine yazılıp yazılmayacağını gösteren bayrak. |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | Kaydedilen imzalı belgeyi korumak için kullanılan şifre. Görüntü belgeleri için desteklenmez. |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | İmzalı belgeyi korumalı olarak kaydederken [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) içindeki şifrenin kullanılıp kullanılmayacağını belirten bayrak. Varsayılan değer True'dır. Görüntü belgeleri için desteklenmez. |

### Ayrıca Bakınız
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
