---
title: Anwendungsinformationen für dynamisches Signal durch dynamisches Signal
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Alle verfügbaren Sicherheits- und Complianceinformationen für Dynamic Signal, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552226"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 16. Dezember 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Informationen, die von Dynamic Signal an Microsoft bereitgestellt werden:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Dynamic Signal |
| ID | WA200000102 |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | Dynamic Signal |
| URL der Partnerwebsite | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL Teams Anwendungsinfoseite | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL der Datenschutzrichtlinie | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL der Nutzungsbedingungen | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von Dynamic Signal bereitgestellt, um zu erfahren, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | Dynamic Signal synchronisiert Den Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Lesen der Berechtigungen eines bestimmten Benutzers zum Synchronisieren von Benutzern der Dynamischen Signalplattform mit Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegierte | Dynamic Signal synchronisiert Den Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Lesen der Berechtigungen eines bestimmten Benutzers zum Synchronisieren von Benutzern der Dynamischen Signalplattform mit Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegierte | Dynamic Signal synchronisiert Den Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Behalten Sie den Zugriff auf die Gruppen und Teams des Mandanten bei. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | delegierte | Dynamic Signal synchronisiert Den Benutzer von Azure AD mit seiner Plattform, um eine optimierte Aktivierung und Deaktivierung von Benutzern in Echtzeit zu ermöglichen. Daten werden im dynamischen Signal gespeichert, damit Benutzer diese Anwendung während der Synchronisierung verwenden können. | Authentifizieren Sie Benutzer mit der Dynamischen Signalanwendung. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>| **Begründung für den Zugriff auf EUII?**  | **Wird EUII in Datenbanken gespeichert?** | **Begründung für die Speicherung von EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid melden Sie sich mit openid directory.readwrite.all-Zugriff auf die Domäne und Gruppen des Mandanten an, fügen Sie einem Team eine App hinzu, offline_access den Zugriff auf die Gruppen und Teams des Mandanten beibehalten | openid Die unabhängige Authentifizierung zulassen. directory.readwrite.all access to the tenant's domain and groups, add an app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal's application uses the teams bot to apply groups and permissions created within Dynamic Signal to Teams so that a user that is active in Dynamic Signal will have access to the same groups and users that within Teams. |  |


#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Die Dynamische Signal-App und -Plattform nutzen Benutzerinformationen, um die Integration in Microsoft Teams. Diese Informationen stehen Benutzern mit entsprechenden Berechtigungen innerhalb der Dynamic Signal-Plattform zur Verfügung. Relevante Informationen sind Name, Anzeigename und E-Mail. Diese Informationen werden in den Protokollen der Dynamic Signal-Plattform in Übereinstimmung mit der Richtlinie der jeweiligen Organisation mit der Dynamic Signal-Lizenz gespeichert.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Die PII-Daten, die während der Registrierung gesammelt und auf der Dynamic Signal-Plattform gespeichert werden, umfassen: Vorname, Nachname, E-Mail/Id und alle benutzerdefinierten Felder, die von den Marken- und/oder Agenturpartnern eingerichtet werden. Wenn Mitglieder Facebook oder Twitter mithilfe der oAuth-Registrierung verwenden, werden einige der verfügbar gemachten Benutzerdaten der Dynamic Signal-Plattform angezeigt, um Daten vorab zu füllen. Diese Daten umfassen Name, Ort und Foto. Benutzer haben die Kontrolle darüber, welche Informationen und Daten benutzern auf den Bioseiten für die Community angezeigt werden. Mitglieder können sich dafür entscheiden, persönliche Fotos oder Markenfotos zu laden, Soziale Konten/Kanäle und Nutzungs-/Punkte im Programm zu verbinden, das auf der Bio-Seite angezeigt werden soll.

#### <a name="human-review-of-organizational-information"></a>Human review of organizational information

Sind Menschen an der Überprüfung oder Analyse von Organisationsdaten (Organizational Identifiable Information, OII) beteiligt, die von dieser App gesammelt oder gespeichert werden?

>Nein

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

