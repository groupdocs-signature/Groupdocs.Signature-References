---
title: "BaseSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "描述签名的基类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

描述签名的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | 指定签名的类型。 |
|
|  | [getPageNumber()](#getPageNumber--) | 指定签名所在的页面。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 指定签名所在的页面。 |
|
|  | [getSignatureId()](#getSignatureId--) | 用于在文档中通过 Update 或 Delete 方法修改签名的唯一签名标识符。 |
|
|  | [isSignature()](#isSignature--) | 获取或设置标志，以指示此组件是签名还是文档内容。 |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | 获取或设置标志，以指示此组件是签名还是文档内容。 |
|
|  | [getDeleted()](#getDeleted--) | 获取或设置标志，以指示此签名是否已从文档中删除。 |
|
|  | [getCreatedOn()](#getCreatedOn--) | 获取或设置签名创建日期。 |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | 获取或设置签名创建日期。 |
|
|  | [getModifiedOn()](#getModifiedOn--) | 获取或设置签名修改日期。 |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | 获取或设置签名修改日期。 |
|
|  | [getTop()](#getTop--) | 指定签名的顶部位置。 |
|
|  | [setTop(int value)](#setTop-int-) | 指定签名的顶部位置。 |
|
|  | [getLeft()](#getLeft--) | 指定签名的左侧位置。 |
|
|  | [setLeft(int value)](#setLeft-int-) | 指定签名的左侧位置。 |
|
|  | [getWidth()](#getWidth--) | 指定签名的宽度。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 指定签名的宽度。 |
|
|  | [getHeight()](#getHeight--) | 指定签名的高度。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 指定签名的高度。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


指定签名的类型。数字签名将具有此属性。


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


指定签名所在的页面。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


指定签名所在的页面。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


用于在文档中通过 Update 或 Delete 方法修改签名的唯一签名标识符。
在调用 Sign 或 Search 方法后，此属性将自动设置。
如果此属性之前已保存，则可以手动设置以操作签名。


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


获取或设置标志，以指示此组件是签名还是文档内容。
此属性与 Update 方法一起使用，用于将元素设置为签名（true）或文档元素（false）。


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


获取或设置标志，以指示此组件是签名还是文档内容。
此属性与 Update 方法一起使用，用于将元素设置为签名（true）或文档元素（false）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


获取或设置标志，以指示此签名是否已从文档中删除。
此属性仅用于文档历史日志记录，以保留已删除签名的列表。


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


获取或设置签名创建日期。


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


获取或设置签名创建日期。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


获取或设置签名修改日期。


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


获取或设置签名修改日期。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


指定签名的顶部位置。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


指定签名的顶部位置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


指定签名的左侧位置。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


指定签名的左侧位置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


指定签名的宽度。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


指定签名的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


指定签名的高度。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


指定签名的高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


覆盖 Equals 方法以比较签名属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 签名 | java.lang.Object | 用于比较的签名对象。 |
|

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String - 
