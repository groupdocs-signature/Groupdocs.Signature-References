---
title: "log_level egenskap"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Loggnivåflaggorna som bestämmer vilka typer av meddelanden som skickas till SignatureSettings.Logger."
type: docs
url: /sv/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Loggnivåflaggorna som bestämmer vilka typer av meddelanden som skickas till [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

Värdet är en uppsättning `LogLevel`‑flaggor som kan kombineras, till exempel `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` loggar ingenting. Standardvärdet är `LogLevel.All`: fel, varningar och spår.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Se även
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
