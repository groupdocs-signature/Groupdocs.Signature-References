---
title: "Clase SwissAddress"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Representa la dirección del acreedor o deudor."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Representa la dirección del acreedor o deudor.

Puede establecer la calle, el número de casa, el código postal y la ciudad (tipo de dirección estructurada) o la línea de dirección 1 y 2 (tipo de elementos de dirección combinados).

El tipo SwissAddress expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | La línea de dirección 1, que contiene el nombre de la calle, el número de casa o el apartado postal, es opcional y se usa solo para direcciones de elementos combinados. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | La línea de dirección 2, que contiene el código postal y la ciudad, es obligatoria para direcciones de elementos combinados. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | El código de país ISO de dos letras. El código de país es obligatorio a menos que toda la dirección contenga valores nulos o vacíos. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | El número de casa. Este campo solo se usa para direcciones estructuradas y es opcional. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | El nombre, ya sea el nombre y apellido de una persona natural o el nombre de la empresa de una persona jurídica. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | El código postal. Este campo solo se usa para direcciones estructuradas. Para este tipo, es obligatorio. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | La calle de la dirección, sin número de casa; opcional y usada solo para direcciones estructuradas. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | La ciudad o pueblo, usada solo para direcciones estructuradas y obligatoria para este tipo. |

### Ver también
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
