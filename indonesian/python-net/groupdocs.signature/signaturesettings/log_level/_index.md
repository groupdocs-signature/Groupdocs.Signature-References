---
title: "properti log_level"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Bendera level log yang menentukan jenis pesan apa yang diteruskan ke SignatureSettings.Logger."
type: docs
url: /id/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Flag level log yang menentukan jenis pesan apa yang diteruskan ke [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

Nilai adalah sekumpulan flag `LogLevel` yang dapat digabungkan, misalnya `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` tidak mencatat apa pun. Defaultnya adalah `LogLevel.All`: error, peringatan, dan jejak.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Lihat Juga
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
