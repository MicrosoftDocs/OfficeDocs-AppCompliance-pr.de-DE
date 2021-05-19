---
title: Anwendungsinformationen für Trivia von Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Trivia, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553846"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 13. Januar 2021</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Springworks HR Tech Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Trivia |
| ID | WA200001956 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Springworks HR Tech |
| URL der Partner-Website | [https://springworks.in/](https://springworks.in/) |
| URL Teams Anwendungsinfoseite | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL der Datenschutzrichtlinie | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL der Nutzungsbedingungen | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Springworks HR Tech darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Delegiert | Nein | So erhalten Sie die Liste der Teams, an denen der Benutzer teilnimmt | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | Delegiert | Ja, die Liste der Teams, in denen der Bot hinzugefügt wurde, wird gespeichert | So sammeln Sie grundlegende Informationen zu allen Teams, die in einem Arbeitsbereich vorhanden sind | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | Delegiert | Ja, zum Speichern der eindeutigen aadObjectId eines Benutzers. Auch verschiedene Details des Benutzers wie Benutzername, E-Mail, etc. und zeigen Sie es auf dem Trivia Dashboard | So erhalten Sie die Details aller Benutzer, die in einem Arbeitsbereich vorhanden sind | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | Delegiert | Ja, um die Benutzer zu speichern, die sich bei der App anmelden. |  Damit sowohl der Benutzer die App mit seinem Konto als auch die App die Daten des Benutzers verwenden kann | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Profil | Delegiert | Ja, um die Benutzer-IDs und Namen von Hosts von Quizfragen und anderen Funktionen zu speichern und diese eindeutig zu identifizieren | So lesen Sie die grundlegenden Profilinformationen des Benutzers wie Benutzername, E-Mail | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe.  | Kundenname, E-Mail, IP, Zahlungsinformationen | Wir nutzen diese Dritten, um unseren Kunden das beste Kundenerlebnis zu bieten |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Diese Daten werden verwendet, um die Teilnehmerliste in einem Quiz und anderen Solchen Funktionen anzuzeigen und zu speichern. | Name, E-Mail | Ja, Speicherung der Daten des Hosts und der Teilnehmer von Quizfragen und anderen Funktionen für Analysen und Kommunikation mit dem Host im Fehlerfall |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>OII: Organisationsname, Mandanten-ID wird in Protokollen angezeigt; EUII: aad Object ID, voller Name, E-Mail in den Protokollen angezeigt. wir haben eine 30-Tage-Aufbewahrungsfrist Post, die die Protokolle automatisch gelöscht wird. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>In RDS, AWS gespeicherte Daten. es ist verschlüsselt. Der Zugang erfolgt nur für einen DevOps Ingenieur, Engineering Lead und Gründer

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Springworks HR Tech darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
