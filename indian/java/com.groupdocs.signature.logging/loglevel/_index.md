---
title: "LogLevel"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "उपलब्ध लॉग लेवल प्रकारों को निर्दिष्ट करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

उपलब्ध लॉग लेवल प्रकारों को निर्दिष्ट करता है।
इस एनीमरेशन का उपयोग कई संभावित मानों को सक्षम बिट्स के रूप में सेट करने के लिए फ़्लैग्स के रूप में किया जा सकता है।
उदाहरण: LogLevel.Error \| LogLevel.Warning या LogLevel.Error \| LogLevel.Trace

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [None](#None) | कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी। |
|
|  | [Error](#Error) | कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी। |
|
|  | [Warning](#Warning) | All स्तर के समान, सभी संदेशों में ट्रेस स्तर भी शामिल होगा और लॉग किया जाएगा। |
|
|  | [Trace](#Trace) | चेतावनी से त्रुटि स्तर तक के संदेशों को शामिल करने के लिए लॉगिंग स्तर। |
|
|  | [All](#All) | सभी लॉग स्तर की घटनाएँ (त्रुटि, चेतावनी, ट्रेस) लॉगिंग में शामिल की जाएँगी। |
|
### None {#None}
```
public static final int None
```


कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी।


### Error {#Error}
```
public static final int Error
```


कोई लॉगिंग सीमा नहीं, सभी जानकारी ट्रेस, चेतावनी से लेकर त्रुटियों तक लॉग की जाएगी।


### Warning {#Warning}
```
public static final int Warning
```


All स्तर के समान, सभी संदेशों में ट्रेस स्तर भी शामिल होगा और लॉग किया जाएगा।


### Trace {#Trace}
```
public static final int Trace
```


चेतावनी से त्रुटि स्तर तक के संदेशों को शामिल करने के लिए लॉगिंग स्तर।


### All {#All}
```
public static final int All
```


सभी लॉग स्तर की घटनाएँ (त्रुटि, चेतावनी, ट्रेस) लॉगिंग में शामिल की जाएँगी।


