---
title: Anwendungsinformationen für SHL von SHL
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für SHL, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4a80f46a20f26bd879c1260bf091c1490c60b13c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2021
ms.locfileid: "60423095"
---
# <a name="shl"></a>SHL

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: June 25, 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c52adc0-18a0-45ca-b6ee-154cf1ef87e2" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002887" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von SHL an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | SHL |
| ID | WA200002887 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | SHL |
| URL der Partnerwebsite | [https://shl.com](https://shl.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://www.shl.com/en/about/](https://www.shl.com/en/about/) |
| URL der Datenschutzrichtlinie | [https://www.shl.com/en/privacy/administrator-data-protectio...](https://www.shl.com/en/privacy/administrator-data-protection-notice/) |
| URL der Nutzungsbedingungen | [https://www.shl.com/en/terms-of-service/](https://www.shl.com/en/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von SHL darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | Delegiert | Verfügbare freigegebene Calander-Slots | – | [afd2c390-8b78-40fa-913b-7fc5911e884a](https://docs.microsoft.com/microsoft-365-app-certification/azure/afd2c390-8b78-40fa-913b-7fc5911e884a) |


#### <a name="non-microsoft-services-used"></a>Nicht-Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>| **Alle nicht Microsoft-Dienste OII werden an** |  **Welche OII wird übertragen?** | **Begründung für die Übertragung von OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Wir übertragen Daten an die Dienste unserer eigenen Anwendung (Talentcentral: https://talentcentral.eu.shl.com/admin) | EUII: Microsoft Teams-Benutzername und Teams-Benutzer-ID | Der Benutzername aus Teams App wird in unserer anderen Anwendung verwendet, die E-Mails mit dem Benutzernamen auslöst. und Benutzer-ID, die wir als Bezeichner beibehalten und mit der Benutzer-ID unserer Anwendung&#8217;zuordnen. |

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Der Benutzername aus Teams App wird in unserer anderen Anwendung verwendet, die E-Mails mit dem Benutzernamen auslöst. und Benutzer-ID, die wir als Bezeichner beibehalten und mit der Benutzer-ID unserer Anwendung&#8217;zuordnen | Microsoft Teams-Benutzername und Teams-Benutzer-ID | Der Benutzername aus Teams App wird in unserer anderen Anwendung verwendet, die E-Mails mit dem Benutzernamen auslöst. und Benutzer-ID, die wir als Bezeichner beibehalten und mit der Benutzer-ID unserer Anwendung&#8217;zuordnen |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>In den Telemetrie- oder Protokollen der Anwendungen werden keine OII oder EUII angezeigt.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Wir steuern die Daten nicht, wir verarbeiten nur die Daten.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Identitätsinformationen

Diese Informationen wurden von SHL darüber bereitgestellt, wie diese App Authentifizierung, Autorisierung, bewährte Methoden für die Anwendungsregistrierung und andere Identitätskriterien behandelt.

| **Information** | **Antwort** |
|:----------------|:-------------|
| Integrieren Sie die Microsoft Identify Platform (Azure AD)?  | Nein |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
