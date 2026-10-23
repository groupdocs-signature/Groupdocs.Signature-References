---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης Padding με μηδενικές τιμές."
type: docs
url: /el/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της κλάσης Padding με μηδενικές τιμές.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.signature.domain import Padding

# Δημιουργήστε ένα αντικείμενο padding με προεπιλεγμένες (μηδενικές) τιμές
default_padding = Padding()
```

## __init__ {#all}

Αρχικοποιεί μια νέα παρουσία της κλάσης Padding χρησιμοποιώντας το παρεχόμενο μέγεθος περιθωρίου για όλες τις άκρες.

```python
def __init__(self, all):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| all | `int` | Ο αριθμός των μονάδων μέτρησης που θα χρησιμοποιηθούν για padding σε όλες τις άκρες. |

### Παράδειγμα

```python
# Ομοιόμορφο περιθώριο 5 μονάδων σε όλες τις πλευρές
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Αρχικοποιεί μια νέα παρουσία της κλάσης Padding χρησιμοποιώντας τα παρεχόμενα μεγέθη περιθωρίων.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| left | `int` | Το μέγεθος του padding αριστερά. |
| right | `int` | Το μέγεθος του padding δεξιά. |
| top | `int` | Το μέγεθος του padding πάνω. |
| bottom | `int` | Το μέγεθος του padding κάτω. |

### Παράδειγμα

```python
from groupdocs.signature.domain import Padding

# Δημιουργήστε padding με μετατοπίσεις δεξιά και κάτω
margin = Padding(right=40, bottom=60)
```

### Δείτε επίσης
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
