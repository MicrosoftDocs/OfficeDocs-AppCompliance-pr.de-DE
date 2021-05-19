---
title: Anwendungsinformationen für Guru von Guru Technologies
ms.author: elmalova
author: elenamalova
ms.date: 03/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Informationen zu Sicherheits- und Complianceinformationen für Guru, seine Datenverarbeitungsrichtlinien, die informationen Microsoft Cloud App Security App-Katalogs und Sicherheits-/Compliance-Informationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 16abdcc7ab9b3da8cef55b17e5b63a3a7d916c51
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553136"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 1. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Ansicht in Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die Guru Technologies Microsoft zur Verfügung gestellt hat:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Guru |
| ID | WA200001719 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Guru Technologies |
| URL der Partner-Website | [https://www.getguru.com/](https://www.getguru.com/) |
| URL Teams Anwendungsinfoseite | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.getguru.com/privacy](https://www.getguru.com/privacy) |
| URL der Nutzungsbedingungen | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Wie die App mit Daten umgeht

Diese Informationen wurden von Guru Technologies darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App erfassten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mit Microsoft Graph

Listen Sie alle [Microsoft-Graph Berechtigungen](https://docs.microsoft.com/graph/permissions-reference) auf, die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft-Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienst überträgt oder diese teilt, listen Sie den Nicht-Microsoft-Dienst auf, den die App verwendet, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden auf** |  **Welche OII wird übertragen?** | **Rechtfertigung für die Übertragung von OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Gurus Endbenutzeranwendung und interne Datenbanken | Wenn ein Benutzer oder ein Unternehmen die Guru-App für Teams einrichtet, werden allgemeine Informationen wie Benutzername, E-Mail und Firmenname, die mit seinem Benutzerprofil verknüpft sind, aufgezeichnet und von Guru zugänglich gemacht. | Da ein Benutzer sowohl über ein Teams- als auch über ein Guru-Konto verfügen muss, um die Integration nutzen zu können, verfolgen und verfolgen wir, welche Benutzer die Integration ermöglichen, um diesen Benutzern Unterstützung und Verwaltung zu bieten. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf identitätsnahe Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Es wird kein EUII abgerufen.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden in der Telemetrie oder in den Protokollen dieser Anwendung unternehmensbezogene identifizierbare Informationen (OII) oder Benutzer-identifizierbare Informationen (EUII) angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Richtlinien für aufbewahrungs- und Entfernungsrichtlinien?

>Wenn ein Benutzer oder ein Unternehmen die Guru-App für Teams einrichtet, werden allgemeine Informationen wie Benutzername, E-Mail und Firmenname, die mit seinem Benutzerprofil verknüpft sind, aufgezeichnet und von Guru zugänglich gemacht. Bei einer Kontobeendigung werden die Daten 90 Tage lang aufbewahrt und dann entfernt. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben Sie, wie Administratoren von Organisationen ihre Informationen in Partnersystemen steuern können? z.B. Löschen, Aufbewahrung, Auditing, Archivierung, Endbenutzerrichtlinie usw.

>Gurus Team Einstellungen es Administratoren in einem Team ermöglichen, zu bestimmen, welche Gruppen- und Zugriffs-/Rollensteuerelemente pro Sammlung bereitgestellt werden sollen, mit der Möglichkeit, Karten zu wechselnden Personen hinzuzufügen, zu entfernen und neu zuzuweisen. Enterprise Kunden, die SSO bereitgestellt haben, haben auch den Vorteil der SSO-Providerkonsole, über SCIM ein-/ausbordalen zu können und Gruppen zu gründen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational identifiabling Information) beteiligt, die von dieser App erfasst oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Die Informationen aus dem [Microsoft Cloud App Security-Katalog](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">Anzeigen in einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Guru Technologies darüber bereitgestellt, wie diese App authentifizierung, Autorisierung, Best Practices für die Anwendungsregistrierung und andere Identitätskriterien verarbeitet.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Können Sie sich in Microsoft Identifizplattform (Azure AD) integrieren?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
