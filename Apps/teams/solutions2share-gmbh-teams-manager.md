---
title: Anwendungsinformationen für Teams Manager von Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Teams Manager, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e51b08446bed1f22f1e058b92604841ce255eb8f
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/28/2021
ms.locfileid: "59971797"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: September 24, 2021</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Solutions2Share GmbH für Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Teams Manager |
| ID | WA200000764 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Solutions2Share GmbH |
| URL der Partnerwebsite | [https://teams-manager.com](https://teams-manager.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://teams-manager.com](https://teams-manager.com) |
| URL der Datenschutzrichtlinie | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Solutions2Share GmbH bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | Beide | Wir speichern die TenantID und TeamId, um die Vorlagen zuzuordnen.  | Alle Teams auflisten und auch Teams erstellen. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| Notes.ReadWrite.All | Anwendung | Keine | Ermöglicht der App das Hinzufügen von Notizbüchern zu einem genehmigten Team. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read | Delegiert | Keine | Ermöglicht dem Benutzer die Anmeldung und ermöglicht app-Zugriff auf den UPN, um die automatische Anmeldung zu aktivieren. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read.All | Beide | Wir speichern die ID des Benutzers, der im Abschnitt "Genehmigende Person/Administrator" eingegeben wird. | Listet alle Benutzer auf, um sie in der Personenauswahl innerhalb der App anzuzeigen. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.ReadBasic.All | Delegiert | Keine | Listet alle Benutzer auf, um sie in der Personenauswahl innerhalb der App anzuzeigen. | [b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird nicht auf EUII zugegriffen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Wir melden uns bei Azure Log Analytics an und verwenden deren Archiv-/Aufbewahrungsrichtlinien.
Wir protokollieren die Mandanten-ID und die Team-ID, um Probleme zu identifizieren und Kunden bei der Lösung von Problemen zu unterstützen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir verfügen über Compliance- und Vorgangsprozesse für die Zugriffssteuerung. Alle benutzerbezogenen Daten und Token werden verschlüsselt. Die Daten werden in einem Azure SQL-Datenbank gespeichert. Wir verwenden die Firewall, um nur Verbindungen von bestimmten IP-Adressen (geschützte IP-Bereiche zwischen Systemen) zuzulassen. Wir haben privileged Access Management (PMA) in Azure aktiviert.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>No

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Solutions2Share GmbH bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Ja |
| Haben Sie alle anwendbaren bewährten Methoden, die in der Checkliste für die Microsoft Identity Platform Integration beschrieben sind, überprüft und befolgt?  | Ja |
| Verwendet Ihre App MSAL (Microsoft-Authentifizierungsbibliothek) für die Authentifizierung? | Ja |
| Unterstützt Ihre App Richtlinien für bedingten Zugriff? | No |
| Fordert Ihre App berechtigungen mit den geringsten Rechten für Ihr Szenario an? | Ja |
| Spiegeln die statisch registrierten Berechtigungen Ihrer App genau die Berechtigungen wider, die Ihre App dynamisch und inkrementell anfordert? | Ja |
| Unterstützt Ihre App Mehrmandantenfähigkeit? | Ja |
| Verfügt Ihre App über einen vertraulichen Client? | No |
| Besitzen Sie alle Umleitungs-URI (Unified Resource Identifier), die für Ihre App registriert sind? | Ja |
| Was vermeiden Sie für Ihre App? | – URIs für Platzhalterumleitung,<br/><br/> |
| Macht Ihre App Web-APIs verfügbar? | Ja |
| Ermöglicht Ihr Berechtigungsmodell nur, dass Aufrufe erfolgreich sind, wenn die Client-App die richtige Zustimmung erhält? | Ja |
| Verwendet Ihre App Vorschau-APIs? | Ja |
| Verwendet Ihre App veraltete APIs? | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
