---
title: Anwendungsinformationen für Guru von Guru Technologies
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Guru, seine Datenverarbeitungsrichtlinien, seine Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b623d0d92400219e5ad31d58ade4d98409aced98
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226559"
---
# <a name="guru"></a>Guru

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Letzte Aktualisierung durch den Entwickler am: 1. März 2021</p>

* <a href="https://teams.microsoft.com/l/app/094bf90e-e413-4740-b2dc-68d624d0e40e" target="_blank">Anzeigen im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001719" target="_blank">Anzeigen in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von Guru Technologies an Microsoft bereitgestellte Informationen:

| **Information** | **Response** |
|:----------------|:-------------|
| App-Name | Guru |
| ID | WA200001719 |
| unterstützte Office 365 Clients | Microsoft Teams |
| Name des Partnerunternehmens | Guru Technologies |
| URL der Partnerwebsite | [https://www.getguru.com](https://www.getguru.com) |
| URL der Teams Anwendungsinformationsseite | [https://www.getguru.com/integrations/microsoft-teams](https://www.getguru.com/integrations/microsoft-teams) |
| URL der Datenschutzrichtlinie | [https://www.getguru.com/privacy/](https://www.getguru.com/privacy/) |
| URL der Nutzungsbedingungen | [https://www.getguru.com/terms-of-service](https://www.getguru.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Guru Technologies darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Auflisten aller [Microsoft Graph Berechtigungen](/graph/permissions-reference), die diese App benötigt.

>Diese Anwendung verwendet keine Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder freigibt, listen Sie den von der App nicht von Microsoft stammenden Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII wird übertragen an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Gurus Endbenutzeranwendung und interne Datenbanken | wenn ein Benutzer oder ein Unternehmen die Guru-App für Teams einrichtet, werden allgemeine Informationen wie Benutzername, E-Mail und Firmenname, die mit ihrem Benutzerprofil verknüpft sind, aufgezeichnet und von Guru zugänglich. | Da ein Benutzer sowohl über ein Teams- als auch ein Guru-Konto verfügen muss, um die Integration nutzen zu können, verfolgen und verfolgen wir, welche Benutzer die Integration ermöglichen, um diesen Benutzern Unterstützung und Verwaltung bereitzustellen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Endbenutzer-identifizierbare Informationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wurde. Nutzt diese App diese Funktion?

>Es wird kein EUII-Zugriff erfolgt.


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder Endbenutzer-identifizierbare Informationen (EUII) in den Telemetriedaten oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und welche Aufbewahrungs- und Entfernungsrichtlinien gelten?

>wenn ein Benutzer oder ein Unternehmen die Guru-App für Teams einrichtet, werden allgemeine Informationen wie Benutzername, E-Mail und Firmenname, die mit ihrem Benutzerprofil verknüpft sind, aufgezeichnet und von Guru zugänglich. Nach der Kündigung eines Kontos werden die Daten 90 Tage lang aufbewahrt und dann entfernt. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren der Organisation ihre Informationen in Partnersystemen steuern können? z.B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Gurus Team Einstellungen es Administratoren in einem Team ermöglichen, zu bestimmen, welche Gruppen- und Zugriffs-/Rollensteuerelemente pro Sammlung bereitgestellt werden sollen, mit der Möglichkeit, Karten zu alternativen Personen hinzuzufügen, zu entfernen und neu zuzuweisen. Enterprise Kunden, die SSO bereitgestellt haben, profitieren auch von der SSO-Anbieterkonsole zum Onboarding/Offboarden und Einrichten von Gruppen über SCIM

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von OII-Daten (Organizational Identifiable Information) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36912" target="_blank">Auf einer neuen Registerkarte anzeigen</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von Guru Technologies darüber bereitgestellt, wie diese App die Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Response** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
