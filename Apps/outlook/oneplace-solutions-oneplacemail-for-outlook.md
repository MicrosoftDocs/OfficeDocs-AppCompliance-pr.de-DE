---
title: Anwendungsinformationen für OnePlaceMail für Outlook von OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Compliance-Informationen für OnePlaceMail für Outlook, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552496"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 31. Januar 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von OnePlace Solutions für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | OnePlaceMail für Outlook |
| ID | WA104380723 |
| Office 365 unterstützten Clients | Outlook 2013 oder später Windows, Outlook 2016 oder später auf Mac, Outlook auf iOS, Outlook auf Android, Outlook im Web |
| Name des Partnerunternehmens | OnePlace-Lösungen |
| URL der Partner-Website | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL der Datenschutzrichtlinie | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL der Nutzungsbedingungen | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von OnePlace Solutions darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierter/Antrag)** | **Werden Daten gesammelt? Rechtfertigung für die Sammlung?** | **Werden Daten gespeichert? Rechtfertigung für die Lagerung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegiert | Erforderlich, um zu bestimmen, Teams der der aktuelle Benutzer Mitglied ist. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| Mail.ReadWrite.Shared | Delegiert | Erforderlich für den Zugriff auf E-Mail-Eigenschaften zum Festlegen SharePoint Spalten und Hinzufügen der Kategorie Übertragen zu SharePoint des E-Mail-Elements | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| MailboxSettings.ReadWrite | Delegiert | Keine daten gesammelt oder verwendet werden, dies wird zum Hinzufügen einer Kategorie zur Masterkategorieliste in einem Benutzerpostfach verwendet. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| Sites.ReadWrite.All | Delegiert | Erforderlich, um Eigenschaften für Elemente festzulegen, die die App in SharePoint hochgeladen hat. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| User.Read | Delegiert | Erforderlich für die Authentifizierung bei der Microsoft-Graph. | Die folgenden Daten werden von der App in einer Datenbank gespeichert und für die Nachverfolgung von Abonnements und Benutzerlizenzen verwendet: Benutzer-ID, E-Mail, Vorname, Nachname. | 44a72516-136f-4a55-ae26-ef0977230be |
>| User.ReadBasic.All | Delegiert | Erforderlich, um das Benutzerprofilbild im Feld Personenauswahl anzuzeigen. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| User.ReadBasic.All | Delegiert | Erforderlich, um das Benutzerprofilbild im Feld Personenauswahl anzuzeigen. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |
>| User.ReadWrite.All | Delegiert | Erforderlich, um zu bestimmen, ob der Teams Dienst in den Benutzern aktiviert ist Office 365 Mandanten. | Keine | 44a72516-136f-4a55-ae26-ef0977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mithilfe anderer Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, können zusätzliche Microsoft-APIs verwenden, die nicht microsoft Graph sind, um unternehmensbezogene identifizierbare Informationen (OII) zu sammeln oder zu verarbeiten. Listen Sie alle Microsoft-APIs auf, die nicht von Microsoft Graph diese App verwendet.

>| **API** |  **Wird OII gesammelt?** |  **Welche OII wird gesammelt?** | **Rechtfertigung für das Sammeln von OII?** | **Wird OII gespeichert?** | **Rechtfertigung für die Speicherung von OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Ja | SharePoint URLs, Bibliotheks-/Listen-/Ordnernamen | Die organisatorischen Informationen, auf die zugegriffen wird, werden verwendet, um das Speichern von E-Mails und Anhängen von Exchange bis SharePoint zu erleichtern. Diese zusätzlichen Daten werden nicht im Ruhezustand gespeichert und während der Übertragung verschlüsselt. Beispiele für diese Daten sind SharePoint Spaltenwerte wie Spaltenwerte auswählen, Taxonomiewerte, Inhaltstypnamen, Ordnernamen, Websitenamen.  | Diese Daten werden zwar nicht von der App gespeichert oder gesammelt, sie können zwar in Telemetrieprotokollen angezeigt werden, wo sie 90 Tage lang aufbewahrt werden. | Daten werden nicht gespeichert |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Der Chargify-Dienst wird für die Abonnementverwaltung und -abrechnung verwendet. Bei der Erstellung von In-App-Abonnements (kostenlos) werden der Vorname, Nachname und E-Mail-Adresse des Benutzers mit Chargify geteilt. Bei erworbenen Abonnements (die mehrere lizenzierte Benutzer unterstützen) werden die einzelnen Benutzerdetails nicht für den Chargify-Dienst freigegeben. | E-Mail-Adresse | So können Abonnementlebenszyklusereignisse an den Benutzer übermittelt werden |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII erscheinen in telemetrie. Diese Informationen werden in Application Insights gespeichert, im Ruhezustand verschlüsselt, nach 90 Tagen gelöscht

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Die in der Anwendung gespeicherten Daten werden während der Übertragung und im Ruhezustand verschlüsselt. Wir verlassen uns auf Office 365 Anmeldeinformationen für unsere Apps, so dass wir keine Benutzerkennwörter in unserem System speichern. Der Zugriff auf gespeicherte Daten/Protokolle/Telemetriedaten wird für interne Verwaltungsmitarbeiter streng kontrolliert, wobei sie auf die Informationen zugreifen müssen, um den Zustand der App auszuführen und zu überwachen. Two-Factor Authentifizierung für alle internen Verwaltungsmitarbeiter erzwungen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von OnePlace Solutions zur Verfügung gestellt, wie diese App authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Ja |
| Haben Sie alle in der Checkliste für die Microsoft Identity Platform-Integration beschriebenen bewährten Methoden überprüft und eingehalten?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
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
