---
title: "propriété log_level"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Les indicateurs de niveau de journalisation qui déterminent quels types de messages sont transmis à SignatureSettings.Logger."
type: docs
url: /fr/python-net/groupdocs.signature/signaturesettings/log_level/
is_root: false
weight: 2030
---


## log_level property

Les indicateurs de niveau de journal qui déterminent quels types de messages sont transmis à [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/).

La valeur est un ensemble de drapeaux `LogLevel` qui peuvent être combinés, par exemple `LogLevel.Error | LogLevel.Warning`. `LogLevel.None` ne journalise rien. La valeur par défaut est `LogLevel.All` : erreurs, avertissements et traces.

### Definition:
```python
@property
def log_level(self):
    ...
@log_level.setter
def log_level(self, value):
    ...
```

### Voir aussi
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/)
