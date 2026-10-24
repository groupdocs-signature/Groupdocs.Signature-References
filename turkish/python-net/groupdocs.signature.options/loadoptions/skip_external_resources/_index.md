---
title: "skip_external_resources özelliği"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belgenin dış kaynakları yüklemesini durduran bayrak."
type: docs
url: /tr/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

Belgenin harici kaynakları yüklemesini durduran bayrak. Varsayılan değer True'dır; harici kaynaklar, [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) ile eşleşenler dışındaki kaynaklar yüklenmez.

Bir belge, bağlı görüntüler, INCLUDEPICTURE alanı ile eklenen resimler, sunumlar ve elektronik tablolardaki bağlı resimler ve bir SVG görüntüsü tarafından başvurulan görüntüler ve stil sayfaları gibi dışarıda depolanan kaynaklara başvurabilir. Böyle bir kaynağın yüklenmesi, kütüphanenin adresini talep etmesini sağlar. Güvenilmeyen belgeleri işleyen bir sunucuda, bir belge bunu kullanarak sunucunun iç adreslere istek göndermesini (sunucu‑tarafı istek sahteciliği) sağlayabilir ve bir UNC ya da `file://` yolu, Windows'un hesabın NTLM kimlik bilgilerini başka bir ana bilgisayara göndermesine neden olabilir. Çevrim dışı ya da hava boşluğu (air‑gapped) kurulumda, istekler başarısız olur ya da zaman aşımına kadar bekler.

Atlanan kaynaklar sayfa ön izlemelerinde veya görüntü olarak kaydedilen belgelerde çizilmez ve görüntü, barkod ve QR‑kod aramaları onları görmez. Bu özelliği yalnızca güvenilir belgeler için False olarak ayarlayın ve belirli adreslere izin vermeyi [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) ile tercih edin.

Ayar, arşiv içindeki belgeler dahil, kelime işlem belgeleri, sunumlar, elektronik tablolar ve SVG görüntülerine uygulanır. SVG görüntülerinde, izin verilmeyen referanslar görüntü okunmadan önce kaldırılır ve düzgün XML olmayan bir SVG görüntüsü reddedilir. Ayar, sertifika iptal kontrollerini, zaman damgası sunucularını veya lisanslamayı kontrol etmez.

Bu özellik, ters anlamı olan [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) özelliğinin yerini alır.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Ayrıca Bakınız
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
