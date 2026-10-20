---
title: "DigitalSearchOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "डिजिटल हस्ताक्षर खोज के लिए मूल विकल्पों का प्रतिनिधित्व करता है"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

डिजिटल हस्ताक्षर खोज के लिए मूल विकल्पों का प्रतिनिधित्व करता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | डिफ़ॉल्ट मानों के साथ DigitalSearchOptions क्लास का नया उदाहरण प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getComments()](#getComments--) | खोज के लिए Digital सिग्नेचर की टिप्पणी। |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | खोज के लिए Digital सिग्नेचर की टिप्पणी। |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | खोज के लिए Digital सिग्नेचर की तिथि और समय सीमा। |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | खोज के लिए Digital सिग्नेचर की तिथि और समय सीमा। |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | खोज के लिए Digital Signature की तिथि और समय सीमा। |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | खोज के लिए Digital Signature की तिथि और समय सीमा। |
|
|  | [getSubjectName()](#getSubjectName--) | खाली न होने वाले मानों के लिए खोज हेतु प्रमाणपत्र के विशिष्ट विषय नाम को निर्दिष्ट करता है। |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | खाली न होने वाले मानों के लिए खोज हेतु प्रमाणपत्र के विशिष्ट विषय नाम को निर्दिष्ट करता है। |
|
|  | [getIssuerName()](#getIssuerName--) | खाली नहीं होने वाले मानों के लिए खोज हेतु प्रमाणपत्र जारीकर्ता का विशिष्ट नाम निर्दिष्ट करता है। |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | खाली नहीं होने वाले मानों के लिए खोज हेतु प्रमाणपत्र जारीकर्ता का विशिष्ट नाम निर्दिष्ट करता है। |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


डिफ़ॉल्ट मानों के साथ DigitalSearchOptions क्लास का नया उदाहरण प्रारंभ करता है।


### getComments() {#getComments--}
```
public final String getComments()
```


खोज के लिए Digital सिग्नेचर की टिप्पणी।


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


खोज के लिए Digital सिग्नेचर की टिप्पणी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


डिजिटल हस्ताक्षर की खोज के लिए तिथि और समय सीमा। nullable मान को नजरअंदाज किया जाएगा।


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


डिजिटल हस्ताक्षर की खोज के लिए तिथि और समय सीमा। nullable मान को नजरअंदाज किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


डिजिटल हस्ताक्षर की खोज के लिए तिथि और समय सीमा। nullable मान को नजरअंदाज किया जाएगा।


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


डिजिटल हस्ताक्षर की खोज के लिए तिथि और समय सीमा। nullable मान को नजरअंदाज किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


खाली न होने वाले मानों के लिए खोज हेतु प्रमाणपत्र के विशिष्ट विषय नाम को निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


खाली न होने वाले मानों के लिए खोज हेतु प्रमाणपत्र के विशिष्ट विषय नाम को निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


खाली नहीं होने वाले मानों के लिए खोज हेतु प्रमाणपत्र जारीकर्ता का विशिष्ट नाम निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


खाली नहीं होने वाले मानों के लिए खोज हेतु प्रमाणपत्र जारीकर्ता का विशिष्ट नाम निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

