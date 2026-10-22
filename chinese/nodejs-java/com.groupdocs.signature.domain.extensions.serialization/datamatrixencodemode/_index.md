---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "DataMatrix 编码器的编码模式默认为 Auto"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix 编码器的编码模式，默认自动。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Auto](#Auto) | 自动选择 DataMatrix 编码的最佳编码模式 |
| [ASCII](#ASCII) | 每字节编码一个字母数字字符或两个数字字符 |
| [Full](#Full) | 编码 8 位值 |
| [Custom](#Custom) | 使用 BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding 中指定的编码进行编码 |
| [C40](#C40) | 使用 C40 编码。 |
| [Text](#Text) | 使用 Text 编码。 |
| [EDIFACT](#EDIFACT) | 使用 EDIFACT 编码。 |
| [ANSIX12](#ANSIX12) | 使用 ANSI X12 编码。 |
| [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext 模式允许在代码文本中手动切换编码方案。 |
### Auto {#Auto}
```
public static final int Auto
```


自动选择 DataMatrix 编码的最佳编码模式

### ASCII {#ASCII}
```
public static final int ASCII
```


每字节编码一个字母数字字符或两个数字字符

### Full {#Full}
```
public static final int Full
```


编码 8 位值

### Custom {#Custom}
```
public static final int Custom
```


使用 BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding 中指定的编码进行编码

### C40 {#C40}
```
public static final int C40
```


使用 C40 编码。编码大写字母数字、小写字母和特殊字符

### Text {#Text}
```
public static final int Text
```


使用 Text 编码。编码小写字母数字、大写字母和特殊字符。

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


使用 EDIFACT 编码。每个字符使用六位，编码数字、大写字母和许多标点符号，但不支持小写字母。

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


使用 ANSI X12 编码。

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext 模式允许在代码文本中手动切换编码方案。格式：\"\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text\"。允许的编码方案有：EDIFACT、ANSIX12、ASCII、C40、Text、Auto。扩展代码文本示例：@\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText\" 文本中的所有反斜杠 (\\) 必须加倍。

