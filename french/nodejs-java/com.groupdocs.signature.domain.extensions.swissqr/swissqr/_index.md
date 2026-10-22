---
title: "SwissQR"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code SwissQR."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

Classe pour l'encodage et le décodage du texte intégré dans le code SwissQR.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SwissQR()](#SwissQR--) | Crée une instance de SwissQR. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAmount()](#getAmount--) | Obtient ou définit le montant du paiement. |
| [setAmount(double value)](#setAmount-double-) | Obtient ou définit le montant du paiement. |
| [getCurrency()](#getCurrency--) | Obtient ou définit la devise du paiement. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Obtient ou définit la devise du paiement. |
| [getAccount()](#getAccount--) | Obtient ou définit le numéro de compte du créancier. |
| [setAccount(String value)](#setAccount-java.lang.String-) | Obtient ou définit le numéro de compte du créancier. |
| [getCreditor()](#getCreditor--) | Obtient ou définit l'adresse du créancier. |
| [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Obtient ou définit l'adresse du créancier. |
| [getReference()](#getReference--) | Obtient ou définit la référence de paiement du créancier. |
| [setReference(String value)](#setReference-java.lang.String-) | Obtient ou définit la référence de paiement du créancier. |
| [getDebtor()](#getDebtor--) | Obtient ou définit l'adresse du débiteur. |
| [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | Obtient ou définit l'adresse du débiteur. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Obtient ou définit le message non structuré supplémentaire. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Obtient ou définit le message non structuré supplémentaire. |
| [getBillInformation()](#getBillInformation--) | Obtient ou définit les informations de facture structurées supplémentaires. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Obtient ou définit les informations de facture structurées supplémentaires. |
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


Crée une instance de SwissQR.

### getAmount() {#getAmount--}
```
public final double getAmount()
```


Obtient ou définit le montant du paiement. Les valeurs valides sont comprises entre 0.01 et 999,999,999.99.

Valeur : le montant du paiement.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


Obtient ou définit le montant du paiement. Les valeurs valides sont comprises entre 0.01 et 999,999,999.99.

Valeur : le montant du paiement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


Obtient ou définit la devise du paiement. Les valeurs valides sont "CHF" et "EUR".

Valeur : la devise du paiement.

**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


Obtient ou définit la devise du paiement. Les valeurs valides sont "CHF" et "EUR".

Valeur : la devise du paiement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


Obtient ou définit le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

Valeur : le numéro de compte du créancier.

**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


Obtient ou définit le numéro de compte du créancier. Les numéros de compte doivent être des IBAN valides d'une banque de Suisse ou du Liechtenstein. Les espaces sont autorisés dans le numéro de compte.

Valeur : le numéro de compte du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


Obtient ou définit l'adresse du créancier.

Valeur : l'adresse du créancier.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


Obtient ou définit l'adresse du créancier.

Valeur : l'adresse du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtient ou définit la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c’est‑à‑dire les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx. Si elle est spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

Valeur : la référence de paiement du créancier.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


Obtient ou définit la référence de paiement du créancier. La référence est obligatoire pour les IBAN SwissQR, c’est‑à‑dire les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx. Si elle est spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

Valeur : la référence de paiement du créancier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


Obtient ou définit l'adresse du débiteur. Le débiteur est facultatif. S'il est omis, il est acceptable de définir ce champ à null ou de définir une adresse avec toutes les valeurs nulles ou vides.

Valeur : l'adresse du débiteur.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


Obtient ou définit l'adresse du débiteur. Le débiteur est facultatif. S'il est omis, il est acceptable de définir ce champ à null ou de définir une adresse avec toutes les valeurs nulles ou vides.

Valeur : l'adresse du débiteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


Obtient ou définit le message non structuré supplémentaire.

Valeur : le message non structuré.

**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


Obtient ou définit le message non structuré supplémentaire.

Valeur : le message non structuré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


Obtient ou définit les informations de facture structurées supplémentaires.

Valeur : les informations de facture structurées.

**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


Obtient ou définit les informations de facture structurées supplémentaires.

Valeur : les informations de facture structurées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

