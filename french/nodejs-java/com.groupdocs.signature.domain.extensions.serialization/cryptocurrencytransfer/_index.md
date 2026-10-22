---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente le destinataire ou le transfert de crypto-monnaie pour le QR-Code."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

Représente le transfert de crypto-monnaie (destinataire ou transfert) pour le QR-Code.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient ou définit l'un des types de crypto-monnaie pris en charge. |
| [setType(int value)](#setType-int-) | Obtient ou définit l'un des types de crypto-monnaie pris en charge. |
| [getAmount()](#getAmount--) | Obtient ou définit le montant du transfert. |
| [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | Obtient ou définit le montant du transfert. |
| [getAddress()](#getAddress--) | Obtient ou définit l'adresse publique de la crypto-monnaie. |
| [setAddress(String value)](#setAddress-java.lang.String-) | Obtient ou définit l'adresse publique de la crypto-monnaie. |
| [getMessage()](#getMessage--) | Obtient ou définit le message de transfert optionnel. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Obtient ou définit le message de transfert optionnel. |
| [getCustomType()](#getCustomType--) | Obtient ou définit le message de transfert optionnel. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Obtient ou définit le message de transfert optionnel. |
| [equals(Object obj)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés du transfert de crypto-monnaie. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


Obtient ou définit l'un des types de crypto-monnaie pris en charge.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Obtient ou définit l'un des types de crypto-monnaie pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


Obtient ou définit le montant du transfert.

**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


Obtient ou définit le montant du transfert.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


Obtient ou définit l'adresse publique de la crypto-monnaie.

**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


Obtient ou définit l'adresse publique de la crypto-monnaie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


Obtient ou définit le message de transfert optionnel.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


Obtient ou définit le message de transfert optionnel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


Obtient ou définit le message de transfert optionnel.

**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


Obtient ou définit le message de transfert optionnel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Écrase la méthode Equals pour comparer les propriétés du transfert de crypto-monnaie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet de transfert de crypto-monnaie à comparer. |

**Returns:**
booléen - Retourne true si l'objet de transfert de crypto-monnaie passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int - Code de hachage du transfert de crypto-monnaie
