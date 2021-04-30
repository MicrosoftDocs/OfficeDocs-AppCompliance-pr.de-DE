---
title: Anwendungsinformationen für den virtuellen Agent von ServiceNow
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: Alle verfügbaren Sicherheits- und Complianceinformationen für den virtuellen Agent jetzt, seine Datenverarbeitungsrichtlinien, die Microsoft Cloud App Security-App-Kataloginformationen und Sicherheits-/Complianceinformationen in der CSA STAR-Registrierung.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c6cc9da641b2e1f03aee7b23b0bae5312793cc80
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096129"
---
# <a name="now-virtual-agent"></a>Now Virtual Agent

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Zuletzt aktualisiert vom Entwickler am: 23. März 2020</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">Ansicht im Teams Store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">Ansicht in AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Allgemeine Informationen

Von ServiceNow an Microsoft bereitgestellte Informationen:

| **Information** | **Antwort** |
|:----------------|:-------------|
| App-Name | Now Virtual Agent |
| ID | WA104381816 |
| Funktionen | Bot |
| Office 365 unterstützten Clients | Microsoft Teams |
| Partnerunternehmensname | ServiceNow |
| URL der Partnerwebsite | [https://www.servicenow.com/](https://www.servicenow.com/) |
| URL Teams Anwendungsinfoseite | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| URL der Datenschutzrichtlinie | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| URL der Nutzungsbedingungen | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>So verarbeitet die App Daten

Diese Informationen wurden von ServiceNow darüber bereitgestellt, wie diese App Organisationsdaten sammelt und speichert und welche Kontrolle Ihre Organisation über die von der App gesammelten Daten hat.

#### <a name="data-access-using-microsoft-graph"></a>Datenzugriff mithilfe von Microsoft Graph

Listet alle [Microsoft Graph berechtigungen auf,](https://docs.microsoft.com/graph/permissions-reference) die diese App benötigt.

>| **Berechtigung**  | **Berechtigungstyp (Delegierte/Anwendung)** | **Werden Daten gesammelt? Begründung für die Erfassung?** | **Werden Daten gespeichert? Begründung für die Speicherung?** | **Azure AD-App-ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegierte | Die Domäne wird zu zukünftigen Nachrichtenroutingzwecken in unserem Rechenzentrum gespeichert. | Wenn der ServiceNow-Administrator die Integration mit MS Teams installiert, muss sich der Administrator bei seinem MS-Teams anmelden. Wir lesen die Domäne aus der E-Mail-Adresse (nicht der vollständigen E-Mail-Adresse). |  |


#### <a name="non-microsoft-services-used"></a>Nicht Microsoft-Dienste verwendet

Wenn die App Organisationsdaten an Nicht-Microsoft-Dienste überträgt oder teilt, listen Sie den von der App verwendeten Nicht-Microsoft-Dienst auf, welche Daten übertragen werden, und geben Sie eine Begründung dafür an, warum die App diese Informationen übertragen muss.

>Nicht-Microsoft-Dienste werden nicht verwendet.

#### <a name="data-access-via-bots"></a>Datenzugriff über Bots

Wenn diese App einen Bot oder eine Messagingerweiterung enthält, kann sie auf identifizierbare Endbenutzerinformationen (EUII) zugreifen: die Liste (Vorname, Nachname, Anzeigename, E-Mail-Adresse) jedes Teammitglieds in einem Team oder Chat, dem es hinzugefügt wird. Nutzt diese App diese Funktion?

>Auf EUII wird nicht zugegriffen.



#### <a name="telemetry-data"></a>Telemetriedaten

Werden organisationsidentifizierbare Informationen (OII) oder endbenutzeridentifizierbare Informationen (EUII) in den Telemetrie- oder Protokollen dieser Anwendung angezeigt? Wenn ja, beschreiben Sie, welche Daten gespeichert werden und was sind die Aufbewahrungs- und Entfernungsrichtlinien?

>Nicht standardmäßig von ServiceNow. Kunden können das Virtual Agent-Framework nutzen, um zusätzliche Funktionen zu erstellen, die potenziell auf Organisations- oder Endbenutzerinformationen zugreifen können. Benutzer können während der Interaktion mit dem Bot persönliche identifizierbare Informationen eingeben und die Informationen an ServiceNow übersenen.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Organisationssteuerelemente für vom Partner gespeicherte Daten

Beschreiben, wie Administratoren ihrer Organisation ihre Informationen in Partnersystemen steuern können? z. B. Löschung, Aufbewahrung, Überwachung, Archivierung, Endbenutzerrichtlinie usw.

>Weitere Informationen finden Sie im [Abschnitt Cloud Security Alliance.](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa)


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Informationen aus dem [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) werden unten angezeigt.

<iframe height='1020' title='Microsoft Cloud App Security Informationen' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">Anzeigen auf einer neuen Registerkarte</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

