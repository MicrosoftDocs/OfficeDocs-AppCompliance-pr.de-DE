---
title: Anwendungsinformationen für Plumm von Plumm Health LTD
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Plumm, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 47a0607828ff96d92cea8be21819fa9e4680f0b4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412174"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: August 18, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Plumm Health LTD an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Plumm |
| ID | WA200003326 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Plumm Health LTD |
| URL der Partnerwebsite | [https://www.plummhealth.com](https://www.plummhealth.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| URL der Datenschutzrichtlinie | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| URL der Nutzungsbedingungen | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Plumm Health LTD darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | Anwendung | Wir verwenden die userID in dieser Berechtigung. Dies wird verwendet, um erforderliche Benachrichtigungen basierend auf der Nutzung unseres Diensts an den Benutzer zu senden. Dies ist wichtig, damit der Benutzer entsprechende Benachrichtigungen für sein Konto in unserer App erhält. | In dieser Berechtigung speichern wir keine Daten in unserer Datenbank. Tatsächlich verwenden wir die UserID, um die entsprechende Benachrichtigung basierend auf ihrer Nutzung an jeden einzelnen Benutzer zu senden. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | Anwendung | Wir erhalten die Installations-ID mithilfe dieser Berechtigung. Dies ist für uns wichtig, um die entsprechende und richtige Benachrichtigung für jeden einzelnen Benutzer senden zu können. | Wir speichern keine Daten in unserer App mit dieser Berechtigung. Dies ist nicht erforderlich, da wir nur die Installations-ID benötigen, die zur Laufzeit durch Die Angabe der UserID abgerufen wird. Dies wird dynamisch zur Laufzeit abgerufen, daher ist es nicht erforderlich, die Installations-ID zu speichern. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | Delegiert | Wir erfassen Namen, Bilder und E-Mails für unsere Benutzer über diese Berechtigung. Dies ist erforderlich, damit wir einzelne Benutzer identifizieren können, und diese Datenpunkte werden überall dort angezeigt, wo dies erforderlich ist, z. B. auf einer einzelnen Profilseite und bei der E-Mail-/Benachrichtigungskommunikation. | Diese Berechtigungen ermöglichen unserer App, das grundlegende Profil unserer Benutzer (Name, Bild, E-Mail) anzuzeigen. Diese Daten werden verwendet, um den Namen und/oder das Profilbild des Benutzers auf dem App-Konto bei uns und bei der E-Mail-Kommunikation und/oder Benachrichtigung anzuzeigen. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | Anwendung | Mit dieser Berechtigung kann unsere App Benutzerprofile lesen, ohne dass ein Benutzer angemeldet ist. Hier erfassen wir derzeit nur Namen, Profilbilder und E-Mails. Dies ist erforderlich, damit wir einzelne Benutzer identifizieren können, und diese Datenpunkte werden überall dort angezeigt, wo dies erforderlich ist, z. B. auf einer einzelnen Profilseite und bei der E-Mail-/Benachrichtigungskommunikation. | Diese Berechtigungen ermöglichen unserer App, das grundlegende Profil unserer Benutzer (Name, Bild, E-Mail) anzuzeigen. Diese Daten werden verwendet, um den Namen und/oder das Profilbild des Benutzers auf dem App-Konto bei uns und bei der E-Mail-Kommunikation und/oder Benachrichtigung anzuzeigen. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | Delegiert | Die E-Mail-ID des Benutzers wird erfasst. Wir benötigen diese Daten, um dem Benutzer Zugriff auf unsere Dienste zu gewähren und uns bei unserer App anzumelden und Benachrichtigungen zu ihren Konten und unseren Diensten über diese E-Mail-ID zu erhalten.  | Die E-Mail-ID wird in der Datenbank gespeichert. Wir müssen die E-Mail-ID speichern, um Benutzer eindeutig zu identifizieren, ihnen Zugriff auf unsere App zu gewähren, ihnen bei der Anmeldung zu helfen und ihnen zu helfen, Benachrichtigungen über ihr Konto bei uns zu erhalten. Beispielsweise kann ein Benutzer mit einer E-Mail-ID &quot; abc@xyz.com auf unsere App und Dienste &quot; zugreifen, wenn er sich bei Teams mit dieser E-Mail-ID anmeldet. Basierend auf der Nutzung können wir Benachrichtigungen an diesen Benutzer über seine E-Mail-ID senden. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | Delegiert | Für diese Berechtigung sammeln wir keine Daten.  | Für diese Berechtigung sammeln wir keine Daten. Mit dieser Berechtigung können sich Benutzer mit ihrer geschäftlichen E-Mail-ID bei unserer App anmelden, und die App kann grundlegende Benutzerprofilinformationen anzeigen. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| Profil | Delegiert | Wir erfassen Namen, Bilder und E-Mails für unsere Benutzer über diese Berechtigung. Dies ist erforderlich, damit wir einzelne Benutzer identifizieren können, und diese Datenpunkte werden überall dort angezeigt, wo dies erforderlich ist, z. B. auf einer einzelnen Profilseite und bei der E-Mail-/Benachrichtigungskommunikation. | Diese Berechtigungen ermöglichen unserer App, das grundlegende Profil unserer Benutzer (Name, Bild, E-Mail) anzuzeigen. Diese Daten werden verwendet, um den Namen und/oder das Profilbild des Benutzers auf dem App-Konto bei uns und bei der E-Mail-Kommunikation und/oder Benachrichtigung anzuzeigen. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | Vorname, Nachname, E-Mail | Intercom ist unser CRM, das uns bei der Verwaltung der Kommunikation mit allen unseren Benutzern hilft. Deshalb müssen wir den Vornamen, nachnamen und die E-Mail-ID unserer Benutzer an das CRM senden, damit entsprechende Nachrichten/E-Mails an die Benutzer gesendet werden können. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir speichern Dienstnutzungsdaten, z. B. die Anzahl der verwendeten Sitzungssitzungen, die angezeigten Kurse, die angezeigten Kurse, das Datum der Sitzungen usw. Wir speichern Daten für unsere Benutzer, bis der Benutzer ausdrücklich darum bittet, sein Konto zu löschen oder "vergessen" zu machen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verwalten die Daten, die über unseren Server an das CRM gesendet werden. Mindestdaten, die für die Funktion erforderlich sind, werden an das CRM (Intercom) übergeben. Plumm hat die vollständige Kontrolle darüber, welche Daten an das CRM übergeben werden, die Aufbewahrung der Daten auf Intercom und deren Löschung. Hier ist ein Link zum Überprüfen der Kundendatenrichtlinien von Intercom: https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Plumm Health LTD darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Nein |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/><br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

