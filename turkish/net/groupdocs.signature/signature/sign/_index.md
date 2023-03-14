---
title: Sign
second_title: .NET API Başvurusu için GroupDocs.Signature
description: ile belgeyi imzalarSignOptionsgroupdocs.signature.options/signoptions ve sonucu bir akışa kaydeder.
type: docs
weight: 160
url: /tr/net/groupdocs.signature/signature/sign/
---
## Sign(Stream, SignOptions) {#sign}

ile belgeyi imzalar[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, SignOptions signOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Çıktı belge akışı. |
| signOptions | SignOptions | İmza seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(Stream, SignOptions, SaveOptions) {#sign_1}

ile belgeyi imzalar[`SignOptions`](../../../groupdocs.signature.options/signoptions)ve sonucu önceden tanımlanmış bir akışa kaydeder[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Çıktı belge akışı. |
| signOptions | SignOptions | İmza seçenekleri. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)
* Elektronik olarak imzalanmış belgeleri kaydetme ve kaydetme sürecini özelleştirme hakkında daha fazla bilgi: [Elektronik olarak imzalanmış belgeler, GroupDocs.Signature kullanılarak kaydedilirken nasıl özelleştirilir?](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;) {#sign_2}

Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu bir akışa kaydeder.

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Çıktı belge akışı. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(Stream, List&lt;SignOptions&gt;, SaveOptions) {#sign_3}

Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../../groupdocs.signature.options/signoptions)ve sonucu önceden tanımlanmış bir akışa kaydeder[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(Stream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Çıktı belge akışı. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)
* Elektronik olarak imzalanmış belgeleri kaydetme ve kaydetme sürecini özelleştirme hakkında daha fazla bilgi: [Elektronik olarak imzalanmış belgeler, GroupDocs.Signature kullanılarak kaydedilirken nasıl özelleştirilir?](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions) {#sign_4}

ile belgeyi imzalar[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu belirtilen dosya yoluna kaydeder.

```csharp
public SignResult Sign(string filePath, SignOptions signOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Çıkış dosyası yolu. |
| signOptions | SignOptions | İmza seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(string, SignOptions, SaveOptions) {#sign_5}

ile belgeyi imzalar[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış dosya yoluna kaydeder[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, SignOptions signOptions, SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Çıkış dosyası yolu. |
| signOptions | SignOptions | İmza seçenekleri. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)
* Elektronik olarak imzalanmış belgeleri kaydetme ve kaydetme sürecini özelleştirme hakkında daha fazla bilgi: [Elektronik olarak imzalanmış belgeler, GroupDocs.Signature kullanılarak kaydedilirken nasıl özelleştirilir?](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;) {#sign_6}

Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu belirtilen dosya yoluna kaydeder.

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Çıkış dosyası yolu. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Sign(string, List&lt;SignOptions&gt;, SaveOptions) {#sign_7}

Belgeyi şu koleksiyonla imzalar:[`SignOptions`](../../../groupdocs.signature.options/signoptions) ve sonucu önceden tanımlanmış dosya yoluna kaydeder[`SaveOptions`](../../../groupdocs.signature.options/saveoptions) .

```csharp
public SignResult Sign(string filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Çıkış dosyası yolu. |
| signOptionsList | List`1 | İmza seçeneklerinin listesi. |
| saveOptions | SaveOptions | Kaydetme seçenekleri. |

### Geri dönüş değeri

örneğini döndürür[`SignResult`](../../../groupdocs.signature.domain/signresult) yeni oluşturulan imzaların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen elektronik imza türleri hakkında daha fazla bilgi. İmza: [GroupDocs.Signature tarafından desteklenen elektronik imza türleri](https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types)
* C#: 'de belgelerin eSign ile nasıl imzalanacağı hakkında daha fazla bilgi[GroupDocs.Signature kullanarak belgelere e-Sign nasıl yapılır?](https://docs.groupdocs.com/display/signaturenet/Signing)
* Elektronik olarak imzalanmış belgeleri kaydetme ve kaydetme sürecini özelleştirme hakkında daha fazla bilgi: [Elektronik olarak imzalanmış belgeler, GroupDocs.Signature kullanılarak kaydedilirken nasıl özelleştirilir?](https://docs.groupdocs.com/display/signaturenet/Saving)

### Ayrıca bakınız

* class [SignResult](../../../groupdocs.signature.domain/signresult)
* class [SignOptions](../../../groupdocs.signature.options/signoptions)
* class [SaveOptions](../../../groupdocs.signature.options/saveoptions)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
