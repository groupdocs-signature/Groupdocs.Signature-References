---
title: "A consumo"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Fornisce metodi per applicare la licenza Metered."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per applicare la licenza [Metered][].

--------------------

**Learn more**

 *  More about Metered licensing: [Metered Licensing FAQ][Metered]
 *  More about GroupDocs.Signature licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/signaturejava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Signature
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Attiva il prodotto con chiavi Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la quantità di MB elaborati. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Recupera il conteggio dei crediti consumati. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Attiva il prodotto con chiavi Metered.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | La chiave pubblica. |
| privateKey | java.lang.String | La chiave privata. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Recupera la quantità di MB elaborati.

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


Recupera il conteggio dei crediti consumati.

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
