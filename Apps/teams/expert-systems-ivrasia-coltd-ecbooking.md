---
title: Anwendungsinformationen für ecBooking von Expert Systems IVR(Asia) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für ecBooking, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 6ec806440fb2ec8c6b0cc79042aee072adc40c05
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252615"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 28. Dezember 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Expert Systems IVR(Asia) bereitgestellt Co.Ltd. an Microsoft:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | ecBooking |
| ID | WA200002096 |
| Funktionen | Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Expert Systems IVR (Asia) Co.Ltd. |
| URL der Partnerwebsite | [https://www.esi-asia.com/](https://www.esi-asia.com/) |
| URL Teams Anwendungsinfoseite | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL der Datenschutzrichtlinie | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL der Nutzungsbedingungen | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Expert Systems IVR(Asia) Co.Ltd. Informationen dazu, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Anwendung | Daten wie Benutzer-E-Mail, Benutzerereignisse werden gespeichert. Benutzerereignisse werden gesammelt, um die Verfügbarkeit von Räumen zu überprüfen und Ereignisse zu erstellen. | Die ID des Users-Ereignisses, der Ortsname und die Details des anderen Ereignisses werden gespeichert. Daten werden für die Überprüfung der Verfügbarkeit von Räumen und das Erstellen von Ereignissen gesammelt. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| Mail.Send | Anwendung | Daten wie Z. B. Benutzer-E-Mail. Benutzer-E-Mails werden zum Senden von Erinnerungs-E-Mails für Raumbuchungen gesammelt. | Daten wie Z. B. Benutzer-E-Mail. Benutzer-E-Mails werden zum Senden von Erinnerungs-E-Mails für Raumbuchungen gesammelt. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read | delegierte | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für den Anmeldebenutzer in der Anwendung gesammelt. | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für den Anmeldebenutzer in der Anwendung gesammelt. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read.All | Anwendung | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für den Anmeldebenutzer in der Anwendung gesammelt. | Daten wie Benutzer-ID, Name und E-Mail. Benutzerdaten werden für den Anmeldebenutzer in der Anwendung gesammelt. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| email | delegierte | Daten wie Z. B. Benutzer-E-Mail. Benutzer-E-Mails werden gesammelt, um die Verfügbarkeit des Benutzers zu überprüfen und Ereignisse zu erstellen. | Daten wie Z. B. Benutzer-E-Mail. Benutzer-E-Mails werden gesammelt, um die Verfügbarkeit des Benutzers zu überprüfen und Ereignisse zu erstellen. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| openid | delegierte | Die openid des Benutzers inorder, damit der Benutzer sich bei der Anwendung anmelden kann. | Die openid des Benutzers inorder, damit der Benutzer sich bei der Anwendung anmelden kann. | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Daten wie Benutzer-E-Mail, Benutzerereignisse werden gespeichert. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In der Datenbank gespeicherte Daten.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Expert Systems IVR(Asia) Co.Ltd. Informationen dazu, wie diese App bewährte Methoden für die Authentifizierung, Autorisierung, Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Nein |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/><br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
