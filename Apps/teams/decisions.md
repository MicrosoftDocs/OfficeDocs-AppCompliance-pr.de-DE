---
title: Anwendungsinformationen für Entscheidungen nach Entscheidungen
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Entscheidungen, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 99e01d0ad5874c62f51a3f78b5b612766f397ea1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415142"
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
| Office 365 unterstützten Clients | Microsoft Teams |
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

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegiert | Wird verwendet, um Informationen aus dem Kalender des Benutzers&#8217;zu lesen, um Features wie die Besprechungsliste und die Suche zu aktivieren. Es bietet dem Benutzer auch die Möglichkeit, bestimmte Besprechungen aus dem Kalender zu löschen, wenn das Element aus Entscheidungen gelöscht wird. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | Delegiert | Wird verwendet, um Entscheidungen für die Abstimmung zu senden und Referentenlisten für einzelne Agendaelemente direkt an den Microsoft Teams Besprechungschat zu erstellen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | Delegiert | Wird verwendet, um grundlegende Informationen zum Office 365 Mandanten bei der Registrierung zu sammeln, z. B. Mandantenname und überprüfte Domänen. Es ist auch erforderlich, um Gruppenmitgliedschaften zu überprüfen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | Delegiert | Wird verwendet, um Dateien zu lesen, die für den Benutzer freigegeben sind, um diese Dateien in das PDF-Besprechungsbuch zusammenzuführen. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | Delegiert | Wird verwendet, um Benutzern Unterstützung für persönliche Dateianmerkungen bereitzustellen. Kommentierte Dateien werden privat im OneDrive for Business des Benutzers&#8217;gespeichert. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | Delegiert | Wird zum Erstellen von Ordnerstrukturen in der Office 365 Gruppenwebsite&#8217;SharePoint für Besprechungstermine, zugehörige Dateien und Gruppenunterhaltungen verwendet.   Hinweis: Benutzer von Entscheidungen erhalten nie Zugriff auf Ressourcen (z. B. Gruppen), auf die sie noch nicht im Office 365 Mandanten Ihrer Organisation zugreifen können. | Kundendaten werden im Office 365 Mandanten des Kunden&#8217;gespeichert, und alle Kundendaten werden nur auf Kundengeräten verarbeitet. Die Datenbank "Entscheidungen" verwaltet nur Verweise auf Objekte in den Kunden Office 365 Mandanten, nicht auf die tatsächlichen Daten. Weitere Informationen finden Sie https://www.meetingdecisions.com/security-and-privacy unter. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
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


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

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


::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Entscheidungen darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden in der Checkliste für die Microsoft Identity Platform Integration überprüft und berücksichtigt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | Alle |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/>– Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/>- ROPC-Fluss (Resource Owner Password Credential) |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

