---
title: Anwendungsinformationen für Trivia von Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Trivia, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f13ce283151405688c68d16c79d7d68498a3635e
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093234"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 13. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Springworks HR Tech an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Trivia |
| ID | WA200001956 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Springworks HR Tech |
| URL der Partnerwebsite | [https://springworks.in/](https://springworks.in/) |
| URL Teams Anwendungsinfoseite | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL der Datenschutzrichtlinie | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL der Nutzungsbedingungen | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Springworks HR Tech bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | delegierte | Nein | So erhalten Sie die Teams, zu der der Benutzer gehört | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | delegierte | Ja, Speichern der Liste der Teams, in denen der Bot hinzugefügt wurde | So sammeln Sie grundlegende Informationen zu allen teams, die in einem Arbeitsbereich vorhanden sind | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | delegierte | Ja, zum Speichern der eindeutigen aadObjectId eines Benutzers. Auch verschiedene Details des Benutzers wie Benutzername, E-Mail usw. und Anzeigen im Trivia-Dashboard | So erhalten Sie die Details aller Benutzer, die in einem Arbeitsbereich vorhanden sind | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | delegierte | Ja, um die Benutzer zu speichern, die sich bei der App anmelden. |  So ermöglichen Sie es dem Benutzer, die App mit seinem Konto zu verwenden, und die App, um die Daten des Benutzers zu verwenden | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Profil | delegierte | Ja, um die Benutzer-IDs und Namen von Hosts von Quizzes und anderen Features zu speichern und sie eindeutig zu identifizieren | So lesen Sie die grundlegenden Profilinformationen des Benutzers wie Benutzername, E-Mail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe.  | Kundenname, E-Mail, IP, Zahlungsinformationen | Wir verwenden diese Drittanbieter, um unseren Kunden die beste Kundenerfahrung zu bieten. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Diese Daten werden zum Anzeigen und Speichern der Liste der Teilnehmer an einem Quiz und anderen features verwendet. | Name, E-Mail | Ja, das Speichern der Daten des Hosts und der Teilnehmer von Quiz und anderen Funktionen für die Analyse und Kommunikation mit dem Host bei Fehlern |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>OII: Organisationsname, Mandanten-ID in Protokollen angezeigt; EUII: aad-Objekt-ID, vollständiger Name, E-Mail werden in Protokollen angezeigt. Wir haben einen Aufbewahrungszeitraum von 30 Tagen, der automatisch gelöscht wird. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten, die in RDS, AWS, gespeichert sind. es ist verschlüsselt. Zugriff ist nur für einen DevOps, Engineering Lead und Gründer

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Springworks HR Tech dazu bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
