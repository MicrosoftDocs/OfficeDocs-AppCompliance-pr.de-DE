---
title: Anwendungsinformationen für Entscheidungen nach Entscheidungen
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Entscheidungen, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59282137"
---
# <a name="decisions"></a>Decisions

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 2, 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Microsoft von Entscheidungen bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Decisions |
| ID | WA104381880 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Decisions |
| URL der Partnerwebsite | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL der Datenschutzrichtlinie | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Entscheidungen darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert sowie die Kontrolle, über die Ihre Organisation über die von der App gesammelten Daten verfügt.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Wird verwendet, um Informationen aus dem Kalender des Benutzers&#8217;zu lesen, um Features wie die Besprechungsliste und die Suche zu aktivieren. Es bietet dem Benutzer auch die Möglichkeit, bestimmte Besprechungen aus dem Kalender zu löschen, wenn das Element aus Entscheidungen gelöscht wird. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | Delegiert | Wird verwendet, um Entscheidungen zur Abstimmung zu senden und Sprecherlisten für einzelne Agendaelemente direkt an den Microsoft Teams Besprechungschat zu erstellen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | Delegiert | Wird verwendet, um grundlegende Informationen zum Office 365 Mandanten bei der Registrierung zu sammeln, z. B. Mandantenname und überprüfte Domänen. Es ist auch erforderlich, um Gruppenmitgliedschaften zu überprüfen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | Delegiert | Wird verwendet, um Dateien zu lesen, die für den Benutzer freigegeben sind, um diese Dateien in das PDF-Besprechungsbuch zusammenzuführen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | Delegiert | Wird verwendet, um Benutzern Unterstützung für persönliche Dateianmerkungen bereitzustellen. Kommentierte Dateien werden privat im&#8217;OneDrive for Business des Benutzers gespeichert. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | Delegiert | Wird verwendet, um Ordnerstrukturen in der Office 365 Gruppenwebsite&#8217;SharePoint für Besprechungstermine, verwandte Dateien und Gruppenunterhaltungen zu erstellen.   Hinweis: Benutzer von Entscheidungen erhalten niemals Zugriff auf Ressourcen (z. B. Gruppen), auf die sie im Office 365 Mandanten Ihrer Organisation noch keinen Zugriff haben. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | Delegiert | Wird verwendet, um Benutzern von Entscheidungen das Senden von Besprechungsteilnehmerbenachrichtigungen zu ermöglichen, z. B. Aktualisierungen der Tagesordnung und Links zur Besprechung für Mitautoren. E-Mails werden an Besprechungsteilnehmer oder an die verteilerliste gesendet, die vom Besprechungsbesitzer ausgewählt wurde. Alle gesendeten Benachrichtigungen und E-Mails werden aktiv von den Entscheidungsbenutzern durchgeführt.  Hinweis: Dadurch erhält der Benutzer keinen Zugriff auf seinen Posteingang über Entscheidungen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | Delegiert | Wird verwendet, um die Spracheinstellungen eines Benutzers&#8217;zu identifizieren. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | Delegiert | Wird verwendet, um private Notizbücher für Besprechungen einzurichten, um Notizen zu machen und Anmerkungen und Fragen vorzubereiten. Außerdem können Gruppenbesprechungsminuten in ihrem freigegebenen OneNote Notizbuch gespeichert werden, wenn die Gruppe OneNote verwenden möchte. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | Delegiert | Dient zum Erstellen von Ordnerstrukturen in privaten Kanälen für Besprechungsinformationen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | Delegiert | Wird verwendet, um Aufgaben und Entscheidungen mit Microsoft Planner zu synchronisieren. Darüber hinaus können Benutzer Aufgaben und Entscheidungen in Excel exportieren. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | Delegiert | Erforderlich, um die App "Entscheidungen" im Chat programmgesteuert zu installieren. Dies ist erforderlich, bevor die Registerkarte "Entscheidungen" für die Besprechungsoberfläche hinzugefügt wird. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | Delegiert | Erforderlich, um die App "Entscheidungen" im Chat programmgesteuert zu installieren. Dies ist erforderlich, bevor die Registerkarte "Entscheidungen" für die Besprechungsoberfläche hinzugefügt wird. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | Delegiert | Sie müssen die Registerkarte "In-Besprechung/Kanal" in Teams hinzufügen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | Delegiert | Erforderlich, um zu überprüfen, ob die Registerkarte installiert ist oder nicht. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | Delegiert | Wird zum Anzeigen des Vor- und Nachnamens, des Fotos und der E-Mail-Adresse von Gruppenmitgliedern und externen Teilnehmern verwendet. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Profil | Delegiert | Wird verwendet, um sich anzumelden. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die vom Kunden während der Verwendung der Software bereitgestellten Daten sind nur für den Kunden verfügbar.  Der Dienst wird über Microsoft Office 365 Cloud Services und Microsoft Azure bereitgestellt. Alle Kundendaten werden in den Kunden Microsoft Office 365 Mandanten gespeichert. Alle auf dem Dienst gespeicherten oder verarbeiteten Daten sind anonym und für einzelne Personen nicht nachverfolgbar. Daher werden personenbezogene Daten von Entscheidungen nicht im Auftrag des Kunden gespeichert, gesammelt oder verarbeitet.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Entscheidungen darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Alle |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
