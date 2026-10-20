---
title: "ProcessStartEventHandler"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 검증 및 검색의 시작 이벤트에서 프로세스를 처리할 메서드 대리자를 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

서명, 검증 및 검색에 대한 시작 이벤트를 처리할 메서드 대리자를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Signature signature, ProcessStartEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-) |  |
### ProcessStartEventHandler() {#ProcessStartEventHandler--}
```
public ProcessStartEventHandler()
```


### invoke(Signature signature, ProcessStartEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-}
```
public abstract void invoke(Signature signature, ProcessStartEventArgs args)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

