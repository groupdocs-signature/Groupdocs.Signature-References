---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Classe pour stocker les données secondaires et supplémentaires du HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

Classe permettant de stocker les données secondaires et supplémentaires du HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | Constructeur par défaut() |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifie le format de la date d'expiration. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | Identifie le format de la date d'expiration. |
|
|  | [getExpiryDate()](#getExpiryDate--) | Identifie la date d'expiration. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | Identifie la date d'expiration. |
|
|  | [getLotNumber()](#getLotNumber--) | Identifie le numéro de lot ou de lot (batch). |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifie le numéro de lot ou de lot (batch). |
|
|  | [getSerialNumber()](#getSerialNumber--) | Identifie le numéro de série. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifie le numéro de série. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | Identifie la date de fabrication. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | Identifie la date de fabrication. |
|
|  | [getQuantity()](#getQuantity--) | Identifie la quantité, qui doit être une valeur entière de 0 à 500. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | Identifie la quantité, qui doit être une valeur entière de 0 à 500. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | Identifie le caractère de liaison dans la chaîne de sortie. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | Identifie le caractère de liaison dans la chaîne de sortie. |
|
|  | [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


Constructeur par défaut()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


Identifie le format de la date d'expiration.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


Identifie le format de la date d'expiration.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


Identifie la date d'expiration. Sera utilisée si ExpiryDateFormat n'est pas réglé sur None.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


Identifie la date d'expiration. Sera utilisée si ExpiryDateFormat n'est pas réglé sur None.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


Identifie le numéro de lot ou de lot (batch).
Le numéro de lot/batch doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


Identifie le numéro de lot ou de lot (batch).
Le numéro de lot/batch doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Identifie le numéro de série.
Le numéro de série doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Identifie le numéro de série.
Le numéro de série doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


Identifie la date de fabrication.
La date de fabrication peut être définie à DateTime.MinValue afin de ne pas utiliser ce champ.
Valeur par défaut : DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


Identifie la date de fabrication.
La date de fabrication peut être définie à DateTime.MinValue afin de ne pas utiliser ce champ.
Valeur par défaut : DateTime.MinValue


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


Identifie la quantité, qui doit être une valeur entière de 0 à 500.
La quantité peut être définie à -1 afin de ne pas utiliser ce champ. Valeur par défaut : -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


Identifie la quantité, qui doit être une valeur entière de 0 à 500.
La quantité peut être définie à -1 afin de ne pas utiliser ce champ. Valeur par défaut : -1


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


Identifie le caractère de liaison dans la chaîne de sortie.


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


Identifie le caractère de liaison dans la chaîne de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtient une copie de cet objet.


**Returns:**
java.lang.Object
