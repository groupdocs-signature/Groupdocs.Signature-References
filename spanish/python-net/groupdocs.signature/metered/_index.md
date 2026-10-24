---
title: "Clase Metered"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Administra la licencia medida (pago por uso)."
type: docs
url: /es/python-net/groupdocs.signature/metered/
is_root: false
weight: 40
---


## Metered class

Administra la licencia medida (pago por uso).

Las licencias Metered facturan según el consumo real (normalmente páginas o
documentos procesados). Establezca el par de claves pública/privada una vez en
el inicio de la aplicación; el contenedor informa del uso al servidor de GroupDocs
de licencias en segundo plano.

El tipo Metered expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get_consumption_credit](/signature/python-net/groupdocs.signature/metered/get_consumption_credit/) | Devuelve el número de créditos consumidos hasta ahora. |
| [get_consumption_quantity](/signature/python-net/groupdocs.signature/metered/get_consumption_quantity/) | Devuelve la cantidad de datos procesados hasta ahora. |
| [set_metered_key](/signature/python-net/groupdocs.signature/metered/set_metered_key/#public_key-private_key) | Active la facturación medida con el par de claves pública/privada proporcionado. |

### Ver también
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
