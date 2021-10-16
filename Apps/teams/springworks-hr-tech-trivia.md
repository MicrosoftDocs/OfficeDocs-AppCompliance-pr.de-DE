---
title: Anwendungsinformationen für Trivia von Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Trivia, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f2e79a1843977a1c8c1ea0f62259cfa4bde8f076
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410849"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: January 13, 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen von Springworks HR Tech an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Trivia |
| ID | WA200001956 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Springworks HR Tech |
| URL der Partnerwebsite | [https://www.springworks.in](https://www.springworks.in) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL der Datenschutzrichtlinie | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL der Nutzungsbedingungen | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Springworks HR Tech darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | Delegiert | Nein | So rufen Sie die Liste der Teams ab, zu denen der Benutzer gehört | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Team.ReadBasic.All | Delegiert | Ja, speichern der Liste der Teams, in denen der Bot hinzugefügt wurde | So sammeln Sie grundlegende Informationen zu allen Teams, die in einem Arbeitsbereich vorhanden sind | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| User.Read.All | Delegiert | Ja, zum Speichern eindeutiger aadObjectId eines Benutzers. Außerdem werden verschiedene Details des Benutzers wie Benutzername, E-Mail usw. angezeigt und im Trivia-Dashboard angezeigt. | So rufen Sie die Details aller Benutzer ab, die in einem Arbeitsbereich vorhanden sind | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| openid | Delegiert | Ja, um die Benutzer zu speichern, die sich bei der App anmelden. |  So ermöglichen Sie sowohl dem Benutzer, die App mit ihrem Konto zu verwenden, als auch der App, die Daten des Benutzers zu verwenden | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |
>| Profil | Delegiert | Ja, um die Benutzer-IDs und Namen von Hosts von Quizfragen und anderen Features zu speichern und eindeutig zu identifizieren | So lesen Sie die grundlegenden Profilinformationen des Benutzers wie Benutzername, E-Mail | [43bc466a-7678-476f-b904-2d933c5bbfc3](https://docs.microsoft.com/microsoft-365-app-certification/azure/43bc466a-7678-476f-b904-2d933c5bbfc3) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| AWS, Mailchimp, Stripe.  | Kundenname, E-Mail, IP, Zahlungsinformationen | Wir verwenden diese Drittanbieter, um unseren Kunden die beste Benutzererfahrung zu bieten. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Diese Daten werden verwendet, um die Liste der Teilnehmer in einem Quiz und andere features anzuzeigen und zu speichern. | Name, E-Mail | Ja, das Speichern der Daten des Hosts und der Teilnehmer von Quizfragen und anderer Features für Analysen und die Kommunikation mit dem Host bei Fehlern |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>OII: Organisationsname, Mandanten-ID in Protokollen; EUII: aad-Objekt-ID, vollständiger Name, E-Mail-Adresse werden in Protokollen angezeigt. Wir haben einen Aufbewahrungszeitraum von 30 Tagen, nach dem die Protokolle automatisch gelöscht werden. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Daten, die in RDS, AWS gespeichert sind. es ist verschlüsselt. Zugriff ist nur für einen DevOps Engineer, Engineering Lead und Gründer

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Springworks HR Tech darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

