---
title: "Mailmark2D"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Classe pour encoder et décoder le texte intégré dans le Royal Mail 2D Mailmark."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Classe pour encoder et décoder le texte intégré dans le Royal Mail 2D Mailmark.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | Crée des données combinées Royal Mail Mailmark avec les valeurs par défaut des données primaires et secondaires. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | Identifie l’ID pays UPU. Longueur maximale : 4 caractères. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifie l’ID pays UPU. Longueur maximale : 4 caractères. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
|
|  | [getVersionID()](#getVersionID--) | Identifie la version du code-barres pertinente pour chaque ID de type d’information. |
|
|  | [getClass_()](#getClass---) | Identifie la classe de l’article. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | Identifie la classe de l’article. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | Identifie le groupe unique de clients impliqués dans l’envoi. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifie le groupe unique de clients impliqués dans l’envoi. |
|
|  | [getItemID()](#getItemID--) | Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement. |
|
|  | [setItemID(int value)](#setItemID-int-) | Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contient le code postal de l’adresse de livraison avec DPS |
Si intérieur, le code postal/DP contient le nombre de caractères suivant.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contient le code postal de l’adresse de livraison avec DPS |
Si intérieur, le code postal/DP contient le nombre de caractères suivant.
|
|  | [getRTSFlag()](#getRTSFlag--) | Indicateur qui indique le niveau de service Retour à l’expéditeur demandé. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Indicateur qui indique le niveau de service Retour à l’expéditeur demandé. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contient le code postal Retour à l’expéditeur mais pas de DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contient le code postal Retour à l’expéditeur mais pas de DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | Espace optionnel à l’usage du client. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Espace optionnel à l’usage du client. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Mode d'encodage du code-barres DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Mode d'encodage du code-barres DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
|
|  | [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Crée des données combinées Royal Mail Mailmark avec les valeurs par défaut des données primaires et secondaires.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifie l’ID pays UPU. Longueur maximale : 4 caractères.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifie l’ID pays UPU. Longueur maximale : 4 caractères.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit.

<br />

*** ** * ** ***

Valeurs valides : "0" - Domestique trié et non trié "A" - Affranchissement en ligne "B" - Marquage "C" - Consolidation

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit.

<br />

*** ** * ** ***

Valeurs valides : "0" - Domestique trié et non trié "A" - Affranchissement en ligne "B" - Marquage "C" - Consolidation

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifie la version du code-barres pertinente pour chaque ID de type d’information.

<br />

*** ** * ** ***

Valeurs valides : "1" - actuellement la seule valeur utilisée (par défaut) "0" et "2" à "9" ainsi que "A" à "Z" réservés pour une utilisation future éventuelle.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifie la classe de l’article.

<br />

*** ** * ** ***

Valeurs valides : "1" - 1C (Commerce de détail) "2" - 2C (Commerce de détail) "3" - Économie (Commerce de détail) "5" - Différé (Commerce de détail) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifie la classe de l’article.

<br />

*** ** * ** ***

Valeurs valides : "1" - 1C (Commerce de détail) "2" - 2C (Commerce de détail) "3" - Économie (Commerce de détail) "5" - Différé (Commerce de détail) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifie le groupe unique de clients impliqués dans l’envoi.
Valeur maximale : 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifie le groupe unique de clients impliqués dans l’envoi.
Valeur maximale : 9999999.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement.
Chaque code-barres Mailmark doit contenir un identifiant afin d'être identifié de manière unique pendant au moins 90 jours.
Valeur maximale : 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifie l’élément unique au sein de l’ID de la chaîne d’approvisionnement.
Chaque code-barres Mailmark doit contenir un identifiant afin d'être identifié de manière unique pendant au moins 90 jours.
Valeur maximale : 99999999.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Contient le code postal de l’adresse de livraison avec DPS
Si intérieur, le code postal/DP contient le nombre de caractères suivant.
Zone (1 ou 2 caractères)
District (1 ou 2 caractères)
Secteur (1 caractère)
Unité (2 caractères)
DPS (2 caractères).
Le code postal et le DPS doivent respecter un format PAF® valide. La longueur maximale est de 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Contient le code postal de l’adresse de livraison avec DPS
Si intérieur, le code postal/DP contient le nombre de caractères suivant.
Zone (1 ou 2 caractères)
District (1 ou 2 caractères)
Secteur (1 caractère)
Unité (2 caractères)
DPS (2 caractères).
Le code postal et le DPS doivent respecter un format PAF® valide. La longueur maximale est de 9.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Indicateur qui précise le niveau du service Retour à l'expéditeur demandé. La longueur maximale est de 1.


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Indicateur qui précise le niveau du service Retour à l'expéditeur demandé. La longueur maximale est de 1.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Contient le code postal Retour à l’expéditeur mais pas de DPS.
Le PC (sans DPS) doit respecter un format PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Contient le code postal Retour à l’expéditeur mais pas de DPS.
Le PC (sans DPS) doit respecter un format PAF®.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Espace optionnel à l’usage du client.

<br />

*** ** * ** ***

Longueur maximale par type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype) : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Espace optionnel à l’usage du client.

<br />

*** ** * ** ***

Longueur maximale par type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype) : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


Mode d'encodage du code-barres DataMatrix. Valeur par défaut : DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


Mode d'encodage du code-barres DataMatrix. Valeur par défaut : DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


Le type Mailmark 2D définit la taille du code-barres Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


Le type Mailmark 2D définit la taille du code-barres Data Matrix.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Obtient une copie de cet objet.


**Returns:**
java.lang.Object
