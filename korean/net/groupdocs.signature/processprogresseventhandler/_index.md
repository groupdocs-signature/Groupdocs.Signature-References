---
title: ProcessProgressEventHandler
second_title: .NET API 참조용 GroupDocs.Signature
description: 서명 확인 및 검색을 위한 진행 이벤트에 대한 프로세스를 처리할 메서드 대리자를 나타냅니다.
type: docs
weight: 1850
url: /ko/net/groupdocs.signature/processprogresseventhandler/
---
## ProcessProgressEventHandler delegate

서명, 확인 및 검색을 위한 진행 이벤트에 대한 프로세스를 처리할 메서드 대리자를 나타냅니다.

```csharp
public delegate void ProcessProgressEventHandler(Signature signature, 
    ProcessProgressEventArgs args);
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signature | Signature | 서명 개체 |
| args | ProcessProgressEventArgs | 인수[`ProcessProgressEventArgs`](../processprogresseventargs)Progress 이벤트의 속성을 지정합니다. |

### 또한보십시오

* class [Signature](../signature)
* class [ProcessProgressEventArgs](../processprogresseventargs)
* 네임스페이스 [GroupDocs.Signature](../../groupdocs.signature)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->