---
title: Anwendungsinformationen für Vacation Tracker by Vacation Tracker
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Vacation Tracker, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 33a6ecf06db07878a62a9b9a9edf4360f2507ee7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52093566"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 5. Februar 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Vacation Tracker an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Vacation Tracker |
| ID | WA200002167 |
| Funktionen | Bot, Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Vacation Tracker |
| URL der Partnerwebsite | [https://vacationtracker.io](https://vacationtracker.io) |
| URL Teams Anwendungsinfoseite | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL der Datenschutzrichtlinie | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL der Nutzungsbedingungen | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Vacation Tracker bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | delegierte | Wir lesen IDs und Namen des öffentlichen Kanals, wenn Benutzer ihre wöchentlichen oder täglichen Benachrichtigungen festlegen. | Benutzer können einen Kanal auswählen, in dem sie tägliche oder wöchentliche Benachrichtigungen von Vacation Tracker erhalten möchten. Wenn ein Benutzer seinen bevorzugten Kanal wählt, speichern wir die Kanal-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | delegierte | Wir listen die Microsoft Teams Teams auf, die während der Anmeldung beigetreten sind, um Benutzern die Auswahl eines Teams zu ermöglichen, das sie sich für Vacation Tracker registrieren möchten. Sie können sich alternativ bei ihrer gesamten Organisation registrieren. | Wir speichern die Microsoft Teams Team-ID für ein ausgewähltes Team nur, wenn sich der Benutzer für Vacation Tracker als einzelnes Team (nicht als ganze Organisation) einschreibt. Wir verwenden Team-IDs, um einen angemeldeten Benutzer mit einem vorhandenen Konto in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | delegierte | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | delegierte | Unsere Benutzer können alle Benutzer aus ihrer Microsoft 365 oder Microsoft Teams importieren. Wir verwenden diese Berechtigung, um nur lizenzierte Benutzer für ein ausgewähltes Microsoft Teams oder Organisation zu importieren. | Wir speichern grundlegende Informationen zu importierten Benutzern, einschließlich Name, E-Mail-Adresse und Benutzer-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | delegierte | Wir ermöglichen Benutzern das Importieren der anderen Benutzer aus ihrer Organisation oder ihrem Microsoft Teams Team. Wir verwenden diese Berechtigung, um die verfügbaren Benutzer und ihre E-Mail-Adressen im Importpopup auflisten. | Wenn Benutzer ihre Kollegen auswählen, die in die Urlaubsverfolgung importiert werden sollen, speichern wir grundlegende Informationen zu diesen importierten Benutzern, einschließlich Name, E-Mail-Adresse und Benutzer-ID. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | delegierte | Wenn sich der Benutzer mit Microsoft AAD anmeldet, speichern wir seine E-Mail-Adresse als eindeutigen Bezeichner. | Wir speichern die E-Mails des Benutzers als eindeutigen Bezeichner. Wir verwenden diese E-Mail nicht für die Kommunikation, Benutzer geben ihre geschäftliche E-Mail-Adresse ein, die wir während der Anmeldung für die Kommunikation verwenden. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | delegierte | Wir sammeln keine Daten mit dieser Berechtigung. Es wird verwendet, um den Zugriff auf Daten zu verwalten, auf die wir zugreifen dürfen. | Wir speichern keine Daten mit dieser Berechtigung. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | delegierte | Wir verwenden diese Berechtigung zum Anmelden oder Registrieren von Benutzern bei Vacation Tracker. Wir sammeln keine bestimmten Daten mit dieser Berechtigung. | Wir verwenden diese Berechtigung zum Anmelden oder Registrieren von Benutzern bei Vacation Tracker. Wir speichern keine bestimmten Daten mit dieser Berechtigung. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Profil | delegierte | Wir erfassen die grundlegenden Benutzerinformationen, einschließlich name, ID und Mandanten-ID. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | Wir speichern den Namen, die ID und die Mandanten-ID des Benutzers. Wir verwenden diese Daten, um angemeldete Benutzer mit ihrer Organisation in Vacation Tracker zu verbinden. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Firmenname (wie vom Benutzer eingegeben) | Wenn sich ein Benutzer meldet, gibt er seinen Firmennamen ein, und wir verwenden diesen Namen als Organisationsname innerhalb des Produkts. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Der Bot kann die grundlegenden Informationen über den Benutzer sehen, der mit dem Bot kommuniziert. Diese Informationen werden jedoch nicht gespeichert oder verwendet. Wir verwenden nur die Benutzer-ID, die Unterhaltungs-ID und eine Nachricht, die an unseren Bot gesendet wird. | Wir speichern die E-Mail-Adresse des Benutzers, den Benutzernamen (wie im Microsoft AAD definiert) und das Profilfoto des Benutzers (von Microsoft AAD) | Wir verwenden eine E-Mail-Adresse als eindeutige ID für unsere Benutzer sowie den Namen und das Profilfoto des Benutzers, um Administratoren und genehmigende Benutzer aus demselben Unternehmen zu ermöglichen, ihre Mitarbeiter in unserem Dashboard zu erkennen.  |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Firmenname und wird gemäß unserer standardmäßigen Ein-Jahres-Aufbewahrungsrichtlinie für diese Art von Daten beibehalten und entfernt

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Zu Beginn erfassen wir die Mindestmenge an Daten, die von Benutzern benötigt werden. Dann teilen wir das Möglichste mit unseren Partnern und schließlich haben wir Richtlinien für die Datenaufbewahrung, sodass alle Daten ggf. innerhalb eines Jahres entfernt werden.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Vacation Tracker bereitgestellt, um zu erfahren, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,
<br />
- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich
<br />
- Ablauf der Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers | | Macht Ihre App Web-APIs verfügbar? | Ja | | Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja | | Verwendet Ihre App Vorschau-APIs? | Keine | | Verwendet Ihre App veraltete APIs? | Keine |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
