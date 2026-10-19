---
title: "PngSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement PNG pour les documents image."
type: docs
weight: 22
url: /fr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Options d'enregistrement PNG pour les documents image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | Crée PngSaveOptions avec les valeurs par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | La profondeur de bits. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | La profondeur de bits. |
|
|  | [getColorType()](#getColorType--) | Obtient ou définit le type de |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | Obtient ou définit le type de |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale |
et 0 est le mode stockage.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale |
et 0 est le mode stockage.
|
|  | [getFilterType()](#getFilterType--) | Obtient ou définit le type de filtre |
PngFilterType
utilisé lors du processus d'enregistrement du fichier png.
|
|  | [setFilterType(int value)](#setFilterType-int-) | Obtient ou définit le type de filtre |
PngFilterType
utilisé lors du processus d'enregistrement du fichier png.
|
|  | [getProgressive()](#getProgressive--) | Obtient ou définit une valeur indiquant si ce PngSaveOptions est progressif. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | Obtient ou définit une valeur indiquant si ce PngSaveOptions est progressif. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Crée PngSaveOptions avec les valeurs par défaut.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


La profondeur de bits.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


La profondeur de bits.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtient ou définit le type de
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtient ou définit le type de
PngColorType
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale
et 0 est le mode stockage.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale
et 0 est le mode stockage.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Obtient ou définit le type de filtre
PngFilterType
utilisé lors du processus d'enregistrement du fichier png.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Obtient ou définit le type de filtre
PngFilterType
utilisé lors du processus d'enregistrement du fichier png.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Obtient ou définit une valeur indiquant si ce PngSaveOptions est progressif.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Obtient ou définit une valeur indiquant si ce PngSaveOptions est progressif.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

