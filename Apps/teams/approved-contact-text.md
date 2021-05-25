---
title: Anwendungsinformationen für Text von genehmigten Kontakten
ms.author: elmalova
author: elenamalova
ms.date: 05/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 'Alle verfügbaren Sicherheits- und Complianceinformationen für Text, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security Informationen zum #A0 sowie Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.'
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8d9e5cfd3b082692656c7bb9a67417564cf7ab57
ms.sourcegitcommit: abce882d3e2ca5b9b0b47fc4a26c01e6e111a9b4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/24/2021
ms.locfileid: "52629660"
---
# <a name="text"></a>Text

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 10. Mai 2021</p>

* <a href="https://teams.microsoft.com/l/app/a622ceb4-b6e2-4557-8218-e22e80975ba4" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000383" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Vom genehmigten Kontakt an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Text |
| ID | WA200000383 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Approved Contact |
| URL der Partnerwebsite | [www.approvedcontact.com](www.approvedcontact.com) |
| URL der Datenschutzrichtlinie | [https://sales.approvedcontact.com/wp-content/uploads/text-p...](https://sales.approvedcontact.com/wp-content/uploads/text-privacy-policy.pdf) |
| URL der Nutzungsbedingungen | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden vom genehmigten Kontakt bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegierte | Für den Text BOT erfassen wir die Team-ID zum Erstellen zukünftiger Kanäle für eingehende Textnachrichten. | Ermöglicht es uns, Teams für Benutzer zu erstellen. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| E-Mail | delegierte | E-Mail-Adressen | Abrufen von Benutzerkontaktinformationen. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| offline_access | delegierte | Aktualisierungstoken werden in unserer Datenbank gespeichert. | Wird verwendet, um Aktualisierungstoken in unserer Datenbank zu speichern | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| openid | delegierte | Anmeldeinformationen | Ermöglicht dem Benutzer die Anmeldung. so, dass Texte in Teams werden können | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| Profil | delegierte | E-Mail-Adressen | Abrufen von Benutzerkontaktinformationen. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Wird verwendet, um Aktualisierungstoken in unserer Datenbank zu speichern | Wir speichern E-Mail-Adressen. | Wird verwendet, um Aktualisierungstoken in unserer Datenbank zu speichern |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Ja, wir protokollieren E-Mail-Adressen zum Verbinden von Lizenzkäufen mit Commercial Appsource. Wir bieten die Möglichkeit, diese Informationen aus unseren Protokollen zu löschen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Nur Entwickler haben Zugriff auf unsere Protokolle. Wir erzwingen 2FA für den Zugriff auf alle Entwicklungsplattformen.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Approved Contact darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Macht Ihre App Web-APIs verfügbar? | Nein |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
