---
title: "propiedad data_encryption"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "La implementación de IDataEncryption utilizada para descifrar todas las firmas de metadatos dentro de esta colección de opciones."
type: docs
url: /es/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/
is_root: false
weight: 2010
---


## data_encryption property

La implementación de [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) utilizada para descifrar todas las firmas de metadatos dentro de esta colección de opciones.

Si está configurado, todas las firmas encontradas usarán este cifrado por defecto a menos que tengan su propio DataEncryption asignado.

### Definition:
```python
@property
def data_encryption(self):
    ...
@data_encryption.setter
def data_encryption(self, value):
    ...
```

### Ver también
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
