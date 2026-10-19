---
title: "DicomSaveOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Options d'enregistrement pour les documents image DICOM."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/dicomsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class DicomSaveOptions extends ImageSaveOptions
```

Options d'enregistrement pour les documents image DICOM.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DicomSaveOptions()](#DicomSaveOptions--) | Crée DicomSaveOptions avec les valeurs par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getXmpEntries()](#getXmpEntries--) | Données XMP pour DICOM. |
|
|  | [setXmpEntries(List<DicomXmpEntry> value)](#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--) | Données XMP pour DICOM. |
|
### DicomSaveOptions() {#DicomSaveOptions--}
```
public DicomSaveOptions()
```


Crée DicomSaveOptions avec les valeurs par défaut.


### getXmpEntries() {#getXmpEntries--}
```
public final List<DicomXmpEntry> getXmpEntries()
```


Données XMP pour DICOM. Utilisez‑les pour définir les métadonnées de l’image.


**Returns:**
java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry>
### setXmpEntries(List<DicomXmpEntry> value) {#setXmpEntries-java.util.List-com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry--}
```
public final void setXmpEntries(List<DicomXmpEntry> value)
```


Données XMP pour DICOM. Utilisez‑les pour définir les métadonnées de l’image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<com.groupdocs.signature.options.saveoptions.imagessaveoptions.DicomXmpEntry> |  |

