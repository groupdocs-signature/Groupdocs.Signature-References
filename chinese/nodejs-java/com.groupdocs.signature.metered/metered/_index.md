---
title: "计量"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "提供用于应用计量许可证的方法。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于应用  [Metered][]  许可证的方法。

--------------------

**Learn more**

 *  More about Metered licensing: [Metered Licensing FAQ][Metered]
 *  More about GroupDocs.Signature licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/signaturejava/Evaluation+Limitations+and+Licensing+of+GroupDocs.Signature
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 使用计量密钥激活产品。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 检索已处理的 MB 数量。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 检索已消耗的积分数量。 |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


使用计量密钥激活产品。

--------------------

> ```
> Following example demonstrates how to activate product with Metered keys.
>  
>  string publicKey = "Public Key";
>  string privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.SetMeteredKey(publicKey, privateKey);
> ```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公钥。 |
| privateKey | java.lang.String | 私钥。 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


检索已处理的 MB 数量。

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal mbProcessed = Metered.GetConsumptionQuantity();
> ```

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


检索已消耗的积分数量。

--------------------

> ```
> Following example demonstrates how to retrieve count of credits consumed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal creditsConsumed = Metered.GetConsumptionCredit();
> ```

**Returns:**
double
