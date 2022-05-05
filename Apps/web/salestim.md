---
title: Anwendungsinformationen für SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SalesTim, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222436"
---
# <a name="application-information-for-salestim-by-salestim"></a>Anwendungsinformationen für SalesTim nach SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 24. Juni 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von SalesTim an Microsoft bereitgestellt werden:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | SalesTim |
| ID | salestim.salestim |
| Name des Partnerunternehmens | SalesTim |
| URL der Partnerwebsite | [https://salestim.com](https://salestim.com) |
| URL der Datenschutzrichtlinie | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL der Nutzungsbedingungen | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SalesTim darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegiert/Anwendung)** | **Werden Daten erfasst? Begründung für das Sammeln?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegiert | NEIN | Zulassen, dass die App ihre eigenen Pakete im Unternehmens-App-Katalog installiert und aktualisiert. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht es einem Benutzer, andere Benutzer an verschiedenen Stellen in der Anwendung auszuwählen, z. B. genehmigende Personen in einem Workflow auszuwählen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegiert | Wir&#8217;nur Gruppen-/Teams-IDs speichern,&#8217;keine Gruppen-/Teams-Inhalte speichern. | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und Mitgliedschaften im Namen des angemeldeten Benutzers zu lesen. Darüber hinaus können Gruppenbesitzer ihre eigenen Gruppen verwalten, und Gruppenmitglieder können Gruppeninhalte aktualisieren. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegiert | Wir&#8217;die Metadaten dieser Aktion speichern, z. B. Benachrichtigungsdatum, Empfänger (nur ID), Anforderungs-ID. | Ermöglicht der App das Senden von Benachrichtigungs-E-Mails, z. B. während eines Genehmigungsworkflows. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegiert | Wir verwenden einige Azure-Dienste zum Speichern von Daten, insbesondere Redis in Azure und Cosmos DB | Ermöglicht der App, die einem Team zugeordneten Laufwerke (Dateien und Ordner) während eines Teambereitstellungsprozesses zu verwalten. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegiert | Wir&#8217;nur einige Benutzer-IDs speichern, nicht Profildaten. | Ermöglicht der App, den vollständigen Satz von Profileigenschaften, Berichten und Managern eines beliebigen Benutzers zu lesen. Es wird insbesondere während des Zielgruppenadressierungsprozesses verwendet, um einige Inhalte basierend auf dem aktuellen Benutzerprofil zu filtern. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | Delegiert | Nein | Ermöglicht der App, einige Hintergrundvorgänge und Aktionen als Benutzer auszuführen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII wird übertragen an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir verwenden Intercom als unsere wichtigste Supportanwendung. Intercom kann einige grundlegende Benutzerprofilinformationen enthalten, wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#support-data | Firmenname | Wir verwenden GitHub-APIs, um Probleme automatisch aus unserer Produktionsumgebung zu generieren. Wir speichern auch einige technische Protokolle in GitHub (wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data). Diese Probleme und Protokolle können einige grundlegende Benutzerprofilinformationen enthalten. Diese Probleme und Protokolle werden automatisch alle 15 Tage gelöscht. |



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>Alle erfassten Daten werden hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#application-data Wie beschrieben, werden Protokolle vorübergehend für 15 Tage gespeichert und dann automatisch gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die meisten Daten werden in Azure Cosmos DB gespeichert.
Der Zugriff auf die Produktionsumgebung ist auf zwei Personen beschränkt, und diese Administratorkonten werden durch MFA erzwungen.
Diese Konten sind dediziert und unterscheiden sich von unseren Unternehmenskonten.
Daten werden im Ruhezustand in allen Azure-Diensten verschlüsselt, die wir verwenden.
Bereitstellungen in Produktionsumgebungen werden über einen dedizierten geschützten Zweig in unserer GitHub-Umgebung automatisiert, in dem nur zwei Personen Änderungen genehmigen können.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von SalesTim darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden überprüft und eingehalten, die in der Checkliste für die Microsoft Identity Platform Integration aufgeführt sind?  | Ja |
| Verwendet Ihre App MSAL (Microsoft Authentication Library) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | Ja |
| Auflisten der unterstützten Richtlinientypen | MFA, Standortbedingungen |
| Fordert Ihre App Berechtigungen mit den geringsten Berechtigungen für Ihr Szenario an? | Ja |
| Entsprechen die statisch registrierten Berechtigungen Ihrer App genau den Berechtigungen, die ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrinstanzenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | Ja |
| Besitzen Sie den gesamten umleitenden Unified Resource Identifier (URI), der für Ihre App registriert ist? | Ja |
| Was vermeiden Sie für Ihre App? | ,<br/>- Implizite OAuth2-Flow, es sei denn, dies ist für eine SPA erforderlich<br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Lässt Ihr Berechtigungsmodell nur den Erfolg von Aufrufen zu, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Nein |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
