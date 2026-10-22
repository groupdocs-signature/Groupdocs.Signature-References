---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Contient les propriétés de la signature de métadonnées d'image."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Contient les propriétés de la signature de métadonnées d'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Crée Image Metadata Signature avec Id et valeur |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getId()](#getId--) | L'identifiant de la signature Image Metadata. |
| [setId(int value)](#setId-int-) | L'identifiant de la signature Image Metadata. |
| [getSize()](#getSize--) | Valeur en lecture seule pour obtenir la taille de la valeur Metadata |
| [setSize(int value)](#setSize-int-) | Valeur en lecture seule pour obtenir la taille de la valeur Metadata |
| [getDescription()](#getDescription--) | Valeur en lecture seule pour obtenir la description de la signature Image Metadata standard |
| [equals(Object signature)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés de la signature. |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
| [deepClone()](#deepClone--) | Clone l'instance de Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone l'instance Image Metadata Signature avec la valeur donnée. |
| [toBoolean()](#toBoolean--) | Convertit en booléen. |
| [toInteger()](#toInteger--) | Convertit en entier. |
| [toLong()](#toLong--) | Convertit en long. |
| [toSingle()](#toSingle--) | Convertit en float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Convertit en float. |
| [toDouble()](#toDouble--) | Convertit en Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Convertit en Double. |
| [toDecimal()](#toDecimal--) | Convertit en Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Convertit en Decimal. |
| [toDateTime()](#toDateTime--) | Convertit en DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Convertit en DateTime. |
| [toString()](#toString--) | Convertit en String avec la méthode ToString() surchargée |
| [toString(String format)](#toString-java.lang.String-) | Convertit en String avec le format spécifié |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Convertit en String avec le format spécifié |
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Crée Image Metadata Signature avec Id et valeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Identifiant unique du nom de la signature d'image de métadonnées. Voir les références pour les spécifications des balises Exif afin d'obtenir les valeurs d'identifiant possibles. |
| valeur | java.lang.Object | Valeur des métadonnées |

### getId() {#getId--}
```
public final int getId()
```


L'identifiant de la signature Image Metadata. Voir la classe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) qui contient la signature standard avec une valeur Id prédéfinie.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


L'identifiant de la signature Image Metadata. Voir la classe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) qui contient la signature standard avec une valeur Id prédéfinie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Valeur en lecture seule pour obtenir la taille de la valeur Metadata

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Valeur en lecture seule pour obtenir la taille de la valeur Metadata

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Valeur en lecture seule pour obtenir la description de la signature Image Metadata standard

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Écrase la méthode Equals pour comparer les propriétés de la signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Objet de signature à comparer. |

**Returns:**
boolean - Retourne true si l'objet signature passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int - Code de hachage de la signature
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone l'instance de Metadata Signature.

**Returns:**
java.lang.Object - Renvoie l'instance clonée de Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone l'instance Image Metadata Signature avec la valeur donnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | Valeur pour le nouvel objet cloné. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Convertit en booléen.

**Returns:**
boolean - Retourne la valeur de la signature des métadonnées en tant que booléen.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Convertit en entier.

**Returns:**
int - Retourne la valeur de la signature des métadonnées en tant qu'entier.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.
### toLong() {#toLong--}
```
public final long toLong()
```


Convertit en long.

**Returns:**
long - Retourne la valeur de la signature Metadata en tant que long.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


Convertit en float.

**Returns:**
float - Retourne la valeur de la signature Image Metadata en tant que float.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Convertit en float.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
float - Retourne la valeur de la signature des métadonnées en tant que float.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Convertit en Double.

**Returns:**
double - Retourne la valeur de la signature Image Metadata en tant que Double.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Convertit en Double.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
double - Retourne la valeur de la signature des métadonnées en tant que Double.
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Convertit en Decimal.

**Returns:**
java.math.BigDecimal - Retourne la valeur de la signature Image Metadata en tant que Decimal.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Convertit en Decimal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
java.math.BigDecimal - Retourne la valeur de la signature Metadata en tant que Decimal.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Convertit en DateTime.

**Returns:**
java.util.Date - Retourne la valeur de la signature des métadonnées en tant que DateTime.

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie. Si la valeur d'origine est basée sur une chaîne, les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Convertit en DateTime.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Lance une exception si la valeur des métadonnées n'a pas pu être convertie |

**Returns:**
java.util.Date - Retourne la valeur de la signature des métadonnées en tant que DateTime.
### toString() {#toString--}
```
public String toString()
```


Convertit en String avec la méthode ToString() surchargée

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Convertit en String avec le format spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | java.lang.String | Chaîne de format de données. |

--------------------

Convertit une propriété booléenne en "True" ou "False". Les informations de propriété de culture par défaut seront utilisées à partir des propriétés de SignatureSettings  SignatureSettings.DefaultCulture  |

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Convertit en String avec le format spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Chaîne de format de données. |
|  | fournisseur | java.util.Locale | Fournisseur de format de données à utiliser avec les opérations de conversion de données. |

--------------------

Convertit une propriété booléenne en "True" ou "False". |

**Returns:**
java.lang.String - Retourne la valeur de la signature des métadonnées en tant que String.
### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

**Returns:**
booléen
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object |  |

