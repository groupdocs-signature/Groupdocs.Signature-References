---
title: "SignatureSettings sınıfı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Signature davranışını özelleştirmek için ayarları temsil eder."
type: docs
url: /tr/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

[`Signature`](/signature/python-net/groupdocs.signature/signature/) davranışını özelleştirmek için ayarları temsil eder.

SignatureSettings türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Varsayılan değerlerle bir varsayılan SignatureSettings örneği başlatır. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Logger uygulamasıyla bir varsayılan SignatureSettings örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Belge işleme sırasında kullanılan varsayılan kültür. Varsayılan değer "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Standart belge meta verisi imzaları (Yazar, Sahip, oluşturma tarihi ve değiştirilme tarihi gibi) meta veri listesine dahil edilip edilmediğini gösteren bayrak. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Hangi tür mesajların [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/) adresine iletileceğini belirleyen günlük seviyesi bayrakları. |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Günlükleme (Hatalar, Uyarılar, İzlemeler) için kullanılan günlük kaydedici uygulaması. [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Delete yöntemi kaldırılacak etkilenmiş imza bulunmadığında kaynak belgenin yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | `Update` yöntemi güncellenecek imza bulunmadığında kaynak belgenin yeniden kaydedilip kaydedilmeyeceğini belirleyen bayrak. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Silinen imzaların belge bilgisi sonucuna dahil edilip edilmediğini belirleyen bayrak. Her [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) bir `Deleted` bayrağına sahiptir ve bu bayrak silinip silinmediğini gösterir. |

### Ayrıca Bakınız
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
