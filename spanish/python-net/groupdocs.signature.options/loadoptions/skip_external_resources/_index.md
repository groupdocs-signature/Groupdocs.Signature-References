---
title: "propiedad skip_external_resources"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El indicador que impide que el documento cargue recursos externos."
type: docs
url: /es/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/
is_root: false
weight: 2050
---


## skip_external_resources property

La bandera que impide que el documento cargue recursos externos. El valor predeterminado es True; los recursos externos no se cargan excepto aquellos que coinciden con [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

Un documento puede referirse a recursos almacenados fuera de él, como imágenes vinculadas, imágenes insertadas mediante un campo INCLUDEPICTURE, imágenes vinculadas en presentaciones y hojas de cálculo, e imágenes y hojas de estilo referenciadas por una imagen SVG. Cargar dicho recurso hace que la biblioteca solicite su dirección. En un servidor que procesa documentos no confiables, un documento podría usar esto para que el servidor envíe solicitudes a direcciones internas (falsificación de solicitudes del lado del servidor), y una ruta UNC o `file://` podría hacer que Windows envíe las credenciales NTLM de la cuenta a otro host. En una instalación sin conexión o aislada, las solicitudes fallan o esperan un tiempo de espera.

Los recursos que se omiten no se dibujan en las vistas previas de página ni en los documentos guardados como imágenes, y la búsqueda de imágenes, códigos de barras y códigos QR no los detecta. Establezca esta propiedad en False solo para documentos de confianza, y prefiera permitir direcciones específicas con [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/).

La configuración se aplica a documentos de procesamiento de texto, presentaciones, hojas de cálculo e imágenes SVG, incluidos los documentos dentro de archivos. Para imágenes SVG, las referencias que no están permitidas se eliminan de la imagen antes de leerla, y una imagen SVG que no sea XML bien formado se rechaza. La configuración no controla las comprobaciones de revocación de certificados, los servidores de sellado de tiempo ni la licencia.

Esta propiedad reemplaza a [`LoadOptions.LoadExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/), que tiene el significado opuesto.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Ver también
* class [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/)
