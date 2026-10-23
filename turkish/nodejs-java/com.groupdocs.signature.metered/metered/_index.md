---
title: "Ölçümlü"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Metered lisansını uygulamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

[Metered][] lisansını uygulamak için yöntemler sağlar.

--------------------

**Learn more**

 *  More about Metered licensing: [Metered Licensing FAQ][Metered]
 *  More about GroupDocs.Signature licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/signaturejava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Signature
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered anahtarlarla ürünü etkinleştirir. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | İşlenen MB miktarını alır. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Tüketilen kredi sayısını alır. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered anahtarlarla ürünü etkinleştirir.

--------------------

> ```
> Following example demonstrates how to activate product with Metered keys.
>  
>  string publicKey = "Public Key";
>  string privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.SetMeteredKey(publicKey, privateKey);
> ```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | Açık anahtar. |
| privateKey | java.lang.String | Özel anahtar. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


İşlenen MB miktarını alır.

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal mbProcessed = Metered.GetConsumptionQuantity();
> ```

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Tüketilen kredi sayısını alır.

--------------------

> ```
> Following example demonstrates how to retrieve count of credits consumed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal creditsConsumed = Metered.GetConsumptionCredit();
> ```

**Returns:**
double
