---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Options d’enregistrement au format GIF pour les documents image."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Options d’enregistrement au format GIF pour les documents image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Crée GifSaveOptions avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtient ou définit l'index de couleur d'arrière-plan du GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtient ou définit l'index de couleur d'arrière-plan du GIF. |
| [getColorResolution()](#getColorResolution--) | Obtient ou définit la résolution couleur du GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Obtient ou définit la résolution couleur du GIF. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [hasTrailer()](#hasTrailer--) | Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce. |
| [getInterlaced()](#getInterlaced--) | Vrai si l'image doit être entrelacée. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Vrai si l'image doit être entrelacée. |
| [isPaletteSorted()](#isPaletteSorted--) | Obtient ou définit une valeur indiquant si les entrées de palette sont triées. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtient ou définit une valeur indiquant si les entrées de palette sont triées. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtient ou définit le rapport d'aspect des pixels du GIF. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Crée GifSaveOptions avec les valeurs par défaut.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtient ou définit l'index de couleur d'arrière-plan du GIF.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtient ou définit l'index de couleur d'arrière-plan du GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtient ou définit la résolution couleur du GIF.

--------------------

Résolution couleur - Nombre de bits par couleur primaire disponible dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble complet de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtient ou définit la résolution couleur du GIF.

--------------------

Résolution couleur - Nombre de bits par couleur primaire disponible dans l'image originale, moins 1. Cette valeur représente la taille de l'ensemble complet de la palette à partir de laquelle les couleurs du graphique ont été sélectionnées, et non le nombre de couleurs réellement utilisées dans le graphique. Par exemple, si la valeur de ce champ est 3, alors la palette de l'image originale disposait de 4 bits par couleur primaire pour créer l'image. Cette valeur doit être définie pour indiquer la richesse de la palette originale, même si toutes les couleurs de la palette complète ne sont pas disponibles sur la machine source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

--------------------

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source seront analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image de sortie disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.

**Returns:**
booléen
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtient ou définit une valeur indiquant si la correction de palette est appliquée.

--------------------

La correction de palette signifie que chaque fois qu'une image est exportée au format GIF, les couleurs de l'image source seront analysées afin de créer la palette la mieux adaptée (dans le cas où la palette de l'image n'existe pas ou n'est pas spécifiée dans les options). Le processus d'analyse prend du temps, cependant l'image de sortie disposera de la palette de couleurs la mieux adaptée et le résultat sera visuellement meilleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce.

**Returns:**
booléen
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtient ou définit une valeur indiquant si le GIF possède une bande-annonce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Vrai si l'image doit être entrelacée.

**Returns:**
booléen
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Vrai si l'image doit être entrelacée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtient ou définit une valeur indiquant si les entrées de palette sont triées.

**Returns:**
booléen
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtient ou définit une valeur indiquant si les entrées de palette sont triées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtient ou définit le rapport d'aspect des pixels du GIF.

--------------------

Rapport d'aspect des pixels - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Rapport d'aspect = (Rapport d'aspect des pixels + 15) / 64 Le rapport d'aspect des pixels est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs de ce champ permet de spécifier le pixel le plus large de 4:1 au pixel le plus haut de 1:4 par incréments de 1/64. Valeurs : 0 - Aucune information de rapport d'aspect fournie. 1..255 - Valeur utilisée dans le calcul.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtient ou définit le rapport d'aspect des pixels du GIF.

--------------------

Rapport d'aspect des pixels - Facteur utilisé pour calculer une approximation du rapport d'aspect du pixel dans l'image originale. Si la valeur du champ n'est pas 0, cette approximation du rapport d'aspect est calculée selon la formule : Rapport d'aspect = (Rapport d'aspect des pixels + 15) / 64 Le rapport d'aspect des pixels est défini comme le quotient de la largeur du pixel sur sa hauteur. La plage de valeurs de ce champ permet de spécifier le pixel le plus large de 4:1 au pixel le plus haut de 1:4 par incréments de 1/64. Valeurs : 0 - Aucune information de rapport d'aspect fournie. 1..255 - Valeur utilisée dans le calcul.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

