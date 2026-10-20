---
title: "GroupDocs.Signature.Domain.Extensions"
second_title: "Référence API de GroupDocs.Signature pour .NET"
description: "L’espace de noms fournit des extensions pour les apparences de signature et des fonctionnalités supplémentaires."
type: docs
weight: 30
url: /fr/net/groupdocs.signature.domain.extensions/
---
L’espace de noms fournit des extensions pour les apparences de signature et des fonctionnalités supplémentaires.

## Classes

| Classe | Description |
| --- | --- |
| [Address](./address) | Représente l'adresse du contact. |
| [Brush](./brush) | Représente la classe de base pour divers pinceaux. |
| [CryptoCurrencyTransfer](./cryptocurrencytransfer) | Représente le transfert de cryptomonnaie (réception ou envoi) pour QR-Code. |
| [DigitalVBA](./digitalvba) | Représente la signature numérique pour les projets VBA de Spreadsheets. Elle fournit la capacité de signer le projet VBA dans des formats de documents Spreadsheets spécifiques comme Xlsm ou Xltm. Si plusieurs extensions DigitalVBA sont ajoutées à DigitalSignOptions.Extensions, seule la première est impliquée dans la signature du document. |
| [Email](./email) | Représente le format Email pour QR-Code. |
| [EPC](./epc) | Représente le European Payments Council Quick Response Code. |
| [Event](./event) | Représente les détails standard d'un événement QR-Code. |
| [FormatAttribute](./formatattribute) | Indique à la sérialisation des objets de sérialiser le membre avec le nom et le format spécifiés. |
| [HIBCLICCombinedData](./hibcliccombineddata) | Classe pour stocker les données combinées HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) avec les entités de données primaires et secondaires. |
| [HIBCLICPrimaryData](./hibclicprimarydata) | Classe pour stocker les données primaires HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCLICSecondaryAdditionalData](./hibclicsecondaryadditionaldata) | Classe pour stocker les données secondaires et supplémentaires HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code). |
| [HIBCPASData](./hibcpasdata) | Classe pour encoder et décoder le texte intégré dans le code HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord) | Classe pour stocker l'enregistrement HIBC (Healthcare Industry Bar Code Council) PAS (Provider Applications Standard). |
| [LinearGradientBrush](./lineargradientbrush) | Représente un pinceau à dégradé linéaire. |
| [Mailmark2D](./mailmark2d) | Classe pour encoder et décoder le texte intégré dans le Royal Mail 2D Mailmark. |
| [MaxiCodeMode2](./maxicodemode2) | Classe pour encoder et décoder le texte intégré dans le code MaxiCode pour les modes. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage) | Classe pour encoder et décoder le second message standard pour le code-barres MaxiCode. |
| [MeCard](./mecard) | Représente les détails de contact standard MeCard. |
| [RadialGradientBrush](./radialgradientbrush) | Représente un pinceau à dégradé radial. |
| [SignatureExtension](./signatureextension) | Représente la classe de base pour les extensions de signatures. |
| [SkipSerializationAttribute](./skipserializationattribute) | Indique à la sérialisation d'ignorer le membre. |
| [SMS](./sms) | Représente les détails du service de messages courts SMS. |
| [SolidBrush](./solidbrush) | Représente un pinceau plein. Il peut être utilisé à la place de la propriété de couleur d'arrière-plan. |
| [SpreadsheetPosition](./spreadsheetposition) | Définit la position de la signature pour les documents de feuille de calcul. |
| [SwissAddress](./swissaddress) | Représente l'adresse du créancier ou du débiteur. Vous pouvez soit définir la rue, le numéro, le code postal et la ville (type d'adresse structurée), soit la ligne d'adresse 1 et 2 (type d'éléments d'adresse combinés). |
| [SwissQR](./swissqr) | Classe pour l'encodage et le décodage du texte intégré dans le code SwissQR. |
| [SymmetricEncryption](./symmetricencryption) | Implémente les algorithmes symétriques standards pour le chiffrement des données avec une clé unique et une phrase de passe (sel). |
| [SymmetricEncryptionAttribute](./symmetricencryptionattribute) | Indique à la sérialisation des instances de chiffrer/déchiffrer la chaîne de sérialisation d'objet. |
| [TextShadow](./textshadow) | Représente les propriétés d'ombre du texte pour les signatures de texte. Le résultat peut varier en fonction du type de signature et du format du document. TextShadow est recommandé pour une utilisation avec la signature TextAsImage pour tous les types de documents pris en charge, ainsi qu'avec la simple TextSignature et TextSignature en tant que filigrane pour les feuilles de calcul (.xslx) et les présentations (.pptx). La simple TextSignature pour Words (.docx) est également recommandée, mais possède des fonctionnalités limitées. |
| [TextureBrush](./texturebrush) | Représente un pinceau à texture. |
| [VCard](./vcard) | Représente les coordonnées standard d'une carte de visite électronique. |
| [WiFi](./wifi) | Représente les détails de connexion au réseau WiFi. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDataEncryption](./idataencryption) | Interface de chiffrement fournissant des méthodes d'encodage et de décodage d'objets. |
| [IDataSerializer](./idataserializer) | Interface de sérialisation fournissant des méthodes de sérialisation et de désérialisation d'objets. |
## Énumération

| Énumération | Description |
| --- | --- |
| [CryptoCurrencyType](./cryptocurrencytype) | Représente le type de cryptomonnaie. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Mode d'encodage de l'encodeur DataMatrix, par défaut sur Auto. |
| [HIBCLICDateFormat](./hibclicdateformat) | Spécifie les différents types de formats de date pour HIBC (Healthcare Industry Bar Code) LIC (Licensed Identification Code). |
| [HIBCPASDataLocation](./hibcpasdatalocation) | Spécifie les types d'emplacement des données HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [HIBCPASDataType](./hibcpasdatatype) | Spécifie les différents types de données du registre HIBC PAS. HIBC - Healthcare Industry Bar Code PAS - Provider Applications Standard. |
| [Mailmark2DType](./mailmark2dtype) | Le type 2D Mailmark définit la taille du code-barres Data Matrix. |
| [SymmetricAlgorithmType](./symmetricalgorithmtype) | Représente le type d'algorithme de chiffrement symétrique. |
| [WiFiEncryptionType](./wifiencryptiontype) | Représente le type de chiffrement WiFi. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
