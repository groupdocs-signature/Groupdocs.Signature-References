---
title: "Licence"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Fournit des méthodes pour licencier le composant. En savoir plus sur la licence  [here][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) | Instancier la licence |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licence le composant. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licence le composant. |
### License() {#License--}
```
public License()
```


Instancier la licence

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licence le composant.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  string licensePath = "GroupDocs.Signature.lic";
>  GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>  lic.SetLicense(licensePath);
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | Le chemin de la licence. |

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licence le composant.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (FileStream licenseStream = new FileStream("GroupDocs.Signature.lic", FileMode.Open))
>  {
>      GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>      lic.SetLicense(licenseStream);
>  }
> ```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Le flux de licence. |

