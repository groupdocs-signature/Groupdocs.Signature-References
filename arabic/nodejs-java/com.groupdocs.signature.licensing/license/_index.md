---
title: "رخصة"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يوفر طرقًا لترخيص المكوّن."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

يوفر طرقًا لترخيص المكوّن. تعرف على المزيد حول الترخيص [here][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [License()](#License--) | إنشاء الترخيص |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | يرخص المكوّن. |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
### License() {#License--}
```
public License()
```


إنشاء الترخيص

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| licensePath | java.lang.String | مسار الترخيص. |

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseStream | java.io.InputStream | دفق الترخيص. |

