---
title: "SwissQR"
second_title: "GroupDocs.Signature for Java API 参考"
description: "用于对嵌入 SwissQR 代码中的文本进行编码和解码的类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

用于对嵌入 SwissQR 代码中的文本进行编码和解码的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | 创建 SwissQR 的实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAmount()](#getAmount--) | 获取或设置付款金额。 |
|
|  | [setAmount(double value)](#setAmount-double-) | 获取或设置付款金额。 |
|
|  | [getCurrency()](#getCurrency--) | 获取或设置付款货币。 |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | 获取或设置付款货币。 |
|
|  | [getAccount()](#getAccount--) | 获取或设置债权人的账户号码。 |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | 获取或设置债权人的账户号码。 |
|
|  | [getCreditor()](#getCreditor--) | 获取或设置债权人地址。 |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 获取或设置债权人地址。 |
|
|  | [getReference()](#getReference--) | 获取或设置债权人付款参考。 |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 获取或设置债权人付款参考。 |
|
|  | [getDebtor()](#getDebtor--) | 获取或设置债务人地址。 |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 获取或设置债务人地址。 |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | 获取或设置附加的非结构化消息。 |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 获取或设置附加的非结构化消息。 |
|
|  | [getBillInformation()](#getBillInformation--) | 获取或设置附加的结构化账单信息。 |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 获取或设置附加的结构化账单信息。 |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


创建 SwissQR 的实例。


### getAmount() {#getAmount--}
```
public final double getAmount()
```


获取或设置付款金额。
有效值范围为 0.01 到 999,999,999.99。
值：付款金额。


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


获取或设置付款金额。
有效值范围为 0.01 到 999,999,999.99。
值：付款金额。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


获取或设置付款货币。
有效值为 "CHF" 和 "EUR"。
值：付款货币。


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


获取或设置付款货币。
有效值为 "CHF" 和 "EUR"。
值：付款货币。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


获取或设置债权人的账户号码。
账户号码必须是瑞士或列支敦士登银行的有效 IBAN。
账户号码中允许有空格。
值：收款人账户号码。


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


获取或设置债权人的账户号码。
账户号码必须是瑞士或列支敦士登银行的有效 IBAN。
账户号码中允许有空格。
值：收款人账户号码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


获取或设置债权人地址。
值：收款人地址。


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


获取或设置债权人地址。
值：收款人地址。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


获取或设置债权人付款参考。
对于 SwissQR IBAN，即范围在 CHxx30000xxxxxx 之间的 IBAN，参考号是必填的
至 CHxx31999xxxxx。
如果指定，参考号必须是有效的 SwissQR 参考（对应
ISR 参考表格）或符合 ISO 11649 的有效收款人参考（"RFxxxx"）。
两者都可以包含空格用于格式化。
值：收款人付款参考。


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


获取或设置债权人付款参考。
对于 SwissQR IBAN，即范围在 CHxx30000xxxxxx 之间的 IBAN，参考号是必填的
至 CHxx31999xxxxx。
如果指定，参考号必须是有效的 SwissQR 参考（对应
ISR 参考表格）或符合 ISO 11649 的有效收款人参考（"RFxxxx"）。
两者都可以包含空格用于格式化。
值：收款人付款参考。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


获取或设置债务人地址。
债务人是可选的。如果省略，则将此字段设为 null 或
将地址的所有值设为 null 或空也是可以的。
值：债务人地址。


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


获取或设置债务人地址。
债务人是可选的。如果省略，则将此字段设为 null 或
将地址的所有值设为 null 或空也是可以的。
值：债务人地址。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


获取或设置附加的非结构化消息。
值：非结构化消息。


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


获取或设置附加的非结构化消息。
值：非结构化消息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


获取或设置附加的结构化账单信息。
值：结构化账单信息。


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


获取或设置附加的结构化账单信息。
值：结构化账单信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

