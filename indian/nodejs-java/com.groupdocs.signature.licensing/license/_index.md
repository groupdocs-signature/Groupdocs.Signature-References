---
title: "लाइसेंस"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है। लाइसेंसिंग के बारे में अधिक जानें  [here][] .


[here]: https://purchase.groupdocs.com/faqs/licensing
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) | लाइसेंस को इंस्टैंशिएट करें |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस करता है। |
### License() {#License--}
```
public License()
```


लाइसेंस को इंस्टैंशिएट करें

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


घटक को लाइसेंस करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | java.lang.String | लाइसेंस पथ। |

### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


घटक को लाइसेंस करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | java.io.InputStream | लाइसेंस स्ट्रीम। |

