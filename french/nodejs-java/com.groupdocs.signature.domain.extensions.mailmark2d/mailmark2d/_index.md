---
title: "Mailmark2D"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Classe pour encoder et décoder le texte intégré dans le Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Classe pour encoder et décoder le texte intégré dans le Royal Mail 2D Mailmark
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | Crée les données combinées Royal Mail Mailmark avec les valeurs de données primaires et secondaires par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. |
| [getVersionID()](#getVersionID--) | Identifie la version du code-barres selon chaque ID de type d'information. |
| [getClass_()](#getClass---) | Identifie la classe de l'élément. |
| [setClass(String value)](#setClass-java.lang.String-) | Identifie la classe de l'élément. |
| [getSupplyChainID()](#getSupplyChainID--) | Identifie le groupe unique de clients impliqués dans l'envoi. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Identifie le groupe unique de clients impliqués dans l'envoi. |
| [getItemID()](#getItemID--) | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. |
| [setItemID(int value)](#setItemID-int-) | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant. |
| [getRTSFlag()](#getRTSFlag--) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Contient le code postal de Retour à l'expéditeur mais sans DPS. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Contient le code postal de Retour à l'expéditeur mais sans DPS. |
| [getCustomerContent()](#getCustomerContent--) | Espace optionnel à l'usage du client. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Espace optionnel à l'usage du client. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Mode d'encodage du code-barres DataMatrix. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | Mode d'encodage du code-barres DataMatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


Crée les données combinées Royal Mail Mailmark avec les valeurs de données primaires et secondaires par défaut.

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


Identifie l'ID pays UPU. Longueur maximale : 4 caractères.

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


Identifie l'ID pays UPU. Longueur maximale : 4 caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit.

--------------------

Valeurs valides : "0" - Domestique trié et non trié "A" - Affranchissement en ligne "B" - Marquage "C" - Consolidation

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit.

--------------------

Valeurs valides : "0" - Domestique trié et non trié "A" - Affranchissement en ligne "B" - Marquage "C" - Consolidation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


Identifie la version du code-barres selon chaque ID de type d'information.

--------------------

Valeurs valides : "1" - actuellement la seule valeur utilisée (par défaut) "0" et "2" à "9" et "A" à "Z" réservés pour une utilisation future éventuelle.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


Identifie la classe de l'élément.

--------------------

Valeurs valides : "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - Économie (Vente au détail) "5" - Différé (Vente au détail) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


Identifie la classe de l'élément.

--------------------

Valeurs valides : "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - Économie (Vente au détail) "5" - Différé (Vente au détail) "8" - Premium (Accès réseau) "9" - Standard (Accès réseau)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit porter un ID afin d'être identifié de manière unique pendant au moins 90 jours. Valeur maximale : 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit porter un ID afin d'être identifié de manière unique pendant au moins 90 jours. Valeur maximale : 99999999.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant : Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide. Longueur maximale : 9.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre de caractères suivant : Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide. Longueur maximale : 9.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. Longueur maximale : 1

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. Longueur maximale : 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Contient le code postal de Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Contient le code postal de Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


Espace optionnel à l'usage du client.

--------------------

Longueur maximale par type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype) : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


Espace optionnel à l'usage du client.

--------------------

Longueur maximale par type [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype) : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

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
