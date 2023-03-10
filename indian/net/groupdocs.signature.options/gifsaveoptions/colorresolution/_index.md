---
title: ColorResolution
second_title: .NET API संदर्भ के लिए GroupDocs.Signature
description: GIF रंग रज़ल्यूशन प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/groupdocs.signature.options/gifsaveoptions/colorresolution/
---
## GifSaveOptions.ColorResolution property

GIF रंग रिज़ॉल्यूशन प्राप्त या सेट करता है।

```csharp
public byte ColorResolution { get; set; }
```

### टिप्पणियों

रंग रिज़ॉल्यूशन - मूल छवि के लिए उपलब्ध प्रति प्राथमिक रंग में बिट्स की संख्या, माइनस 1. यह मान पूरे पैलेट के आकार का प्रतिनिधित्व करता है from जो ग्राफ़िक में रंगों का चयन किया गया था, न कि उन रंगों की संख्या का जो वास्तव में ग्राफ़िक में उपयोग किए गए थे। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो छवि बनाने के लिए मूल छवि के पैलेट में 4 बिट प्रति प्राथमिक रंग उपलब्ध था। यह मान मूल पैलेट की समृद्धि को इंगित करने के लिए सेट किया जाना चाहिए, भले ही पूरे पैलेट से प्रत्येक रंग स्रोत मशीन पर उपलब्ध न हो।

### यह सभी देखें

* class [GifSaveOptions](../../gifsaveoptions)
* नाम स्थान [GroupDocs.Signature.Options](../../gifsaveoptions)
* सभा [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->