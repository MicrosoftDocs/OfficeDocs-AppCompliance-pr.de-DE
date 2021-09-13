---
title: Anwendungsinformationen für dynamisches Signal durch dynamisches Signal
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Dynamic Signal, seine Datenverarbeitungsrichtlinien, Microsoft Cloud App Security App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5b5906e8eee51821481de11c3cbd720600d4c36e
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/12/2021
ms.locfileid: "59283061"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Last updated by the developer on: December 16, 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Anzeigen im Teams Speicher</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Dynamic Signal an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Dynamic Signal |
| ID | WA200000102 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Name des Partnerunternehmens | Dynamic Signal |
| URL der Partnerwebsite | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| URL der Seite mit Teams Anwendungsinformationen | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL der Datenschutzrichtlinie | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL der Nutzungsbedingungen | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So behandelt die App Daten

Diese Informationen wurden von Dynamic Signal bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph Berechtigungen auf, die](https://docs.microsoft.com/graph/permissions-reference) diese App benötigt.

>| **Berechtigung**  | **Typ der Berechtigung (delegiert/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Leseberechtigungen eines bestimmten Benutzers zum Synchronisieren von Benutzern der Dynamischen Signalplattform mit Azure AD. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| User.Read.All | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Leseberechtigungen eines bestimmten Benutzers zum Synchronisieren von Benutzern der Dynamischen Signalplattform mit Azure AD. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| offline_access | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Behalten Sie den Zugriff auf die Gruppen und Teams des Mandanten bei. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| openid | Delegiert | Dynamic Signal synchronisiert Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Authentifizieren von Benutzern mit der Dynamic Signal-Anwendung. | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten mit einem Nicht-Microsoft-Dienst überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messaging-Erweiterung enthält, kann sie auf Personenbezogene Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) eines beliebigen Teammitglieds in einem Team oder Chat, dem sie hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| openid sign in using openid directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams | openid Allow for independent authentication. directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal's application uses the teams bot to apply groups and permissions created within Dynamic Signal to Teams so that a user that is active in Dynamic Signal will have access to the same groups and users that within Teams. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsbezogene Informationen (OII) oder Endbenutzer-Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die Dynamic Signal-App und -Plattform nutzen Benutzerinformationen, um die Integration mit Microsoft Teams zu vereinfachen. Diese Informationen stehen Benutzern mit entsprechenden Berechtigungen innerhalb der Dynamic Signal-Plattform zur Verfügung. Relevante Informationen sind Name, Anzeigename und E-Mail. Diese Informationen werden in den Dynamic Signal Platform-Protokollen gemäß der Richtlinie der jeweiligen Organisation mit der Dynamic Signal-Lizenz gespeichert.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerungen für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschen, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die pii-Daten, die während der Registrierung gesammelt und in der Dynamic Signal-Plattform gespeichert werden, umfassen: Vorname, Nachname, E-Mail/Bezeichner und alle benutzerdefinierten Felder, die von der Marke und/oder Agenturpartnern eingerichtet werden. Wenn Mitglieder Facebook oder Twitter mithilfe der oAuth-Registrierung verwenden, werden einige der verfügbar gemachten Benutzerdaten der Dynamic Signal-Plattform angezeigt, um Daten vorab auszufüllen. Zu diesen Daten gehören Name, Position und Foto. Benutzer haben die Kontrolle darüber, welche Informationen und Daten Benutzern auf den Bioseiten für die Community angezeigt werden. Mitglieder können sich für das Laden von persönlichen Fotos oder Markenfotos, das Verbinden von sozialen Konten/Kanälen und die Nutzung/Punkte im Programm entscheiden, die auf der Bio-Seite angezeigt werden sollen.

#### <a name="human-review-of-organizational-information"></a>Menschliche Überprüfung von Organisationsinformationen

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) Katalog werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Ansicht auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

