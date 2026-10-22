---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Le mode d'encodage des encodeurs DataMatrix est par défaut Auto"
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Mode d'encodage de l'encodeur DataMatrix, par défaut sur Auto
## Champs

| Champ | Description |
| --- | --- |
| [Auto](#Auto) | Détecter automatiquement le meilleur mode d'encodage pour l'encodage DataMatrix |
| [ASCII](#ASCII) | Encode un caractère alphanumérique ou deux caractères numériques par octet |
| [Full](#Full) | Encode des valeurs 8 bits |
| [Custom](#Custom) | Encode avec l'encodage spécifié dans BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](#C40) | Utilise l'encodage C40. |
| [Text](#Text) | Utilise l'encodage Text. |
| [EDIFACT](#EDIFACT) | Utilise l'encodage EDIFACT. |
| [ANSIX12](#ANSIX12) | Utilise l'encodage ANSI X12. |
| [ExtendedCodetext](#ExtendedCodetext) | Le mode ExtendedCodetext permet de changer manuellement les schémas d'encodage dans le code-text. |
### Auto {#Auto}
```
public static final int Auto
```


Détecter automatiquement le meilleur mode d'encodage pour l'encodage DataMatrix

### ASCII {#ASCII}
```
public static final int ASCII
```


Encode un caractère alphanumérique ou deux caractères numériques par octet

### Full {#Full}
```
public static final int Full
```


Encode des valeurs 8 bits

### Custom {#Custom}
```
public static final int Custom
```


Encode avec l'encodage spécifié dans BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding

### C40 {#C40}
```
public static final int C40
```


Utilise l'encodage C40. Encode les caractères alphanumériques majuscules, minuscules et les caractères spéciaux

### Text {#Text}
```
public static final int Text
```


Utilise l'encodage Text. Encode les caractères alphanumériques minuscules, majuscules et les caractères spéciaux.

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Utilise l'encodage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreuses marques de ponctuation, mais ne prend pas en charge les lettres minuscules.

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Utilise l'encodage ANSI X12.

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Le mode ExtendedCodetext permet de changer manuellement les schémas d'encodage dans le code-text. Format : \"\\\\Encodation\\_scheme\\_name:text\\\\Encodation\\_scheme\\_name:text\". Les schémas d'encodage autorisés sont : EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Exemple de code-text étendu : @\"\\\\ansix12:ANSIX12TEXT\\\\ascii:backslash must be \\\\\\ doubled\\\\edifact:EdifactEncodedText\" Tous les antislashs (\\\\) doivent être doublés dans le texte.

