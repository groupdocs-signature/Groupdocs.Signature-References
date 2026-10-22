---
title: "Μετρημένο"
second_title: "GroupDocs.Signature για Node.js μέσω αναφοράς Java API"
description: "Παρέχει μεθόδους για την εφαρμογή άδειας Metered."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.signature.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή  [Metered][]  άδειας.

--------------------

**Learn more**

 *  More about Metered licensing: [Metered Licensing FAQ][Metered]
 *  More about GroupDocs.Signature licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/signaturejava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Signature
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ενεργοποιεί το προϊόν με κλειδιά Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ανακτά το ποσό των επεξεργασμένων MB. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά τον αριθμό των credits που καταναλώθηκαν. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ενεργοποιεί το προϊόν με κλειδιά Metered.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | Το public key. |
| privateKey | java.lang.String | Το private key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ανακτά το ποσό των επεξεργασμένων MB.

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


Ανακτά τον αριθμό των credits που καταναλώθηκαν.

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
