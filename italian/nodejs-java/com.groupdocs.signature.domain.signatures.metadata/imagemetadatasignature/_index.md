---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Contiene le proprietà della firma di metadati immagine."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Contiene le proprietà della firma di metadati immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Crea Image Metadata Signature con Id e valore |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getId()](#getId--) | L'identificatore della firma Image Metadata. |
| [setId(int value)](#setId-int-) | L'identificatore della firma Image Metadata. |
| [getSize()](#getSize--) | Valore di sola lettura per ottenere la dimensione del valore di Metadata. |
| [setSize(int value)](#setSize-int-) | Valore di sola lettura per ottenere la dimensione del valore di Metadata. |
| [getDescription()](#getDescription--) | Valore di sola lettura per ottenere la descrizione della firma standard Image Metadata. |
| [equals(Object signature)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà della firma |
| [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
| [deepClone()](#deepClone--) | Clona l'istanza di Metadata Signature. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona l'istanza di Image Metadata Signature con il valore fornito. |
| [toBoolean()](#toBoolean--) | Converte in booleano. |
| [toInteger()](#toInteger--) | Converte in intero. |
| [toLong()](#toLong--) | Converte in long. |
| [toSingle()](#toSingle--) | Converte in float. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Converte in float. |
| [toDouble()](#toDouble--) | Converte in Double. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Converte in Double. |
| [toDecimal()](#toDecimal--) | Converte in Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Converte in Decimal. |
| [toDateTime()](#toDateTime--) | Converte in DateTime. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | Converte in DateTime. |
| [toString()](#toString--) | Converte in String con il metodo ToString() sovrascritto |
| [toString(String format)](#toString-java.lang.String-) | Converte in String con formato specificato |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Converte in String con formato specificato |
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


Crea Image Metadata Signature con Id e valore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int | Identificatore univoco del nome della firma Image Metadata. Vedi le referenze per le specifiche dei tag Exif per i possibili valori di id. |
| valore | java.lang.Object | Valore dei metadati |

### getId() {#getId--}
```
public final int getId()
```


L'identificatore della firma Image Metadata. Vedi la classe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) che contiene la firma standard con valore Id predefinito.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


L'identificatore della firma Image Metadata. Vedi la classe [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) che contiene la firma standard con valore Id predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Valore di sola lettura per ottenere la dimensione del valore di Metadata.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Valore di sola lettura per ottenere la dimensione del valore di Metadata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Valore di sola lettura per ottenere la descrizione della firma standard Image Metadata.

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sovrascrive il metodo Equals per confrontare le proprietà della firma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firma | java.lang.Object | Oggetto firma con cui confrontare. |

**Returns:**
boolean - Restituisce true se l'oggetto firma passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode

**Returns:**
int - Codice hash della firma
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clona l'istanza di Metadata Signature.

**Returns:**
java.lang.Object - Restituisce l'istanza clonata di Metadata Signature
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clona l'istanza di Image Metadata Signature con il valore fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Valore per il nuovo oggetto clonato. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Converte in booleano.

**Returns:**
boolean - Restituisce il valore della firma Metadata come booleano.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Converte in intero.

**Returns:**
int - Restituisce il valore della Firma Metadata come intero.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito.
### toLong() {#toLong--}
```
public final long toLong()
```


Converte in long.

**Returns:**
long - Restituisce il valore della Metadata Signature come long.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


Converte in float.

**Returns:**
float - Restituisce il valore della Image Metadata Signature come float.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Converte in float.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
float - Restituisce il valore della Firma Metadata come float.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Converte in Double.

**Returns:**
double - Restituisce il valore della Image Metadata Signature come Double.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Converte in Double.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
double - Restituisce il valore della Firma Metadata come Double.
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Converte in Decimal.

**Returns:**
java.math.BigDecimal - Restituisce il valore della Image Metadata Signature come Decimal.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Converte in Decimal.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
java.math.BigDecimal - Restituisce il valore della Metadata Signature come Decimal.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Converte in DateTime.

**Returns:**
java.util.Date - Restituisce il valore della Firma Metadata come DateTime.

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito. Se il valore originale è basato su stringa, verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


Converte in DateTime.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Genera un'eccezione se il valore Metadata non può essere convertito |

**Returns:**
java.util.Date - Restituisce il valore della Firma Metadata come DateTime.
### toString() {#toString--}
```
public String toString()
```


Converte in String con il metodo ToString() sovrascritto

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Converte in String con formato specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | formato | java.lang.String | Stringa di formato dati. |

--------------------

Converte una proprietà boolean in "True" o "False". Verrà utilizzata l'informazione della proprietà di cultura predefinita da SignatureSettings proprietà SignatureSettings.DefaultCulture |

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Converte in String con formato specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | java.lang.String | Stringa di formato dati. |
|  | provider | java.util.Locale | Provider di formattazione dati da utilizzare con le operazioni di conversione dei dati. |

--------------------

Converte una proprietà boolean in "True" o "False". |

**Returns:**
java.lang.String - Restituisce il valore della Firma Metadata come String.
### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

