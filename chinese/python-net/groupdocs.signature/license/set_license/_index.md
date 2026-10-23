---
title: "set_license 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "为当前进程应用许可证。"
type: docs
url: /zh/python-net/groupdocs.signature/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

为当前进程应用许可证。

```python
def set_license(self, license_source):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| license_source |  | 可以是指向 ``.lic`` 文件的字符串路径，或是可读取的类文件对象（file-like object），该对象会产生许可证字节。类文件输入会先写入临时文件，然后再传递给桥接层。 |

| 引发 | 描述 |
| :- | :- |
| `TypeError` | 如果 ``license_source`` 既不是字符串路径，也不是可读取的类文件对象。 |

### 另见
* class [`License`](/signature/python-net/groupdocs.signature/license/)
