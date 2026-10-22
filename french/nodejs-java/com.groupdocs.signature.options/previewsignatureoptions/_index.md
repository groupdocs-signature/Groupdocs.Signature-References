---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les options d’aperçu de la signature."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

Représente les options d’aperçu de la signature.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | Initialise l'objet PreviewSignatureOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignatureId()](#getSignatureId--) | Valeur unique pour distinguer la signature. |
| [setSignatureId(String value)](#setSignatureId-java.lang.String-) | Valeur unique pour distinguer la signature. |
| [getSignOptions()](#getSignOptions--) | Options de signature pour générer un aperçu. |
| [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | Options de signature pour générer un aperçu. |
| [getPreviewFormat()](#getPreviewFormat--) | Obtient ou définit le format des images d'aperçu. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Obtient ou définit le format des images d'aperçu. |
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


Initialise l'objet PreviewSignatureOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | Les options de signature pour générer l'aperçu. |
| pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | Interface qui définit la méthode pour créer le flux d'aperçu de la page de sortie. |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Valeur unique pour distinguer la signature. Utilisez SignatureId pour identifier les options d'aperçu.

**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


Valeur unique pour distinguer la signature. Utilisez SignatureId pour identifier les options d'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


Options de signature pour générer un aperçu.

**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


Options de signature pour générer un aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtient ou définit le format des images d'aperçu. La valeur par défaut est PNG

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Obtient ou définit le format des images d'aperçu. La valeur par défaut est PNG

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

