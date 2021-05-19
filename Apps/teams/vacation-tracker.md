---
title: Anwendungsinformationen für Vacation Tracker von Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für Vacation Tracker, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550995"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 5. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Von Vacation Tracker an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Vacation Tracker |
| ID | WA200002167 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Vacation Tracker |
| URL der Partner-Website | [https://vacationtracker.io](https://vacationtracker.io) |
| URL Teams Anwendungsinfoseite | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL der Datenschutzrichtlinie | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Vacation Tracker darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Delegiert | Wir lesen öffentliche Kanal-IDs und Namen, wenn Benutzer ihre wöchentlichen oder täglichen Benachrichtigungen festlegen. | Benutzer können einen Kanal auswählen, in dem sie tägliche oder wöchentliche Benachrichtigungen von Vacation Tracker erhalten möchten. Wenn ein Benutzer seinen bevorzugten Kanal wählt, speichern wir die Kanal-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | Delegiert | Wir listen die Microsoft Teams Teams, die während der Anmeldung beigetreten sind, auf, damit Benutzer ein Team auswählen können, das sie für Vacation Tracker anmelden möchten. Sie können sich alternativ bei ihrer gesamten Organisation anmelden. | Wir speichern die Microsoft Teams Team-ID für ein ausgewähltes Team nur, wenn sich der Benutzer als einzelnes Team (nicht als gesamtorganisation) für Vacation Tracker anmeldet. Wir verwenden Team-IDs, um einen angemeldeten Benutzer mit einem vorhandenen Konto in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | Delegiert | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | Delegiert | Unsere Benutzer können alle Benutzer aus ihrer Microsoft 365 Organisation oder Microsoft Teams-Team importieren. Wir verwenden diese Berechtigung, um nur lizenzierte Benutzer für eine ausgewählte Microsoft Teams Team oder Organisation zu importieren. | Wir speichern grundlegende Informationen zu importierten Benutzern, einschließlich ihres Namens, ihrer E-Mail-Adresse und der Benutzer-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | Delegiert | Wir ermöglichen es Benutzern, die anderen Benutzer aus ihrer Organisation oder ihrem Microsoft Teams-Team zu importieren. Wir verwenden diese Berechtigung, um die verfügbaren Benutzer und ihre E-Mail-Adressen im Import-Popup aufzulisten. | Wenn Benutzer ihre Kollegen auswählen, die in Vacation Tracker importiert werden sollen, speichern wir grundlegende Informationen zu diesen importierten Benutzern, einschließlich ihres Namens, ihrer E-Mail-Adresse und der Benutzer-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | Delegiert | Wenn sich benutzerzeichen mit Microsoft AAD angemeldet wird, speichern wir seine E-Mail-Adresse als eindeutige Kennung. | Wir speichern die E-Mail-Adresse des Benutzers als eindeutige Kennung. Wir verwenden diese E-Mail nicht für die Kommunikation, Benutzer geben ihre geschäftliche E-Mail-Adresse ein, die wir während der Anmeldung für die Kommunikation verwenden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | Delegiert | Wir erheben keine Daten mit dieser Erlaubnis. Es wird verwendet, um den Zugriff auf Daten zu erhalten, auf die wir zugreifen dürfen. | Wir speichern keine Daten mit dieser Berechtigung. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | Delegiert | Wir verwenden diese Berechtigung, um sich bei Vacation Tracker anzumelden oder anzumelden. Wir erheben keine spezifischen Daten mit dieser Berechtigung. | Wir verwenden diese Berechtigung, um sich bei Vacation Tracker anzumelden oder anzumelden. Wir speichern keine spezifischen Daten mit dieser Berechtigung. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Profil | Delegiert | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Firmenname (wie vom Benutzer eingegeben) | Wenn sich ein Benutzer anmeldet, gibt er seinen Firmennamen ein, und wir verwenden diesen Namen als Organisationsnamen im Produkt. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Rechtfertigung für den Zugang zu EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Rechtfertigung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Der Bot kann die grundlegenden Informationen über den Benutzer sehen, der mit dem Bot kommuniziert. Wir speichern oder verwenden diese Informationen jedoch nicht. Wir verwenden nur die ID des Benutzers, die Konversations-ID und eine Nachricht, die an unseren Bot gesendet wird. | Wir speichern die E-Mail-Adresse des Benutzers, den Namen des Benutzers (wie im Microsoft AAD definiert) und das Profilfoto des Benutzers (von Microsoft AAD) | Wir verwenden eine E-Mail-Adresse als eindeutige Kennung für unsere Benutzer und den Namen und das Profilfoto des Benutzers, damit Administratoren und Genehmiger desselben Unternehmens ihre Mitarbeiter in unserem Dashboard erkennen können.  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Firmenname und es wird beibehalten und gemäß unserer Standard einjahrsigen Aufbewahrungsrichtlinie für diese Art von Daten entfernt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Zunächst erfassen wir die minimale Datenmenge, die von den Benutzern benötigt wird. Dann teilen wir das Minimum mit unseren Partnern und schließlich haben wir Datenaufbewahrungsrichtlinien, so dass alle Daten innerhalb eines Jahres entfernt werden, falls zutreffend.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Vacation Tracker darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Conditional Access-Richtlinien? | Nein |
| Fordert Ihre App die geringsten Berechtigungsberechtigungen für Ihr Szenario an? | Ja |
| Gibt die statisch registrierten Berechtigungen Ihrer App die Berechtigungen wieder, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Multi-Tenancy? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle für Ihre App registrierten Unified Resource Identifier (URI) umleiten? | Ja |
| Was vermeiden Sie für Ihre App? | - Wildcard-Umleitungs-URIs,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für ein SPA erforderlich<br/>- Ressourcenbesitzer-Kennwortanmeldeinformationen (ROPC)-Flow |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann zu, dass Aufrufe erfolgreich sind, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
