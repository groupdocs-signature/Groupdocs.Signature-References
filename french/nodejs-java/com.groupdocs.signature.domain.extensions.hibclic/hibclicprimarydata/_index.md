---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Classe pour stocker les données primaires du code d’identification licencié HIBC Healthcare Industry Bar Code Council LIC."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

Classe pour stocker les données primaires HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | Constructeur par défaut ctor() |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifie la date du code d’identification du labelisateur. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifie la date du code d’identification du labelisateur. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifie le numéro de produit ou de catalogue. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifie le numéro de produit ou de catalogue. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifie l’ID de l’unité de mesure. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifie l’ID de l’unité de mesure. |
| [deepClone()](#deepClone--) | Obtient une copie de cet objet. |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


Constructeur par défaut ctor()

### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


Identifie la date du code d’identification du labelisateur. Le code d’identification du labelisateur doit être une chaîne alphanumérique de 4 caractères, le premier caractère étant toujours alphabétique.

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


Identifie la date du code d’identification du labelisateur. Le code d’identification du labelisateur doit être une chaîne alphanumérique de 4 caractères, le premier caractère étant toujours alphabétique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


Identifie le numéro de produit ou de catalogue. Le numéro de produit ou de catalogue doit être une chaîne alphanumérique d’une longueur maximale de 18 caractères.

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


Identifie le numéro de produit ou de catalogue. Le numéro de produit ou de catalogue doit être une chaîne alphanumérique d’une longueur maximale de 18 caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


Identifie l’ID de l’unité de mesure. L’ID de l’unité de mesure doit être une valeur entière comprise entre 0 et 9.

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


Identifie l’ID de l’unité de mesure. L’ID de l’unité de mesure doit être une valeur entière comprise entre 0 et 9.

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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
