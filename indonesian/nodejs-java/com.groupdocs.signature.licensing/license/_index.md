---
title: "Lisensi"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menyediakan metode untuk melisensikan komponen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Menyediakan metode untuk melisensikan komponen. Pelajari lebih lanjut tentang lisensi [here][] .


[here]: https://purchase.groupdocs.com/faqs/licensing
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) | Instansiasi Lisensi |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Melisensikan komponen. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Melisensikan komponen. |
### License() {#License--}
```
public License()
```


Instansiasi Lisensi

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licensePath | java.lang.String | Jalur lisensi. |

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Aliran lisensi. |

