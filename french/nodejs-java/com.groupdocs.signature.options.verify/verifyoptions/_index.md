---
title: "VerifyOptions"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Conserve les options pour vérifier le document."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Conserve les options pour vérifier le document.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isValid()](#isValid--) | Indicateur de propriété valide. |
| [setValid(boolean value)](#setValid-boolean-) | Indicateur de propriété valide. |
| [getPageNumber()](#getPageNumber--) | Numéro de page du document à vérifier. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Numéro de page du document à vérifier. |
| [getPagesSetup()](#getPagesSetup--) | Options de page pour spécifier les pages à vérifier. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Options de page pour spécifier les pages à vérifier. |
| [getAllPages()](#getAllPages--) | Indicateur pour vérifier chaque page du document. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Indicateur pour vérifier chaque page du document. |
| [getExtensions()](#getExtensions--) | Extensions supplémentaires pour la vérification des options de signature alternatives. |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Extensions supplémentaires pour la vérification des options de signature alternatives. |
| [toString()](#toString--) | Remplace la conversion de chaîne. |
### isValid() {#isValid--}
```
public final boolean isValid()
```


Indicateur de propriété valide.

**Returns:**
booléen
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Indicateur de propriété valide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Numéro de page du document à vérifier. Si la propriété n'est pas définie - toutes les pages du document seront vérifiées pour la première occurrence. La valeur minimale est 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Numéro de page du document à vérifier. Si la propriété n'est pas définie - toutes les pages du document seront vérifiées pour la première occurrence. La valeur minimale est 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Options de page pour spécifier les pages à vérifier.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Options de page pour spécifier les pages à vérifier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Indicateur pour vérifier chaque page du document. Par défaut, la valeur est vraie.

**Returns:**
booléen
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Indicateur pour vérifier chaque page du document. Par défaut, la valeur est vraie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Extensions supplémentaires pour la vérification des options de signature alternatives.

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Extensions supplémentaires pour la vérification des options de signature alternatives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Remplace la conversion de chaîne.

**Returns:**
java.lang.String -
