---
title: LogLevel
second_title: GroupDocs.Signature لمرجع .NET API
description: تحديد أنواع مستوى السجل المتاحة. يمكن استخدام هذا التعداد كعلامات لتعيين العديد من القيم الممكنة على أنها تمكين bits مثال LogLevel.Error x7C LogLevel.Warning أو LogLevel.Error x7C مستوى السجل. تتبع
type: docs
weight: 1170
url: /ar/net/groupdocs.signature.logging/loglevel/
---
## LogLevel enumeration

تحديد أنواع مستوى السجل المتاحة. يمكن استخدام هذا التعداد كعلامات لتعيين العديد من القيم الممكنة على أنها تمكين bits مثال: LogLevel.Error &#x7C; LogLevel.Warning أو LogLevel.Error &#x7C; مستوى السجل. تتبع

```csharp
[Flags]
public enum LogLevel
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| None | `0` | لا قيود على التسجيل ، سيتم تسجيل جميع المعلومات من التتبع ، تحذير من الأخطاء |
| Error | `1` | لا قيود على التسجيل ، سيتم تسجيل جميع المعلومات من التتبع ، تحذير من الأخطاء |
| Warning | `2` | مثل مستوى الكل ، سيتم تسجيل جميع الرسائل بما في ذلك مستوى التتبع |
| Trace | `4` | مستوى التسجيل لتضمين الرسائل من مستوى التحذير إلى الخطأ |
| All | `7` | سيتم تضمين كافة أحداث مستوى السجل (خطأ ، تحذير ، تتبع) في logging |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature.Logging](../../groupdocs.signature.logging)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->