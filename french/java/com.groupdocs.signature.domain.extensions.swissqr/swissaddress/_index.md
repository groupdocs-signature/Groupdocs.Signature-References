---
title: "SwissAddress"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente l'adresse du créancier ou du débiteur."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

Représente l'adresse du créancier ou du débiteur.
Vous pouvez soit définir la rue, le numéro de maison, le code postal et la ville (type d’adresse structurée)
ou la ligne d’adresse 1 et 2 (type d’éléments d’adresse combinés).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Obtient ou définit le nom, soit le prénom et le nom de famille d’une personne physique ou |
le nom de l’entreprise d’une personne morale.
|
|  | [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom, soit le prénom et le nom de famille d’une personne physique ou |
le nom de l’entreprise d’une personne morale.
|
|  | [getAddressLine1()](#getAddressLine1--) | Obtient ou définit la ligne d’adresse 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Obtient ou définit la ligne d’adresse 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | Obtient ou définit la ligne d'adresse 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Obtient ou définit la ligne d'adresse 2. |
|
|  | [getStreet()](#getStreet--) | Obtient ou définit la rue. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | Obtient ou définit la rue. |
|
|  | [getHouseNo()](#getHouseNo--) | Obtient ou définit le numéro de maison. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Obtient ou définit le numéro de maison. |
|
|  | [getPostalCode()](#getPostalCode--) | Obtient ou définit le code postal. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Obtient ou définit le code postal. |
|
|  | [getTown()](#getTown--) | Obtient ou définit la ville ou la commune. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | Obtient ou définit la ville ou la commune. |
|
|  | [getCountryCode()](#getCountryCode--) | Obtient ou définit le code pays ISO à deux lettres. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Obtient ou définit le code pays ISO à deux lettres. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom, soit le prénom et le nom de famille d’une personne physique ou
le nom de l’entreprise d’une personne morale.
Valeur : le nom.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom, soit le prénom et le nom de famille d’une personne physique ou
le nom de l’entreprise d’une personne morale.
Valeur : le nom.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


Obtient ou définit la ligne d’adresse 1.
La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale.
Ce champ n'est utilisé que pour les adresses d'éléments combinés et est facultatif.
Valeur : la ligne d'adresse 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


Obtient ou définit la ligne d’adresse 1.
La ligne d'adresse 1 contient le nom de la rue, le numéro de maison ou la boîte postale.
Ce champ n'est utilisé que pour les adresses d'éléments combinés et est facultatif.
Valeur : la ligne d'adresse 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


Obtient ou définit la ligne d'adresse 2.
La ligne d'adresse 2 contient le code postal et la ville.
Ce champ n'est utilisé que pour les adresses d'éléments combinés. Pour ce type, il est obligatoire.
Valeur : la ligne d'adresse 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


Obtient ou définit la ligne d'adresse 2.
La ligne d'adresse 2 contient le code postal et la ville.
Ce champ n'est utilisé que pour les adresses d'éléments combinés. Pour ce type, il est obligatoire.
Valeur : la ligne d'adresse 2.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


Obtient ou définit la rue.
La rue doit être indiquée sans le numéro de maison.
Ce champ n'est utilisé que pour les adresses structurées et est facultatif.
Valeur : la rue.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


Obtient ou définit la rue.
La rue doit être indiquée sans le numéro de maison.
Ce champ n'est utilisé que pour les adresses structurées et est facultatif.
Valeur : la rue.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


Obtient ou définit le numéro de maison.
Ce champ n'est utilisé que pour les adresses structurées et est facultatif.
Valeur : le numéro de maison.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


Obtient ou définit le numéro de maison.
Ce champ n'est utilisé que pour les adresses structurées et est facultatif.
Valeur : le numéro de maison.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Obtient ou définit le code postal.
Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.
Valeur : le code postal.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


Obtient ou définit le code postal.
Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.
Valeur : le code postal.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


Obtient ou définit la ville ou la commune.
Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.
Valeur : la ville ou la commune.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


Obtient ou définit la ville ou la commune.
Ce champ n'est utilisé que pour les adresses structurées. Pour ce type, il est obligatoire.
Valeur : la ville ou la commune.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


Obtient ou définit le code pays ISO à deux lettres.
Le code pays est obligatoire sauf si l'intégralité de l'adresse contient des valeurs nulles ou vides.
Valeur : le code pays ISO.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


Obtient ou définit le code pays ISO à deux lettres.
Le code pays est obligatoire sauf si l'intégralité de l'adresse contient des valeurs nulles ou vides.
Valeur : le code pays ISO.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

