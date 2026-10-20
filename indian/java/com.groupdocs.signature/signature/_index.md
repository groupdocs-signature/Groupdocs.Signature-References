---
title: "Signature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ साइनिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

दस्तावेज़ साइनिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्पों के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है। |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्पों के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और सेटिंग्स [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है। |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है और |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है और [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को एक स्ट्रीम में सहेजता है। |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ एक स्ट्रीम में सहेजता है। |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को एक स्ट्रीम में सहेजता है। |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ एक स्ट्रीम में सहेजता है। |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है। |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | दिए गए VerifyOptions डेटा के साथ दस्तावेज़ हस्ताक्षरों की पुष्टि करता है। |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | VerifyOptions डेटा की सूची के साथ दस्तावेज़ हस्ताक्षरों की पुष्टि करता है। |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | प्रदान किए गए सत्यापन विकल्पों और फ़िल्टरों का उपयोग करके दस्तावेज़ हस्ताक्षरों की पुष्टि करता है |
निर्दिष्ट प्रेडिकेट द्वारा सफल परिणाम।
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | सत्यापन विकल्पों की सूची का उपयोग करके दस्तावेज़ हस्ताक्षरों की पुष्टि करता है और फ़िल्टर करता है |
निर्दिष्ट प्रेडिकेट द्वारा सफल परिणाम।
|
|  | [getDocumentInfo()](#getDocumentInfo--) | दस्तावेज़ पृष्ठों के बारे में जानकारी प्राप्त करता है: उनके आकार, |
अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई।
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करता है। |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | दस्तावेज़ में हस्ताक्षरों को [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) सूची द्वारा खोजता है। |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | विकल्पों की सूची द्वारा हस्ताक्षरों को खोजता है और परिणाम को प्रेडिकेट द्वारा फ़िल्टर करता है। |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | दस्तावेज़ में हस्ताक्षरों को [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) विकल्पों द्वारा खोजता है। |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | दस्तावेज़ में निर्दिष्ट प्रकार के हस्ताक्षरों को खोजता है, वैकल्पिक रूप से प्रेडिकेट द्वारा फ़िल्टर किया गया। |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | दस्तावेज़ में हस्ताक्षरों के सटीक प्रकार को [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा खोजता है। |
|
|  | [search(int[] signatureTypes)](#search-int...-) | दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों को [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा खोजता है। |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है। |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | दस्तावेज़ से पास किया गया हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | दस्तावेज़ से पास किया गया हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | दस्तावेज़ से एक निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | दस्तावेज़ से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | दस्तावेज़ से एक निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | दस्तावेज़ से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है। |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | दस्तावेज़ से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है। |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है। |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | दिए गए SignOptions के आधार पर हस्ताक्षर पूर्वावलोकन उत्पन्न करता है। |
|
|  | [dispose()](#dispose--) | आंतरिक संसाधनों को साफ़ करने के लिए IDisposable इंटरफ़ेस को लागू करें |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ की सामग्री स्ट्रीम। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और लोड विकल्पों के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है।
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ की सामग्री स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़ और [SignatureSettings](../../com.groupdocs.signature/signaturesettings) के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ की सामग्री स्ट्रीम। |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


स्ट्रीम द्वारा प्रदान किए गए दस्तावेज़, लोड विकल्पों के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और सेटिंग्स [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ की सामग्री स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | पूर्ण या सापेक्ष फ़ाइल पथ। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है और
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | पूर्ण या सापेक्ष फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है और [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | पूर्ण या सापेक्ष फ़ाइल पथ। |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


फ़ाइल पथ द्वारा प्रदान किए गए दस्तावेज़ के साथ [Signature](../../com.groupdocs.signature/signature) क्लास का नया उदाहरण प्रारंभ करता है,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) और [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | पूर्ण या सापेक्ष फ़ाइल पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | हस्ताक्षर सेटिंग्स। |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को एक स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ एक स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को एक स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ एक स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | हस्ताक्षर विकल्प। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को निर्दिष्ट फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


दस्तावेज़ को [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) के संग्रह के साथ साइन करता है और परिणाम को पूर्वनिर्धारित [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) के साथ निर्दिष्ट फ़ाइल पथ पर सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | हस्ताक्षर विकल्पों की सूची। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | सेव विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


दिए गए VerifyOptions डेटा के साथ दस्तावेज़ हस्ताक्षरों की पुष्टि करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | हस्ताक्षर सत्यापन विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


VerifyOptions डेटा की सूची के साथ दस्तावेज़ हस्ताक्षरों की पुष्टि करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | हस्ताक्षर सत्यापन विकल्प संग्रह। [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection) का उदाहरण। |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


प्रदान किए गए सत्यापन विकल्पों और फ़िल्टरों का उपयोग करके दस्तावेज़ हस्ताक्षरों की पुष्टि करता है
निर्दिष्ट प्रेडिकेट द्वारा सफल परिणाम।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | हस्ताक्षर सत्यापन विकल्प। |
|
|  | पूर्वधारणा | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | सत्यापित हस्ताक्षरों की सूची पर लागू फ़िल्टर प्रेडिकेट। |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - सत्यापन में सफल हुए और प्रेडिकेट को संतुष्ट करने वाले हस्ताक्षरों की सूची।

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


सत्यापन विकल्पों की सूची का उपयोग करके दस्तावेज़ हस्ताक्षरों की पुष्टि करता है और फ़िल्टर करता है
निर्दिष्ट प्रेडिकेट द्वारा सफल परिणाम।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | हस्ताक्षर सत्यापन विकल्पों की सूची। |
|
|  | पूर्वधारणा | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | सत्यापित हस्ताक्षरों की सूची पर लागू फ़िल्टर प्रेडिकेट। |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - सत्यापन में सफल हुए और प्रेडिकेट को संतुष्ट करने वाले हस्ताक्षरों की सूची।

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


दस्तावेज़ पृष्ठों के बारे में जानकारी प्राप्त करता है: उनके आकार,
अधिकतम पृष्ठ ऊँचाई, अधिकतम ऊँचाई वाले पृष्ठ की चौड़ाई।


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


दस्तावेज़ पृष्ठों का पूर्वावलोकन उत्पन्न करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | पूर्वावलोकन विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


दस्तावेज़ में हस्ताक्षरों को [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) सूची द्वारा खोजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | खोज विकल्प संग्रह। |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


विकल्पों की सूची द्वारा हस्ताक्षरों को खोजता है और परिणाम को प्रेडिकेट द्वारा फ़िल्टर करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | खोज विकल्पों की सूची। |
|
|  | पूर्वधारणा | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | परिणामी हस्ताक्षरों को फ़िल्टर करने के लिए उपयोग किया गया प्रेडिकेट। |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


दस्तावेज़ में हस्ताक्षरों को [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) विकल्पों द्वारा खोजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | खोज विकल्प। |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - पाए गए हस्ताक्षरों की सूची लौटाता है।

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


दस्तावेज़ में निर्दिष्ट प्रकार के हस्ताक्षरों को खोजता है, वैकल्पिक रूप से प्रेडिकेट द्वारा फ़िल्टर किया गया।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) का सामान्य प्रकार पैरामीटर। |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | हस्ताक्षर खोज के विकल्प। |
|
|  | पूर्वधारणा | java.util.function.Predicate<T> | खोज के बाद लागू वैकल्पिक प्रेडिकेट फ़िल्टर। यह null हो सकता है। |
|

**Returns:**
java.util.List<T> - पाए गए हस्ताक्षरों की सूची, वैकल्पिक रूप से प्रेडिकेट द्वारा फ़िल्टर की गई।

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


दस्तावेज़ में हस्ताक्षरों के सटीक प्रकार को [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा खोजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | खोजे जाने वाले हस्ताक्षरों का प्रकार। |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - सटीक प्रकार के साथ पाए गए हस्ताक्षरों की सूची लौटाता है।

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


दस्तावेज़ में निर्दिष्ट हस्ताक्षर प्रकारों को [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) मान द्वारा खोजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureTypes | int[] | एक या कई प्रकार के हस्ताक्षर खोजने के लिए। |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ में अपडेट किए जाने वाले हस्ताक्षर ऑब्जेक्ट। |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ में अपडेट करने के लिए हस्ताक्षरों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ में अपडेट करने के लिए हस्ताक्षरों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


दस्तावेज़ में पास किए गए हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को अपडेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ में अपडेट किए जाने वाले हस्ताक्षर ऑब्जेक्ट। |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - सफलतापूर्वक अपडेट किए गए हस्ताक्षरों और विफल हुए हस्ताक्षरों की सूची के साथ UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) लौटाता है।

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


दस्तावेज़ से पास किया गया हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ से हटाने के लिए हस्ताक्षर ऑब्जेक्ट। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


दस्तावेज़ से पास किया गया हस्ताक्षर [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | दस्तावेज़ से हटाने के लिए हस्ताक्षर ऑब्जेक्ट। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | हस्ताक्षर | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | दस्तावेज़ से हटाने के लिए हस्ताक्षरों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


दस्तावेज़ से एक निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है।
केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) हटाए जाएंगे।
निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signatureType | int | दस्तावेज़ से हटाने के लिए हस्ताक्षरों का प्रकार। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


दस्तावेज़ से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है।
केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) हटाए जाएंगे।
निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | आउटपुट दस्तावेज़ स्ट्रीम। |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | दस्तावेज़ से हटाने के लिए हस्ताक्षर प्रकारों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


दस्तावेज़ से एक निश्चित प्रकार के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है।
केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) हटाए जाएंगे।
निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signatureType | int | दस्तावेज़ से हटाने के लिए हस्ताक्षरों का प्रकार। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


दस्तावेज़ से निश्चित प्रकारों की सूची के हस्ताक्षर [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) को हटाता है।
केवल वे हस्ताक्षर जो Sign मेथड द्वारा जोड़े गए थे और Signatures के रूप में चिह्नित हैं
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) हटाए जाएंगे।
निम्नलिखित हस्ताक्षर प्रकार समर्थित हैं: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइल पथ | java.lang.String | आउटपुट फ़ाइल पथ। |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | दस्तावेज़ से हटाने के लिए हस्ताक्षर प्रकारों की सूची। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


दस्तावेज़ से उसके विशिष्ट हस्ताक्षर Id द्वारा हस्ताक्षर को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureId | java.lang.String | दस्तावेज़ से हटाने के लिए हस्ताक्षर की Id। |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - यदि ऑपरेशन सफल रहा तो true लौटाता है।

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


दस्तावेज़ से पास की गई हस्ताक्षरों की सूची [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) को हटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | दस्तावेज़ से हटाने के लिए हस्ताक्षरों के पहचानकर्ताओं की सूची। |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


दिए गए SignOptions के आधार पर हस्ताक्षर प्रीव्यू उत्पन्न करता है। [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | दिए गए SignOptions के साथ प्रीव्यू हस्ताक्षर। [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


आंतरिक संसाधनों को साफ़ करने के लिए IDisposable इंटरफ़ेस को लागू करें


