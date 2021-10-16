---
title: Anwendungsinformationen für OnePlaceMail für Outlook von OnePlace-Lösungen
ms.author: elmalova
author: elenamalova
ms.date: 09/30/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für OnePlaceMail für Outlook, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 310e662c42247476df716e42159ecd5e348ed4e2
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414169"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail für Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 30, 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von OnePlace-Lösungen für Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | OnePlaceMail für Outlook |
| ID | WA104380723 |
| Office 365 unterstützten Clients | Outlook 2013 oder höher auf Windows, Outlook 2016 oder höher auf Mac, Outlook unter iOS, Outlook unter Android, Outlook im Web |
| Name des Partnerunternehmens | OnePlace-Lösungen |
| URL der Partnerwebsite | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| URL der Datenschutzrichtlinie | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL der Nutzungsbedingungen | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von OnePlace Solutions bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | Delegiert | Erforderlich, um zu bestimmen, Teams der aktuelle Benutzer Mitglied ist. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | Delegiert | Erforderlich, um auf E-Mail-Eigenschaften zuzugreifen, um SharePoint Spalten festzulegen und die Kategorie "Übertragen zu SharePoint" des E-Mail-Elements hinzuzufügen. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | Delegiert | Es werden keine Daten erfasst oder verwendet, die zum Hinzufügen einer Kategorie zur Hauptkategorienliste in einem Benutzerpostfach verwendet werden. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | Delegiert | Erforderlich, um Eigenschaften für Elemente festzulegen, die die App in SharePoint hochgeladen hat. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | Delegiert | Erforderlich für die Authentifizierung beim Microsoft Graph. | Die folgenden Daten werden von der App in einer Datenbank gespeichert und für die Abonnement- und Benutzerlizenzverfolgung verwendet: Benutzer-ID, E-Mail, Vorname, Nachname. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | Delegiert | Erforderlich, um das Benutzerprofilbild im Personenauswahlfeld anzuzeigen. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | Delegiert | Erforderlich, um das Benutzerprofilbild im Personenauswahlfeld anzuzeigen. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | Delegiert | Erforderlich, um festzustellen, ob der Teams Dienst innerhalb der Benutzer Office 365 Mandanten aktiviert ist. | Keine | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>Datenzugriff mit anderen Microsoft-APIs

Apps und Add-Ins, die auf Microsoft 365 basieren, verwenden möglicherweise zusätzliche Andere Microsoft-APIs als Microsoft Graph zum Sammeln oder Verarbeiten von organisationsbezogenen Informationen (OII). Auflisten aller anderen Microsoft-APIs als Microsoft Graph diese App verwendet wird.

>| **API** |  **Wird OII erfasst?** |  **Welche OII wird erfasst?** | **Begründung für die Erfassung von OII?** | **Wird OII gespeichert?** | **Begründung für das Speichern von OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Ja | SharePoint URLs, Bibliotheks-/Listen-/Ordnernamen | Die organisatorischen Informationen, auf die zugegriffen wird, werden verwendet, um das Speichern von E-Mails und Anlagen von Exchange in SharePoint zu vereinfachen. Diese zusätzlichen Daten werden nicht im Ruhezustand gespeichert und während der Übertragung verschlüsselt. Beispiele für diese Daten sind SharePoint Spaltenwerte wie Choice-Spaltenwerte, Taxonomiewerte, Inhaltstypnamen, Ordnernamen, Websitenamen.  | Obwohl diese Daten nicht von der App gespeichert oder gesammelt werden, werden sie möglicherweise in Telemetrie/Protokollen angezeigt, in denen sie 90 Tage lang aufbewahrt werden. | Daten werden nicht gespeichert |

#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Der Chargify-Dienst wird für die Abonnementverwaltung und -abrechnung verwendet. Für die (kostenlose) In-App-Abonnementerstellung werden Vorname, Nachname und E-Mail-Adresse des Benutzers für Chargify freigegeben. Für erworbene Abonnements (die mehrere lizenzierte Benutzer unterstützen) werden die details der einzelnen Benutzer nicht mit dem Chargify-Dienst geteilt. | E-Mail-Adresse | So kommunizieren Sie Abonnementlebenszyklusereignisse an den Benutzer |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>EUII und OII werden in der Telemetrie angezeigt. Diese Informationen werden in Application Insights gespeichert, im Ruhezustand verschlüsselt, der Zugriff kontrolliert und nach 90 Tagen gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>In der Anwendung gespeicherte Daten werden während der Übertragung und im Ruhezustand verschlüsselt. Wir verlassen uns auf Office 365 Anmeldeinformationen für unsere Apps, sodass wir keine Benutzerkennwörter in unserem System speichern. Der Zugriff auf gespeicherte Daten/Protokolle/Telemetrie wird für interne Verwaltungsmitarbeiter streng kontrolliert, mit der Notwendigkeit, auf die Informationen zuzugreifen, um den Zustand der App auszuführen und zu überwachen. Two-Factor Authentifizierung für alle internen Verwaltungsmitarbeiter erzwungen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von OnePlace Solutions darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Nein |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Nein |
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

