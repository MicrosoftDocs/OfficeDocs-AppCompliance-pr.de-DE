---
title: Anwendungsinformationen für SalesTim von SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SalesTim, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 82ded2fc8555079ac3446d8446d261dbca5eed73
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250433"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Zuletzt aktualisiert vom Entwickler am: 27. Oktober 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von SalesTim an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SalesTim |
| ID | WA200001393 |
| Funktionen | Registerkarte |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | SalesTim |
| URL der Partnerwebsite | [https://www.salestim.com](https://www.salestim.com) |
| URL der Datenschutzrichtlinie | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL der Nutzungsbedingungen | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von SalesTim darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegierte | NEIN | Zulassen, dass die App eigene Pakete im Unternehmens-App-Katalog installiert und aktualisiert. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | delegierte | Wir&#8217;einige Benutzer-IDs nur speichern, nicht Profildaten. | Ermöglicht es einem Benutzer, andere Benutzer an verschiedenen Stellen in der Anwendung auszuwählen, z. B. genehmigende Benutzer in einem Workflow auszuwählen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | delegierte | Wir&#8217;nur Gruppen-/Teams-IDs speichern, wir&#8217;keine Gruppen-/Teams-Inhalte speichern. | Ermöglicht der App, Gruppen zu erstellen, alle Gruppeneigenschaften und Mitgliedschaften im Namen des angemeldeten Benutzers zu lesen. Darüber hinaus können Gruppenbesitzer ihre eigenen Gruppen verwalten, und Gruppenmitglieder können Gruppeninhalte aktualisieren. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | delegierte | Wir&#8217;die Metadaten dieser Aktion erneut speichern, z. B. Benachrichtigungsdatum, Empfänger (nur ID), Anforderungs-ID. | Ermöglicht der App das Senden von Benachrichtigungs-E-Mails, z. B. während eines Genehmigungsworkflows. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | delegierte | Wir verwenden einige Azure-Dienste zum Speichern von Daten, insbesondere Redis in Azure und Cosmos DB | Ermöglicht der App, die Laufwerke (Dateien und Ordner), die einem Team zugeordnet sind, während eines Teambereitstellungsprozesses zu verwalten. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | delegierte | Wir&#8217;einige Benutzer-IDs nur speichern, nicht Profildaten. | Ermöglicht der App, den vollständigen Satz von Profileigenschaften, Berichten und Managern eines beliebigen Benutzers zu lesen. Es wird insbesondere während des Zielgruppenzielprozesses verwendet, um einige Inhalte basierend auf dem aktuellen Benutzerprofil zu filtern. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offlineaccess | delegierte | Nein | Ermöglicht der App, einige Hintergrundvorgänge und Aktionen als Benutzer durchzuführen. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wir verwenden Sprechanlage als Hauptunterstützungsanwendung. Die Interkom kann einige grundlegende Benutzerprofilinformationen enthalten, wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Wir verwenden GitHub-APIs, um automatisch Probleme aus unserer Produktionsumgebung zu generieren. Außerdem speichern wir einige technische Protokolle in GitHub (wie hier beschrieben: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Diese Probleme und Protokolle können einige grundlegende Benutzerprofilinformationen enthalten. Diese Probleme und Protokolle werden automatisch alle 15 Tage gelöscht. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Alle erfassten Daten werden hier beschrieben: Wie beschrieben werden Protokolle vorübergehend für 15 Tage gespeichert und https://developers.salestim.com/platform/datamanagement.html#application-data dann automatisch gelöscht.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die meisten Daten werden in Azure Cosmos DB gespeichert.
Der Zugriff auf die Produktionsumgebung ist auf zwei Personen beschränkt, und diese Administratorkonten werden MFA erzwungen.
Diese Konten sind dedizierte Konten und unterscheiden sich von unseren Unternehmenskonten.
Daten werden in allen von uns verwendeten Azure-Diensten im Ruhedienst verschlüsselt.
Bereitstellungen in Produktionsumgebungen werden über einen dedizierten geschützten Zweig in unserer GitHub automatisiert, in dem nur zwei Personen Änderungen genehmigen können.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Ja

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

