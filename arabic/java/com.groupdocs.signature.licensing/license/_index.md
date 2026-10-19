---
title: "الترخيص"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يوفر طرقًا لتراخيص المكوّن."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

يوفر طرقًا لترخيص المكوّن. تعرف على المزيد حول الترخيص
[here](../https://purchase.groupdocs.com/faqs/licensing)
.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [License()](#License--) | إنشاء كائن License |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | يرخص المكوّن. |
|
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
|
### License() {#License--}
```
public License()
```


إنشاء كائن License


### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يرخص المكوّن.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing a path to the license file.
>   string licensePath = "GroupDocs.Signature.lic";
>  GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>  lic.SetLicense(licensePath);
>  
>  
> ```

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.lang.String | مسار الترخيص. |
|

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


يرخص المكوّن.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing Stream of the license file.
>   using (FileStream licenseStream = new FileStream("GroupDocs.Signature.lic", FileMode.Open))
>  {
>      GroupDocs.Signature.License lic = new GroupDocs.Signature.License();
>      lic.SetLicense(licenseStream);
>  }
>  
>  
> ```

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | تيار الترخيص. |
|

