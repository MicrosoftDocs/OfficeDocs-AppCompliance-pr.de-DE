---
title: Anwendungsinformationen für OnePlaceMail für Outlook von OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für OnePlaceMail für Outlook, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1eeee8a3aff40a8ca4486308bcfef5887b6ced6c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252956"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 31. Januar 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von OnePlace Solutions für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | OnePlaceMail für Outlook |
| ID | WA104380723 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf Mac, Outlook unter iOS, Outlook unter Android, Outlook im Web |
| Partnerunternehmensname | OnePlace-Lösungen |
| URL der Partnerwebsite | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL der Datenschutzrichtlinie | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL der Nutzungsbedingungen | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von OnePlace Solutions bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | delegierte | Erforderlich, um zu Teams, bei dem der aktuelle Benutzer Mitglied ist. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | delegierte | Erforderlich, um auf E-Mail-Eigenschaften zu zugreifen, SharePoint spalten festlegen und die Kategorie Übertragen in SharePoint E-Mail-Element hinzufügen | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | delegierte | Keine erfassten oder verwendeten Daten, wird zum Hinzufügen einer Kategorie zur Hauptkategorieliste in einem Benutzerpostfach verwendet. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | delegierte | Erforderlich zum Festlegen von Eigenschaften für Elemente, die die App in die App hochgeladen SharePoint. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | delegierte | Erforderlich für die Authentifizierung beim Microsoft-Graph. | Die folgenden Daten werden von der App in einer Datenbank gespeichert und für die Abonnement- und Benutzerlizenzverfolgung verwendet: Benutzer-ID, E-Mail, Vorname, Nachname. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | delegierte | Erforderlich, um das Benutzerprofilbild im Feld Personenauswahl anzeigen zu können. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | delegierte | Erforderlich, um das Benutzerprofilbild im Feld Personenauswahl anzeigen zu können. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | delegierte | Erforderlich, um zu ermitteln, ob Teams dienst innerhalb der Benutzer aktiviert ist, Office 365 werden. | Keine | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 können zusätzliche Microsoft-APIs als Microsoft Graph verwenden, um identifizierbare Informationen (OII) der Organisation zu sammeln oder zu verarbeiten. Listen Sie alle anderen Microsoft-APIs als Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Ja | SharePoint URLs, Bibliotheks-/Listen-/Ordnernamen | Die organisatorischen Informationen, auf die zugegriffen wird, werden verwendet, um das Speichern von E-Mails und Anlagen von Exchange zu SharePoint. Diese zusätzlichen Daten werden nicht im Ruhebereich gespeichert und während der Übertragung verschlüsselt. Beispiele für diese Daten SharePoint Spaltenwerte wie Spaltenwerte für Auswahl, Taxonomiewerte, Inhaltstypnamen, Ordnernamen, Websitenamen.  | Während diese Daten nicht von der App gespeichert oder gesammelt werden, werden sie möglicherweise in Telemetrie-/Protokollen angezeigt, wo sie für 90 Tage aufbewahrt werden. | Daten werden nicht gespeichert |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Der Chargify-Dienst wird für die Abonnementverwaltung und -abrechnung verwendet. Für die Erstellung eines kostenlosen In-App-Abonnements werden Vorname, Nachname, E-Mail-Adresse des Benutzers für Chargify freigegeben. Bei erworbenen Abonnements (die mehrere lizenzierte Benutzer unterstützen) werden die einzelnen Benutzerdetails nicht für den Chargify-Dienst freigegeben. | E-Mail-Adresse | So kommunizieren Sie Abonnementlebenszyklusereignisse an den Benutzer |



#### <a name="add-in-data-access"></a>Add-In-Datenzugriff

Listet die Berechtigungen auf, die diese App für den Zugriff auf die Daten Ihrer Organisation benötigt, die Begründung und den Zweck dieser Berechtigung (wofür verwendet die App diese Informationen?), und ob die App diese Informationen in ihren Datenbanken speichert.

>| **Berechtigung**  | **Beschreibung** |
>|:----------------|:----------------|
>| ReadWrite Mailbox | Dieses Add-In kann den Inhalt eines beliebigen Elements in Ihrem Postfach lesen oder ändern und neue Elemente erstellen. Sie kann auf personenbezogene Informationen – z. B. den Textkörper, den Betreff, den Absender, Empfänger oder Anlagen – in jeder Nachricht oder einem Kalenderelement zugreifen. Diese Daten können an einen Drittanbieterdienst gesendet werden. |
>| Senden von Daten | Kann Daten über das Internet senden |

#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII werden in der Telemetrie angezeigt. Diese Informationen werden in Application Insights gespeichert, im Ruhetag verschlüsselt, zugriffgesteuert und nach 90 Tagen gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In der Anwendung gespeicherte Daten werden während der Übertragung und im Ruhebereich verschlüsselt. Wir vertrauen auf Office 365 Anmeldeinformationen für unsere Apps, daher speichern wir keine Benutzerkennwörter in unserem System. Der Zugriff auf gespeicherte Daten/Protokolle/Telemetrie wird für interne Verwaltungsmitarbeiter streng kontrolliert, mit der Notwendigkeit, auf die Informationen zu zugreifen, um die Integrität der App ausführen und überwachen zu können. Two-Factor Authentifizierung für alle internen Verwaltungsmitarbeiter erzwungen.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von OnePlace Solutions bereitgestellt, um zu erfahren, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden geprüft und befolgt, die in der Prüfliste Microsoft Identity Platform aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
| Bittet Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordern wird? | Ja |
| Unterstützt Ihre App mehrere Mandanzfähigkeiten? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie alle umgeleiteten Unified Resource Identifier (URI), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | - UrIs für die Platzhalterumleitung,<br/>- OAuth2 Implizite Flow, es sei denn, dies ist für eine SPA erforderlich<br/>– Fluss mit Kennwortanmeldeinformationen (Password Credential, ROPC) des Ressourcenbesitzers |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur dann den Erfolg von Aufrufen zu, wenn die Client-App die entsprechende Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
