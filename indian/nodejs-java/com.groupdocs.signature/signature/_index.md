---
title: "हस्ताक्षर"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ साइनिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास दर्शाता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

दस्तावेज़ साइनिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास दर्शाता है।

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ इनिशियलाइज़ करता है। |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्प LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) के साथ इनिशियलाइज़ करता है। |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है। |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्प LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और सेटिंग्स [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है। |
| [Signature(String filePath)](#Signature-java.lang.String-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ के साथ इनिशियलाइज़ करता है। |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) के साथ इनिशियलाइज़ करता है। |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है। |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़,  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को स्ट्रीम में सहेजता है। |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को स्ट्रीम में सहेजता है। |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को स्ट्रीम में सहेजता है। |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को स्ट्रीम में सहेजता है। |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है। |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है। |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है। |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है। |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | दिए गए VerifyOptions डेटा के साथ डॉक्यूमेंट हस्ताक्षरों को सत्यापित करता है। |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | VerifyOptions डेटा की सूची के साथ डॉक्यूमेंट हस्ताक्षरों को सत्यापित करता है। |
| [getDocumentInfo()](#getDocumentInfo--) | डॉक्यूमेंट पृष्ठों की जानकारी प्राप्त करता है: उनका आकार, अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई। |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | डॉक्यूमेंट पृष्ठों का पूर्वावलोकन उत्पन्न करता है। |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) सूची द्वारा डॉक्यूमेंट में हस्ताक्षरों की खोज करता है। |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) विकल्पों द्वारा डॉक्यूमेंट में हस्ताक्षरों की खोज करता है। |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | डॉक्यूमेंट में हस्ताक्षरों के सटीक प्रकार की खोज [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा करता है। |
| [search(int[] signatureTypes)](#search-int...-) | डॉक्यूमेंट में निर्दिष्ट हस्ताक्षर प्रकारों की खोज [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा करता है। |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | डॉक्यूमेंट में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | डॉक्यूमेंट से पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | डॉक्यूमेंट से पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | डॉक्यूमेंट से निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | डॉक्यूमेंट से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | डॉक्यूमेंट से निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | डॉक्यूमेंट से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
| [delete(String signatureId)](#delete-java.lang.String-) | डॉक्यूमेंट से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है। |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | दिए गए SignOptions के आधार पर हस्ताक्षर पूर्वावलोकन उत्पन्न करता है। |
| [dispose()](#dispose--) | आंतरिक संसाधनों को साफ़ करने के लिए IDisposable इंटरफ़ेस को लागू करता है। |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | डॉक्यूमेंट | java.io.InputStream | दस्तावेज़ सामग्री स्ट्रीम। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्प LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.InputStream | दस्तावेज़ सामग्री स्ट्रीम। |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.InputStream | दस्तावेज़ सामग्री स्ट्रीम। |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्प LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और सेटिंग्स [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.InputStream | दस्तावेज़ सामग्री स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | परम या सापेक्ष फ़ाइल पथ। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | परम या सापेक्ष फ़ाइल पथ। |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | परम या सापेक्ष फ़ाइल पथ। |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


[Signature](../../com.groupdocs.signature/signature) क्लास का नया इंस्टेंस फ़ाइल पाथ द्वारा प्रदान किए गए दस्तावेज़,  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | परम या सापेक्ष फ़ाइल पथ। |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ दस्तावेज़ पर हस्ताक्षर करता है और परिणाम को स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


डॉक्यूमेंट को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ परिणाम को निर्दिष्ट फ़ाइल पथ में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.
### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


दिए गए VerifyOptions डेटा के साथ डॉक्यूमेंट हस्ताक्षरों को सत्यापित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | हस्ताक्षर सत्यापन विकल्प। |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


VerifyOptions डेटा की सूची के साथ डॉक्यूमेंट हस्ताक्षरों को सत्यापित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | हस्ताक्षर सत्यापन विकल्प संग्रह। Instance of [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


डॉक्यूमेंट पृष्ठों की जानकारी प्राप्त करता है: उनका आकार, अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई।

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


डॉक्यूमेंट पृष्ठों का पूर्वावलोकन उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | पूर्वावलोकन विकल्प। |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


[SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) सूची द्वारा डॉक्यूमेंट में हस्ताक्षरों की खोज करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | खोज विकल्प संग्रह। |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


[SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) विकल्पों द्वारा डॉक्यूमेंट में हस्ताक्षरों की खोज करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | खोज विकल्प। |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - पाए गए हस्ताक्षरों की सूची लौटाता है।
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


डॉक्यूमेंट में हस्ताक्षरों के सटीक प्रकार की खोज [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | खोजने के लिए हस्ताक्षरों का प्रकार। |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - सटीक प्रकार के साथ पाए गए हस्ताक्षरों की सूची लौटाता है।
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


डॉक्यूमेंट में निर्दिष्ट हस्ताक्षर प्रकारों की खोज [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | signatureTypes | int[] | खोजने के लिए एक या कई प्रकार के हस्ताक्षर। |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.
### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


डॉक्यूमेंट में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ में अपडेट किए जाने वाला हस्ताक्षर ऑब्जेक्ट। |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ में अपडेट करने के लिए हस्ताक्षरों की सूची। |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ में अपडेट करने के लिए हस्ताक्षरों की सूची। |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


डॉक्यूमेंट में पास किए गए हस्ताक्षरों [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ में अपडेट किए जाने वाला हस्ताक्षर ऑब्जेक्ट। |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - सफलतापूर्वक अपडेट किए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची के साथ UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) लौटाता है।
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


डॉक्यूमेंट से पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ से हटाए जाने वाला हस्ताक्षर ऑब्जेक्ट। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


डॉक्यूमेंट से पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ से हटाए जाने वाला हस्ताक्षर ऑब्जेक्ट। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


दस्तावेज़ से निर्दिष्ट प्रकार के हस्ताक्षर को हटाता है [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signatureType | int | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों का प्रकार। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


दस्तावेज़ से निर्दिष्ट प्रकारों की सूची के हस्ताक्षर को हटाता है [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डॉक्यूमेंट | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|  | signatureTypes | java.util.List<java.lang.Integer> | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर प्रकारों की सूची। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


दस्तावेज़ से निर्दिष्ट प्रकार के हस्ताक्षर को हटाता है [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signatureType | int | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों का प्रकार। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


दस्तावेज़ से निर्दिष्ट प्रकारों की सूची के हस्ताक्षर को हटाता है [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)। केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) हटाए जाएंगे। निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | आउटपुट फ़ाइल पथ। |
|  | signatureTypes | java.util.List<java.lang.Integer> | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर प्रकारों की सूची। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


डॉक्यूमेंट से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | signatureId | java.lang.String | दस्तावेज़ से हटाए जाने वाले हस्ताक्षर की Id। |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


डॉक्यूमेंट से पास किए गए हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | दस्तावेज़ से हटाए जाने वाले हस्ताक्षरों के पहचानकर्ताओं की सूची। |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


दिए गए SignOptions के आधार पर हस्ताक्षर पूर्वावलोकन उत्पन्न करता है। [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | दिए गए SignOptions के साथ पूर्वावलोकन हस्ताक्षर। [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


आंतरिक संसाधनों को साफ़ करने के लिए IDisposable इंटरफ़ेस को लागू करता है।

