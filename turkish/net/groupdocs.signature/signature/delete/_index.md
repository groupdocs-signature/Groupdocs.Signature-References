---
title: Delete
second_title: .NET API Başvurusu için GroupDocs.Signature
description: Geçilen imzayı silerBaseSignaturegroupdocs.signature.domain/basesignature belgeden.
type: docs
weight: 110
url: /tr/net/groupdocs.signature/signature/delete/
---
## Delete(BaseSignature) {#delete}

Geçilen imzayı siler[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) belgeden.

```csharp
public bool Delete(BaseSignature signature)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signature | BaseSignature | Belgeden kaldırılacak imza nesnesi. |

### Geri dönüş değeri

İşlem başarılı olursa true döndürür.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [e-İmza, GroupDocs.Signature ile belgeden nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Delete(List&lt;BaseSignature&gt;) {#delete_3}

Geçilen imza listesini siler[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) belgeden.

```csharp
public DeleteResult Delete(List<BaseSignature> signatures)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatures | List`1 | Belgeden kaldırılacak imzaların listesi. |

### Geri dönüş değeri

DeleteResult'u döndürür[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) başarıyla silinen imzaların ve başarısız olanların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [e-İmza, GroupDocs.Signature ile belgeden nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [BaseSignature](../../../groupdocs.signature.domain/basesignature)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Delete(SignatureType) {#delete_2}

Belirli türdeki imzaları siler[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) Document. Yalnızca Sign yöntemiyle eklenen ve İmza olarak işaretlenen imzalar[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kaldırılacak. Aşağıdaki imza türleri desteklenir: Metin, Resim, Dijital, Barkod, QR-Code

```csharp
public DeleteResult Delete(SignatureType signatureType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureType | SignatureType | Belgeden kaldırılacak imzaların türü. |

### Geri dönüş değeri

DeleteResult'u döndürür[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) başarıyla silinen imzaların ve başarısız olanların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [GroupDocs.Signature ile belgeden belirli türdeki e-İmzalar nasıl silinir?](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Delete(List&lt;SignatureType&gt;) {#delete_4}

Belirli türler listesinin imzalarını siler[`SignatureType`](../../../groupdocs.signature.domain/signaturetype) Document. Yalnızca Sign yöntemiyle eklenen ve İmza olarak işaretlenen imzalar[`IsSignature`](../../../groupdocs.signature.domain/basesignature/issignature) kaldırılacak. Aşağıdaki imza türleri desteklenir: Metin, Resim, Dijital, Barkod, QR-Code

```csharp
public DeleteResult Delete(List<SignatureType> signatureTypes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureTypes | List`1 | Belgeden kaldırılacak imza türlerinin listesi. |

### Geri dönüş değeri

DeleteResult'u döndürür[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) başarıyla silinen imzaların ve başarısız olanların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [GroupDocs.Signature ile belgeden belirli türdeki e-İmzalar nasıl silinir?](https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* enum [SignatureType](../../../groupdocs.signature.domain/signaturetype)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Delete(string) {#delete_1}

Belgeden özel imza kimliğine göre imzayı siler.

```csharp
public bool Delete(string signatureId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureId | String | Belgeden kaldırılacak imzanın kimliği. |

### Geri dönüş değeri

İşlem başarılı olursa true döndürür.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [e-İmza, GroupDocs.Signature ile belgeden nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

---

## Delete(List&lt;string&gt;) {#delete_5}

Geçilen imza listesini siler[`BaseSignature`](../../../groupdocs.signature.domain/basesignature) belgeden.

```csharp
public DeleteResult Delete(List<string> signatureIds)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| signatureIds | List`1 | Belgeden kaldırılacak imzaların tanımlayıcılarının listesi. |

### Geri dönüş değeri

DeleteResult'u döndürür[`DeleteResult`](../../../groupdocs.signature.domain/deleteresult) başarıyla silinen imzaların ve başarısız olanların listesiyle.

### Notlar

**Daha fazla bilgi edin**

* C#'ta belgeden elektronik imzanın nasıl silineceği hakkında daha fazla bilgi: [e-İmza, GroupDocs.Signature ile belgeden nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
* Belge e-İmzalarını silmeye ilişkin gelişmiş kullanım örnekleri: [C#'daki belgeden farklı e-imza türleri nasıl silinir?](https://docs.groupdocs.com/display/signaturenet/Deleting)

### Ayrıca bakınız

* class [DeleteResult](../../../groupdocs.signature.domain/deleteresult)
* class [Signature](../../signature)
* ad alanı [GroupDocs.Signature](../../signature)
* toplantı [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
